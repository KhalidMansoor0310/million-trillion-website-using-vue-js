<template>
  <div class="element">
    <div id="premiere" class="font-family-1">
      <div class="justify-content-center element__header-div d-flex m-auto">
        <h2 class="pb-1">PREMIERE</h2>
      </div>

      <div
        class="d-lg-flex d-none justify-content-center m-auto element__framebg"
      >
        <iframe
          src="https://www.youtube.com/embed/E7wJTI-1dvQ"
          frameborder="2"
          allow="autoplay; encrypted-media"
          title="video"
          width="30%"
          height="100%"
        ></iframe>
      </div>

      <div class="d-flex d-lg-none justify-content-center element__framebg">
        <iframe
          src="https://www.youtube.com/embed/E7wJTI-1dvQ"
          frameborder="2"
          allow="autoplay; encrypted-media"
          title="video"
        ></iframe>
      </div>

      <div class="text-center mt-4">
        <h4>PREMIERE</h4>
        <h2>SEPTEMBER 2, 2020</h2>
        <div class="text-white">Available On Our Official YouTube Channel</div>
      </div>

      <div class="d-flex justify-content-center element__youtube-icon py-3">
        <i class="fab fa-youtube fa-3x"></i>
        <button class="btn btn-danger element__youtube-btn">WATCH NOW</button>
      </div>
    </div>
    <div class="events container" id="events">
      <div
        class="events__header-div d-flex m-auto font-family-1 justify-content-center"
      >
        <h2>A HELPING HAND FOR CHARITY</h2>
      </div>
      <div class="col-12 col-lg-5 text-center m-auto events__contents-div">
        <div class="text-muted mb-4">
          From August 13, 2019 <br />at London Hilton on Park Lane Grand
          Ballroom,
        </div>
        <p class="text-white">
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s, when an unknown printer took a galley of type and
          scrambled it to make a type specimen book. It has survived not only
          five centuries, but also the leap into electronic typesetting,
          remaining essentially unchanged. It was popularised in the 1960s with
          the release of Letraset sheets containing Lorem Ipsum passages, and
          more recently with desktop publishing software like Aldus PageMaker
          including versions of Lorem Ipsum.
        </p>
        <div class="events__benifits d-flex justify-content-center m-auto">
          <h2>BENEFICIARIES</h2>
        </div>
      </div>
    </div>

    <div class="imagesGallery" id="images">
      <div
        class="events__header-div d-flex m-auto font-family-1 justify-content-center"
      >
        <h2>IMAGE GALLERY</h2>
      </div>
      <div class="col-lg-6 container">
        <div class="row row-cols-3 row-cols-lg-4">
          <div
            class="imageGallery__images-div"
            :key="img.id"
            v-for="img in images"
          >
            <img :src="img.image" alt="" />
          </div>
        </div>
      </div>
    </div>

    <div id="review">
      <div class="font-family-1">
        <div class="d-flex justify-content-center m-auto review__header-div">
          <h2>REVIEW</h2>
        </div>
        <div class="bg_image row">
          <div class="reviews col-9 col-md-6 col-lg-5">
            <h2>"IT WAS AN INCREDIBLE EVENT!"</h2>
            <p class="text-muted font-family-2" style="text-align: right">
              - Teddy bakraa
            </p>
            <br /><br />
            <h2>"IT WAS AN INCREDIBLE EVENT!"</h2>
            <p class="text-muted font-family-2" style="text-align: right">
              - Teddy bakraa
            </p>
            <br /><br />
            <h2>"IT WAS AN INCREDIBLE EVENT!"</h2>
            <p class="text-muted font-family-2" style="text-align: right">
              - Teddy bakraa
            </p>
            <br /><br />
            <h2>"IT WAS AN INCREDIBLE EVENT!"</h2>
            <p class="text-muted font-family-2" style="text-align: right">
              - Teddy bakraa
            </p>
            <br /><br />
            <h2>"IT WAS AN INCREDIBLE EVENT!"</h2>
            <p class="text-muted font-family-2" style="text-align: right">
              - Teddy bakraa
            </p>
          </div>
          <div class="col-12 col-md-6 col-lg-7">
            <a
              ><img
                src="../assets/img/trillion.png"
                alt="logo"
                style="width: 100%"
            /></a>
          </div>
        </div>
      </div>
    </div>

    <div class="font-family-1 container-fluid footer">
      <div class="row justify-content-center mb-5">
        <div class="col-12 col-lg-5 p-5">
          <h3>SUBSCRIBE TO OUR NEWSLETTER</h3>
          <form class="d-lg-flex align-items-center mt-4">
            <div
              class="mb-2 font-family-2 mb-lg-0 w-100 form-group footer__form-group"
            >
              <input
                name="email"
                id="exampleEmail"
                placeholder="Email Address"
                type="email"
                class="bg-white form-control"
              />
            </div>
            <button class="footer__btn p-2 m-1">SUBSCRIBE</button>
          </form>
        </div>
        <div class="col-12 col-lg-7 p-5">
          <div>
            <h3>FOLLOW US ON</h3>
            <ul class="p-0 pt-3 d-flex justify-content-between">
              <i class="fab fa-facebook fa-3x text-white"></i
              ><i class="fab fa-twitter fa-3x text-white"></i
              ><i class="fab fa-instagram fa-3x text-white"></i
              ><i class="fab fa-youtube fa-3x text-white"></i
              ><i class="fab fa-twitter fa-3x text-white"></i>
            </ul>
            <h3 class="pt-3 pb-3">GOT A QUESTION?</h3>
            <div
              class="d-flex ml-1 row row-cols-1 row-cols-lg-3 justify-content-between"
            >
              <div class="mb-2">
                <h6>FOR MORE INFO</h6>
                <a class="link font-family-2" href="/">info@tritonseries.com</a>
              </div>
              <div class="mb-2">
                <h6>JOIN OUR NEXT EVENT</h6>
                <a class="link font-family-2" href="/"
                  >register@tritonseries.com</a
                >
              </div>
              <div class="mb-2">
                <h6>WANT TO BE A SPONSOR?</h6>
                <a class="link font-family-2" href="/"
                  >sponsors@tritonseries.com</a
                >
              </div>
            </div>
            <div class="pt-4 pb-4">
              <a class="link font-family-2" href="/"
                ><i class="fa fa-map-marker-alt text-site-secondary p-1"></i>85,
                Fenlex House, St. John Street, Valleta, VLT1165, Malta</a
              >
            </div>
          </div>
        </div>
        <div class="d-flex font-family-2 justify-content-between">
          <a class="link" href="/">Privacy Policy</a
          ><a class="link" href="/">Terms &amp; Conditions</a
          ><a class="link" href="/">About Paul phua</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Image1 from "../assets/img/img1.png";
import Image2 from "../assets/img/img2.png";
import Image3 from "../assets/img/img3.png";
import Image4 from "../assets/img/img4.png";
import Image5 from "../assets/img/img5.png";
import Image6 from "../assets/img/img6.png";
import Image7 from "../assets/img/img7.png";
import Image8 from "../assets/img/img8.png";
import Image9 from "../assets/img/img9.png";
import Image10 from "../assets/img/img10.png";
import Image11 from "../assets/img/img11.png";
import Image12 from "../assets/img/img12.png";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
  data() {
    return {
      images: [
        {
          id: 1,
          image: Image1,
        },
        {
          id: 2,
          image: Image2,
        },
        {
          id: 3,
          image: Image3,
        },
        {
          id: 4,
          image: Image4,
        },
        {
          id: 5,
          image: Image5,
        },
        {
          id: 6,
          image: Image6,
        },
        {
          id: 7,
          image: Image7,
        },
        {
          id: 8,
          image: Image8,
        },
        {
          id: 9,
          image: Image9,
        },
        {
          id: 10,
          image: Image10,
        },
        {
          id: 11,
          image: Image11,
        },
        {
          id: 12,
          image: Image12,
        },
      ],
    };
  },
};
</script>
<style>
.element__header-div {
  padding-top: 200px;
}
.element__header-div h2 {
  color: #ecbb52;
  border-bottom: 1px solid;
}
.element {
  background-color: #111010;
}
.element__framebg {
  background-color: rgb(24, 24, 24);
  height: 250px;
}
.font-family-1 {
  color: #ecbb52;
  font-family: TrajanPro;
}
.element__youtube-icon {
  color: red;
}
.element__youtube-btn {
  color: white;
  background: red;
  margin-left: 10px;
}
.events__header-div {
  padding-top: 150px;
}
.events__header-div h2 {
  border-bottom: 1px solid;
  padding: 10px 0;
}
.events__contents-div {
  font-size: 14px;
}
.events__benifits {
  padding-top: 100px;
}
.events__benifits h2 {
  padding: 10px 0px;
  color: #ecbb52;
  border-bottom: 1px solid;
}
.events__row {
  margin: 50px 0px 70px;
}
.imageGallery__images-div {
  padding: 10px;
}
.imageGallery__images-div img {
  height: 100%;
  width: 100%;
}
.footer {
  background-color: rgb(24, 24, 24);
  padding: 50px 0px;
}
.link {
  color: white;
  text-decoration: none;
}
.footer__links {
  padding: 0px 50px;
}
.footer__btn {
  background-color: #ecbb52;
}
.bg_image {
  background-image: linear-gradient(180deg, #2d2d2d, rgba(45, 45, 45, 0)),
    url("/static/media/Triton-Millions_KV_prv2_top_sparkle\ 4.145c95b8.png");
  background-position: bottom;
  background-repeat: no-repeat;
  background-size: 100% 50%, contain;
}
.bg_image .reviews {
  max-height: 150px;
  color: #fff;
  padding-left: 200px;
  margin-left: 200px;
  margin-right: -200px;
  z-index: 200;
  margin-top: 15%;
  padding-top: 10px;
  overflow: scroll;
}
.reviews::-webkit-scrollbar {
  display: none; /* for Chrome, Safari, and Opera */
}
.review__header-div {
  padding-top: 150px;
}
.review__header-div h2 {
  border-bottom: 1px solid;
}
</style>
