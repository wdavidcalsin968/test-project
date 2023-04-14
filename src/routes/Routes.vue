<script lang="ts">
import Home from "../page/home.vue";
import Login from "../page/login.vue";
import Register from "../page/register.vue";
import NotFound from "../page/register.vue";
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
