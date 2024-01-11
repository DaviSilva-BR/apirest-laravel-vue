<template>
    <div class="container mx-5 m-auto mt-5">
        <h1>Login</h1>
        <LoginFormComponent />
    </div>
</template>

<script>
import LoginFormComponent from '../components/LoginFormComponent.vue';

export default {
    name: 'login',
    components: {
        LoginFormComponent
    }
}
</script>