<script>
    // Declare a reactive variable 'message' using the $state() function.
    let message = $state();
</script>

<!-- Main container div for the content -->
<div>
    <!-- Heading for the input section -->
    <h1>What do you want to write?</h1>
    <!-- Paragraph to display the current message -->
    <p>Your Message: {message}</p>
    <!-- Input field bound to the 'message' variable -->
    <input type="text" bind:value={message} />
</div>

<style>
    /* Style for the main container div */
    div {
        display: flex; /* Use flexbox for layout */
        flex-direction: column; /* Arrange children in a column */
        align-items: center; /* Center children horizontally */
        justify-content: center; /* Center children vertically */
        height: 100vh; /* Full viewport height */
        background-color: #f0f8ff; /* Light blue background color */
    }

    /* Style for the heading */
    h1 {
        color: #333; /* Dark gray text color */
        margin-bottom: 20px; /* Space below the heading */
    }

    /* Style for the paragraph */
    p {
        font-size: 20px; /* Larger font size */
        color: #666; /* Medium gray text color */
        margin-bottom: 20px; /* Space below the paragraph */
    }

    /* Style for the input field */
    input {
        padding: 10px; /* Padding inside the input */
        font-size: 15px; /* Font size for the input text */
        border: 2px solid #ccc; /* Light gray border */
        border-radius: 5px; /* Rounded corners */
        width: 300px; /* Fixed width */
        box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); /* Subtle shadow */
    }

    /* Style for the input field when focused */
    input:focus {
        border-color: #007BFF; /* Blue border on focus */
    }
</style>