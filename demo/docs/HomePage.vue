<template>
    <div>


      <container>


      <row>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="cyan" class="icon-arvan"><fa icon="cloud"  /></badge>
            <span class="home-feature-text">Cloud Storage</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="green" class="icon-arvan"><fa icon="cog"  /></badge>
            <span class="home-feature-text">Powerful System</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="purple" class="icon-arvan"><fa icon="check-circle"  /></badge>
            <span class="home-feature-text">Heigh Performance</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
        <column md="3" class="text-center home-feature-box">
          <a href="#">

            <badge pill color="orange" class="icon-arvan"><fa icon="share-alt"  /></badge>
            <span class="home-feature-text">Easy Management</span>
            <p>
              Donec tempore finibus ante ac luctus. Fusce facilisis nisi.
            </p>
          </a>
        </column>
      </row>
      <ul class="py-2 text-center">
        <li><btn tag="a" size="sm" color="default" href="#/components/grid" target="_blank">Grid</btn></li>
        <li><btn tag="a" size="sm" color="default" href="#/components/liveDemo" target="_blank">Live Demo</btn></li>
      </ul>
      </container>
    </div>
</template>

<script>
import { Badge, Container, Column, Row, Fa, Navbar, NavbarItem, NavbarNav, NavbarCollapse, Btn, EdgeHeader, CardBody } from 'mdbvue';

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
  .icon-arvan{
    padding: 11px;
    margin: 11px;
  }
  .home-feature-text{
    display: block;
    color: black;
    font-size: 18px;
    font-weight: normal;
  }
  .home-feature-box p {
    color: black;
    margin: 10px;
  }

</style>
