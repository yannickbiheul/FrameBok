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
    <nav>
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
## Formulaire
    <form>
        <div class="bloc-label-input">
            <label for="champ1">Champ 1</label>
            <input type="text">
        </div>
        <div class="bloc-label-input">
            <label for="champ2">Champ 2</label>
            <input type="text">
        </div>
        <div class="bouton">
            <button type="submit">Valider</button>
        </div>
    </form>
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