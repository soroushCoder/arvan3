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


    <div class="clearfix"></div>
    <section class="footer-style-one">
      <div class="auto-container">
        <div class="row clearfix">

          <div class="column col-md-6 col-sm-12 col-xs-12">
            <div class="copyright">Designed by <a href="http://themebunch.com/newwp/ambition/#">GoldeLayers</a> | Powered by WordPress</div>
          </div>
          <div class="nav-column col-md-6 col-sm-12 col-xs-12">
            <ul class="footer-nav">
              <li id="menu-item-207" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-9 current_page_item menu-item-207 active"><a title="Home" href="http://themebunch.com/newwp/ambition/" class="hvr-underline-from-left1" data-scroll="" data-options="easing: easeOutQuart">Home</a></li>
              <li id="menu-item-206" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-206"><a title="Blog Grid View" href="http://themebunch.com/newwp/ambition/blog-grid-view/" class="hvr-underline-from-left1" data-scroll="" data-options="easing: easeOutQuart">Blog Grid View</a></li>
              <li id="menu-item-205" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-205"><a title="Our Blog" href="http://themebunch.com/newwp/ambition/our-blog/" class="hvr-underline-from-left1" data-scroll="" data-options="easing: easeOutQuart">Our Blog</a></li>
            </ul>
          </div>

        </div>
      </div>
    </section>
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
.footer-arvan{
  background-color: black;
  color: white;
}
  .Create-Button{

    color: white;
    border:1px solid white;
    -webkit-border-radius: 10em;
    border-radius: 10em;
    background-color: inherit;
  }
  .header-arvan{
    /*background-image: linear-gradient(to bottom right,#c96dd8, #3525af)!important;*/

    background-image: url("../demo/assets/background.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    min-height: 500px;

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
.footer-style-one .footer-nav li a {
  position: relative;
  color: #abaab0;
  font-size: 14px;
  font-weight: 500;
  text-transform: uppercase;
  -webkit-transition: all 300ms ease;
  -ms-transition: all 300ms ease;
  -o-transition: all 300ms ease;
  -moz-transition: all 300ms ease;
  transition: all 300ms ease;
}
.footer-style-one .footer-nav li {
  position: relative;
  margin-left: 28px;
  display: inline-block;
}
.footer-style-one .footer-nav {
  position: relative;
}
.footer-style-one .nav-column {
  position: relative;
  text-align: right;
}
  .auto-container {
    position: static;
    max-width: 1200px;
    padding: 0px 15px;
    margin: 0 auto;
  }
.footer-style-one {
  position: relative;
  padding: 28px 0px;
  background-color: #1c232b;
}
.footer-style-one .copyright {
  position: relative;
  color: #abaab0;
  font-size: 16px;
  font-weight: 400;
}
.footer-style-one .copyright a {
  position: relative;
  color: #ffffff;
}
</style>
