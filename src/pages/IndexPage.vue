<template>
  <q-page class="">
    <!-- Header Section-->
    <div class="header-parent">
      <img src="/bg.jpg" alt="">
      <div class="hero-section-logos-contianer">
        <img src="/galH.png" alt="">
        <img src="/Medea.png" alt="">
        <img src="/gsl.png" alt="">
      </div>
      <div class="header-container desktop-hide" id="expand-head" style="height: ; position:absolute; top: 0; left: 5px">
        <div class="grey-logo relative-position">
          <img src="/gsl.png" alt="Logo">
          <div class="hamburger" style="padding: 15px; position: absolute; right: 10px;">
            <q-icon class="text-grey-8" name="eva-menu-outline" size="30px" />
          </div>
        </div>
        <nav class="header-nav">
          <ul>
            <li><a class="nav-button active-nav" href="#">Home</a></li>
            <li><a class="nav-button" href="#">About</a></li>
            <li><a class="nav-button" href="#">Tuition Fees</a></li>
            <li><a class="nav-button" href="#">Documents</a></li>
            <li><a class="nav-button" href="#">Contact</a></li>
          </ul>
        </nav>
      </div>
      <!-- Header for desktop -->
      <div class="header-container mobile-hide">
        <div class="grey-logo">
          <img src="/gsl.png" alt="Logo">
        </div>
        <nav class="header-nav">
          <ul>
            <li><a class="nav-button active-nav" href="#">Home</a></li>
            <li><a class="nav-button" href="#">About</a></li>
            <li><a class="nav-button" href="#">Tuition Fees</a></li>
            <li><a class="nav-button" href="#">Documents</a></li>
            <li><a class="nav-button" href="#">Contact</a></li>
          </ul>
        </nav>
      </div>

      <!-- Hero Section -->
      <div class="hero-section-main-contianer">
        <div class="hero-section-contianer">
          <div class="hero-section-text-contianer">
            <h1>Join Our Civil Engineering Bachelor’s Degree Program</h1>
            <div class="hh6">
              <h6>with Medea International University</h6>
            </div>

            <p>Greysoft Technologies has partnered with Galilee International Management Institute in offering Civil
              Engineering Bachelor’s Degree to Nigerian students at MEDEA International University </p>
              <div class="hero-section-logos-contianer1">
                <img src="/galH.png" alt="">
                <img src="/Medea.png" alt="">
                <img src="/gsl.png" alt="">
              </div>
              <div class="button-container1">
                <a href="#" class="enroll-button hero-enroll-button">ENROLL NOW <img src="/arrow.png" alt=""></a>
              </div>
          </div>
          <div class="button-container">
            <a href="#" class="enroll-button hero-enroll-button">ENROLL NOW <img src="/arrow.png" alt=""></a>
          </div>
        </div>
      </div>
    </div>

    <!-- Infinite flash Carousel -->

    <div class="slider">
      <div class="slide-track">
        <div class="slide">
          <q-img src="/pic1.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic2.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic3.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic4.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic5.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic6.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic7.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic8.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic9.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic10.jpg" spinner-color="white" style="" />>
        </div>
        <div class="slide">
          <q-img src="/pic1.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic2.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic3.jpg" spinner-color="white" style="" />
        </div>
        <div class="slide">
          <q-img src="/pic1.jpg" spinner-color="white" style="" />
        </div>
      </div>
    </div>

    <!-- About Medea -->

    <div class="about-container q-mt-xl q-mb-md desktop-hide">
      <div class="partnership-certificate">
        <h3 style="font-size: 2.2em; text-align: center;">Partnership Certificate</h3>
      </div>
    </div>
    <div class="about-container q-mt-xl q-mb-xl mobile-hide">
      <div class="partnership-certificate">
        <h3 style="font-size: 2.2em; text-align: center;">Partnership Certificate</h3>
      </div>
    </div>

    <q-card class="my-card desktop-hide" flat style="padding: 0 10px">
      <q-card-section >

        <div class="content" style="display: flex; flex-direction: column; justify-content: center;">
          <h3 class="q-mb-none">About MEDEA International University</h3>
          <p style="font-size: 1.4em;">MED.E.A Higher Education Institution for Mediterranean, Europe and Africa,
            previously known as Pegaso
            International, is a member of the Multiversity Group. It is renowned for providing a flexible,
            inclusive, and accessible education to international students, offering innovative online multilingual
            programmes designed to enhance job opportunities worldwide.</p>

          <div class="download-brochure q-mb-md">
            <a href="/brochure.pdf" download class="brochure-button">Download Brochure</a>
          </div>
          <!-- Partnership Certificate -->
        </div>
        <div class="gscert" @click="alert = true">
          <q-img class="" src="/gscert.jpg" width="100%" style="border: 1px solid;" />
        </div>
      </q-card-section>
    </q-card>

    <q-card class="my-card mobile-hide" flat style="padding: 0 120px">
      <q-card-section horizontal>

        <div class="content q-pa-xl" style="display: flex; flex-direction: column; justify-content: center;">
          <h3 class="q-mb-md">About MEDEA International University</h3>
          <p style="font-size: 1.4em;">MED.E.A Higher Education Institution for Mediterranean, Europe and Africa,
            previously known as Pegaso
            International, is a member of the Multiversity Group. It is renowned for providing a flexible,
            inclusive, and accessible education to international students, offering innovative online multilingual
            programmes designed to enhance job opportunities worldwide.</p>

          <div class="download-brochure">
            <a href="/brochure.pdf" download class="brochure-button">Download Brochure</a>
          </div>
          <!-- Partnership Certificate -->
        </div>
        <div class="col-4 gscert" @click="alert = true">
          <q-img class="" src="/gscert.jpg" width="100%" style="border: 1px solid;" />
        </div>
      </q-card-section>
    </q-card>

    <!-- Main content Section for mobile-->
    <div class="main-section-container desktop-hide">

      <q-card class="my-card addmarg backdrop" flat style="margin: ; padding: 0">
        <q-card-section>
          <q-img class="col-12" src="/job.jpg" />

          <div class="content odd">
            <h3>Job Placements</h3>
            <p>Graduates have the chance to secure up to three-year job placements in civil engineering firms in North
              America and Northern Europe, offering valuable hands-on experience. These positions typically come with
              contracts that include monthly salaries ranging from €2,000 to €3,000, setting you on a solid path
              towards a successful career in civil engineering.</p>

            <div class="button-container">
              <a style="margin: 0" href="#" class="">ENROLL NOW <img src="/arrow.png" alt=""></a>
            </div>
          </div>
        </q-card-section>
      </q-card>


      <q-card class="my-card addmarg" flat style="margin: ; padding: 0">
        <q-card-section >
          <div class="content even">
            <h3>Learning Approach</h3>
            <p>The Bachelor’s Degree in Civil Engineering is delivered entirely online, providing a flexible learning
              environment for students. The programme uses advanced e-learning methods and platforms to facilitate
              coursework, lectures, and interaction with professors and peers. This online approach ensures a
              comprehensive education while benefiting from the flexibility of distance learning.</p>
          </div>

          <q-img class="col-5" src="/study.jpg" />
        </q-card-section>
      </q-card>


      <q-card class="my-card addmarg backdrop" flat style="margin: ; padding: 0">
        <q-card-section >
          <q-img class="col-5" src="/payfee.png" />

          <div class="content odd">
            <h3>Tuition Fees</h3>
            <p>The total tuition fee for the 3-year duration of the programme is 6,000 Euros.</p>
            <ul>
              <li>1st Year: 3,000 Euros</li>
              <li>2nd Year: 1,500 Euros</li>
              <li>3rd Year: 1,500 Euros</li>
            </ul>
            <p>Early Birds who enroll on or before the end of June 2024 will save 1,000 Euros. Installments are allowed.
            </p>
            <div class="button-container">
              <a href="#" class="">ENROLL NOW <img src="/arrow.png" alt=""></a>
            </div>
          </div>
        </q-card-section>
      </q-card>



      <q-card class="my-card addmarg" flat style="margin: ; padding: 0">
        <q-card-section >

          <div class="content even" style="padding-left: 26px; padding-right: 15px">
            <h3>Required Documents</h3>
            <p>To register for the programme, you need to provide the following documents:</p>
            <ul>
              <li>A copy of your valid ID card or passport.</li>
              <li>Your High School Diploma Certificate in English.</li>
              <li>A letter from your graduated High School confirming completion of at least 12 years of schooling and
                qualification for university studies (Level 5 according to EQF or equivalent).</li>
              <li>An updated CV.</li>
              <li>English language certification at a minimum level of B2.</li>
            </ul>
          </div>
          <q-img class="col-5" src="/docu.jpg" />
        </q-card-section>
      </q-card>

      <q-card class="my-card addmarg backdrop" flat style="margin: ; padding: 0">
        <q-card-section horizontal>
          <q-img class="col-5" src="/learn.jpg" />
          <div class="content odd">
            <h3>Class Starts</h3>
            <p>The next academic year is 2024/2025. Your study period starts on 1 August 2024 until 31 July 2025. You
              can start at any time during the academic year.</p>
          </div>
        </q-card-section>
      </q-card>
    </div>

    <!-- Main content for desktop -->
    <div class="main-section-container mobile-hide">

      <q-card class="my-card addmarg backdrop" flat>
        <q-card-section horizontal>
          <q-img class="col-5" src="/job.jpg" />

          <div class="content odd">
            <h3>Job Placements</h3>
            <p>Graduates have the chance to secure up to three-year job placements in civil engineering firms in North
              America and Northern Europe, offering valuable hands-on experience. These positions typically come with
              contracts that include monthly salaries ranging from €2,000 to €3,000, setting you on a solid path
              towards a successful career in civil engineering.</p>

            <div class="button-container">
              <a style="margin: 0" href="#" class="">ENROLL NOW <img src="/arrow.png" alt=""></a>
            </div>
          </div>
        </q-card-section>
      </q-card>


      <q-card class="my-card addmarg" flat>
        <q-card-section horizontal>
          <div class="content even">
            <h3>Learning Approach</h3>
            <p>The Bachelor’s Degree in Civil Engineering is delivered entirely online, providing a flexible learning
              environment for students. The programme uses advanced e-learning methods and platforms to facilitate
              coursework, lectures, and interaction with professors and peers. This online approach ensures a
              comprehensive education while benefiting from the flexibility of distance learning.</p>
          </div>

          <q-img class="col-5" src="/study.jpg" />
        </q-card-section>
      </q-card>


      <q-card class="my-card addmarg backdrop" flat>
        <q-card-section horizontal>
          <q-img class="col-5" src="/payfee.png" />

          <div class="content odd">
            <h3>Tuition Fees</h3>
            <p>The total tuition fee for the 3-year duration of the programme is 6,000 Euros.</p>
            <ul>
              <li>1st Year: 3,000 Euros</li>
              <li>2nd Year: 1,500 Euros</li>
              <li>3rd Year: 1,500 Euros</li>
            </ul>
            <p>Early Birds who enroll on or before the end of June 2024 will save 1,000 Euros. Installments are allowed.
            </p>
            <div class="button-container">
              <a href="#" class="">ENROLL NOW <img src="/arrow.png" alt=""></a>
            </div>
          </div>
        </q-card-section>
      </q-card>



      <q-card class="my-card addmarg" flat>
        <q-card-section horizontal>

          <div class="content even">
            <h3>Required Documents</h3>
            <p>To register for the programme, you need to provide the following documents:</p>
            <ul>
              <li>A copy of your valid ID card or passport.</li>
              <li>Your High School Diploma Certificate in English.</li>
              <li>A letter from your graduated High School confirming completion of at least 12 years of schooling and
                qualification for university studies (Level 5 according to EQF or equivalent).</li>
              <li>An updated CV.</li>
              <li>English language certification at a minimum level of B2.</li>
            </ul>
          </div>
          <q-img class="col-5" src="/docu.jpg" />
        </q-card-section>
      </q-card>

      <q-card class="my-card addmarg backdrop" flat>
        <q-card-section horizontal>
          <q-img class="col-5" src="/learn.jpg" />
          <div class="content odd">
            <h3>Class Starts</h3>
            <p>The next academic year is 2024/2025. Your study period starts on 1 August 2024 until 31 July 2025. You
              can start at any time during the academic year.</p>
          </div>
        </q-card-section>
      </q-card>
    </div>
<!-- For mobile -->
    <div class="desktop-hide q-mt-xl" style="background: rgb(255, 170, 0); padding: 10px; display: flex; flex-direction: column;
    justify-content: center; align-items: center">
      <div style="padding: 10px; width: fit-content; background: black; margin: auto;
      margin-bottom: 15px">
        <h5 style="color: rgb(255, 170, 0); font-weight: 600;">Note</h5>
      </div>
      <p style="text-align: center;">Ensure to contact Greysoft Technologies Nigeria before enrolling.</p>

      <p class="text-center q-ma-sm"> For more information visit: <a href="https://www.galilcol.ac.il/contents.php?id=FAQ_Bsc_Eng">Galilee</a> </p>
      <p class="text-center">
        If you are not enrolling via the Gresoft website, please remember to indicate that you are from Greysoft. This
        will
        help us keep track of your progress and ensure smooth study experience. </p>
    </div>
<!-- For desktop -->
    <div class="notice mobile-hide">
      <div style="padding: 15px; width: fit-content; background: black; margin: auto;
      ">
        <h4 style="color: rgb(176, 141, 16); font-weight: 600">Note</h4>
      </div>
      <p>Ensure to contact Greysoft Technologies Nigeria before enrolling.</p>

      <p> For more information visit: <a href="https://www.galilcol.ac.il/contents.php?id=FAQ_Bsc_Eng">Galilee</a> </p>
      <p>
        If you are not enrolling via the Gresoft website, please remember to indicate that you are from Greysoft. This
        will
        help us keep track of your progress and ensure smooth study experience. </p>
    </div>

    <!-- Footer Section -->
    <div class="footer-main-container">
      <div class="floating-bar">
        <div class="footer-floating-text-container">
          <h3>Ready to start learning?</h3>
          <p>Enroll in our Civil Engineering program today!</p>
          <div class="button-container1">
            <a href="#" class="footerBtn">ENROLL NOW <img src="/arrow.png" alt=""></a>
          </div>
        </div>

        <div class="button-container">
          <a href="#" class="">ENROLL NOW <img src="/arrow.png" alt=""></a>
        </div>
      </div>

      <div class="footer-contents-container">
        <div class="footer-contents-sub-container">
          <div class="footer-content-container footer-col-1">
            <div class="footer-logo-container">
              <img width="100px" src="/gsl.png" alt="">
            </div>
            <p class="footer-header">Physical Address in Nigeria:</p>
            <p>GreyHobb</p>
            <p style="display: flex; align-items: center;">
              <img class="q-mr-xs" width="18px" src="/location.png" alt="">
              31, Gwari Avenue, Barnawa, Kaduna, Nigeria
            </p>
            <p>
              <q-icon class="q-mr-xs" size="xs" name="email" />
              <a href="mailto:hi@greysoft.ng">hi@greysoft.ng</a>
            </p>
          </div>

          <div class="footer-content-container footer-col-2">
            <div>
              <p class="footer-header">Greysoft Nigeria</p>
              <p>
                <q-icon size="xs" name="person" />
                Miss Stephanie Akut
              </p>
              <p>
                <q-icon class="q-mr-xs" size="xs" name="phone" />
                <a href="tel:+234 0000 0000 0">+234 0000 0000 0</a>
              </p>
              <p>
                <q-icon class="q-mr-xs" size="xs" name="email" />
                <a href="mailto:stephanie@greysoft.ng">stephanie@greysoft.ng</a>
              </p>
              <p class="" style="display: flex; align-items: center;">
                <img class="q-mr-xs" width="16px" src="/wts.png" alt="" style="">
                <a href="tel:+234 0000 0000 0">+234 0000 0000 0</a>
              </p>
            </div>
          </div>

          <div class="footer-content-container footer-col-3">
            <div>
              <p class="footer-header">Medea University</p>
              <p>
                <q-icon size="xs" name="person" />
                Mrs Sharon Ben Moshe
              </p>
              <p>
                <q-icon class="q-mr-xs" size="xs" name="email" />
                <a href="mailto:sbenmoshe@galilcol.ac.il">sbenmoshe@galilcol.ac.il</a>
              </p>
              <p>
                <q-icon class="q-mr-xs" size="xs" name="phone" />
                <a href="tel:+972 4 642 8832">+972 4 642 8832</a>
              </p>
            </div>
          </div>
        </div>
      </div>

    </div>

    <q-dialog v-model="alert">
      <q-card style="width: 700px;">
        <q-img class="" src="/gscert.jpg" width="100%" style="" />
        <q-card-actions align="right">
          <q-btn flat label="Close" color="primary" v-close-popup />
        </q-card-actions>
      </q-card>
    </q-dialog>
  </q-page>
</template>

<script>

import { ref } from 'vue'
import SvgIcon from '../components/SvgIcon.vue'
export default {
  name: 'IndexPage',

  data() {
    return {
      text: ""
    }
  },

  components: {
    SvgIcon, // Register the SvgIcon component
  },

  mounted() {
    this.setup()
  },

  methods: {
    setup() {
      let navButtons = document.getElementsByClassName('nav-button')

      for (let i = 0; i < navButtons.length; i++) {
        navButtons[i].addEventListener('click', function () {
          let activeNav = document.getElementsByClassName('active-nav')

          if (activeNav.length > 0) {
            activeNav[0].className = activeNav[0].className.replace(
              ' active-nav',
              ''
            )
          }
          this.className += ' active-nav'
        })
      }

      let hamburger = document.getElementById('expand-head');

    hamburger.addEventListener('click', function () {
      let currentHeight = hamburger.style.height
      if (currentHeight === '300px') {
        hamburger.style.height = '50px' 
      } else {
        hamburger.style.height = '300px'
      }
    })
    },
  },

  setup() {
    return {
      alert: ref(false),

      address: ref('')
    }
  }

}

</script>

<!--  -->

<style>
.gscert {}
</style>


<style lang="scss">
@mixin white-gradient {
  background: linear-gradient(to right, rgba(255, 255, 255, 1) 0%, rgba(255, 255, 255, 0) 100%);
}

$animationSpeed: 40s;

// Animation
@keyframes scroll {
  0% {
    transform: translateX(0);
  }

  100% {
    transform: translateX(calc(-250px * 7))
  }
}


// Styling
.slider {
  background: white;
  box-shadow: 0 10px 20px -5px rgba(0, 0, 0, .125);
  height: 300px;
  margin-top: 30px;
  overflow: hidden;
  position: relative;
  width: 100%;

  &::before,
  &::after {
    content: "";
    height: 100px;
    position: absolute;
    width: 200px;
    z-index: 2;
  }

  &::after {
    right: 0;
    top: 0;
    transform: rotateZ(180deg);
  }

  &::before {
    left: 0;
    top: 0;
  }

  .slide-track {
    height: 100%;
    animation: scroll $animationSpeed linear infinite;
    display: flex;
    width: calc(500px * 14);
  }

  .slide {
    height: 100%;
    background: white;
    width: 500px;
  }

  .slide div {
    height: 100%;
  }
}

.partnership-certificate {
  text-align: center;
  margin-top: 20px;
}

.partnership-certificate h3 {
  font-size: 1.5em;
  margin-bottom: 10px;
}

.partnership-certificate img {
  max-width: 100%;
  height: auto;
  border: 2px solid #ddd;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.download-brochure {
  margin-top: 20px;
}

.brochure-button {
  padding: 10px 20px;
  background-color: rgba(0, 73, 112, 0.9);
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  font-size: 1.2em;
  transition: background-color 0.3s;
}

.brochure-button:hover {
  background-color: rgba(0, 73, 112, 1);
}
</style>
