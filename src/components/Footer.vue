<template>
  <div class="card-deck">
    <div class="card">
      <img
        src="../assets/img_mountains_wide.jpg"
        class="card-img-top"
        alt="..."
      />
    </div>
    <div class="card">
      <div class="card-body">
        <a data-toggle="list" href="#list-home" role="tab" aria-controls="home"
          >About Us</a
        ><br />
        <a data-toggle="list" href="#" role="tab" aria-controls="profile"
          >Offers & Promotions</a
        ><br />
        <a data-toggle="list" href="#" role="tab" aria-controls="messages"
          >Advertisement with us</a
        ><br />
        <a data-toggle="list" href="#" role="tab" aria-controls="settings"
          >Careers</a
        ><br />
        <a data-toggle="list" href="#" role="tab" aria-controls="settings"
          >Contact Us</a
        >
      </div>
    </div>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Terms&Condiions Refunds&Cancellations</h5>
        <h5 class="card-title">Customer Care</h5>
        <p class="card-text">
          1800-879-573<br />
          helpme@mlraj.com
        </p>
      </div>
    </div>
    <div class="card">
      <div class="card-body">
        <h5 class="card-title">Follow us</h5>
        <span
          ><i type="button" style="font-size: 24px" class="fa"
            >&#xf09a;</i
          ></span
        >
        <span
          ><i type="button" style="font-size: 24px" class="fa"
            >&#xf09a;</i
          ></span
        >
        <span
          ><i type="button" style="font-size: 24px" class="fa"
            >&#xf09a;</i
          ></span
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
  text-align: right;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: black;
}
.input-group {
  width: 25%;
}
.card {
  text-align: left;
  border: none;
  margin: 0% 2%;
}
.card-deck {
  padding: 3%;
}
</style>
