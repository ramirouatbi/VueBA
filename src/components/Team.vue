<template>
  <v-content>
    <div class="block">
      <v-container>
        <h2 class="titlega text-center">Our Team</h2>
        <v-row>
          <v-col v-for="item in items" :key="item.id" class="d-flex child-flex" cols="12" sm="4">
            <v-card flat tile class="mx-auto mt-16">
              <v-img :src="item.src" aspect-ratio="1" class="grey lighten-2"></v-img>
              <v-card-text class="text--primary text-center">
                <div class="title">{{ item.name }}</div>
                <p class="job">{{ item.title }}</p>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </v-content>
</template>

<script>

export default {
    name: 'Team',
  data () {
    return {
          items: [
        {
          id: 1,
          src: require("../assets/team4.png"),
          name: 'Peter Smith',
          title: 'Director'
        },
        {
          id: 2,
          src: require("../assets/team7.png"),
          name: 'Roy Perry',
          title: 'Photographer'
        },
        {
          id: 3,
          src: require("../assets/team6.png"),
          name: 'Lisa White',
          title: 'Freelancer'
        }
      ]
    }
  }
};
</script>

<style scoped>

.job{
  color:#004372;
}
</style>