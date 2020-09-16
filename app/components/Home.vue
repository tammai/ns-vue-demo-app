<template>
  <Page>
    <ActionBar title="Home" />
    <StackLayout class="container" android:clipToPadding="false">
      <StackLayout class="card" androidElevation="10">
        <Label class="h3" :text="message" />
      </StackLayout>
    </StackLayout>
  </Page>
</template>

<script>
export default {
  computed: {
    message() {
      return "Blank {N}-Vue app";
    }
  }
};
</script>

<style scoped lang="scss">
.container {
  padding: 16;
  background-color: #f0f0f0;
}

.card {
  border-radius: 12;
  background-color: #ffffff;
  padding: 24;
  height: 100;
  vertical-align: center;
}

.h3 {
  color: #444444;
}
</style>
