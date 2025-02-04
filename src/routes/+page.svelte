<script>
    let message = $state();
</script>

<div>
    <h1>What do you want to write?</h1>
    <p>Your Message: {message}</p>
    <input type="text" bind:value={message} />
</div>

<style>
    div {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
        background-color: #f0f8ff;
        font-family: Arial, sans-serif;
    }

    h1 {
        color: #333;
        margin-bottom: 20px;
    }

    p {
        font-size: 20px;
        color: #666;
        margin-bottom: 20px;
    }

    input {
        padding: 10px;
        font-size: 15px;
        border: 2px solid #ccc;
        border-radius: 5px;
        width: 300px;
        box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
    }

    input:focus {
        border-color: #007BFF;
    }
</style>