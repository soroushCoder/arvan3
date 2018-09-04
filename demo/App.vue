<template>
  <div id="app" class="flyout">
    <div class="header-arvan">
    <navbar dark position="top" class="" scrolling>
      <span class="arvan-brand">
        D
      </span>
      <navbar-collapse>
        <navbar-nav right>
          <navbar-item href="#/" waves-fixed>Home</navbar-item>
          <navbar-item href="#" waves-fixed>About</navbar-item>
          <navbar-item href="#" waves-fixed>Screen</navbar-item>
          <navbar-item href="#" waves-fixed>Contact</navbar-item>
          <button class="Create-Button">Create account</button>
        </navbar-nav>
      </navbar-collapse>
    </navbar>
      <div class="row top-position">
        <div class="col-md-6">
          <p class="bolder">
            Manage All of Your Tasks in One Place.
          </p>
          <p >
           Nulla, euismod tellus nec tortor ornare from id luctus lorem pharetra.
          </p>
          <button class="Learn-Button">Learn More</button>
        </div>
        <div class="col-md-6">

          <img src="./assets/mobile.png" height="513" width="280"/></div>
      </div>
    </div>
    <main :style="{marginTop: '60px'}">
      <router-view></router-view>
    </main>
    <Ftr color="default-color">
      <p class="footer-copyright mb-0 py-3 text-center">
        &copy; {{new Date().getFullYear()}} Copyright: <a href="https://www.MDBootstrap.com"> MDBootstrap.com </a>
      </p>
    </Ftr>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import NavbarItem from '@/components/NavbarItem.vue';
import NavbarNav from '@/components/NavbarNav.vue';
import NavbarCollapse from '@/components/NavbarCollapse.vue';
import Ftr from '@/components/Footer.vue';
import EdgHd from '@/components/EdgeHeader.vue';
import mdbNavbarBrand from '@/components/NavbarBrand.vue';
import { Btn } from 'mdbvue';

export default {
  name: 'app',
  components: {
    Navbar,
    NavbarItem,
    NavbarNav,
    NavbarCollapse,
    Ftr,
    EdgHd,
    mdbNavbarBrand,
    Btn
  }
};

</script>

<style>
.flyout {
	display:flex;
	flex-direction: column;
	min-height:100vh;
	justify-content: space-between;
}
  .Create-Button{

    color: white;
    border:1px solid white;
    -webkit-border-radius: 10em;
    border-radius: 10em;
    background-color: inherit;
  }
  .header-arvan{
    background-image: linear-gradient(to bottom right,#c96dd8, #3525af)!important;
    height: 550px;
  }
.header-arvan .navbar{
  -webkit-box-shadow: none;
  box-shadow: none;
}
  .arvan-brand{
    font-weight: 800;
    font-size: x-large;
    background-color: white;
    border-radius: 30px;
    color: #c66cd7!important;
    height: 35px;
    width: 35px;
    text-align: center;
  }
  .top-position{
    margin-top: 150px;
    padding: 0 20%;
  }
  .top-position p {

    width: 180px;
    color: white;
  }
.top-position .bolder{
  font-weight: bolder;
  font-size: 20px;
}
  .Learn-Button{
    color: #3e32b3;
    -webkit-border-radius: 10em;
    border-radius: 10em;
    background-color: white;
    padding: 12px;
    border: 0;
  }

</style>
