<template>
  <q-layout view="lhh Lpr lff">
    <q-header elevated class="headerClass q-pl-lg q-pr-xl">
      <q-toolbar style="max-width: 95%">
        <q-btn flat round class="q-ma-lg">
          <q-avatar size="55px">
            <img src="~assets/starbucks.png">
          </q-avatar>
        </q-btn>

        <div class="gt-sm">
          <q-btn flat color="dark" label="MENU" class="custom-hover text-weight-bold text-7" />
          <q-btn flat color="dark" label="REWARDS" class="custom-hover text-weight-bold text-h7" />
          <q-btn flat color="dark" label="GIFT CARDS" class="custom-hover text-weight-bold text-h7" />
        </div>

        <q-space />

        <div class="q-mr-lg q-gutter-md gt-sm">
          <q-btn flat color="dark" label="Find a store" class="text-weight-bold q-mr-xl" icon="location_on" no-caps />
          <q-btn rounded outline color="dark" label="Sign In" class="text-weight-bold" no-caps />
          <q-btn rounded color="dark" label="Join Now" class="text-weight-bold" no-caps />
        </div>

        <div class="lt-md">
          <q-btn flat dense round icon="menu" aria-label="Menu" @click="drawerOpen = !drawerOpen" color="primary" />
        </div>

      </q-toolbar>
    </q-header>

    <q-drawer v-model="drawerOpen" :width="250" side="right">
      <q-list>
        <q-item clickable exact v-ripple to="/" active-class="q-item-active">
          <q-item-section avatar>
            <q-icon name="list" />
          </q-item-section>
          <q-item-section>
            Todo
          </q-item-section>
        </q-item>

        <q-item clickable exact v-ripple to="/help" active-class="q-item-active">
          <q-item-section avatar>
            <q-icon name="help" />
          </q-item-section>
          <q-item-section>
            Help
          </q-item-section>
        </q-item>
      </q-list>
    </q-drawer>

    <q-footer elevated class="q-pt-lg bg-white">
      <div class="row flex justify-start q-px-lg">
        <div class="column inline q-ml-lg" style="max-width: 190px; width: 190px">
          <div class="text-dark q-mb-md" style="font-size: 19px">
            About Us
          </div>
          <a class="q-py-sm q-mb-sm" href=" #">Our Company</a>
          <a class="q-py-sm q-mb-sm" href="#">Our Coffee</a>
          <a class="q-py-sm q-mb-sm" href="#">Stories and News</a>
          <a class="q-py-sm q-mb-sm" href="#">Starbucks Archive</a>
          <a class="q-py-sm q-mb-sm" href="#">Investor Relations</a>
          <a class="q-py-sm q-mb-sm" href="#">Customer Service</a>
          <a class="q-py-sm q-mb-sm" href="#">Contact Us</a>
        </div>
        <div class="column inline q-ml-lg" style="max-width: 190px;width: 190px">
          <div class="text-dark q-mb-md" style="font-size: 19px">
            Careers
          </div>
          <a class="q-py-sm q-mb-sm" href=" #">Culture and Values</a>
          <a class="q-py-sm q-mb-sm" href="#">Inclusion, Diversity, and Equity</a>
          <a class="q-py-sm q-mb-sm" href="#">College Achievement Plan</a>
          <a class="q-py-sm q-mb-sm" href="#">Alumni Community</a>
          <a class="q-py-sm q-mb-sm" href="#">U.S. Careers</a>
          <a class="q-py-sm q-mb-sm" href="#">Customer Service</a>
          <a class="q-py-sm q-mb-sm" href="#">International Careers</a>
        </div>
        <div class="column inline q-ml-lg" style="max-width: 190px;width: 190px">
          <div class="text-dark q-mb-md" style="font-size: 19px">
            Social Impact
          </div>
          <a class="q-py-sm q-mb-sm" href=" #">People</a>
          <a class="q-py-sm q-mb-sm" href="#">Planet</a>
          <a class="q-py-sm q-mb-sm" href="#">Environmental and Social Impact Reporting</a>
        </div>
        <div class="column inline q-ml-lg" style="max-width: 190px;width: 190px">
          <div class="text-dark q-mb-md" style="font-size: 19px">
            For Business Partners
          </div>
          <a class="q-py-sm q-mb-sm" href=" #">Landlord Support Center</a>
          <a class="q-py-sm q-mb-sm" href="#">Suppliers</a>
          <a class="q-py-sm q-mb-sm" href="#">Corporate Gift Card Sales</a>
          <a class="q-py-sm q-mb-sm" href="#">Office and Foodservice Coffee</a>
        </div>
        <div class="column inline q-ml-lg" style="max-width: 190px;width: 190px">
          <div class="text-dark q-mb-md" style="font-size: 19px">
            Order and Pick Up
          </div>
          <a class=" q-py-sm q-mb-sm" href=" #">Order on the App</a>
          <a class="q-py-sm q-mb-sm" href="#">Order on the Web</a>
          <a class="q-py-sm q-mb-sm" href="#">Delivery</a>
          <a class="q-py-sm q-mb-sm" href="#">Order and Pick Up Options</a>
          <a class="q-py-sm q-mb-sm" href="#">Explore and Find Coffee for Home</a>
        </div>
      </div>

      <q-separator class="q-my-lg" />

      <ul class="flex row ">
        <li>
          <q-btn unelevated color="dark" text-color="white" round size="12px">
            <q-icon name="fa-brands fa-spotify" />
          </q-btn>
        </li>
        <li>
          <q-btn unelevated color="dark" text-color="white" round size="12px">
            <q-icon name="fa-brands fa-facebook" />
          </q-btn>
        </li>
        <li>
          <q-btn unelevated color="dark" text-color="white" round size="12px">
            <q-icon name="fa-brands fa-pinterest" />
          </q-btn>
        </li>
        <li>
          <q-btn unelevated color="dark" text-color="white" round size="12px">
            <q-icon name="fa-brands fa-instagram" />
          </q-btn>
        </li>
        <li>
          <q-btn unelevated color="dark" text-color="white" round size="12px">
            <q-icon name="fa-brands fa-youtube" />
          </q-btn>
        </li>
        <li>
          <q-btn unelevated color="dark" text-color="white" round size="12px">
            <q-icon name="fa-brands fa-twitter" />
          </q-btn>
        </li>
      </ul>

      <ul class="column inline q-mt-md">
        <a class="footerText q-py-md q-mb-xs" href="">Privacy Notice</a>
        <a class="footerText q-py-md q-mb-xs" href="">Consumer Health Privacy Notice</a>
        <a class="footerText q-py-md q-mb-xs" href="">Terms of Use</a>
        <a class="footerText q-py-md q-mb-xs" href="">Do Not Share My Personal Information</a>
        <a class="footerText q-py-md q-mb-xs" href="">CA Supply Chain Act</a>
        <a class="footerText q-py-md q-mb-xs" href="">Accessibility</a>
        <a class="footerText q-py-md q-mb-xs" href="">Cookie Preferences</a>
      </ul>

      <p class="text-dark q-ml-lg" style="opacity: 0.6">© 2024 Starbucks Coffee Company. All rights reserved.</p>

    </q-footer>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup>
import { ref } from 'vue'

const drawerOpen = ref(false)

defineOptions({
  name: 'MainLayout'
})

</script>

<style lang="scss">
.header-image {
  height: 200%;
  z-index: -1;
}

li {
  display: inline-block;
  position: relative;
  margin-right: 9px;
}

.footerText {
  opacity: 1 !important;
}

a {
  text-decoration: none;
  font-size: 16px;
  opacity: 0.6;
  color: #000;
}

.headerClass {
  background: white;
}

.custom-hover {
  transition: color 0.5s;
  font-size: large;
}

.custom-hover:hover {
  color: #00704A !important;
}
</style>
