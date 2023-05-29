<div class="layout">

<ul>
    <li><a href="/">Sobre</a></li>
    <li><a href="/pros_e_contras">Prós e Contras</a></li>
    <li><a href="/avaliacoes">Avaliações</a></li>
    <li><a href="/comunidade">Comunidade</a></li>
</ul>
</div>

<slot />

<style>

    * {
        margin: 0;
        padding: 0;
    }

    .layout {
        background-color: black;
        color: white;
    }

    a {
        text-decoration: none;
        color: white;
        font-family: Arial, Helvetica, sans-serif;
    }

    li {
        margin-left: 22px;
        list-style: none;
        display: inline;
        font-family: Arial, Helvetica, sans-serif;
    }

</style>