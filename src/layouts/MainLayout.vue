<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-img
          src="https://wpocean.com/html/tf/pengu/assets/images/logo.svg"
          :ratio="3 / 1"
          spinner-color="primary"
          spinner-size="5px"
          width="90px"
          height="25px"
        />
        <q-space />
        <div class="q-pa-md text-red">
          <q-btn flat no-focus label="HOME">
            <q-menu transition-show="scale" transition-hide="scale">
              <q-list style="min-width: 100px">
                <q-item clickable>
                  <q-item-section>HOME STYEL 1</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>HOME STYEL 2</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>HOME STYEL 3</q-item-section>
                </q-item>
                <q-separator />
                <q-item clickable>
                  <q-item-section>HOME STYEL 4</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
          <q-btn flat no-focus label="SHOP"/>
          <q-menu transition-show="scale" transition-hide="scale"> </q-menu>
          <q-btn flat no-focus label="PAGES">
            <q-menu transition-show="scale" transition-hide="scale">
              <q-list style="min-width: 100px">
                <q-item clickable>
                  <q-item-section>About</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>cart</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>wishlist</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>checkpot</q-item-section>
                </q-item>
                <q-separator />
                <q-item clickable>
                  <q-item-section>product</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>product single</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>Order</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>Login</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>404 Error</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
          <q-btn flat no-focus label="BLOG">
            <q-menu transition-show="scale" transition-hide="scale">
              <q-list style="min-width: 100px">
                <q-item clickable>
                  <q-item-section>Blog right sider</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>Blog left sider</q-item-section>
                </q-item>
                <q-separator />
                <q-item clickable>
                  <q-item-section>Blog fullwidth</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>Blog details</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
          <q-btn flat no-focus label="CONTACT US">
            <q-menu transition-show="scale" transition-hide="scale">
              <q-list style="min-width: 100px">
                <q-item clickable>
                  <q-item-section>Having fun</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section>Crazy for transitions</q-item-section>
                </q-item>
                <q-separator />
                <q-item clickable>
                  <q-item-section>Mind blown</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
        </div>

        <q-space />

        <div>
          <q-btn icon="shopping_basket" class="q-mx-sm" color="red" round />
          <q-btn icon="search" class="q-mx-sm" color="red" round />
          <q-btn icon="person" class="q-mx-sm" color="red" round />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer reveal class="bg-grey special_footer">
      <div class="q-py-xl">
        <div class="row">
          <div class="col q-px-xl">
            <q-img
              src="https://wpocean.com/html/tf/pengu/assets/images/logo.svg"
              :ratio="3 / 1"
              spinner-color="primary"
              spinner-size="5px"
              width="90px"
              height="25px"
            />
            <div class="q-py-md">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugit
              corporis ducimus iure ad voluptatum modi nam laudantium
              reprehenderit molestiae, suscipit cupiditate. Corrupti, ducimus.
              Iure aut voluptates quia architecto recusandae
            </div>
            <div class="row">
              <div class="col">
                <div>
                  <q-btn flat outline round>
                    <a href="">
                      <q-img
                        style="width: 30px; height: 30px"
                        src="~assets/my-img/facebook.png"
                      />
                    </a>
                  </q-btn>
                </div>
              </div>
              <div class="col">
                <div>
                  <q-btn flat outline round>
                    <a href="">
                      <q-img
                        style="width: 30px; height: 30px"
                        src="~assets/my-img/icons8-skype-50.png"
                      />
                    </a>
                  </q-btn>
                </div>
              </div>
              <div class="col">
                <div>
                  <q-btn flat outline round>
                    <a href="">
                      <q-img
                        style="width: 30px; height: 30px"
                        src="~src/assets/my-img/twitter.png"
                      />
                    </a>
                  </q-btn>
                </div>
              </div>
              <div class="col">
                <div>
                  <q-btn flat outline round>
                    <a href="">
                      <q-img
                        style="width: 30px; height: 30px"
                        src="~src/assets/my-img/linkedin-logo.png"
                      />
                    </a>
                  </q-btn>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="text-bold text-h4">Categories</div>
            <q-btn flat no-caps>
              <div class="row">
                <div class="col-3">
                  <q-icon name="fiber_manual_record" size="14px" />
                </div>
                <div class="col-9">Woman</div>
              </div>
            </q-btn>

            <div>
              <q-btn flat no-caps>
                <div class="row">
                  <div class="col-3">
                    <q-icon name="fiber_manual_record" size="14px" />
                  </div>
                  <div class="col-9">Man</div>
                </div>
              </q-btn>
            </div>
            <div>
              <q-btn flat no-caps>
                <div class="row">
                  <div class="col-3">
                    <q-icon name="fiber_manual_record" size="14px" />
                  </div>
                  <div class="col-9">kids</div>
                </div>
              </q-btn>
            </div>
            <div>
              <q-btn flat no-caps>
                <div class="row">
                  <div class="col-3">
                    <q-icon name="fiber_manual_record" size="14px" />
                  </div>
                  <div class="col-9">Shoes</div>
                </div>
              </q-btn>
            </div>
            <div>
              <q-btn flat no-caps>
                <div class="row">
                  <div class="col-3">
                    <q-icon name="fiber_manual_record" size="14px" />
                  </div>
                  <div class="col-9">Jwellery</div>
                </div>
              </q-btn>
            </div>
            <div>
              <q-btn flat no-caps>
                <div class="row">
                  <div class="col-3">
                    <q-icon name="fiber_manual_record" size="14px" />
                  </div>
                  <div class="col-9">T-Shirt</div>
                </div>
              </q-btn>
            </div>
          </div>
          <div class="col">
            <div>
              <div class="text-bold text-h4">Blog Post</div>
              <div class="row">
                <div class="col-3 q-pa-md">
                  <q-img
                    src="src/assets/my-img/white-female-girl-people-background.jpg"
                    :ratio="16 / 9"
                    width="70px"
                    height="70px"
                  />
                </div>
                <div class="col-9 q-pa-md">
                  <div>
                    it is a long estabalish fact that a reader will be
                    distracted
                  </div>
                  <div class="text-weight-thin">12/july/2025</div>
                </div>
              </div>
              <div class="row">
                <div class="col-3 q-pa-md">
                  <q-img
                    src="src/assets/my-img/white-female-girl-people-background.jpg"
                    :ratio="16 / 9"
                    width="70px"
                    height="70px"
                  />
                </div>
                <div class="col-9 q-pa-md">
                  <div>
                    it is a long estabalish fact that a reader will be
                    distracted
                  </div>
                  <div class="text-weight-thin">12/july/2025</div>
                </div>
              </div>
            </div>
          </div>
          <div class="col q-pa-md">
            <div class="text-bold text-h4">Newslatter</div>
            <div>
              subscribe to our newslatter abd get 10% off your first purchase
            </div>
            <div class="q-pa-md"></div>
            <div class="q-py-sm flex flex-center">
              <q-btn
                color="red"
                label="subscribe"
                dense
                unelevated
                style="width: 325px"
                class="q-py-sm"
              />
            </div>
          </div>
        </div>
      </div>
    </q-footer>
  </q-layout>
</template>

<script>
import { createRouter, createWebHistory } from "vue-router";
</script>

<style lang="scss" scoped>
.special_footer {
  position: static;
  bottom: 0;
  left: 0;
  right: 0;
  z-index: 1000;
}
</style>
