﻿<template>
    <div id="nav">
        <router-link to="/">Home</router-link>
        |
        <router-link to="/about">About</router-link>
        |
        <router-link to="/admin">Admin</router-link>
    </div>
</template>

<script>
	export default {
		name: "Nav"
	}
</script>

<style scoped lang="less">

    #nav {
        padding: 30px;

        a {
            font-weight: bold;
            color: #2c3e50;

            &.router-link-exact-active {
                color: #42b983;
            }
        }
    }
</style>