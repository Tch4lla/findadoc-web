<template>
  <div class="flex h-full flex-col w-full">
    <div class="flex flex-col items-center mx-32">
      <!-- <svg
        role="img"
        alt="heart icon"
        title="heart icon"
        class="heart-plus-icon w-24 h-24 mr-1 fill-primary-text-inverted"
      >
        <use xlink:href="~/assets/images/heart-plus.svg#heart-plus-svg" />
      </svg>-->
      <h1 class="mb-12 font-bold text-4xl">{{ $t('about.heading') }}</h1>
      <p class="mb-12 text-2xl">{{ $t('about.subheading') }}</p>
      <p class="mb-6 text-md text-primary-text-muted">{{ $t('about.paragraph1') }}</p>
      <p class="text-md text-primary-text-muted">{{ $t('about.paragraph2') }}</p>
    </div>
    <!-- <div id="members" class="flex flex-col items-center mx-32 my-14">
            <div id="members-header" class="flex">
                <div class="h-px w-32 border-currentColor/70 border inline-block self-center"></div>
                <div class="text-primary/80 text-xl font-bold inline-block mx-4 whitespace-nowrap">Our Team</div>
                <div class="h-px w-32 border-currentColor/70 border inline-block self-center"></div>
            </div>
            <div class="members-list flex flex-row" :key="index" v-for="(member, index) in members">
                <div class="member flex flex-col">
                    <img :href="member.avatarImg" />
                    <div class="member-name text-xl font-bold">{{ member.name }}</div>
                    <div class="member-title text-md text-primary-text-muted">{{ member.title }}</div>
                    <div class="member-social flex flex-row">
                        <a :href="member.linkedInUrl" target="_blank" rel="noopener noreferrer">
                            <svg role="img" alt="linkedin icon" title="linkedin icon"
                                class="social-icon w-12 h-12 mr-1 fill-primary-text-muted">
                                <use xlink:href="../assets/images/social-linkedin.svg#social-linkedin-svg" />
                            </svg>
                        </a>
                        <a :href="member.githubUrl" target="_blank" rel="noopener noreferrer">
                            <svg role="img" alt="github icon" title="github icon"
                                class="social-icon w-12 h-12 mr-1 fill-primary-text-muted">
                                <use xlink:href="../assets/images/social-github.svg#social-github-svg" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
    </div>-->
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";

const members = ref([
  {
    avatarImg: "../assets/images/avatars/lashawntoyoda.jpg",
    name: "LaShawn Toyoda",
    title: "Founder & Executive Director",
    linkedInUrl: "https://www.linkedin.com/in/lashawn-toyoda/",
    githubUrl: "https://github.com/theyokohamalife/"
  },
  {
    avatarImg: "../assets/images/avatars/philipermish.jpg",
    name: "Philip Ermish",
    title: "Tech Lead",
    linkedInUrl: "https://www.linkedin.com/in/philipermish",
    githubUrl: "https://github.com/ermish"
  },
  {
    avatarImg: "../assets/images/avatars/russellmiller.jpg",
    name: "Russell Miller",
    title: "Healthcare Content Lead",
    linkedInUrl: "https://www.linkedin.com/in/russellmiller",
    githubUrl: "https://github.com/ermish"
  },
  {
    avatarImg: "../assets/images/avatars/russellmiller.jpg",
    name: "Russell Miller",
    title: "Healthcare Content Lead",
    linkedInUrl: "https://www.linkedin.com/in/russellmiller",
    githubUrl: "https://github.com/ermish"
  },
  {
    avatarImg: "../assets/images/avatars/russellmiller.jpg",
    name: "Russell Miller",
    title: "Healthcare Content Lead",
    linkedInUrl: "https://www.linkedin.com/in/russellmiller",
    githubUrl: "https://github.com/ermish"
  },
  {
    avatarImg: "../assets/images/avatars/russellmiller.jpg",
    name: "Russell Miller",
    title: "Healthcare Content Lead",
    linkedInUrl: "https://www.linkedin.com/in/russellmiller",
    githubUrl: "https://github.com/ermish"
  },
  {
    avatarImg: "../assets/images/avatars/russellmiller.jpg",
    name: "Russell Miller",
    title: "Healthcare Content Lead",
    linkedInUrl: "https://www.linkedin.com/in/russellmiller",
    githubUrl: "https://github.com/ermish"
  }
]);
</script>
