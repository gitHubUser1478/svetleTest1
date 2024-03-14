<svelte:head>
    <title>
        Блог
    </title>
</svelte:head>
<div class="container">
    <h1>Мои статьи</h1>
    <div class="blogposts">
        {#each routes as page}
            <div class="post">
                <h2>{page.title}</h2>
                <p>{page.body}</p>
                <p class="readmore">
                    <a href={`/blog/posts/${page.id}`} class="link">Читать далее</a>
                </p>
            </div>
        {/each}
    </div>
</div>

<style>

.container {
    background-color: #f9f9f9;
    margin: 30px auto 50px;
    margin-top: 200px;
    max-width: 900px;
}

.blogposts {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 30px;
}

.post {
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 15px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    background-color: #fff;
    margin-bottom: 20px;
}

.link {
    color: rgb(65, 105, 225);
    text-decoration: none;
}

.link:hover {
    color: rgb(30, 144, 255);
}
</style>

<script>
    import {routes} from './routes.js'
</script>
