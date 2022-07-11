<template>
  <div class="container">
    <p class="compliance">Compliance</p>

    <p class="blue">
      (We have detected that you may be accessing this website from a
      jurisdiction: <span>Malaysia</span> where we do not provide services. Your
      legal rights shall not be protected under the laws and regulations of your
      jurisdiction. You shall be governed by the laws of 'Republic of Vanuatu',
      and you hereby acknowledge the risks in complying with the laws of
      'Republic of Vanuatu'.)
    </p>

    <p>Please read the following Compliance Disclosure carefully</p>

    <p>This website is owned and operated by Doo Prime Vanuatu Limited.</p>
    <p>
      The website can be accessed globally and is not specific to any entity.
      This is mainly for the convenience of centralized display and comparison
      of information. Your actual rights and obligations will be determined
      based on the entity and jurisdiction that you choose to be regulated.
    </p>
    <p>
      You must be of at least 18 years old before you can access our website
      products and services. By accessing our website, you confirm you are an
      individual of full age and capacity.
    </p>
    <p>
      There may be local laws and regulations which prohibit or limit your
      rights to access, download, distribute, disseminate, share or otherwise
      use any or all of the documents and information published on this website.
    </p>

    <div class="border-bottom"></div>

    <div class="in-border">
      <div class="in-border-content">
        <p @click="toggleRiskDisclosure" class="links">
          High Risk Trading Products Risk Disclosure
        </p>
        <p @click="toggleBrandNotice" class="links">Brand And Entity notice</p>
        <p @click="toggleClientNotice" class="links">Client Notice</p>
        <p @click="toggleDooEntitiesNotice" class="links">Doo Entities Notice</p>
      </div>
    </div>

    <div class="border-bottom"></div>

    <p class="content" v-if="showRiskDisclosure">
      <risk-disclosure></risk-disclosure>
    </p>
    <p class="content" v-if="brandNotice">
      <brand-notice></brand-notice>
    </p>
    <p class="content" v-if="showClientNotice">
      <client-notice></client-notice>
    </p>
    <p class="content" v-if="showDooEntities">
      <doo-entities-notice></doo-entities-notice>
    </p>
  </div>
</template>

<script>
import RiskDisclosure from "./RiskDisclosure.vue";
import BrandNotice from "./BrandNotice.vue";
import ClientNotice from "./ClientNotice.vue";
import DooEntitiesNotice from "./DooEntitiesNotice.vue"

export default {
  components: {
    RiskDisclosure,
    BrandNotice,
    ClientNotice,
    DooEntitiesNotice
  },

  data() {
    return {
      showRiskDisclosure: false,
      brandNotice: false,
      showClientNotice: false,
      showDooEntities:false
    };
  },

  methods: {
    toggleRiskDisclosure() {
      console.log("flag1");
      this.showRiskDisclosure = !this.showRiskDisclosure;
      this.brandNotice = false;
      this.showClientNotice = false
      this.showDooEntities = false
    },
    toggleBrandNotice() {
      this.brandNotice = !this.brandNotice;
      this.showRiskDisclosure = false;
      this.showClientNotice = false
      this.showDooEntities = false
    },
    toggleClientNotice() {
      this.showClientNotice = !this.showClientNotice;
      this.brandNotice = false;
      this.showRiskDisclosure = false;
      this.showDooEntities= false
    },
    toggleDooEntitiesNotice() {
        this.showDooEntities= !this.showDooEntities
        this.showRiskDisclosure = false
        this.brandNotice= false
        this.showClientNotice= false
    }

  },
};
</script>

<style scoped>
.container {
  margin: 3rem 4rem;
  width: 90%;
}

h1 {
  font-size: 20px;
}
.compliance {
  font-size: 15px;
  font-weight: bold;
}

.blue {
  color: #16a0ff;
}

span {
  font-weight: bold;
}

.border-bottom {
  border-bottom: 1.5px solid grey;
  opacity: 0.2;
  margin-top: 2rem;
}

.in-border-content {
  display: flex;
  margin-top: 2rem;
  margin-bottom: 0;
  align-items: center;
}

.in-border a {
  margin-left: 2rem;
  margin-top: 3rem;
  text-decoration: none;
  color: black;
  display: flex;
}

.links {
  margin-left: 3rem;
}
.links:hover {
  cursor: pointer;
}
</style>