<template>
  <div>  
    <Navbar/>
    
    <AboutUs/>

    <Services/>

    <b-container fluid class="">
      <b-row class="empty-section bg-white">

      </b-row>
    </b-container>

    <WhyUs/>

    <Comments/>

    <OrderSubmit/>

    <BlogPosts/>

    <SiteFooter/>
  </div>
</template>

<script>
export default {}
</script>

<style>
@font-face {
    font-family: 'yekan';
    src: url(@/src/assets/fonts/yekanm.ttf);
}

body{
  direction: rtl;
  font-family: 'yekan';
}

h1,h2,h3,h4,h5,h6 {
  font-weight: 900!important;
}

p {
  font-size: 14px!important;
}

.blue-section {
  background-color: #0953f0;
}

.border-50 {
  border-radius: 50px;
}

.border-30 {
  border-radius: 30px;
}

.our-services {
  margin-top: -180px;
}

.text-light {
  color: rgb(206, 211, 214)!important;
}

.empty-section {
  height:100px;
  border-radius: 50px;
  margin-top: -110px;
}

.btn {
  border-radius: 14px!important;
  padding: 11px 35px!important;
}

.btn-secondary {
  background-color: #d3d5e5!important;
  border-color: #d3d5e5!important;
  color: #133267!important;
}

.btn-success {
  background-color: #01c28c!important;
  border-color: #01c28c!important;
}

.btn-warning {
  background-color: #FEC44e !important;
  border-color: #FEC44e!important;
}

.bg-success {
  background: #01c28c!important;
}

.bg-warning {
  background: #FEC44e!important;
}

.bg-primary {
  background: #0953f0 important;
  color: #fff!important;
}

.bg-secondary {
  border-radius: 68px;
  padding: 22px;
  background-color:rgb(243, 250, 255)!important;
}

.card img {
  border-top-left-radius: 30px;
  border-top-right-radius: 30px;
}

.white-footer {
  margin-bottom: -40px;
}

.card {
  border: none;
  margin-left: 0!important;
  box-shadow: 0 0px 8px rgba(145, 145, 145, 0.3), 0 2px 2px rgba(141, 141, 141, 0.2);
}
</style>