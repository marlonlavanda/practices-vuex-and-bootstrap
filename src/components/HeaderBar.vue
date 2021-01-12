<script>
  export default {
    name: 'HeaderBar'
  }
</script>
<template>
  <div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-button v-b-toggle.sidebar-1> <a><i class="fas fa-bars"></i></a> </b-button>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <!-- <b-navbar-nav>
        <b-nav-item href="#">Link</b-nav-item>
        <b-nav-item href="#" disabled>Disabled</b-nav-item>
      </b-navbar-nav> -->
      
      
      <b-navbar-nav >
        <b-nav-item>
          <a><i class="fas fa-bars"></i></a>
        </b-nav-item>
        <b-nav-item>
          <a><i class="fas fa-bars"></i></a>
        </b-nav-item>
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template #button-content>
            <!-- <em>User</em> -->
            <b-avatar variant="primary" text="BV"></b-avatar>
          </template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>