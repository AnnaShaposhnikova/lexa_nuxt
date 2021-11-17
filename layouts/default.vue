<template>
  <div class="body">
    <header>
      <div class="container-fluid">
        <div class="row justify-content-sm-end contacts">
          <div class="col" style="text-align: right">
                    <div>
                        <b-icon icon="telephone" style="color: black"></b-icon> <Tel/>
                    </div>
          </div>
        </div>
        <div class="row justify-content-center logo_background">
          <div class="col text-center nadpys">
            <div class="navbar-brand">
                <Logo/>
            </div>
          </div>
        </div>
        <div class="row mainNav">
          <div class="col d-inline-flex justify-content-center">
            <Nav/>
          </div>
        </div>
      </div>
    </header>
    <main>
      <Nuxt />
    </main>
      <footer>
          <section class="container pt-4">
              <div class="row justify-content-center ">
                  <div class="col-sm-4 text-сenter">
                      <h4 class="text-center mb-3">
                          Гостевой дом "Дачная 26"
                      </h4>
                      <p class="text-center">
                          Дом в уникальном, одном из самых красивых мест побережья
                      </p>
                  </div>
                  <div class="col-sm-6 text-center">
                      <h4 class="text-center mb-3">
                          Наши контакты
                      </h4>
                      <p class="contacts-footer text-center">
                          <Tel/>
                      </p>
                      <p  class="contacts-footer text-center">
                         <Mail/>
                      </p>

                  </div>
                  <div class="col-sm-2 text-start">
                      <div>
                          <h4 class="text-center mb-3">Мы в соцсетях</h4>
                          <div class="brand-social p-3">
                              <a href="https://www.instagram.com/ordjo_dachnaya26/">
                                  <img src="/images/insagram.jpg" style="height: 50px">
                              </a>
                          </div>
                      </div>
                  </div>
              </div>

          </section>
      </footer>
  </div>

</template>
<script>
import { BIcon, BIconTelephone, BIconEnvelope } from 'bootstrap-vue';
export default {
    components: {
        BIcon,
        BIconTelephone,
        BIconEnvelope
    }
}
</script>

