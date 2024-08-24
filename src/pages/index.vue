<template>
  <v-container class="fill-height">
    <v-main>
      <div class="text-center">
        <v-img height="360" src="@/assets/logo.svg" />
        <h1 class="text-h2 font-weight-bold">CapyParty</h1>
        <div class="text-body-3 font-weight-light mb-n1">The home for Jackbox mods</div>
        <div class="py-14" />
        <v-row class="d-flex align-center justify-center">
          <v-col cols="auto">
            <v-btn color="white" href="/faq" min-width="230" variant="tonal">
              <v-icon icon="mdi-help" size="large" start />
              Common Questions
            </v-btn>
          </v-col>
          <v-col cols="auto">
            <v-btn color="primary" href="/downloads" min-width="228" size="x-large" variant="elevated">
              <v-icon icon="mdi-download" size="large" start />
              Downloads
            </v-btn>
          </v-col>
          <v-col cols="auto">
            <v-btn color="white" href="https://discord.gg/v7Xzqjg5KQ" min-width="230" variant="tonal">
              <v-icon icon="mdi-chat" size="large" start />
              Our Discord Server
            </v-btn>
          </v-col>
        </v-row>
      </div>
    </v-main>
  </v-container>
</template>

<script setup>
  //
</script>
