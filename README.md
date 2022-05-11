# FrameBok
Un essai de librairie CSS 
# CDN
    <link rel="stylesheet" href="https://yannickbiheul.com/framebok/framebok_mini.css">
# Utilisation
## Grille
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: 80px auto 80px;
    min-height: 100vh;
## Menu de navigation
    <nav class="nav-black>
        <ul class="nav-list">
            <li>
                <a href="">Menu</a>
            </li>
        </ul>
    </nav>
## Contenu principal
    <main>
        contenu
    </main>
## Footer
    <footer class="footer-black">
        <a href="">Footer</a>
    </footer>
## Formulaire
    <form>
        <div class="bloc-label-input">
            <label for="champ1">Input 1</label>
            <input type="text">
        </div>
        <div class="bloc-label-input">
            <label for="champ2">Input2</label>
            <input type="text">
        </div>
        <div class="bloc-label-input">
            <label for="champ2">Textarea 1</label>
            <textarea></textarea>
        </div>
        <div class="bouton">
            <button type="submit">Valider</button>
        </div>
    </form>
## Messages
    <p class="valid">Un message de validation</p>
    <p class="error">Un message d'erreur</p>
## Boutons
    <div class="bouton">
        <button>Bouton</button>
    </div>
    <div class="bouton">
        <a>Bouton</a>
    </div>
## Couleurs
    color: var(--blue1);
* --blue1
* --blue2
* --green1
* --green2
* --red1
* --red2
* --black1
## Backgrounds
    background: var(--bgBlack);
* --bgBlack
* --bgWhite
* --bgBlue
