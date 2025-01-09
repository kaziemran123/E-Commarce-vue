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
          <q-btn flat no-focus label="SHOPE">
            <q-menu transition-show="scale" transition-hide="scale"> </q-menu>
          </q-btn>
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
  </q-layout>
</template>
