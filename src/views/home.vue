<template>
  <div class="home-container">
    <app-header></app-header>
    <div class="home-hero">
      <div class="home-container01">
        <div class="home-card">
          <h1 class="home-text headingOne">Fun &amp; Engaging.</h1>
          <h1 class="home-text01 headingOne">That&apos;s CrimeLogic.</h1>
          <span class="home-text02">
            We are a young &amp; ambitious game development studio, diving into
            the Metaverse to serve immersive &amp; entertaining experiences to
            players over the world.
          </span>
          <div class="home-container02">
            <div class="home-container03">
              <primary-pink-button button="contact us"></primary-pink-button>
            </div>
            <outline-gray-button button="read more"></outline-gray-button>
          </div>
        </div>
      </div>
    </div>
    <img
      alt="image"
      src="/playground_assets/curved6-1500h.jpg"
      class="home-image"
    />
    <section id="below" class="home-container04">
      <div class="home-container05">
        <h1 class="home-text03 headingOne">From nothing to something.</h1>
        <span class="home-text04">
          We create new experiences entirely from scratch, from the initial
          concept and design, through development, to the final product.
        </span>
      </div>
      <div class="home-container06">
        <div class="home-container07">
          <img
            alt="image"
            src="https://images.unsplash.com/photo-1560408677-b4af8a53052e?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDIxfHxvZmZpY2UlMjBkZXNrfGVufDB8fHx8MTY2MDQ3MTE0Mg&amp;ixlib=rb-1.2.1&amp;w=1100"
            class="home-image1"
          />
          <div class="home-container08">
            <img
              alt="image"
              src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/soft-ui-design-system/assets/img/coding.jpg"
              class="home-image2"
            />
          </div>
        </div>
        <div class="home-container09">
          <img
            alt="image"
            src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/soft-ui-design-system/assets/img/tasks.jpg"
            class="home-image3"
          />
          <div class="home-container10">
            <h3 class="headingTwo">What is the Metaverse?</h3>
            <p>
              <br />
              <span>
                The Metaverse is a network of virtual worlds that can be visited
                from any internet-connected device. The concept was first
                described by science fiction author Neal Stephenson in his 1992
                novel, Snow Crash. The Metaverse is an evolution of the Internet,
                where users are able to interact with each other and fully
                rendered 3D environments.
              </span>
              <br class="home-text09" />
              <br class="home-text10" />
              <span>
                At CrimeLogic, we work with clients to create the next generation
                of immersive, interactive experiences. With our unique combination
                of technology and design expertise, we create worlds that are
                engaging, dynamic and fun.
              </span>
              <br />
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="home-testimonials">
      <div class="home-container11">
        <div class="home-container12">
          <div class="home-container13">
            <h2 class="home-text13 headingOne">Work with us.</h2>
            <p class="home-text14 lead">
              Let&apos;s turn your imagination into reality
            </p>
            <p class="home-text15">
              We are a small team consisting of a game designer, programmer and an
              artist who work together to create unique experiences. We love
              breaking new ground in game design and engaging people with our
              games. We believe that games can be more than just entertainment –
              they can be powerful tools for communication, education, health and
              wellbeing.
            </p>
            <p class="home-text16">Sander de Winter</p>
            <p class="home-text17">
              <span>Founder &amp; Programmer</span>
              <br />
            </p>
          </div>
        </div>
        <div class="home-logos"></div>
      </div>
      <img
        alt="image"
        src="/playground_assets/bottom.svg"
        class="home-bottom-wave-image"
      />
      <img
        alt="image"
        src="/playground_assets/waves-white.svg"
        class="home-image4"
      />
      <img
        alt="image"
        src="/playground_assets/top.svg"
        class="home-top-wave-image"
      />
    </section>
    <section class="home-contaier">
      <div class="home-container14">
        <div class="home-container15">
          <div class="home-container16"></div>
          <div class="home-container17">
            <svg viewBox="0 0 987.4285714285713 1024" class="home-icon">
              <path
                d="M438.857 508.571l312 312c-79.429 80.571-190.286 130.286-312 130.286-242.286 0-438.857-196.571-438.857-438.857s196.571-438.857 438.857-438.857v435.429zM545.714 512h441.714c0 121.714-49.714 232.571-130.286 312zM950.857 438.857h-438.857v-438.857c242.286 0 438.857 196.571 438.857 438.857z"
              ></path>
            </svg>
            <h1 class="home-text20 headingOne">Research</h1>
          </div>
        </div>
        <div class="home-container18">
          <p>
            <span>
              CrimeLogic actively researches new technology and the use of AI in
              games. We are passionate about understanding why people play and
              what makes them tick. We believe that by understanding human
              behaviour, we can create more engaging games.
            </span>
            <br />
            <br />
            <span>
              We are also working on our own projects to increase our expertise
              and come up with unforeseen ideas that will keep us ahead of the
              curve. Our mission is to create a new breed of games that will
              change the world and make people happier. We believe games have the
              potential to be much more than just entertainment. They can also
              provide an outlet for creativity, expression and communication. We
              want to be a part of this movement by creating innovative games that
              are fun to play but also challenge players’ minds.
            </span>
          </p>
        </div>
      </div>
      <div class="home-divider"></div>
      <div id="image" class="home-banner blur">
        <h1 class="home-text26">
          <span>Let&apos;s get in touch.</span>
          <br />
        </h1>
        <div class="home-container19">
          <primary-pink-button button="contact us"></primary-pink-button>
        </div>
      </div>
    </section>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppHeader from '../components/header'
import PrimaryPinkButton from '../components/primary-pink-button'
import OutlineGrayButton from '../components/outline-gray-button'
import AppFooter from '../components/footer'

export default {
  name: 'Home',
  components: {
    AppHeader,
    PrimaryPinkButton,
    OutlineGrayButton,
    AppFooter,
  },
  metaInfo: {
    title: 'Soft UI Pro',
    meta: [
      {
        property: 'og:title',
        content: 'Soft UI Pro',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-hero {
  width: 100%;
  display: flex;
  max-width: 1320px;
  padding-left: var(--dl-space-space-unitandahalfunit);
  padding-right: var(--dl-space-space-unitandahalfunit);
  justify-content: center;
}
.home-container01 {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 1320px;
  min-height: 85vh;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.home-card {
  flex: 0 0 auto;
  width: 60%;
  display: flex;
  padding: var(--dl-space-space-tripleunit);
  z-index: 1;
  box-shadow: 0 8px 26px -4px hsla(0,0%,8%,.15),0 8px 9px -5px hsla(0,0%,8%,.06)!important;
  margin-top: var(--dl-space-space-tripleunit);
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-radius1);
  flex-direction: column;
  backdrop-filter: saturate(200%) blur(30px);
  background-color: hsla(0,0%,100%,.8);
}
.home-text {
  text-align: center;
  background-image: linear-gradient(310deg,#7928ca,#ff0080);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.home-text01 {
  color: var(--dl-color-secondary-700);
  text-align: center;
  margin-bottom: var(--dl-space-space-unitandahalfunit);
}
.home-text02 {
  color: var(--dl-color-secondary-600);
  font-size: 20px;
  margin-right: var(--dl-space-space-tripleunit);
  margin-bottom: var(--dl-space-space-unit);
  padding-right: var(--dl-space-space-tripleunit);
}
.home-container02 {
  display: flex;
  margin-top: var(--dl-space-space-unitandahalfunit);
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-container03 {
  display: flex;
  align-items: flex-start;
  margin-right: var(--dl-space-space-unit);
  flex-direction: row;
}
.home-image {
  top: 0px;
  left: auto;
  right: 0px;
  width: 50%;
  bottom: 0px;
  height: 80vh;
  position: absolute;
  object-fit: cover;
  object-position: right;
  border-bottom-left-radius: 10rem;
}
.home-container04 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  max-width: 1320px;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
}
.home-container05 {
  display: flex;
  align-items: center;
  margin-left: auto;
  margin-right: auto;
  flex-direction: column;
}
.home-text03 {
  margin-bottom: var(--dl-space-space-halfunit);
  background-image: linear-gradient(310deg,#7928ca,#ff0080);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.home-text04 {
  max-width: 600px;
  text-align: center;
  margin-bottom: var(--dl-space-space-halfunit);
}
.home-container06 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  margin-top: var(--dl-space-space-tripleunit);
  align-items: flex-start;
  margin-left: var(--dl-space-space-unitandahalfunit);
  margin-right: var(--dl-space-space-unitandahalfunit);
  flex-direction: row;
}
.home-container07 {
  flex: 0 0 auto;
  width: 50%;
  height: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.home-image1 {
  width: 100%;
  box-shadow: 0 8px 26px -4px hsla(0,0%,8%,.15),0 8px 9px -5px hsla(0,0%,8%,.06)!important;
  object-fit: cover;
  margin-left: 3rem;
  margin-right: -3rem;
  border-radius: var(--dl-radius-radius-radius75);
}
.home-container08 {
  width: 100%;
  height: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.home-image2 {
  top: 0px;
  left: auto;
  width: 90%;
  bottom: auto;
  display: block;
  position: absolute;
  box-shadow: 0 8px 26px -4px hsla(0,0%,8%,.15),0 8px 9px -5px hsla(0,0%,8%,.06)!important;
  margin-top: -1.5rem;
  object-fit: cover;
  margin-left: 2rem;
  border-radius: var(--dl-radius-radius-radius75);
  margin-bottom: var(--dl-space-space-tripleunit);
}
.home-container09 {
  flex: 0 0 auto;
  width: 40%;
  display: flex;
  position: relative;
  align-items: flex-start;
  padding-left: var(--dl-space-space-triplequarterunit);
  padding-right: var(--dl-space-space-triplequarterunit);
  flex-direction: column;
}
.home-image3 {
  width: 100%;
  box-shadow: 0 8px 26px -4px hsla(0,0%,8%,.15),0 8px 9px -5px hsla(0,0%,8%,.06)!important;
  margin-top: 8rem;
  object-fit: cover;
  margin-left: -1.5rem;
  border-radius: var(--dl-radius-radius-radius75);
  margin-bottom: var(--dl-space-space-tripleunit);
}
.home-container10 {
  width: 90%;
  display: flex;
  align-self: center;
  align-items: flex-start;
  flex-direction: column;
}
.home-testimonials {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  background-image: linear-gradient(310deg,#7928ca,#ff0080);
}
.home-container11 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  z-index: 1;
  max-width: 1320px;
  align-items: flex-start;
  padding-top: 15rem;
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: row;
  padding-bottom: 15rem;
  justify-content: space-between;
}
.home-container12 {
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  align-items: space-between;
  flex-direction: column;
}
.home-container13 {
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  margin-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
}
.home-text13 {
  color: var(--dl-color-gray-white);
}
.home-text14 {
  color: var(--dl-color-gray-white);
  opacity: 0.8;
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-text15 {
  color: var(--dl-color-gray-white);
  opacity: 0.8;
  margin-bottom: var(--dl-space-space-doubleunit);
}
.home-text16 {
  color: var(--dl-color-gray-white);
}
.home-text17 {
  color: var(--dl-color-gray-white);
  opacity: 0.8;
}
.home-logos {
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-bottom-wave-image {
  top: auto;
  left: auto;
  right: 0px;
  width: 100%;
  bottom: -5px;
  position: absolute;
  object-fit: cover;
}
.home-image4 {
  top: auto;
  left: 0px;
  right: 0px;
  width: 100%;
  bottom: auto;
  height: 100%;
  position: absolute;
  object-fit: cover;
}
.home-top-wave-image {
  top: -5px;
  left: auto;
  right: 0px;
  width: 100%;
  bottom: auto;
  position: absolute;
  object-fit: cover;
}
.home-contaier {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  max-width: 1320px;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-tripleunit);
  padding-right: var(--dl-space-space-tripleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
}
.home-container14 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  margin-top: var(--dl-space-space-tripleunit);
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-container15 {
  display: flex;
  position: relative;
  box-shadow: 0 8px 26px -4px hsla(0,0%,8%,.15),0 8px 9px -5px hsla(0,0%,8%,.06)!important;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-sixunits);
  border-radius: var(--dl-radius-radius-radius1);
  padding-right: var(--dl-space-space-sixunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-doubleunit);
  background-size: cover;
  justify-content: flex-start;
  background-image: url('https://raw.githubusercontent.com/creativetimofficial/public-assets/master/soft-ui-design-system/assets/img/team-working.jpg');
  background-position: center;
}
.home-container15:hover {
  transform: scale(1.04);
}
.home-container16 {
  top: 0px;
  left: 0px;
  right: auto;
  width: 100%;
  bottom: auto;
  height: 100%;
  position: absolute;
  background: rgba(0,0,0,.4);
  border-radius: var(--dl-radius-radius-radius1);
}
.home-container17 {
  display: flex;
  z-index: 1;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-icon {
  fill: var(--dl-color-gray-900);
  width: 30px;
  height: 30px;
  margin-bottom: var(--dl-space-space-tripleunit);
}
.home-text20 {
  color: var(--dl-color-gray-white);
  max-width: 200px;
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
.home-container18 {
  display: flex;
  align-items: flex-start;
  margin-left: var(--dl-space-space-fourunits);
  flex-direction: column;
}
.home-divider {
  flex: 0 0 auto;
  width: 90%;
  height: 1px;
  display: flex;
  opacity: 0.25;
  margin-top: 4rem;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-radius75);
  margin-bottom: 4rem;
  flex-direction: column;
  background-color: var(--dl-color-gray-700);
}
.home-banner {
  width: 100%;
  display: flex;
  box-shadow: 0 8px 26px -4px hsla(0,0%,8%,.15),0 8px 9px -5px hsla(0,0%,8%,.06)!important;
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: 48px;
  border-radius: var(--dl-radius-radius-radius1);
  padding-right: 48px;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  background-size: cover;
  justify-content: space-between;
  background-image: url("https://images.unsplash.com/photo-1541746972996-4e0b0f43e02a?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEwfHxvZmZpY2UlMjBtZWV0aW5nfGVufDB8fHx8MTY2MDQ5MTg2OA&ixlib=rb-1.2.1&w=1400");
  background-position: center;
}
.home-text26 {
  color: var(--dl-color-gray-white);
  z-index: 100;
  font-size: 3rem;
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
.home-container19 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  z-index: 100;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
@media(max-width: 1200px) {
  .home-text02 {
    color: var(--dl-color-secondary-600);
    font-size: 20px;
  }
  .home-text04 {
    color: rgb(103, 116, 142);
    font-weight: 400;
    background-color: rgb(255, 255, 255);
  }
  .home-text09 {
    color: #67748e;
    font-weight: 400;
    background-color: rgb(255, 255, 255);
  }
  .home-text10 {
    color: #67748e;
    font-weight: 400;
    background-color: rgb(255, 255, 255);
  }
  .home-text15 {
    color: var(--dl-color-gray-white);
    font-weight: 700;
  }
  .home-text16 {
    color: var(--dl-color-gray-white);
  }
  .home-text17 {
    color: var(--dl-color-gray-white);
  }
}
@media(max-width: 991px) {
  .home-hero {
    padding-left: var(--dl-space-space-tripleunit);
    padding-right: var(--dl-space-space-tripleunit);
  }
  .home-container01 {
    max-width: 960px;
  }
  .home-card {
    width: 100%;
  }
  .home-container04 {
    max-width: 960px;
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
  }
  .home-container05 {
    max-width: 80%;
  }
  .home-text04 {
    text-align: center;
  }
  .home-container11 {
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
    justify-content: center;
  }
  .home-container12 {
    align-items: center;
  }
  .home-container13 {
    margin-right: 0px;
  }
  .home-logos {
    display: none;
  }
  .home-contaier {
    padding-left: var(--dl-space-space-doubleunit);
    padding-right: var(--dl-space-space-doubleunit);
  }
  .home-container18 {
    width: 45%;
    margin-left: var(--dl-space-space-unit);
  }
}
@media(max-width: 767px) {
  .home-card {
    align-items: center;
  }
  .home-text02 {
    text-align: center;
    margin-right: 0px;
    padding-right: 0px;
  }
  .home-image {
    display: none;
  }
  .home-container04 {
    max-width: 720px;
  }
  .home-container06 {
    align-items: center;
    flex-direction: column;
  }
  .home-container07 {
    width: 80%;
  }
  .home-image1 {
    margin-left: 0px;
    margin-right: 0px;
  }
  .home-image2 {
    display: none;
  }
  .home-container09 {
    width: 80%;
  }
  .home-image3 {
    display: none;
  }
  .home-container11 {
    padding-top: 12rem;
    padding-bottom: 12rem;
  }
  .home-container14 {
    flex-direction: column;
  }
  .home-container18 {
    width: 80%;
    margin-top: var(--dl-space-space-fourunits);
    align-items: center;
    margin-left: 0px;
  }
  .home-divider {
    margin-top: var(--dl-space-space-doubleunit);
    margin-bottom: var(--dl-space-space-doubleunit);
  }
  .home-banner {
    padding-left: 32px;
    padding-right: 32px;
  }
}
@media(max-width: 479px) {
  .home-card {
    padding: var(--dl-space-space-unit);
  }
  .home-container02 {
    align-items: center;
    flex-direction: column;
  }
  .home-container03 {
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-container11 {
    padding-top: var(--dl-space-space-sixunits);
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .home-banner {
    padding-top: 48px;
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: 48px;
  }
  .home-container19 {
    align-items: center;
    flex-direction: column;
  }
}
</style>
