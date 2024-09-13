<template>
      <v-card
        class="mx-auto daniel"
        subtitle="Verified Graduate"
        title="Daniel Clifford"
        style="background-color: hsl(263, 55%, 52%); color: hsl(0, 0%, 100%)"
      >
        <template v-slot:prepend>
          <v-avatar size="24">
            <v-img
              alt="Daniel"
              src="./../assets/image-daniel.jpg"
            ></v-img>
          </v-avatar>
        </template>
        <v-card-text>
          I received a job offer mid-course, and the subjects I learned were current, if not more so, in the company I joined. I honestly feel I got every penny’s worth.
          <p>“ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a transition and have heard some people who had an amazing experience here. I signed up for the free intro course and found it incredibly fun! I enrolled shortly thereafter. The next 12 weeks was the best - and most grueling - time of my life. Since completing the course, I’ve successfully switched careers, working as a Software Engineer at a VR startup. ”
          </p>
        </v-card-text>
      </v-card>
      <v-card
        class="mx-auto jonathan"
        subtitle="Verified Graduate"
        title="Jonathan Walters"
        style="background-color: hsl(217, 19%, 35%); color: hsl(0, 0%, 100%)"
      >
        <template v-slot:prepend>
          <v-avatar size="24">
            <v-img
              alt="Jonathan"
              src="./../assets/image-jonathan.jpg"
            ></v-img>
          </v-avatar>
        </template>
        <v-card-text>
          The team was very supportive and kept me motivated
          <p>“ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer
            for a big company. This was one of the best investments I’ve made in myself. ”
          </p>
        </v-card-text>
      </v-card>
      <v-card
        class="mx-auto jeanette"
        subtitle="Verified Graduate"
        title="Jeanette Harmon"
        style="color: hsl(217, 19%, 35%)"
      >
        <template v-slot:prepend>
          <v-avatar size="24">
            <v-img
              alt="Jeanette"
              src="./../assets/image-jeanette.jpg"
            ></v-img>
          </v-avatar>
        </template>
        <v-card-text>An overall wonderful and rewarding experience
          <p>“ Thank you for the wonderful experience! I now have a job I really enjoy, and make a good living
            while doing something I love. ”
          </p>
        </v-card-text>
      </v-card>
      <v-card
        class="mx-auto patrick"
        subtitle="Verified Graduate"
        title="Patrick Abrams"
        style="background-color: hsl(219, 29%, 14%); color: hsl(0, 0%, 100%)"
      >
        <template v-slot:prepend>
          <v-avatar size="24">
            <v-img
              alt="Patrick"
              src="./../assets/image-patrick.jpg"
            ></v-img>
          </v-avatar>
        </template>
        <v-card-text>Awesome teaching support from TAs who did the bootcamp themselves. Getting guidance from them and learning from their experiences was easy.
          <p>“ The staff seem genuinely concerned about my progress which I find really refreshing. The program gave me the confidence necessary to be able to go out in the world and present myself as a capable junior developer. The standard is above the rest. You will get the personal attention you need from an incredible community of smart and amazing people. ”
          </p>
        </v-card-text>
      </v-card>
      <v-card
        class="mx-auto kira"
        subtitle="Verified Graduate"
        title="Kira Whittle"
        style="color: hsl(219, 29%, 14%)"
      >
        <template v-slot:prepend>
          <v-avatar size="24">
            <v-img
              alt="Kira"
              src="./../assets/image-patrick.jpg"
            ></v-img>
          </v-avatar>
        </template>
        <v-card-text>Such a life-changing experience. Highly recommended!
          <p>“ Before joining the bootcamp, I’ve never written a line of code. I needed some structure from professionals who can help me learn programming step by step. I was encouraged to enroll by a former student of theirs who can only say wonderful things about the program. The entire curriculum and staff did not disappoint. They were very hands-on and I never had to wait long for assistance. The agile team project, in particular, was outstanding. It took my learning to the next level in a way that no tutorial could ever have. In fact, I’ve often referred to it during interviews as an example of my developent experience. It certainly helped me land a job as a full-stack developer after receiving multiple offers. 100% recommend! ”
          </p>
        </v-card-text>
      </v-card>
      <div class="attribution">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded by <a href="#">Mary P</a>.
  </div>
</template>

<script setup lang="ts">
  //
</script>

<style>
.v-application {
  padding: 1.8rem !important;
}

.v-card {
  padding: 1.5rem !important;
  margin-block-end: 5%;
}

.v-card-title {
  font-size: 0.7rem !important;
}

.v-card-subtitle {
  font-size: 0.6rem !important;
  opacity: 50% !important;
}

.v-card-text {
  font-weight: 600 !important;
}

p {
  opacity: 70%;
  font-weight: 500 !important;
  font-size: 0.6rem;
}

@media (max-width: 961px) {
  .v-card {
    max-width: 400px;
  }

  .attribution {
    text-align: center;
    font-size: 0.8rem;
  }
}

@media (min-width:962px) {
  .v-card {
  padding: 0.8rem !important;
  margin-block-end: 0%;
}

  main {
    display: grid;
    grid-template-columns: repeat(4, 22vw);
    gap: 20px
  }

  .v-card.daniel {
  grid-column-start: 1;
  grid-column-end: 3;
  }

  .v-card.jonathan {
    grid-column-start: 3;
    grid-column-end: 4;
  }

  .v-card.jeanette {
    grid-row-start: 2;
    grid-column-start: 1;
    grid-column-end: 2;
  }

  .v-card.patrick {
    grid-row-start: 2;
    grid-column-start: 2;
    grid-column-end: 4;
  }

  .v-card.kira {
    grid-row-start: 1;
    grid-row-end: 3;
    grid-column-start: 4;
    grid-column-end: 4;
  }

  .attribution {
    grid-row-start: 3;
    grid-column-start: 2;
    grid-column-end: 4;
    text-align: center;
  }
}
</style>
