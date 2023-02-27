<script>
    import Nav from "./Nav.svelte";
</script>

<section id='hero'>
    <Nav />
    <div class="tagline">
        <h1>Uniting Hearts with Purpose...</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
    </div>
</section>

<style>
    
    @import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&family=Lobster&display=swap');
    #hero {
      height: 100vh;
      width: 100%;
      background-image: url('../assets/wedding-ring-black-table_41050-791.avif');
      background-size: cover;
    }

    .tagline {
        color: white;
        display: flex;
        flex-direction: column;
        max-width: 50%;
        height: 80vh;
        padding-left: 1rem;
        justify-content: center;
        align-items: center;
    }

    .tagline > h1 {
        padding-bottom: 1rem;
        font-size: 3rem;
        width: fit-content;
        font-family: Lobster, open-sans;
    }

    .tagline > p {
        font-family: 'Josefin Sans';
        max-width: 65ch;
    }
</style>
