<template>
  <div class="about">
    <h2>{{msg}}</h2>
     <div class="row v-scroll">
        <div class="left-floater">
            <h4>Lorem ipsum dolor sit<div class="subheader">Amet aliquam faucibus ac</div></h4>
            <p>
                Elementum euismod aenean fermentum. Ligula luctus consequat proin. Mollis bibendum fringilla eu non sed in ac. Sem in nonummy mauris. At id urna vel dolor ipsum tempus mus. Gravida torquent neque dolor. Fusce a tortor vulputate. Habitasse cras ultrices aliquet sagittis augue dui fusce consequat nullam libero et ipsum vel consequat dictumst.
            </p>
            <p>
                Et pellentesque at lacus. Est turpis quis proin eget, scelerisque sociis penatibus tellus massa, justo mauris nobis vestibulum. Wisi sapien sagittis id vel ut odio.
            </p>
        </div>
        <div class="right-floater">
            <h4>Accumsan rutrum arcu quis</h4>
            <p>
                In vulputate nam aliquam. Porttitor suspendisse ultricies sit. Felis eu ac felis. Pharetra omnis eget ornare odio wisi metus risus morbi semper nulla donec vitae in.
                <p>
                    <p class="lead">Eu quis est vestibulum tellus proin purus rhoncus.</p> <p>Turpis ipsum potenti sit ut dolor elit duis. Vitae sed cras a. Elit interdum eleifend sed porta arcu lectus justo dolor malesuada sed ultricies. Enim semper aliquam lectus. Malesuada orci nunc etiam. Risus pede nibh vel. Proin adipiscing laboris vitae suscipit at nisl amet ultricies convallis nulla pede. Nullam eget vestibulum placerat. Nisl et volutpat mauris torquent nam proin sed nulla odio in.</p><p> Proin eu nulla ac duis vitae nulla neque. Ante arcu imperdiet litora ut elit nostra auctor. Phasellus neque mi orci interdum lectus fringilla cursus. Vel mauris maecenas vivamus. Etiam mauris enim felis. Enim interdum porttitor augue. Ut tortor congue feugiat blandit in nulla dui. Blandit sed sodales penatibus. Ornare scelerisque justo suscipit. Vel vestibulum risus erat. At integer vitae arcu. Venenatis ornare semper vel. Integer fringilla nunc orci. Ad mauris felis volutpat. Sagittis rutrum magna lorem nec perspiciatis.</p>
                </p>
            </p>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      msg: 'About Us'
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
