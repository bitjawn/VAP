<template>
  <div class="row">
    <div class="left-floater">
        <h3 class="heading">Contact Us <small>Use snail-mail or call</small></h3>
        <p class="lead text-left">
            Compnay Name and Sub-Name<br>
            12345 Jump Street, Suite 6789</br>
            Philadelphia, PA 19100-2468,</br>
            484-922-3530
        </p>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3054.630027495842!2d-75.14686668430349!3d40.03903897941084!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c6b77848b28efd%3A0xe43e3e1429729ba9!2sOlney+Transportation+Center!5e0!3m2!1sen!2sus!4v1492990855383" class="map" frameborder="0" style="border:0" allowfullscreen></iframe>
    </div>

    <div class="right-floater">
        <h3 class="heading">Send us a message <small>Web Mail</small></h3>
        <form method="post" action="/contact">
                 <div class="input-group">
                    <span class="input-group-label"><i class="fa fa-edit" aria-hidden="true"></i></span>
                    <input type="text" name="name" class="input-group-field" placeholder="Name" required>
                </div>
                
                <div class="input-group">
                    <span class="input-group-label"><i class="fa fa-envelope" aria-hidden="true"></i></span>
                    <input type="email" name="email" class="input-group-field" placeholder="Email" required>
                </div>
                
                 <div class="input-group">
                    <span class="input-group-label"><i class="fa fa-edit" aria-hidden="true"></i></span>
                    <input type="text" name="subject" class="input-group-field" placeholder="Subject">
                </div>
                
                <div class="input-group">
                    <span class="input-group-label"><i class="fa fa-edit" aria-hidden="true"></i></span>                    
                    <textarea class="input-group-field message" name="message" placeholder="Message" ></textarea>
                </div>
                
                <div class="input-group">
                    <div class="input-group-button">
                        <input type="submit" class="button" value="Submit">
                    </div>
                </div>
            </form>
    </div>
</div>
      
</template>

<script>
export default {
  name: 'contact',
  data () {
    return {
      msg: 'Contact Us'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
    font-family: "Comic Sans MS", cursive, sans-serif;
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
