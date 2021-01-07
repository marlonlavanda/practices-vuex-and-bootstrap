<template>
  <div class="form mt-5">
    <h1>Formularios</h1>

    <form> 
      <b-row>
        <b-col md="3">
          <b-form-input type="text" v-model="texto" :state="comprobar"></b-form-input>
          <small>Mínimo 3 caracteres</small>
        </b-col>
        
        <b-col md="3">
          <b-form-select v-model="select" :options="animals"></b-form-select>
          <p>Selección: {{select}}</p>
        </b-col>

        <b-col md="3">
          <b-form-radio-group v-model="radio" :options="animalsRadio"></b-form-radio-group>
          <p>Radio: {{radio}}</p>
        </b-col>

        <b-col md="3">
          <b-form-checkbox-group v-model="check" :options="animalsRadio"></b-form-checkbox-group>
          <p>Múltiple: {{check}}</p>
        </b-col>
      </b-row>
      
    </form>
        <p>{{texto}}</p>

  </div>
</template>

<script>
    export default {
    name: 'Form',
    data(){
      return{
        texto: ' ',
        check: [],
        radio: null,
        select: null,
        animals: [
          { value: null, text: 'Seleccione un animal' },
          { value: 'dog', text: 'gua gua' },
          { value: 'cat', text: 'miau' },
          { value: 'duck', text: 'cuack' },
        ],
        animalsRadio: [
          { value: 'dog', text: 'gua gua' },
          { value: 'cat', text: 'miau' },
          { value: 'duck', text: 'cuack' },
        ]
      }
    },
    computed: {
      comprobar(){
        return this.texto.length > 2 ? true : false
      }
    }
  }
</script>