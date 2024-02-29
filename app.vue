<template>
  <div>
    <header>
      <h1>{{ title }}</h1>
    </header>

    <main>
      <nuxt />
    </main>

    <footer>
      <p>&copy; 2024 Your Company</p>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "Hello From Nishant",
    };
  },
};
</script>

<style>
/* Add your global styles here */
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #3498db;
  color: #fff;
  text-align: center;
  padding: 1rem;
}

main {
  padding: 2rem;
}

footer {
  background-color: #2c3e50;
  color: #fff;
  text-align: center;
  padding: 1rem;
}
</style>
