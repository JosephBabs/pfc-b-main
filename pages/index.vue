<template>
  <div>
    <NavOne />
    <!-- <BannerOne /> -->
    
    <HeaderHome title="Présentation du Projet Forêts Classées Bénin (PFC – B)" />
    <AboutTwo />
    <CourseOne />
    <!-- <VideoTwo />
    <CountdownOne /> -->
    <CourseCategory />
    <CallToActionThree />
    <Subscribe />
    <Footer />
  </div>
</template>

<script>
  import NavOne from "../components/NavOne";
  import BannerOne from "../components/BannerOne";
  import HeaderHome from "../components/HeaderHome";
  import Footer from "../components/Footer";
  import AboutTwo from "../components/AboutTwo";
  import CourseOne from "../components/CourseOne";
  import VideoTwo from "../components/VideoTwo";
  import CountdownOne from "../components/CountdownOne";
  import CourseCategory from "../components/CourseCategory";
  import CallToActionThree from "../components/CallToActionThree";
  import ClientsLogoTwo from "../components/ClientsLogoTwo";
  import BlogCarousel from "../components/BlogCarousel";
  import CallToActionFour from "../components/CallToActionFour";
  import Subscribe from "../components/Subscribe";

  export default {
    components: {
      Subscribe,
      CallToActionFour,
      BlogCarousel,
      HeaderHome,
      ClientsLogoTwo,
      CallToActionThree,
      CourseCategory,
      CountdownOne,
      VideoTwo,
      CourseOne,
      NavOne,
      BannerOne,
      AboutTwo,
      Footer,
    }
  }
</script>
