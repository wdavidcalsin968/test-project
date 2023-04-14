<script lang="ts">
import Home from "../page/Home.vue";
import Login from "../page/Login.vue";
import Register from "../page/Register.vue";
import NotFound from "../page/NotFound.vue";
import VueRouter from "vue-router";

const routes = [
  { path: "/", component: Home },
  { path: "/login", component: Login },
  { path: "/register", component: Register },
];

const router = VueRouter.createRouter({
  history: VueRouter.createWebHashHistory(),
  routes,
});

export default router;
</script>
