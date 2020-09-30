<template>
  <div class="home">
    <div class="slideshow-container">
      <div class="mySlides fade">
        <div class="numbertext">1 / 3</div>
        <img src="../assets/img_nature_wide.jpg" />
        <div class="text">Caption Text</div>
      </div>

      <div class="mySlides fade">
        <div class="numbertext">2 / 3</div>
        <img src="../assets/img_snow_wide.jpg" />
        <div class="text">Caption Two</div>
      </div>

      <div class="mySlides fade">
        <div class="numbertext">3 / 3</div>
        <img src="../assets/img_mountains_wide.jpg" />
        <div class="text">Caption Three</div>
      </div>

      <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
      <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>
    <br />

    <div style="text-align: center">
      <span class="dot" onclick="currentSlide(1)"></span>
      <span class="dot" onclick="currentSlide(2)"></span>
      <span class="dot" onclick="currentSlide(3)"></span>
    </div>

    <!--<img
      class="img-fluid"
      alt="Mountains Wide"
      src="../assets/img_mountains_wide.jpg"
    />
    <img
      class="img-fluid"
      alt="Nature Wide"
      src="../assets/img_nature_wide.jpg"
    />
    <img class="img-fluid" alt="Snow Wide" src="../assets/img_snow_wide.jpg" />-->
    <div class="home-page">
      <div class="booking">
        <h5>Quick Booking</h5>
        <div class="d-flex">
          <div class="dropdown mr-1">
            <button
              type="button"
              class="btn btn-secondary dropdown-toggle"
              id="dropdownMenuOffset"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              data-offset="10,20"
            >
              Select Movie
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenuOffset">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </div>
          <div class="dropdown mr-1">
            <button
              type="button"
              class="btn btn-secondary dropdown-toggle"
              id="dropdownMenuOffset"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              data-offset="10,20"
            >
              Select Cinema
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenuOffset">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </div>
          <div class="dropdown mr-1">
            <button
              type="button"
              class="btn btn-secondary dropdown-toggle"
              id="dropdownMenuOffset"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              data-offset="10,20"
            >
              Select Date
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenuOffset">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </div>
          <div class="dropdown mr-1">
            <button
              type="button"
              class="btn btn-secondary dropdown-toggle"
              id="dropdownMenuOffset"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              data-offset="10,20"
            >
              Select Timing
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenuOffset">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </div>
          <div>
            <button class="btn btn-secondary">Booking</button>
          </div>
        </div>
      </div>
      <div class="card-group">
        <div class="card jubotron">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Malang</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128151;2.82k</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128151;200</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128151;1k</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128155;1.4k</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
      </div>

      <div class="card-group">
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Malang</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128151;1.2k</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128155;1.2k</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128151;2k</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted">
                Hindi+Comedy+U/A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                &nbsp; &#128151;2.5k</small
              >
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
      </div>
      <h5>Coming Soon</h5>
      <div class="card-group">
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Malang</h5>
            <p class="card-text">
              <small class="text-muted"> Hindi+Comedy+U/A</small>
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted"> Hindi+Comedy+U/A</small>
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted"> Hindi+Comedy+U/A</small>
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
        <div class="card">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              <small class="text-muted"> Hindi+Comedy+U/A </small>
            </p>
            <button id="trailer-btn" class="btn btn-primary" type="submit">
              Play Trailer
            </button>
            <button class="btn btn-primary" type="submit">Show Info</button>
          </div>
        </div>
      </div>
      <h5>Promos & Offers</h5>
      <div class="card-group">
        <div class="card" id="promo">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
            id="promo-img"
          />
        </div>
        <div class="card" id="promo">
          <div class="card-body" id="promo-body">
            <h5 class="card-title">Axis Bank platinum credit card offer</h5>
            <p class="card-text">
              50% off upto 100rs on your first transaction*
            </p>
          </div>
        </div>
        <div class="card" id="promo">
          <img
            src="../assets/img_mountains_wide.jpg"
            class="card-img-top"
            alt="..."
            id="promo-img"
          />
        </div>
        <div class="card" id="promo">
          <div class="card-body" id="promo-body">
            <h5 class="card-title">Win official john Wicks merchandise</h5>
            <p class="card-text">
              Book a ticket for john wick 3 and three lucky winner get a chance
              to win th official meet.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="jumbotron">
      <div class="card-body" id="android">
        <h5 class="card-title">Book Your seats on the Go!</h5>
        <p class="card-text">
          Download the app and book tickets to youe=r <br />favorite films
          whenever, where ever!
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "home",
  components: {},
};
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides((slideIndex += n));
}

function currentSlide(n) {
  showSlides((slideIndex = n));
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {
    slideIndex = 1;
  }
  if (n < 1) {
    slideIndex = slides.length;
  }
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex - 1].style.display = "block";
  dots[slideIndex - 1].className += " active";
}
</script>

<style scoped>
#android {
  background: none;
}

.booking,
.booking h5 {
  text-align: center;
  padding: 1.5%;
  background-color: aliceblue;
  border-radius: 10px;
}
#trailer-btn {
  background-color: white;
  color: black;
}
.home-page {
  padding: 8%;
}
.card-group {
  padding: 1%;
}
#promo {
  height: 192.5px;
}
#promo-body {
  background-color: white;
}
#promo-img {
  height: 100%;
}
.card {
  margin: 1%;
  border: none;
  height: 350px;
}
.card-body {
  background-color: aliceblue;
}
.card-img-top {
  width: 100%;
  height: 55%;
}
.card-body p,
h5 {
  text-align: left;
}
.dropdown,
mr-1 show {
  width: 25%;
}
#dropdownMenuOffset {
  width: 100%;
  text-align: left;
  background-color: white;
  color: black;
}
* {
  box-sizing: border-box;
}
body {
  font-family: Verdana, sans-serif;
  margin: 0;
}
.mySlides {
  display: none;
}
img {
  vertical-align: middle;
}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active,
.dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {
    opacity: 0.4;
  }
  to {
    opacity: 1;
  }
}

@keyframes fade {
  from {
    opacity: 0.4;
  }
  to {
    opacity: 1;
  }
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev,
  .next,
  .text {
    font-size: 11px;
  }
}
</style>