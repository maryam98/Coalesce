<template>
  <q-page-container>
  <q-page  class="q-pt-none ">
    <!-- Above the fold, main landing page content -->

  <div style="background-color:#fef0e5" >
<div class="row q-pt-lg justify-center" >
    <div class="col-12 col-md-4 ">
      <div class="text-subtitle1 text-uppercase text-teal-10" >Volunteering made easy</div>
      <div class="text-h1 text-weight-bolder " style="color: #2a4264; " >Welcome to Coalesce</div>
      <div class="text-h5 text-weight-medium text-grey-14">A 100% open-source volunteer management platform... in development</div>

      <q-btn unelevated no-caps class="submit-button q-mt-xl q-mr-md"  to="/organisers/create" text-color="white" label="Register as volunteer " color="accent" padding="md xl"></q-btn>
       <q-btn unelevated no-caps class="submit-button q-mt-xl"  to="/organisers/create" text-color="white" label="Register as an Organisation" color="accent" padding="md xl"></q-btn>

    </div>
      <div class="col-12 col-md-7  q-pb-xl  " >
      <img src="../assets/book.png">
      </div>
</div>
    <!-- <div class="row q-pt-sm">
      <div class="col-12 col-md-4">
          </div>
    </div> -->
</div>

    <!-- Below the fold, how it works information -->
    <div class="col-12 page-banner q-px-xl q-my-xl">
      <q-item to="/" class=" text-weight-bolder text-h4 "  style="color: #2a4264; ">How it works</q-item>
      <div class="row q-gutter-lg">
        <q-card class="col-3">
          <q-card-section>
            <q-icon name="account_circle" size="xl" color="accent" ></q-icon>
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Step 1</div>
            <div class="text-h6">Register as a Volunteer or an Organisation</div>
            <div class="text-body">Sign up as a Volunteer or a group looking for volunteers.</div>
          </q-card-section>
        </q-card>
        <q-card class="col-3">
          <q-card-section>
            <q-icon name="description" size="xl" color="accent" ></q-icon>
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Step 2</div>
            <div class="text-h6">Create, manage or apply for opportunities on the dashboard</div>
            <div class="text-body">Create and oppertunity or apply to Volunteer.</div>
          </q-card-section>
        </q-card>
        <q-card class="col-3">
          <q-card-section>
            <q-icon name="check_circle" size="xl" color="accent"  ></q-icon>
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Step 3</div>
            <div class="text-h6">Shortlist candidates and accept opportunities</div>
            <div class="text-body">Use our tools to review and recruit your new Volunteer.</div>
          </q-card-section>
        </q-card>
      </div>
    </div>
    <!-- About Coalesce -->
    <div style="background-color:#eaf3ff" class="q-pa-xl q-my-xl">
      <q-item to="/" class=" text-weight-bolder text-h4 "  style="color: #2a4264; ">About Coalesce</q-item>
       <p>Coalesce lowers the time spent recruiting and managing volunteers by centralizing recruiting and data management in one web platform.</p>
      <p>We improve non-profit operational scalability by engaging more significant numbers of volunteers who deliver more to the overall mission.</p>
      <q-btn type="submit" unelevated class="orange-button"  label="Read more" />

    </div>
    <!-- ***************************Who is using Coalesce?*************************************-->
    <div class="q-px-xl q-my-xl ">
      <q-item to="/" class=" text-weight-bolder text-h4 "  style="color: #2a4264; ">Who is using Coalesce?</q-item>
        <div class="row q-gutter-lg">
        <q-card class="col-2">
          <q-card-section>
            <q-icon name="face" size="xl" color="accent" />
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Alice</div>
          </q-card-section>
        </q-card>
        <q-card class="col-2">
          <q-card-section>
            <q-icon name="face" size="xl" color="accent" />
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Shreya</div>
          </q-card-section>
        </q-card>
        <q-card class="col-2">
          <q-card-section>
            <q-icon name="face" size="xl" color="accent" />
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Frank</div>
          </q-card-section>
        </q-card>
      </div>
    </div>
    <!--****************************************************-->
    <!-- Connect with us -->
    <div class="col-10 page-banner q-px-xl q-my-xl ">
      <q-item to="/" class=" text-weight-bolder text-h4 "  style="color: #2a4264; ">Connect with us</q-item>

      <div class="row q-gutter-lg">
        <q-card class="col-2">
          <q-card-section>
            <q-icon name="favorite" size="xl" color="accent" ></q-icon>
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Federation of Humanitarian Technologists</div>
            <div class="text-body">We are the organisation that created this service during the 2019/20 pandemic.</div>
          </q-card-section>
        </q-card>
        <q-card class="col-2">
          <q-card-section>
            <q-icon name="thumb_up" size="xl" color="accent" ></q-icon>
          </q-card-section>
          <q-card-section>
            <div class="text-subtitle2">Find us on GitHub</div>
            <div class="text-body">If you are a developer or have a development team, you are more than welcome to help the aid community by building this product out more.</div>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </q-page>
</q-page-container>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>

<style lang="scss">
            h1 {
                color: $font-primary;
            }

            .submit-button {
                margin-top: 24px;
                font-weight: bold;
                color: white;
                background: $accent;
                border-radius: 8px;
                min-width: 200px;
            }

            .volunteer-link {
                color: $accent;
            }
            .orange-button {
    font-weight: bold;
    color: white;
    background: $accent;
    border-radius: 8px;
    min-width: 100px;
    max-width: 150px;

  }

</style>
