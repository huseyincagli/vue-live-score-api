<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
  </div>
</template>
<script>
import Header from "./components/header/Header.vue";
import Footer from "./components/footer/Footer.vue";
import Main from "./components/main/Main.vue";
export default {
  name: "App",
  components: {
    Header,
    Footer,
    Main,
  },
};
</script>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
:root {
  --blue: #007bff;
  --indigo: #6610f2;
  --purple: #6f42c1;
  --pink: #e83e8c;
  --red: #dc3545;
  --orange: #fd7e14;
  --yellow: #ffc107;
  --green: #28a745;
  --teal: #20c997;
  --cyan: #17a2b8;
  --white: #fff;
  --gray: #6c757d;
  --gray-dark: #343a40;
  --primary: #007bff;
  --secondary: #6c757d;
  --success: #28a745;
  --info: #17a2b8;
  --warning: #ffc107;
  --danger: #ff4b55;
  --light: #f8f9fa;
  --dark: #343a40;
  --betist-blue: #3199e1;
  --betist-darkblue: #2e91d5;
  --betist-darkblue2: #2a85c4;
  --betist-green: #3fb26e;
  --betist-darkgreen: #3ba868;
  --betist-darkgreen2: #37a163;
  --betist-red: #ff4b55;
  --betist-dark: #424757;
  --betist-lightdark: #4c5262;
  --betist-light: #f4f5f9;
  --betist-yellow: #ffc64b;
  --breakpoint-xs: 0;
  --breakpoint-sm: 576px;
  --breakpoint-md: 768px;
  --breakpoint-lg: 992px;
  --breakpoint-xl: 1200px;
  --font-family-sans-serif: -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol";
  --font-family-monospace: SFMono-Regular, Menlo, Monaco, Consolas,
    "Liberation Mono", "Courier New", monospace;
}
body {
  min-height: 100vh;
}
body ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
.container {
  width: 1290px;
}
#app {
  background-color: #ececec;
}
</style>
