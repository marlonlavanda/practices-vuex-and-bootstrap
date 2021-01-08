<template>
  <div class="login min-vh-100">

    <b-container class="bv-example-row min-vh-100" fluid="xl">
      <b-row class="mt-5" >
        <b-col>
          <b-img center src="https://images.pexels.com/photos/1540977/pexels-photo-1540977.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="Center image" class="w-100"></b-img>
        </b-col>

        <b-col align-self="center">
          <b-container >
            <h1>Log in</h1>
              <form-group label-cols-lg="3"
                label-cols-sm="4"
                content-cols-lg="7"
                 class="m-5"> 
                <b-form-input id="nested-street" placeholder="username"></b-form-input>
              </form-group>
              <form-group label-cols-lg="3"> 
                <b-form-input id="nested-street" placeholder="password"></b-form-input>
              </form-group>
               <b-button href="#" variant="dark" class="mt-3" block>Login</b-button>

          </b-container>
        </b-col>
      </b-row>
    </b-container>


      
  </div>
</template>

<script>
export default {

}
</script>