<template>
    <header class="header">
        <div class="container">
            <div class="header-wrapper">
                <nav class="header-nav">
                    <router-link class="header-link" to="/">Home</router-link>
                    <router-link class="header-link" to="/saved">Saved</router-link>
                </nav>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
    @import 'header.scss';
</style>