<template>
  <main>
    <!-- ***** -->
    <!-- ***** -->
    <!-- ***** -->
    <!-- ***** -->
    <!-- ***** -->
    <!-- CODED BY DANTEANDHUBBLE -->

    <!-- Header -->
    <Header />
    <script type="text/javascript" src="../bot/index.js"></script>

    <!--MAIN BODY-->
    <div class="fONKFl fromtyes CODED_BY_DANTEANDHUBBLE">
      <PageLoader />
      <div class="lcGJBI">
        <div class="bYtPLw d-flex justify-content-center head">
          <h1><b>Build the best Discord Server!</b></h1>
        </div>
        <div class="iBcFYM d-flex">
          <p>
            Configure moderation, leveling, support, and much more with just a
            quick setup!
          </p>
        </div>

        <div class="descSubText">
          <div class="cYpCFy"></div>
          <svg
            width="24"
            height="24"
            viewbox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="sc-m9d8o3-0 ihKWaM sc-133bauo-4 cZYeXb"
            main="#9B9D9F"
          >
            <path
              d="M18 7L9.429 17 6 13"
              stroke="#9B9D9F"
              data-stroke="main"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></path>
          </svg>
          <span>Moderation</span>
        </div>

        <br />

        <div class="">
          <div class="descSubText"></div>
          <svg
            width="24"
            height="24"
            viewbox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="sc-m9d8o3-0 ihKWaM sc-133bauo-4 cZYeXb"
            main="#9B9D9F"
          >
            <path
              d="M18 7L9.429 17 6 13"
              stroke="#9B9D9F"
              data-stroke="main"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></path>
          </svg>
          <span>Reaction Roles</span>
        </div>
        <br />
        <div class="">
          <div class="descSubText"></div>
          <svg
            width="24"
            height="24"
            viewbox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="sc-m9d8o3-0 ihKWaM sc-133bauo-4 cZYeXb"
            main="#9B9D9F"
          >
            <path
              d="M18 7L9.429 17 6 13"
              stroke="#9B9D9F"
              data-stroke="main"
              stroke-width="1.5"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></path>
          </svg>
          <span>ChatBot</span>
        </div>

        <br />

        <div>
          <div class="">
            <a class="btn btn-primary btn-lg" href="#features"
              >Add to Discord</a
            >

            <a class="btn btn-secondary btn-lg" href="#features">Features</a>
          </div>
          <div class="subtext"></div>
        </div>
      </div>
      <div class="middlepadding justify-content-center">
        <div class="fwXcEk justify-content-center">
          <h2 id="serversize"></h2>
        </div>
      </div>
    </div>

    <br />

    <div class="container custom-1 pt-16" id="features">
      <img
        class="bWWqTX sc-z8ujbu-11"
        src="https://cdn.discordapp.com/attachments/756237108443611357/935401393123110953/welcome.png"
      />
      <h3 class="rblwY align-self-start">
        <b>Say "Hello!" to new users on your Discord server</b>
      </h3>
      <p>
        Take advantage of the welcome message to inform newcomers about your
        server rules, topic, or ongoing events. You can design your own welcome
        message to keep it simple.
      </p>
    </div>

    <br />

    <div class="container" style="padding-top: 5rem !important"></div>

    <div class="footer"></div>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

    <!--JS-->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0"
      crossorigin="anonymous"
    ></script>
  </main>
</template>

<script type="text/javascript">
var count = DiscordBot.count;

var str = "Serving " + count + " servers";



export default {
  mounted() {
    document.getElementById("serversize").innerHTML = str;
  }
}
</script>

<script>
import PageLoader from "./pageLoader.vue";

export default {
  components: { PageLoader },
  head: {
    link: [
      {
        href: "https://fonts.googleapis.com/icon?family=Material+Icons",
        rel: "stylesheet",
      },
      {
        rel: "stylesheet",
        href: "/css/index.css",
      },
    ],
    link: [
      {
        href: "https://use.typekit.net/gdy1bio.css",
        rel: "stylesheet",
      },
      {
        rel: "stylesheet",
        href: "/css/index.css",
      },
    ],
    meta: [
      {
        charset: "utf-8",
      },
      {
        name: "viewport",
        content: "width=device-width, initial-scale=1",
      },
    ],
    title: "OutLand",
  },
};
</script>