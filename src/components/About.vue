<template>
    <div class="about">
        <h1>Hello {{ their_name }}, This is an about page</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Labore, provident. Veritatis qui voluptates cupiditate quia similique officiis debitis, quis expedita sit deserunt obcaecati distinctio eveniet non perspiciatis reiciendis sequi dolore.</p>
    </div>
</template>

<script>
export default {
  name: "About",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>
