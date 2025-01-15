<template>
  <div class="">
    <q-card class="my-card">
      <img
        src="src/assets/my-img/colourful-packets-decorated-leaves.jpg"
        height="500px"
      />

      <div>
        <div class="absolute-full">
          <div class="text-center">
            <div class="text-h3 text-white text-bold">Shope</div>
            <div class="text-white">Home.shop</div>
          </div>
        </div>

        <!-- ygj -->
        <div>
          <div class="row">
            <div class="col-3 q-pa-md">
              <q-card class="my-card q-qx-sm">
                <div class="text-bold text-h4 q-pa-md">search</div>
                <div class="q-pa-md">
                  <q-separator style="width: 70px" color="red"></q-separator>
                </div>
                <div class="q-pa-md">
                  <q-input type="text" placeholder="search" outlined dense>
                    <q-btn color="red" icon-right="search" />
                  </q-input>
                </div>
                <div class="text-bold text-h4 q-pa-md">price</div>
                <div class="q-pa-md">
                  <q-separator style="width: 70px" color="red"></q-separator>
                </div>
                <div>
                  <q-list bordered>
                    <q-item
                      v-for="(item, index) in items"
                      :key="index"
                      clickable
                      @click="toggleRadio(index)"
                      v-ripple
                    >
                      <q-item-section>{{ item.label }}</q-item-section>
                      <q-item-section avatar>
                        <q-radio v-model="item.value" :val="true" color="red" />
                      </q-item-section>
                    </q-item>
                  </q-list>
                </div>
                <div class="text-bold text-h4 q-pa-md">Size</div>
                <div class="q-pa-md">
                  <q-separator style="width: 70px" color="red"></q-separator>
                </div>
                 <div>
                  <q-list bordered>
                    <q-item
                      v-for="(item, index) in items"
                      :key="index"
                      clickable
                      @click="toggleRadio(index)"
                      v-ripple
                    >
                      <q-item-section>{{ item.label }}</q-item-section>
                      <q-item-section avatar>
                        <q-radio v-model="item.value" :val="true" color="red" />
                      </q-item-section>
                    </q-item>
                  </q-list>
                </div>
              </q-card>
            </div>
          </div>
        </div>
      </div>
      <div>size</div>
    </q-card>
  </div>
</template>

<script>
import { reactive } from "vue";

export default {
  setup() {
    const items = reactive([
      { label: "All items", value: false },
      { label: "$50-$100", value: false },
      { label: "$100-$200", value: false },
      { label: "$200-$300", value: false },
      { label: "$300-$400", value: false },
      { label: "$400-and more", value: false },
    ]);

    const toggleRadio = (index) => {
      items[index].value = !items[index].value;
    };

    return {
      items,
      toggleRadio,
    };
  },
};
</script>
