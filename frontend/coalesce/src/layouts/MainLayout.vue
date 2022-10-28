<template>
  <q-layout view="lHh Lpr lFf " >

    <!--<q-header>-->
      <div class="q-px-xl " >
    <q-toolbar  >

      <img src="../assets/coalesce-logo.png">
      <div view="lHh Lpr lFf">
        <q-tabs shrink>
          <q-route-tab to="/" name="home">Home</q-route-tab>
          <q-tab>
            <a target="_blank" href="https://www.federationof.tech/humanitarian-software">About</a>
          </q-tab>
          <q-route-tab to="/opportunities" name="opportunities">Opportunities</q-route-tab>
          <q-tab>
            <a target="_blank" href="https://www.federationof.tech/humanitarian-software">Contact Us</a>
          </q-tab>
        </q-tabs>
      </div>
      <q-space />
      <q-btn flat round dense icon="search" class="q-mr-xs"></q-btn>
      <div>
        <q-tabs shrink>
          <q-route-tab to="/login" name="login">
            <q-btn type="submit" unelevated padding="8px 16px" label="Log in" />
          </q-route-tab>
          <q-route-tab to="/organisers/create" name="signup">
            <q-btn type="submit" unelevated class="orange-button" padding="8px 16px" label="Sign Up" />
          </q-route-tab>
        </q-tabs>
      </div>

    </q-toolbar>
    </div>
 <!-- </q-header>-->
    <q-page-container>
      <router-view />
    </q-page-container>

<div  style="background-color: #eeeeee; height: 500px;">

 <div class="row">

    <q-form class="q-pl-xl col "  style=" width: 200px; overflow:auto; padding-top:250px;    ">
<div class="text-h6">subscribe to receive coalesce News</div>
  <q-input class="bg-white rounded-borders" v-model="email" type="email" placeholder="Email Address" style=" border:groove; border-color:#F35C36; float: left;
width: 70%; height: 55px; border-radius: 5px 0px 0px 5px;" />
  <q-btn   label="Sign up" style="width: 30%;  height: 55px;  background: #F35C36; color: white; float: left;border-radius: 0 5px 5px 0; "  />
<div  class="text-subtitle1 q-pl-xl q-pt-xl"  >Coalesce 2021. All rights reserved </div>
   </q-form>
<div class="col q-pl-xl" style="padding-top:250px" >
<h5> Other Links </h5>

<a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Referral Network</a>
<a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Volunteer</a>
<a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Monitoring & Reporting</a>

</div>
<div class="col " style="padding-top:250px">
  <h5> Get Started </h5>
  <a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Free Download</a>
<a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Feature</a>
<a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Subscribe</a>

</div>
<div class="col " style="padding-top:300px">

  <a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">About</a>
<a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Blog</a>
<a target="_blank" class="row" href="https://www.federationof.tech/humanitarian-software">Vision</a>

</div>

</div>
 </div>
      <!-- newsletter -->
    <q-toolbar  style="background-color: #2a4264; ">
      <q-img src="../assets/footer.png" />
    </q-toolbar>

  </q-layout>
</template>

<script>
export default {
  name: 'MainLayout',
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
  a { text-decoration: none; color:black; }
  a:visited { text-decoration: none; color:black; }
  a:hover { text-decoration: none; color:black; }
  a:focus { text-decoration: none; color:black; }
  a:hover, a:active { text-decoration: none; color:black }
  .orange-button {
    font-weight: bold;
    color: white;
    background: $accent;
    border-radius: 8px;
    min-width: 100px;
    max-width: 150px;
    align-self: flex-end;
  }
</style>
