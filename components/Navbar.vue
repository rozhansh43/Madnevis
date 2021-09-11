<template>
    <b-navbar type="light">
        <b-container class="my-5 py-2 bg-secondary">
            <b-col cols="8">
                <b-navbar-nav>
                    <b-navbar-brand class="d-flex justify-content-center align-items-center mx-3">
                        <NuxtLink to="/">
                            <b>
                                LOGO
                            </b>
                        </NuxtLink>
                    </b-navbar-brand>

                    <b-nav-item>
                        <NuxtLink to="/" class="nav-link">
                            خانه
                            <span class="sr-only">
                                (current)
                            </span>
                          </NuxtLink>
                    </b-nav-item>
                    
                    <b-nav-item>
                        <NuxtLink to="/my-items" class="nav-link">
                            وبلاگ
                            <span class="sr-only">
                                (current)
                            </span>
                          </NuxtLink>
                    </b-nav-item>

                    <b-nav-item>
                        <NuxtLink to="/my-items" class="nav-link">
                            ثبت سفارش   
                            <span class="sr-only">
                                (current)
                            </span>
                        </NuxtLink>
                    </b-nav-item>

                    <b-nav-item>
                        <NuxtLink to="/my-items" class="nav-link">
                             تعرفه
                            <span class="sr-only">
                                (current)
                            </span>
                        </NuxtLink>
                    </b-nav-item>

                    <b-nav-item>
                        <NuxtLink to="/my-items" class="nav-link">
                            خدمات
                            <span class="sr-only">
                                (current)
                            </span>
                        </NuxtLink>
                    </b-nav-item>
                </b-navbar-nav>
            </b-col>

            <b-col cols="4">
                <b-button pill variant="success" class="border-50">
                    <NuxtLink to="/register" class="text-white">
                        ورود/عضویت
                    </NuxtLink>
                </b-button>
            </b-col>
        </b-container>
    </b-navbar>
</template>

<script>

</script>

<style scoped>
.container {
    box-shadow: 2px 2px 2px lightgrey;
    border-radius: 50px;
}

.nav-link {
    font-weight: 700;
}

.btn {
    text-decoration: none;
    border-radius: 50px!important;
}
</style>