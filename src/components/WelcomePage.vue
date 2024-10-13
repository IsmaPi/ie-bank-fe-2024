<template>
    <div class="welcome-container">
        <h1>Welcome to the IE Bank</h1>
        <p>We host accounts for students of all years and backgrouds.</p>
        <div class="links">
            <router-link to="/accounts" class="link-button">Accounts</router-link>
            <router-link to="/skull" class="link-button">Skull</router-link>
        </div>
    </div>
</template>

<script>
export default {
    name: "WelcomePage",
}
</script>

<style scoped>
.welcome-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100vh;
    background-color: #f0f4f8;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 3.5rem;
    color: #004080;
    margin-bottom: 20px;
}

p {
    font-size: 1.2rem;
    color: #555;
    margin-bottom: 40px;
}

.links {
    display: flex;
    width: 100%;
    justify-content: center;
    gap: 20px;
}

</style>
