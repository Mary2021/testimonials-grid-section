<template>
      <v-card
        class="mx-auto daniel"
        style="background-color: hsl(263, 55%, 52%); color: hsl(0, 0%, 100%)"
      >
      <v-container>
       <v-container id="avatar">
          <v-avatar size="24">
            <v-img
              alt="Daniel"
              src="./../assets/image-daniel.jpg"
            ></v-img>
          </v-avatar>
          <v-container id="title">
            <v-card-title><h1>Daniel Clifford</h1></v-card-title>
            <v-card-subtitle>Verified Graduate</v-card-subtitle>
          </v-container>
  </v-container>
</v-container>
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
.v-card {
  padding: 1.5rem !important;
  margin-block-end: 5%;
}

.v-container {
  display: flex;
  padding: 0% !important;
}

.v-container #avatar {
  display: flex !important;
  align-items: center;
  padding: 0%;
}

.v-container #title {
  display: flex !important;
  flex-direction: column;
  padding: 0% !important;
  margin-left: 2% !important;
}

.v-container #title .v-card-title {
  padding: 0% !important;
}

.v-container #title .v-card-subtitle {
  padding: 0% !important;
}

h1 {
  font-size: 0.7rem !important;
  font-family: 'Barlow Semi Condensed';
}

.v-card-title {
  font-size: 0.7rem !important;
  font-family: 'Barlow Semi Condensed';
}

.v-card-subtitle {
  display: block;
  font-size: 0.6rem !important;
  opacity: 50% !important;
  font-family: 'Barlow Semi Condensed';
}

.v-card-text {
  font-weight: 600 !important;
  font-family: 'Barlow Semi Condensed';
}

p {
  opacity: 70%;
  font-weight: 500 !important;
  font-size: 0.7rem;
  font-family: 'Barlow Semi Condensed';
}

@media (max-width: 961px) {
  .v-application {
    padding: 1.8rem !important;
  } 

  .v-card {
    max-width: 400px;
  }

  .v-container {
    margin-left: 2% !important;
  }

  .attribution {
    text-align: center;
    font-size: 0.8rem;
  }
}

@media (min-width: 962px) and (max-width:1080px) {
  .v-application {
    display: grid;
  }
  .v-application__wrap {
    flex-wrap: wrap;
    padding-block: 4rem;
    padding-inline: 2rem;
  }
  .v-main {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    max-height: 97%;
  }

  .v-card {
    padding: 0.8rem !important;
    margin-block-end: 0%;
  }

  .v-container {
    margin-left: 2% !important;
  }

  .v-card.daniel {
    display: grid;
    grid-column-start: 1;
    grid-column-end: 3;
  }

  .v-card.jonathan {
    display: grid;
    grid-column-start: 3;
    grid-column-end: 4;
  }

  .v-card.jeanette {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 1;
    grid-column-end: 2;
  }

  .v-card.patrick {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 2;
    grid-column-end: 4;
  }

  .v-card.kira {
    display: grid;
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

@media (min-width: 1081px) and (max-width:1400px) {
  .v-application {
    display: grid;
  }
  .v-application__wrap {
    flex-wrap: wrap;
    padding-block: 3rem;
    padding-inline: 5rem;
  }
  .v-main {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    max-height: 100%;
  }

  .v-card {
    padding: 0.8rem !important;
    margin-block-end: 0%;
  }

  .v-container {
    margin-left: 2% !important;
  }

  .v-card.daniel {
    display: grid;
    grid-column-start: 1;
    grid-column-end: 3;
  }

  .v-card.jonathan {
    display: grid;
    grid-column-start: 3;
    grid-column-end: 4;
  }

  .v-card.jeanette {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 1;
    grid-column-end: 2;
  }

  .v-card.patrick {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 2;
    grid-column-end: 4;
  }

  .v-card.kira {
    display: grid;
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

@media (min-width: 1440px) and (max-width:1999px) {
  .v-application {
    display: grid;
  }
  .v-application__wrap {
    flex-wrap: wrap;
    padding-block: 6rem;
    padding-inline: 10rem;
  }
  .v-main {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    max-height: 100%;
  }

  .v-card {
    padding: 0.8rem !important;
    margin-block-end: 0%;
  }

  .v-container {
    margin-left: 2% !important;
  }

  .v-avatar {
    width: 30px !important;
    height: 30px !important;
  }

  .v-card-title {
    font-size: 0.8rem !important;
  }

  .v-card-subtitle {
    font-size: 0.7rem !important;
  }

  .v-card-text {
    font-size: 1.2rem !important;
  }
  
  p{
    font-size: 0.8rem !important;
   }

  .v-card.daniel {
    display: grid;
    grid-column-start: 1;
    grid-column-end: 3;
  }

  .v-card.jonathan {
    display: grid;
    grid-column-start: 3;
    grid-column-end: 4;
  }

  .v-card.jeanette {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 1;
    grid-column-end: 2;
  }

  .v-card.patrick {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 2;
    grid-column-end: 4;
  }

  .v-card.kira {
    display: grid;
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

@media (min-width: 2000px) and (max-width:2560px) {
  .v-application {
    display: grid;
  }
  .v-application__wrap {
    flex-wrap: wrap;
    padding-block: 9rem;
    padding-inline: 14rem;
  }
  .v-main {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    max-height: 100%;
  }

  .v-card {
    padding: 2rem !important;
    margin-block-end: 0%;
  }

  .v-container {
    margin-left: 1% !important;
  }

  .v-avatar {
    width: 50px !important;
    height: 50px !important;
  }

  .v-card-title {
    font-size: 1.5rem !important;
  }

  .v-card-subtitle {
    font-size: 1.5rem !important;
  }

  .v-card-text {
    font-size: 2rem !important;
  }
  
  p{
    font-size: 1.5rem !important;
   }

  .v-card.daniel {
    display: grid;
    grid-column-start: 1;
    grid-column-end: 3;
  }

  .v-card.jonathan {
    display: grid;
    grid-column-start: 3;
    grid-column-end: 4;
  }

  .v-card.jeanette {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 1;
    grid-column-end: 2;
  }

  .v-card.patrick {
    display: grid;
    grid-row-start: 2;
    grid-column-start: 2;
    grid-column-end: 4;
  }

  .v-card.kira {
    display: grid;
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
    font-size: 1.5rem !important;
  }
}
</style>
