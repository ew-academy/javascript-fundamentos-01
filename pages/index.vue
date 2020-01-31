<template>
  <div class="IndexPage">
    <Hero />
    <AboutCourse />
    <VideoPublicity />
    <LearnChecks />
    <CourseContent />
    <Author />
    <!-- <Communities /> -->
    <!-- <Sponsor /> -->
    
    <HowItWorks />
    <CTA />
    <CountDown />
  </div>
</template>

<script>
import Hero from "@/components/Hero";
import AboutCourse from "@/components/AboutCourse";
import HowItWorks from "@/components/HowItWorks";
import LearnChecks from "@/components/LearnChecks";
import CourseContent from "@/components/CourseContent";
import Author from "@/components/Author";
import Sponsor from "@/components/Sponsor";
import VideoPublicity from "@/components/VideoPublicity";
import Communities from "@/components/Communities";
import CTA from "@/components/CTA";
import CountDown from "@/components/CountDown";

export default {
  name: "Home",
  components: {
    CountDown,
    Hero,
    AboutCourse,
    LearnChecks,
    CourseContent,
    Author,
    Sponsor,
    Communities,
    CTA,
    HowItWorks,
    VideoPublicity,
  }
};
</script>

<style lang="scss">
.IndexPage {
  position: relative;
}
</style>
