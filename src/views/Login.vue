<template>
  <div >

    <!-- <b-container class="bv-example-row min-vh-100" fluid="xl">
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
    </b-container> -->

      <b-container class="w-50">
        <b-row class="vh-100 text-center" align-v="center">
          <b-col>
            <b-container class="mb-3">
                <img src="https://media.glassdoor.com/sqll/1928032/utility-hive-squarelogo-1579012564148.png" alt="">
            </b-container>
            <b-container class="mb-3">
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
      <b-container>
      <b-carousel
        id="carousel-no-animation"
        style="text-shadow: 0px 0px 2px #000"
        animation
        indicators
        img-width="1024"
        img-height="480"
      >
        <b-carousel-slide
          caption="First slide"
          img-src="https://picsum.photos/1024/480/?image=10"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Second Slide"
          img-src="https://picsum.photos/1024/480/?image=12"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Third Slide"
          img-src="https://picsum.photos/1024/480/?image=22"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Fourth Slide"
          img-src="https://picsum.photos/1024/480/?image=23"
        ></b-carousel-slide>
      </b-carousel>
    </b-container>
    </b-container>
    
        
  </div>
  <!-- https://vuejsexamples.com/tag/slider/ -->
</template>

<script>
export default {

}
</script>