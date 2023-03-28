<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      THE REAL INFORMATICS SCHOOL
    </p>
    <h3>Address</h3>
    <p>
    Jl. A. P. Pettarani No.4, Gn. Sari, Kec. Rappocini, Kota Makassar, Sulawesi Selatan 90221
    </p>
    <ul>
      <li><a href="https://goo.gl/maps/maURg8YbDWM7JF9c9" target="_blank" rel="noopener">maps</a></li>
    </ul>
    <h3>Phone Number</h3>
    <p>
    0411865222
    </p>
    <ul>
      <li><a href="0411865222" target="_blank" rel="noopener">number</a></li>
    </ul>
    <h3>Our Website</h3>
    <p>
    smktelkom-mks.sch.id
    </p>
    <ul>
      <li><a href="https://smktelkom-mks.sch.id/" target="_blank" rel="noopener">stelk</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  margin: 20px 0 0;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  font-size: 20px;
}
a {
  color: #42b983;
}
p {
  margin: 10px 0 0;
}
</style>
