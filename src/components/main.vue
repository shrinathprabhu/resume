<template>
  <div class="main">
    <p class="main-title">
      <img
        src="@/assets/skills.png"
        class="title-icon"
        style="margin-top: -12px"
      />
      Skills
    </p>
    <div class="main-subtitle">Frontend</div>
    <image-transition
      logo="skills/javascript.svg"
      tooltip="Javascript"
      height="70px"
    />
    <image-transition logo="skills/vue.svg" tooltip="Vue" />
    <image-transition logo="skills/angular.svg" tooltip="Angular" />
    <image-transition logo="skills/html5.svg" tooltip="HTML 5" />
    <image-transition logo="skills/css3.svg" tooltip="CSS 3" />
    <image-transition
      logo="typescript.svg"
      tooltip="Typescript"
      height="65px"
    />
    <div class="main-subtitle">Backend and database</div>
    <image-transition logo="skills/nodejs.svg" tooltip="Node.js" />
    <image-transition
      logo="skills/expressjs.svg"
      tooltip="Express.js"
      height="40px"
    />
    <image-transition logo="skills/nest.svg" tooltip="Nest.js" />
    <image-transition logo="skills/mongodb.svg" tooltip="MongoDB" />
    <image-transition
      logo="skills/cloud_firestore.svg"
      tooltip="Cloud Firestore"
    />
    <image-transition logo="skills/pm2.svg" tooltip="PM2" width="100px" />
    <div class="main-subtitle">Cloud</div>
    <image-transition logo="skills/heroku.svg" tooltip="Heroku" height="60px" />
    <image-transition logo="skills/aws_ec2.svg" tooltip="AWS EC2" />
    <image-transition logo="skills/aws_s3.svg" tooltip="AWS S3" />
    <image-transition logo="skills/netlify.svg" tooltip="Netlify" />
    <div class="main-subtitle">Versioning Tools</div>
    <image-transition logo="skills/git.svg" tooltip="Git" />
    <image-transition logo="skills/github.svg" tooltip="Github" />
    <image-transition logo="skills/bitbucket.svg" tooltip="Bitbucket" />
    <image-transition logo="skills/gitlab.svg" tooltip="Gitlab" />
    <div class="main-subtitle">Kanban</div>
    <image-transition logo="skills/trello.svg" tooltip="Trello" />
    <image-transition logo="skills/asana.svg" tooltip="Asana" />
    <div class="main-subtitle">Others</div>
    <image-transition logo="skills/linux.svg" tooltip="Linux (Ubuntu)" />
    <image-transition logo="skills/json.svg" tooltip="JSON" />
    <image-transition logo="skills/jest.svg" tooltip="Jest" />
    <image-transition logo="skills/vscode.svg" tooltip="VS Code" />
    <image-transition logo="skills/prettier.svg" tooltip="Prettier" />
    <image-transition
      logo="skills/circleci.svg"
      tooltip="Circle CI"
      height="60px"
    />
    <image-transition logo="skills/coveralls.svg" tooltip="Coveralls.io" />
    <image-transition logo="skills/code_climate.svg" tooltip="Code Climate" />
    <div class="main-subtitle">Very little knowledge about</div>
    <image-transition logo="skills/redis.svg" tooltip="Redis" />
    <image-transition logo="skills/flutter.svg" tooltip="Flutter" />
    <image-transition logo="skills/mysql.svg" tooltip="MySQL" />
    <p class="main-title">
      <img src="@/assets/experience.png" class="title-icon" />
      Experience
    </p>
    <ul>
      <li>
        <a class="main-subtitle" href="https://hashbinary.com/">
          Hashbinary Services LLP
        </a>
        <div class="main-mini-subtitle">Team Lead (March 2020 - Present)</div>
        <p>
          Worked on a real estate app that helps builders manage their
          inventory, upload property or building plans, create tasks and
          generate a report for all the involved stakeholders. Also currently
          working on an agricultural product. I lead the team of 5 during this
          phase.
          <br />
          <strong>Bonus Integrations:</strong>
          Razorpay (Payment gateway), modified image properties using
          Imagemagick, created beautiful graphs for admin dashboard using
          ngx-charts, integrated apis for creating user in Salesforce and Office
          365 and inviting user to Asana
        </p>
      </li>
      <li>
        <a class="main-subtitle" href="https://hashbinary.com/">
          Hashbinary Services LLP
        </a>
        <div class="main-mini-subtitle">
          Full Stack Web Developer (May 2019 - April 2020)
        </div>
        <div class="p">
          Worked on a Chrome extension, that helps user fetch cheaper prices on
          various booking websites and also can be used as a privacy tool that
          helps mask the identity. Also worked on a campaign management tool
          which helps the company automate the information collection and
          reusability tasks and generate reports faster than relying on
          spreadsheets.
          <br />
          <strong>Bonus Integrations:</strong>
          <ul>
            <li>Payments and subscriptions: Paypal, Stripe, Braintree</li>
            <li>Single sign on: Google, Facebook, Linkedin, Amazon</li>
            <li>
              Others: Websockets, MQTT, Middleware Proxy Server, RBAC (Role
              based access control), SQS, IMAP (for incoming mails), Fetched
              currency values using Fixer.io, got location of user from ip using
              Maxmind
            </li>
          </ul>
        </div>
      </li>

      <li>
        <a class="main-subtitle" href="https://hashbinary.com/">
          Hashbinary Services LLP
        </a>
        <div class="main-mini-subtitle">
          Web Developer Intern (May 2018 - April 2019)
        </div>
        <p>
          Worked on an on-demand aggregation of car-wash services where user can
          book a service nearest to him in map based UI. Also created a tool
          that takes an excel in predefined format and then generate charts
          based on that data.
          <br />
          <strong>Bonus Integrations:</strong>
          Firebase Push Notifications, Twilio (SMS gateway), Nodemailer (Send
          mails using SMTP), AWS S3, GridFS, Google Maps API, GeoJSON, Pug,
          converted html to pdf using a library, converted excel data to json
          using xlsx, Windcave PxPay(Formerly PaymentExpress) and APIDoc.js
        </p>
      </li>
    </ul>
    <p class="main-title">
      <img src="@/assets/interests.png" class="title-icon" />
      Interests
    </p>
    <p style="padding-left: 40px">
      Apart from coding, I love to watch anime and read manga. Whenever I'm
      free, I just go to my watchlist and start binge watching some anime. Also
      I love to play cricket, read answers on quora and do some random internet
      stuff #SocialMediaAddict
    </p>
    <app-footer />
  </div>
</template>

<style scoped>
.main {
  position: absolute;
  top: 180px;
  left: 36%;
  bottom: 0;
  right: 0;
  padding-top: 100px;
  color: #35495e;
  padding-left: 40px;
  padding-right: 30px;
}
.main-title {
  font-weight: 600;
  font-size: 1.5em;
  color: #35495e;
  margin-top: 30px;
}
.main-subtitle {
  color: #35495e;
  font-weight: 600;
}
.main-mini-subtitle {
  color: #53b883;
  font-weight: 500;
}
.title-icon {
  height: 40px;
  margin-top: -20px;
  margin-right: 12px;
}

.p {
  display: block;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
}

@media only screen and (min-width: 320px) and (max-width: 812px) {
  .main {
    position: relative;
    width: 100%;
    left: 0;
    top: 0;
    right: 0;
    bottom: 0;
    padding-top: 0px;
    padding-left: 10px;
    padding-bottom: 100px;
  }
}
</style>

<script>
import AppFooter from "./app-footer.vue";
import ImageTransition from "./image-transition.vue";
export default {
  name: "main-bar",
  components: { ImageTransition, AppFooter },
};
</script>
