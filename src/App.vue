<template>
    <TopBar></TopBar>
    <NavigationBar></NavigationBar>
    <trading-environment></trading-environment>
    <fade-in-elements-one></fade-in-elements-one>
    <multiple-trading-account></multiple-trading-account>
    <safe-reliable></safe-reliable>
    <social-trading></social-trading>
    <international-presence></international-presence>
    <awards-awarded></awards-awarded>
    <red-banner></red-banner>


    


</template>

<script>
import TopBar from './components/TopBar.vue'
import NavigationBar from "./components/NavigationBar.vue"
import TradingEnvironment from "./components/TradingEnvironment/TradingEnvironment.vue"
import FadeInElementsOne from "./components/FadeInElementsOne.vue"
import MultipleTradingAccount from "./components/MultipleTradingAccount/MultipleTradingAccount.vue"
import SafeReliable from "./components/SafeReliable/SafeReliable.vue"
import SocialTrading from "./components/SocialTrading/SocialTrading.vue"
import InternationalPresence from "./components/InternationalPresence/InternationalPresence.vue"
import AwardsAwarded from "./components/Awards/AwardsAwarded.vue"
import RedBanner from "./components/Banner/RedBanner.vue"


export default {

  components: {
    TopBar,
    NavigationBar,
    TradingEnvironment,
    FadeInElementsOne,
    MultipleTradingAccount,
    SafeReliable,
    SocialTrading,
    InternationalPresence,
    AwardsAwarded,
    RedBanner
  },

  
}


</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');


body{
  font-family: 'Poppins';
  padding: 0;
  margin: 0;
  min-height: 1000vh;
}
</style>
