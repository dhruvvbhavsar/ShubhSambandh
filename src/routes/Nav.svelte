<div>
    <nav>
        <h1>ShubhSambandh</h1>
        <ul class="links">
            <li>Home</li>
            <li>About</li>
            <li>Blogs</li>
            <li>FAQs</li>
            <li>Contact Us</li>
            <button>Log In</button>
        </ul>
    </nav>
</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Libre+Baskerville&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@500&display=swap');

    div {
        padding: 1.5rem 1.5rem;
    }

    nav {
        background-color: white;
        border-radius: 10px;
        height: 7.5vh;
        display: flex;
        align-items: center;
        justify-content: space-between;
        font-family: "Libre Baskerville", sans-serif;
        font-size: 1rem;
    }

    h1 {
        margin-left: 1rem;
        font-family: sans-serif;
    }

    ul {
        display: flex;
        gap: 1rem;
        list-style: none;
        align-items: center;
    }

    li, button {
        padding: 1rem;
    }

    button {
        height: 18px;
        width: 5rem;
        margin-right: 1rem;
        text-align: center;
        display: flex;
        align-items: center;
        font-size: 0.9rem;
        color: white;
        background-color: black;
        border-radius: 7px;
        font-family: 'Roboto Slab';
    }

    li:hover {
       cursor: pointer;
    }

    button:active {
        background-color: blueviolet;
    }

</style>