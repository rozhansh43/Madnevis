<template>
  <div>  
    <Navbar/>
    <b-container>
      <b-row>
        <b-col>
          <h1>
            مدنویس چی هست؟
          </h1>

          <p>
            لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد
          </p>

          <div>
            <b-button variant="warning">
              Warning
            </b-button>

            <b-button variant="light">
              Light
            </b-button>

          </div>
        </b-col>

        <b-col>
          <b-img src="@/src/assets/sizemini_113.jpg" width="600">
          </b-img>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid class="blue-section">
      <b-row>
        <h2>
          خدمات مدنویس
        </h2>
        
        <p>
          لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است
        </p>
      </b-row>
    </b-container>

    <b-container>
      <b-row>
        <b-col>
          <b-img src="@/src/assets/calendar.svg" width="60"/>
          <h5>
            تایپ مقالات پزشکی
          </h5>
        </b-col>

        <b-col>
          <b-img src="@/src/assets/folder.svg" width="60"/>
          <h5>
            ترجمه متون پزشکی
          </h5>
        </b-col>

        <b-col>
          <b-img src="@/src/assets/file (1).svg" width="60"/>
          <h5>
            کتابخانه
          </h5>
        </b-col>

        <b-col>
          <b-img src="@/src/assets/file.svg" width="60"/>
          <h5>
            ویراستاری کتاب
          </h5>
        </b-col>

        <b-col>
          <b-img src="@/src/assets/calendar.svg" width="60"/>
          <h5>
            سوالات متداول
          </h5>
        </b-col>

        <b-col>
          <b-img src="@/src/assets/calendar (1).svg" width="60"/>
          <h5>
            ویراستاری کتاب
          </h5>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {}
</script>

<style>
body{
  direction: rtl;
}
.blue-section {
  background-color: #0953f0;
}
</style>