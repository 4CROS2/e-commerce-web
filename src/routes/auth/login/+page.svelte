<script lang="ts">
	import TextField from '../components/textField.svelte';
</script>

<title> Login </title>

<div class="display">
	<div class="login-container">
		<h1>Login</h1>
		<TextField label="email" inputType="email" />
		<TextField label="password" inputType="password" />
	</div>
</div>

<style>
    .display{
        height: 100vh;
        width: 100vw;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
	.login-container {
        width: 350px;
		padding: 20px;
		display: flex;
		flex-direction: column;
		align-items: center;
		background: #9c7070;
        border-radius: 17px;
	}
    h1{
        margin-bottom: 20px;
    }
</style>
