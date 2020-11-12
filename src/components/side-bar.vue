<template>
  <div class="side-bar" ref="side-bar">
    <div class="contact-container">
      <span class="title" style="margin-bottom: -10px">
        <img src="@/assets/contact.png" class="projects-icon" />Contact
      </span>
      <a href="mailto:shrinathprabhu.123@gmail.com">
        <image-transition
          logo="contact/gmail.svg"
          tooltip="Mail"
          width="40px"
          noGrayscale="true"
        />
      </a>
      <a href="https://www.facebook.com/shrinath.prabhu" target="__blank">
        <image-transition
          logo="contact/facebook.svg"
          tooltip="Facebook"
          width="40px"
          noGrayscale="true"
        />
      </a>
      <a href="https://www.instagram.com/shrinathprabhu/" target="__blank">
        <image-transition
          logo="contact/instagram.svg"
          tooltip="Instagram"
          width="40px"
          noGrayscale="true"
        />
      </a>
      <a
        href="https://www.linkedin.com/in/shrinath-prabhu-459107b2"
        target="__blank"
      >
        <image-transition
          logo="contact/linkedin.svg"
          tooltip="Linkedin"
          width="40px"
          noGrayscale="true"
        />
      </a>
    </div>
    <span class="title">
      <img src="@/assets/about-me.png" class="projects-icon" />About me
    </span>
    <p>
      Hi, my name is {{ name }}. I am experienced in developing code for the web
      using Javascript and its frameworks, with over 2 and a half years of
      experience in this field.
    </p>
    <p>
      I led a team and delivered solutions based on complex queries. I have
      experience in developing scalable applications with robust backend.
    </p>
    <p class="title">
      <img src="@/assets/projects.png" class="projects-icon" />
      Projects
    </p>
    <ol>
      <strong>
        <li>
          <a
            class="projects"
            href="https://openforms.herokuapp.com"
            target="__blank"
          >
            Openforms (Still under development)
          </a>
        </li>
      </strong>
      <span>
        A simple web app for creating forms inspired from Google forms. The idea
        is, you can create forms without having to give your personal info in
        the name of user registration. Also this project is fully open source.
      </span>
      <br />
      <strong>
        Website:
        <a class="projects-link" href="https://openforms.herokuapp.com">
          https://openforms.herokuapp.com
        </a>
      </strong>
      <br />
      <strong>Technologies Used:</strong>
      <br />
      <ul>
        <li>
          <strong>Frontend:</strong> Vue, Vuetify (MaterialUI library), Vuex
          (Central state management), Vue-axios (For ajax requests) and
          Vue-router(For navigating to different views)
        </li>
        <li>
          <strong>Backend:</strong> Node.js, Express.js, Mongoose, Cookie-parser
        </li>
        <li>
          <strong>Cloud Solutions:</strong> Heroku, MongoDB Atlas, UptimeRobot
        </li>
        <li><strong>Others:</strong> CircleCI, Coveralls</li>
      </ul>
      <strong style="margin-right: 10px; margin-bottom: 10px">
        Source Code:
        <a
          class="projects-link"
          href="https://github.com/shrinathprabhu/survey-form-ui"
        >
          Frontend
        </a>
        <a
          class="projects-link"
          href="https://github.com/shrinathprabhu/survey-form-backend"
        >
          Backend
        </a>
      </strong>
      <br /><br />
      <strong>
        <li>
          <a
            class="projects"
            href="https://credenstore.web.app"
            target="__blank"
          >
            Credenstore
          </a>
        </li>
      </strong>
      <span>
        A simple web app for storing your credentials or any other data on cloud
        in encrypted format. This web app directly interacts with firestore and
        no middleware servers are involved. Also strict security rules are set
        in firestore such that no one can access the data without retrieval link
        and password. Also this project is fully open source.
      </span>
      <br />
      <strong>
        Website:
        <a
          class="projects-link"
          href="https://credenstore.web.app"
          target="__blank"
        >
          https://credenstore.web.app
        </a>
      </strong>
      <br />
      <strong>Technologies Used:</strong>
      <br />
      <ul>
        <li><strong>Frontend:</strong> Vue, Vuetify and Vue-router</li>
        <li><strong>Datastore:</strong> Firebase Firestore</li>
        <li><strong>Hosting:</strong> Firebase Hosting</li>
      </ul>
      <strong style="margin-right: 10px; margin-bottom: 10px">
        Source Code:
        <a
          class="projects-link"
          href="https://github.com/shrinathprabhu/credenstore"
        >
          Credenstore
        </a>
      </strong>
      <br /><br />
      <strong>
        <li>
          <a
            class="projects"
            href="https://checkbox-tree-vue.surge.sh"
            target="__blank"
          >
            Checkbox Tree Vue
          </a>
        </li>
      </strong>
      <span>
        A simple vue component created for having a tree view with checkboxes.
        This component is created from scratch without use of any external
        library. It uses axios to fetch data from mocky api and then creates a
        tree view. Selecting parent selects all children, deselecting parent
        deselects all children. Selecting a child, marks its parent as
        indeterminate. This project is created using Vue.
      </span>
      <br />
      <strong>
        Website:
        <a
          class="projects-link"
          href="https://checkbox-tree-vue.surge.sh"
          target="__blank"
        >
          https://checkbox-tree-vue.surge.sh
        </a>
      </strong>
      <br />
      <strong style="margin-right: 10px; margin-bottom: 10px">
        Source Code:
        <a
          class="projects-link"
          href="https://github.com/shrinathprabhu/simple-treeview"
        >
          Simple treeview
        </a>
      </strong>
      <br /><br />
      <strong>
        <li>
          <a
            class="projects"
            href="https://github.com/shrinathprabhu/scrawpe"
            target="__blank"
          >
            Scrawpe (Under development)
          </a>
        </li>
      </strong>
      <span> A simple library for crawling and scraping of web pages. </span>
      <br />
      <strong style="margin-right: 10px; margin-bottom: 10px">
        Dependencies:
        <a class="projects-link" href="https://www.npmjs.com/package/puppeteer">
          Puppeteer
        </a>
        <a class="projects-link" href="https://www.npmjs.com/package/cheerio">
          Cheerio
        </a>
        <a
          class="projects-link"
          href="https://www.npmjs.com/package/puppeteer-extra-plugin-stealth"
        >
          Puppeteer-extra-plugin-stealth
        </a>
      </strong>
      <br />
      <strong>
        Source Code:
        <a
          class="projects-link"
          href="https://github.com/shrinathprabhu/scrawpe"
          target="__blank"
        >
          Scrawpe
        </a>
      </strong>
      <br /><br />
      <strong>
        <li>
          <a
            class="projects"
            href="https://github.com/shrinathprabhu/vue-material-kickstart"
            target="__blank"
          >
            Vue Material Kickstart
          </a>
        </li>
      </strong>
      <span>
        A simple boilerplate/ kickstart for creating Vue apps. It is already pre
        loaded with dependencies and plugins like Vuetify, Vuex, Vue-axios,
        Vue-router, Vue-meta, Jest and Cypress. Also it is loaded with some
        additional scripts for testing and linting. Just clone the project and
        start developing on top of it
      </span>
      <br />
      <strong>
        Source Code:
        <a
          class="projects-link"
          href="https://github.com/shrinathprabhu/vue-material-kickstart"
          target="__blank"
        >
          Vue Material Kickstart
        </a>
      </strong>
    </ol>
  </div>
</template>

<style scoped>
.side-bar {
  position: absolute;
  top: 180px;
  height: fit-content;
  padding-bottom: 200px;
  background-color: #35495e;
  width: calc(30% + 80px);
  color: white;
  padding-top: 20px;
  padding-left: 40px;
  padding-right: 40px;
  min-height: calc(100% - 180px);
}
.projects-icon {
  height: 40px;
  margin-top: -12px;
  margin-right: 12px;
}
.title {
  font-weight: 600;
  font-size: 1.5em;
  display: block;
}
.subtitle {
  font-weight: 600;
  display: block;
}
.projects {
  color: #53b883;
  font-size: 1.1em;
}
.projects-link {
  color: #53b883;
  margin-left: 10px;
  text-decoration: underline;
}
.contact-container {
  margin-bottom: 10px;
}
@media only screen and (min-width: 320px) and (max-width: 812px) {
  .side-bar {
    position: relative;
    top: 0;
    right: 0;
    background-color: #35495e;
    width: 100%;
    color: white;
    padding-top: 100px;
    padding-left: 10px;
    padding-bottom: 20px;
  }
}
</style>

<script>
import ImageTransition from "./image-transition.vue";
export default {
  name: "side-bar",
  components: { ImageTransition },
  data: () => ({
    name: process.env.VUE_APP_NAME,
  }),
  mounted() {
    console.log(this.$refs["side-bar"].style);
    this.$refs["side-bar"].style.height = document.body.scrollHeight;
  },
};
</script>