<script>
    import './styles.css';

    let link = 'https://cloud.vincentsmid.xyz/s/xTYydH6ZiB9WX9a';

    function goToLink() {
        window.location.href = link;
    }
</script>

<body>
    <h1>Vítej na stránce pro studijní materiály oboru SIT. Momentálně jsou na odkaze dole.</h1>
    <h1>V budoucnu budou materiály přesunuty přímo sem.</h1>
    <h1>Pro jakékoliv dotazy mě můžete kontaktovat na <a href="mailto:support@cvutsit.cz">support@cvutsit.cz</a></h1>
    <h1> DŮLEŽITÉ - mail server měl výpadek, takže mi nechodily maily. Pokud jste nějaké odeslali, odešlete je, prosím, znovu.</h1>
    <div class="button-box">
        <button on:click={goToLink}>Odkaz na materiály</button>
    </div>
</body>

<style>
    h1 {
        margin-top: 5rem;
        text-align: center;
    }

    .button-box {
        display: flex;
        position: fixed;
        bottom: 0;
        left: 0;
        right: 0;
        margin-bottom: 5rem;
        justify-content: center;
    }

    button {
        background: var(--color-theme-1);
        color: var(--color-theme-4);
        display: inline-block;
        outline: 0;
        cursor: pointer;
        border: 5px solid var(--color-theme-1);
        border-radius: 5px;
        height: 50px;
        font-size: 18px;
        font-weight: 700;
        line-height: 1;
        opacity: 0.9;
        box-shadow: 0 19px 38px rgba(0,0,0,0.30), 0 15px 12px rgba(0,0,0,0.22);
        margin-top: 5rem;
    }
</style>