<template>
    <section class="inner-banner">
        <div class="container">
            <ul class="list-unstyled thm-breadcrumb">
                <!-- <li><a href="/">Accueil</a></li> -->
                <!-- <li class="active"><a href="#">{{ title }}</a></li> -->
            </ul><!-- /.list-unstyled -->
            <h2 class="inner-banne__title" style="color:#fff; font-size: 40px; ; 
">{{ title }}</h2>
            <br>
            <br>
            <!-- /.inner-banner__title -->
        </div><!-- /.container -->
    </section>
  </template>
  
  <script>
      export default {
        name: "HeaderHome",
        props: {
          title: {
            type: String
          }
        }
      }
  </script>
  
  <style scoped>
  
  </style>
  