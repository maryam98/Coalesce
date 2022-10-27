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

 <div style=" position: absolute; ">

    <q-form class="q-pl-xl"  style=" width: 400px; overflow:auto; padding-top:300px  ">
<div class="text-h6">subscribe to receive coalesce News</div>
  <q-input class="bg-white rounded-borders" v-model="email" type="email" placeholder="Email Address" style=" border:groove; border-color:#F35C36; float: left;
width: 70%; height: 55px; border-radius: 5px 0px 0px 5px;" />
  <q-btn   label="Sign up" style="width: 30%;  height: 55px;  background: #F35C36; color: white; float: left;border-radius: 0 5px 5px 0; "  />

   </q-form>
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
    max-width: 100px;
    align-self: flex-end;
  }
</style>
