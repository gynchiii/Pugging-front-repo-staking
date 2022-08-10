<template>
  <q-page style="background-color: " class="flex bannerWpp flex-center">
    <q-toolbar style="margin-top: -7em;" class="q-mt-none q-pt-none">
    <!-- PRE BASED -->
      <q-btn-dropdown rounded color="blue-5" label="Lock Period">
        <q-list>
          <q-item clickable v-close-popup @click="onItemClick">
            <q-item-section>
              <q-item-label>NO LOCK</q-item-label>
            </q-item-section>
          </q-item>

          <q-item clickable v-close-popup @click="onItemClick">
            <q-item-section>
              <q-item-label>1 WEEK</q-item-label>
            </q-item-section>
          </q-item>

          <q-item clickable v-close-popup @click="onItemClick">
            <q-item-section>
              <q-item-label>2 WEEK</q-item-label>
            </q-item-section>
          </q-item>

          <q-item clickable v-close-popup @click="onItemClick">
            <q-item-section>
              <q-item-label>3 WEEK</q-item-label>
            </q-item-section>
          </q-item>
        </q-list>
      </q-btn-dropdown>

      <q-toolbar-title>

      </q-toolbar-title>

      <q-btn rounded color="blue-4" glossy label="Connect Wallet" />
    </q-toolbar>
    <div style="width: 100vw; margin-bottom: -200px;" class="flex q-gutter-y-sm flex-center column">
      <q-btn style="opacity: 0.8;" rounded icon="arrow_right" color="blue-5" class="col"></q-btn>
      <q-btn style="opacity: 0.8;" rounded icon="arrow_left" color="blue-5" class="col"></q-btn>
    </div>
    <div class="container q-gutter-x-md row flex flex-center">
      <div style="width: 45vw; height: 50vh; margin-left:;" class="containerNft q-gutter-sm col q-pa-md">
        <div class="flex q-gutter-sm grid flex-grid">
          <!-- CHANGE TO DIV w CDL -->
          <q-img class="clickable" style="border-radius: 20px; width: 10vw; height: 20vh;"
            src="https://arweave.net/R2rUcHLGmcKQlwioZfTqwAiLgmG91uNH6ftPCcWaTfU?ext=png">
          </q-img>
          <q-img style="border-radius: 20px; width: 10vw; height: 20vh;"
            src="https://arweave.net/R2rUcHLGmcKQlwioZfTqwAiLgmG91uNH6ftPCcWaTfU?ext=png">
          </q-img>
          <q-img style="border-radius: 20px; width: 10vw; height: 20vh;"
            src="https://arweave.net/R2rUcHLGmcKQlwioZfTqwAiLgmG91uNH6ftPCcWaTfU?ext=png">
          </q-img>
          <q-img style="border-radius: 20px; width: 10vw; height: 20vh;"
            src="https://arweave.net/R2rUcHLGmcKQlwioZfTqwAiLgmG91uNH6ftPCcWaTfU?ext=png">
          </q-img>
          <q-img style="border-radius: 20px; width: 10vw; height: 20vh;"
            src="https://arweave.net/R2rUcHLGmcKQlwioZfTqwAiLgmG91uNH6ftPCcWaTfU?ext=png">
          </q-img>
          <q-img style="border-radius: 20px; width: 10vw; height: 20vh;"
            src="https://arweave.net/R2rUcHLGmcKQlwioZfTqwAiLgmG91uNH6ftPCcWaTfU?ext=png">
          </q-img>
        </div>
      </div>
      <div style="width: 45vw; height: 50vh" class="containerNft col">

      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
<style>
.bannerWpp {
  background-image: url("https://cdn.discordapp.com/attachments/966042812879618068/987228951158083614/banner_2.png");
  background-size: cover;
  background-position: center;
}

.containerNft {
  background: rgba(49, 89, 137, 0.35);
  border-radius: 16px;
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(12.4px);
  -webkit-backdrop-filter: blur(12.4px);
  border: 1px solid rgba(73, 156, 172, 0.11);
}
</style>
