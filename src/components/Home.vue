<template>
    <span>
        <h2 class="home">{{msg}}</h2>
        <div class="row">
            <div class="left-floater">
                <h4 class="header">Some input</h4>
            </div>
            <div class="right-floater">
                <input type="text" name="input" v-on:keyup="keyPressed">
            </div>
        </div>
    </span>
</template>

<script>
    export default {
        name: 'home',
        data () {
            return {
              msg: 'Welcome to Your Vue.js App'
            }
        },
        methods: {
            keyPressed: function(e){
                console.log('Input name: ' + e.target.name + '\n' +                 e.target.name + '\'s value: ' + e.target.value);
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
