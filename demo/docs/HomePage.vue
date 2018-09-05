<template>
  <div>

    <container>

      <row>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="cyan" class="icon-arvan">
              <fa icon="cloud"/>
            </badge>
            <span class="home-feature-text">Cloud Storage</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="green" class="icon-arvan">
              <fa icon="cog"/>
            </badge>
            <span class="home-feature-text">Powerful System</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="purple" class="icon-arvan">
              <fa icon="check-circle"/>
            </badge>
            <span class="home-feature-text">Heigh Performance</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="orange" class="icon-arvan">
              <fa icon="share-alt"/>
            </badge>
            <span class="home-feature-text">Easy Management</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
      </row>

    </container>
    <row>
      <column md="6"><img style="max-width: 100%;" src="../assets/left.png"/></column>
      <column md="6" class="text-Keep">
        <img src="../assets/watch.png" height="40" width="40"/>
        <p class="bolder">
          Keep Tracking Your Work Progress
        </p>
        <p>
          Donec tempore finibus ante ac luctus. Fusce facilisis nisi.vel odio tincidunt maximus. pellentesque tempus
          gravida viverra Pellentesque dui vehicula.
        </p>
        <button class="Learn-Button">Learn More</button>
      </column>

    </row>
    <row>
      <column md="6" class="text-Keep ">
        <div class="keep-center">
          <img src="../assets/list.png" height="40" width="40"/>
          <p class="bolder">
            Analyse Your Expertise & Capabilities
          </p>
          <p>
            Donec tempore finibus ante ac luctus. Fusce facilisis nisi.vel odio tincidunt maximus. pellentesque tempus
            gravida viverra Pellentesque dui vehicula.
          </p>
          <button class="Learn-Button">Learn More</button>
        </div>
      </column>
      <column md="6"><img style="max-width: 100%;" src="../assets/right.png"/></column>


    </row>
    <container>
      <row>
        <column md="10" class="mx-auto mt-4 text-center">
          <h2 class="pt-4 bolder">
            How It Works
          </h2>
          <p>Donec tempore finibus ante ac luctus. Fusce facilisis nisi.vel odio tincid-</p>
          <p>unt maximus. pellentesque tempus gravida viverra.</p>
        </column>
      </row>
    </container>
    <div class="background-get-app">
      <row class="bottom-get-app">
        <column md="6" class="text-Keep ">
          <div class="keep-center">

            <p class="bolder">
              Get This App Now
            </p>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.vel odio tincidunt maximus. pellentesque tempus
              gravida viverra Pellentesque dui vehicula.
            </p>

          </div>
        </column>
        <column md="6">
          <div class="keep-center-right">
          <row>
            <column md="6"><img src="../assets/playstore.jpg" height="60" width="204"/></column>
            <column md="6"><img src="../assets/appstore.jpg" height="60" width="200"/></column>
          </row>
          </div>
        </column>
      </row>

    </div>
    <container>
      <row>
        <column md="10" class="mx-auto mt-4 text-center">
          <h2 class="pt-4 bolder">
        Quick Overview
          </h2>
          <p>Donec tempore finibus ante ac luctus. Fusce facilisis nisi.vel odio tincid-</p>
          <p>unt maximus. pellentesque tempus gravida viverra.</p>
        </column>
      </row>
    </container>

  </div>
</template>

<script>
  import {
    Badge,
    Container,
    Column,
    Row,
    Fa,
    Navbar,
    NavbarItem,
    NavbarNav,
    NavbarCollapse,
    Btn,
    EdgeHeader,
    CardBody
  } from 'mdbvue';

  export default {
    name: 'HomePage',
    components: {
      Container,
      Column,
      Row,
      Fa,
      Navbar,
      NavbarItem,
      NavbarNav,
      NavbarCollapse,
      Btn,
      EdgeHeader,
      CardBody,
      Badge
    }
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
  }

  .home-feature-box {
    padding: 40px 0;
  }

  .home-feature-box i {
    font-size: 2rem;
  }

  .home-feature-box .icon-arvan {

  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
  }

  a {
    color: #42b983;
  }

  .icon-arvan {
    padding: 11px;
    margin: 11px;
  }

  .home-feature-text {
    display: block;
    color: black;
    font-size: 18px;
    font-weight: normal;
  }

  .home-feature-box p {
    color: black;
    margin: 10px;
  }

  .text-Keep {
    margin: auto;
  }

  .text-Keep p {

    width: 370px;

  }

  .text-Keep .bolder {
    font-weight: bolder;
    font-size: 25px;
    padding-top: 10px;
  }

  .Learn-Button {
    color: #fff;
    -webkit-border-radius: 10em;
    border-radius: 10em;
    background-color: #3023ae;
    padding: 12px;
    border: 0;
  }

  .keep-center {
    padding: 10% 20% 10% 30%;
  }
  .keep-center-right {
    padding: 10% 30% 10% 10%;
  }


  .background-get-app {
    background-image: url("../assets/background2.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    width: 100%;
    min-height: 1000px;
    margin-top: 100px;
  }

  .bottom-get-app {
    padding-top: 700px;
  }
.bottom-get-app .text-Keep{
  color: white!important;
}
</style>
