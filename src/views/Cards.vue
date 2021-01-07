<template>
  <div class="grid mt-5">
    <b-button variant="succes">Texto</b-button>
    <b-button variant="info">Texto</b-button>
    <b-button variant="danger">Texto</b-button>
    <b-button variant="primary">Texto</b-button>
    <b-button variant="warning">Texto</b-button>
    <b-button variant="dark">Texto</b-button>

    <b-row class="mt-5">
      <b-col cols="12" md="4">
        <b-card
        img-src="https://picsum.photos/600/300/?image=25"
        img-top
        >
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta qui voluptate doloremque eius explicabo eum iste mollitia sunt tempore nostrum reprehenderit placeat odit voluptates, corporis esse unde debitis harum? Delectus!</p>
        <b-button href="#" variant="dark">Go somewhere</b-button>
        </b-card>
      </b-col>
      <b-col cols="12" md="4" class="mt-5">
        <b-card
        img-src="https://picsum.photos/600/300/?image=25"
        img-top
        >
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta qui voluptate doloremque eius explicabo eum iste mollitia sunt tempore nostrum reprehenderit placeat odit voluptates, corporis esse unde debitis harum? Delectus!</p>
        <b-button href="#" variant="dark">Go somewhere</b-button>
        </b-card>
      </b-col>
      <b-col cols="12" md="4" class="mt-5">
        <b-card
        img-src="https://picsum.photos/600/300/?image=25"
        img-top
        >
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta qui voluptate doloremque eius explicabo eum iste mollitia sunt tempore nostrum reprehenderit placeat odit voluptates, corporis esse unde debitis harum? Delectus!</p>
        <b-button href="#" variant="dark">Go somewhere</b-button>
        </b-card>
      </b-col>
    </b-row>

  </div>
</template>

<script>
    export default {
    name: 'Grid'
  }
</script>