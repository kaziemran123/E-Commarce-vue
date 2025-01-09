<template>
  <div>
    <div class="row flex-center q-px-xl">
      <div class="col-7 q-pa-xl border">
        <div class="text-h2 text-bold">Sneakers For Woman</div>
        <div class="text-weight-thin text-caption">
          These can include things such as website crashes, slow loading times,
          poor customer service, and more. However, there are ways to overcome
          these challenges and succeed in the world of ecommerce.
        </div>
        <div class="row q-py-lg">
          <div class="col-2">
            <div class="text-h6">price:</div>
            <div class="text-weight-thin text-caption">$50.60</div>
          </div>
          <div class="col-2">
            <div class="text-h6">Color:</div>
            <q-avatar
              size="20px"
              font-size="10px"
              color="grey-3"
              text-color="white"
              class="q-mr-sm"
            />
            <q-avatar
              size="20px"
              font-size="10px"
              color="brown-3"
              text-color="white"
              class="q-mr-sm"
            />
            <q-avatar
              size="20px"
              font-size="10px"
              color="purple-11"
              text-color="white"
              class="q-mr-sm"
            />
            <q-avatar
              size="20px"
              font-size="10px"
              color="green-9"
              text-color="white"
            />
          </div>

          <div class="col-5">
            <div class="text-h6">size</div>

            <q-btn color="white" label="9" class="text-black q-mr-sm" />
            <q-btn color="white" label="10" class="text-black q-mr-sm" />
            <q-btn color="white" label="11" class="text-black q-mr-sm" />
            <q-btn color="white" label="12" class="text-black q-mr-sm" />
            <q-btn color="white" label="13" class="text-red" />
          </div>
        </div>
      </div>

      <div class="col-5 q-py-md">
        <div class="flex flex-center q-pa-md">
          <q-img
            src="https://wpocean.com/html/tf/pengu/assets/images/slider/8.png"
            :ratio="14 / 13"
          />
        </div>
      </div>
    </div>
    <div class="row q-px-xl">
      <div class="q-px-lg col">
        <q-btn
          color="red"
          label="50% off"
          class="q-mr-lg"
          style="width: 200px; height: 60px"
          outline
          dense
        />
        <q-btn
          text-color="white"
          label="Shoop Now"
          style="width: 200px; height: 60px"
          outline
          dense
          class="bg-red"
        />
      </div>
    </div>
    <!-- seccond page -->
    <div class="q-py-xl">
      <div class="text-center text-h4">New Arraival</div>
      <div class="text-center text-h5 text-weight-thin text-caption">
        hear is our new arraival products that you may like
      </div>
      <div class="q-pa-md text-center flex flex-center">
        <q-separator style="width: 100px" color="red"></q-separator>
      </div>
    </div>
    <div class="row q-px-lg">
      <div class="col q-pa-md">
        <q-card class="my-card">
          <q-img
            src="https://wpocean.com/html/tf/pengu/assets/images/product-single/1.jpg"
            spinner-size="70px"
          />
          <div class="q-pa-md flex flex-center">
            <div class="text-bold text-h6 flex flex-center">
              Long Sleeve Tops
            </div>
            <div class="row q-px-md flex justyfy-center items-center">
              <div class="col q-pa-md" style="text-decoration: line-through">
                $85.50
              </div>
              <div class="col text-red">$70.30</div>
            </div>
          </div>
        </q-card>
      </div>
      <div class="col q-pa-md">
        <q-card class="my-card">
          <q-img
            src="https://wpocean.com/html/tf/pengu/assets/images/product-single/2.jpg"
            spinner-color="primary"
            spinner-size="70px"
          />
          <div class="q-pa-md flex flex-center">
            <div class="text-bold text-h6">white wedding shoe</div>
            <div class="row q-px-md flex justyfy-center items-center">
              <div class="col q-pa-md" style="text-decoration: line-through">
                $150.50
              </div>
              <div class="col text-red">$120.50</div>
            </div>
          </div>
        </q-card>
      </div>
      <div class="col q-pa-md">
        <q-card class="my-card">
          <q-img
            src="https://wpocean.com/html/tf/pengu/assets/images/product-single/3.jpg"
            spinner-color="primary"
            spinner-size="70px"
          />
          <div class="q-pa-md flex flex-center">
            <div class="text-bold text-h6">Long chain Whit Lockel</div>
            <div class="row q-px-md flex justyfy-center items-center">
              <div class="col q-pa-md" style="text-decoration: line-through">
                $85.50
              </div>
              <div class="col text-red">$70.30</div>
            </div>
          </div>
        </q-card>
      </div>
      <div class="col q-pa-md">
       <q-card class="my-card">
        <q-img
          src="https://wpocean.com/html/tf/pengu/assets/images/product-single/4.jpg"
          spinner-color="primary"
          spinner-size="70px"
        />
        <div class="q-pa-md flex flex-center">
            <div class="text-bold text-h6">Winter Jacket</div>
            <div class="row q-px-md flex justyfy-center items-center">
              <div class="col q-pa-md" style="text-decoration: line-through">
                $100.50
              </div>
              <div class="col text-red">$80.30</div>
            </div>
          </div>
       </q-card>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
