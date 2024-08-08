<template>
    <section id="proyectos" role="region" aria-labelledby="proyectos-heading">
        <h2 id="proyectos-heading">Proyectos</h2>
        <div class="container">
            <article class="art" role="article">
                <p>Próximamente</p>
            </article>
            <article class="art" role="article">
                <p>Próximamente</p>
            </article>
            <article class="art" role="article">
                <p>Próximamente</p>
            </article>
            <article class="art" role="article">
                <p>Próximamente</p>
            </article>
            <article class="art" role="article">
                <p>Próximamente</p>
            </article>
            <article class="art" role="article">
                <p>Próximamente</p>
            </article>
        </div>
    </section>
</template>

<script setup>
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');

#proyectos {
    width: 80%;
    margin: 0 auto;
    padding: 2em;
    border: 2px solid #19c778;
    border-radius: 1em;
}

#proyectos h2 {
    font-family: "Lato", sans-serif;
    font-weight: 700;
    font-style: normal;
    text-align: center;
    font-size: 2.5em;
    margin: 0.8em 0 1em;
    color: whitesmoke;
    text-decoration: underline;
}

.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5em;
}

.art {
    height: 200px;
    border: 2px solid #19c778;
    border-radius: 1em;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.8em;
    color: whitesmoke;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.art:hover {
    transform: scale(1.05);
    cursor: pointer;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.art p {
    font-weight: 400;
    font-style: italic;
    text-align: center;
}

@media (max-width: 1024px) {
    .container {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (max-width: 768px) {
    .container {
        grid-template-columns: 1fr;
    }
}
</style>
