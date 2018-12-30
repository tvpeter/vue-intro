<template>
<div>
    <h1> Hello {{the_name}},</h1>
    <h3>This is the about page </h3>
    <p>We're adding a nav element with two links using the Vue component router-link.

We've also added another Vue component router-view which denotes where the views will be placed when the user clicks on a nav item.

While we're here in App.vue, let's give our nav some style in the styles section of the component. Also, modify the body selector so that our UI is no longer centered vertically: </p>
</div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      the_name: this.$route.params.id
    }
  }
}
</script>

