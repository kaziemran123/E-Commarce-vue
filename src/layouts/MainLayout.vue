<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar>
        <q-img
          src="https://wpocean.com/html/tf/pengu/assets/images/logo.svg"
          :ratio="3/1"
          spinner-color="primary"
          spinner-size="5px"
          width="90px"
          height="25px"
        />
        <q-space />
        <div class="q-pa-md text-red" >
          <q-btn flat no-focus
           label="Scale Menu">
        <q-menu
          transition-show="scale"
          transition-hide="scale"
        >
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
          <q-btn  flat label="SHOP" class="q-mx-sm" />
          <q-btn  flat label="PAGES" class="q-mx-sm" />
          <q-btn  flat label="BLOG" class="q-mx-sm" />
          <q-btn  flat label="CONTUCT US" class="q-px-sm" />
        </div>
         <q-space />

        <div>
          <q-btn icon="shopping_basket" class="q-mx-sm"  color="red" round/>
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
