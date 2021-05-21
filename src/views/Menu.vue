<template>
    <div class="row h-100">
        <div class="col h-100">
            <div class="row-1 h-5">
                <div class="nav h-100">
                    <router-link to="/"> Home </router-link>|
                    <router-link to="/About"> A Propos </router-link>|
                    <router-link to="/Contact"> Contact </router-link>
                </div>
            </div>
            <div class="row h-95">
                <router-view/>
            </div>
        </div> 
    </div>
</template>

<script>
export default {
  name: 'Menu'
}
</script>

<style scoped>
.nav {
  place-content: center;
}

.nav a {
  font-weight: bold;
  color: #2c3e50;
}

.nav a.router-link-exact-active {
  color: #42b983;
}

.h-5 {
    height: 5%;
}

.h-10{
    height: 10%;
}

.h-90{
    height: 90%;
}

.h-95{
    height: 95%;
}
</style>