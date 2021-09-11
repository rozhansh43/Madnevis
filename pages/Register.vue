<template>
    <b-container class="py-5 bg-secondary">
        <b-row class="mb-4">
            <div class="col-lg-8 mx-auto text-center">
            <h1 class="display-4">
                در مدنویس عضو شوید
            </h1>
            <p class="lead mb-0">
                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است 
            </p>

            <p class="lead">
                با
                <a href="https://google.com">
                    شرایط و ضوابط    
                </a>
                موافقم
            </p>
            </div>
        </b-row>

        <b-row>
            <b-col lg="7" class="mx-auto">
                <div class="bg-white rounded-lg shadow-sm p-5">
                    <!-- Credit card form tabs -->
                    <ul role="tablist" class="nav bg-light nav-pills rounded-pill nav-fill mb-3">
                    <li class="nav-item">
                        <a data-toggle="pill" href="#nav-tab-card" class="nav-link active rounded-pill">
                            <i class="fa fa-credit-card"></i>
                            ثبت نام
                        </a>
                    </li>
                    <li class="nav-item">
                        <a data-toggle="pill" href="#nav-tab-paypal" class="nav-link rounded-pill">
                            <i class="fa fa-paypal"></i>
                            ورود
                        </a>
                    </li>
                    <li class="nav-item">
                        <a data-toggle="pill" href="#nav-tab-bank" class="nav-link rounded-pill">
                            <i class="fa fa-university"></i>
                            مهمان
                        </a>
                    </li>
                    </ul>
                    <!-- End -->

                    <!-- Credit card form content -->
                    <div class="tab-content">

                    <!-- credit card info-->
                    <div id="nav-tab-card" class="tab-pane fade show active text-right">
                        <p class="alert alert-success">
                            ثبت نام سما با موفقیت انجام شد
                        </p>
                        <form role="form">
                        <div class="form-group">
                            <label for="username">
                                نام و نام خانوادگی
                            </label>
                            <input type="text" name="username" placeholder="علی نادری" required class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="cardNumber">
                                شماره تماس
                            </label>
                            <div class="input-group">
                            <input type="text" name="cardNumber" placeholder="09*****987" class="form-control" required>
                            <div class="input-group-append">
                                <span class="input-group-text text-muted">
                                    <i class="fa fa-cc-visa mx-1"></i>
                                    <i class="fa fa-cc-amex mx-1"></i>
                                    <i class="fa fa-cc-mastercard mx-1"></i>
                                </span>
                            </div>
                            </div>
                        </div>
                        <div class="row">
                            <div class="form-group">
                                <label>
                                    <span class="hidden-xs">
                                        تاریخ تولد
                                    </span>
                                </label>
                                <div class="input-group">
                                <input type="number" placeholder="MM" name="" class="form-control" required>
                                <input type="number" placeholder="YY" name="" class="form-control" required>
                                <input type="number" placeholder="DD" name="" class="form-control" required>
                                </div>
                            </div>
                        </div>
                        <button type="button" class="subscribe btn btn-primary btn-block rounded-pill shadow-sm">           
                            ثبت
                        </button>
                        </form>
                    </div>
                    <!-- End -->

                    <!-- Paypal info -->
                    <div id="nav-tab-paypal" class="tab-pane fade">
                        <p>Paypal is easiest way to pay online</p>
                        <p>
                        <button type="button" class="btn btn-primary rounded-pill"><i class="fa fa-paypal mr-2"></i> Log into my Paypal</button>
                        </p>
                        <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                        </p>
                    </div>
                    <!-- End -->

                    <!-- bank transfer info -->
                    <div id="nav-tab-bank" class="tab-pane fade">
                        <h6>Bank account details</h6>
                        <dl>
                        <dt>Bank</dt>
                        <dd> THE WORLD BANK</dd>
                        </dl>
                        <dl>
                        <dt>Account number</dt>
                        <dd>7775877975</dd>
                        </dl>
                        <dl>
                        <dt>IBAN</dt>
                        <dd>CZ7775877975656</dd>
                        </dl>
                        <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                        </p>
                    </div>
                    <!-- End -->
                    </div>
                    <!-- End -->

                </div>
            </b-col>
        </b-row>
    </b-container>
</template>

<style>
.bg-secondary {
  border-radius: 68px;
  padding: 22px;
  background-color:rgb(243, 250, 255)!important;
}
</style>