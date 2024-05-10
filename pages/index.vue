<template>
  <v-row no-gutters class="fill-height pa-16" justify="center">
    <v-col cols="12" xxl="5" xl="5" lg="5">
      <v-row no-gutters class="fill-height" align-content="center">
        <v-col cols="12" class="text-h2 font-weight-black"> Welcome to </v-col>
        <v-col cols="12" class="text-h2 font-weight-black">
          UIC Bookstore
        </v-col>
        <v-col cols="12" class="text-h2 font-weight-black">
          Reservation System
        </v-col>
        <v-col cols="12" class="text-h2 font-weight-black">
          (Fr. Selga Campus)
        </v-col>

        <v-col cols="12" class="mt-4">
          <v-row no-gutters>
            <v-col xxl="2" xl="2" lg="4" class="mx-2">
              <v-btn block @click="useRouter().push({ name: 'login' })">
                sign in
              </v-btn>
            </v-col>

            <v-col xxl="2" xl="2" lg="4" class="mx-2">
              <v-btn block @click="useRouter().push({ name: 'sign-up' })">
                sign up
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-col>

    <v-col cols="12" xxl="5" xl="5" lg="5">
      <v-row no-gutters> </v-row>
    </v-col>
  </v-row>
</template>

<script setup>
definePageMeta({
  layout: "plain",
});
</script>
