<template>

    <div>
        <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">Name</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item to="/">Home</b-nav-item>
            <b-nav-item to="/about">About</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item-dropdown text="DD" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item-dropdown text="DD" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto mr-1">
        <router-link to="/AddtoCart">
        <b-button style="width=2px; height= 2px;" class="mr-2">
         <div class="mr-1">
            <svg  width=50 height=30 xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" x="0px" y="0px" viewBox="0 0 100 125" style="enable-background:new 0 0 100 100;" xml:space="preserve"><path d="M39.8,76.1c-5.6,0-10.2,4.6-10.2,10.2c0,5.6,4.6,10.2,10.2,10.2C45.4,96.5,50,92,50,86.3v0C50,80.7,45.4,76.1,39.8,76.1z   M44.7,86.3c0,2.7-2.2,4.9-4.9,4.9c-2.7,0-4.9-2.2-4.9-4.9c0-2.7,2.2-4.9,4.9-4.9C42.5,81.5,44.7,83.6,44.7,86.3z M73.8,76.1  c-5.6,0-10.2,4.6-10.2,10.2c0,5.6,4.6,10.2,10.2,10.2h0C79.4,96.6,84,92,84,86.3c0-2.7-1.1-5.3-3-7.2C79.1,77.2,76.5,76.1,73.8,76.1  z M78.6,86.3c0,1.3-0.5,2.5-1.4,3.4c-0.9,0.9-2.1,1.4-3.4,1.4c-2.7,0-4.9-2.2-4.9-4.9c0-2.7,2.2-4.9,4.9-4.9  C76.4,81.5,78.6,83.6,78.6,86.3z M98.7,18.7c-0.5-0.7-1.3-1.1-2.2-1.1H25l-0.8-4.9c-0.8-5.3-5.4-9.2-10.8-9.2c0,0,0,0,0,0H3.5  c-1.5,0-2.7,1.2-2.7,2.7s1.2,2.7,2.7,2.7h9.9c0,0,0,0,0,0c2.8,0,5.1,2,5.5,4.7l7.9,49.6c0.8,5.4,5.3,9.2,10.8,9.2c0,0,0,0,0,0h48.5  c1.5,0,2.7-1.2,2.7-2.7c0-1.5-1.2-2.7-2.7-2.7H37.6c0,0,0,0,0,0c-2.7,0-5.1-2-5.5-4.7L31,55.1h48.5c4.7,0,8.8-3,10.3-7.4L99,21.1  C99.3,20.3,99.2,19.4,98.7,18.7z M92.7,22.9l-8,23.1c-0.8,2.2-2.9,3.7-5.3,3.7H30.1l-4.2-26.8L92.7,22.9z"/><text x="0" y="115" fill="#000000" font-size="5px" font-weight="bold" font-family="'Helvetica Neue', Helvetica, Arial-Unicode, Arial, Sans-serif">Created by Kru</text><text x="0" y="120" fill="#000000" font-size="5px" font-weight="bold" font-family="'Helvetica Neue', Helvetica, Arial-Unicode, Arial, Sans-serif"></text></svg>
            <b-badge variant="light"></b-badge> 
         </div>
        </b-button>
        </router-link>
    
        
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>
       

        <b-nav-item-dropdown text="Lang" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template #button-content>
            <em>User</em>
          </template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  
    </div>
</template>




<script>


export default {
  name:"home",
components: {
    
    
}
        
    };

</script>

<style  lang="scss" scoped>
#nav a.router-link-exact-active {
    color: white;;
}
</style>