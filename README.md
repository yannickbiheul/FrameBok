# FrameBok
Un essai de librairie CSS 
# CDN (à copier dans le "head")
    <link rel="stylesheet" href="https://yannickbiheul.com/framebok/framebok_mini.css">
# Utilisation
## Grille (pas touche, c'est juste pour info)
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: 80px auto 80px;
    min-height: 100vh;
Le menu de navigation (nav) fait 80px de hauteur, le contenu (main) à une hauteur automatique et le footer à une hauteur de 80px.
## Menu de navigation
    <nav class="nav-black">
        <ul class="nav-list">
            <li>
                <a href="">Menu</a>
            </li>
        </ul>
    </nav>
3 couleurs: nav-black, nav-blue, nav-white
## Contenu principal
    <main>
        contenu
    </main>
## Footer
    <footer class="footer-black">
        <a href="">Footer</a>
    </footer>
3 couleurs: footer-black, footer-blue, footer-white
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
    <div class="bouton bouton-bleu">
        <a>Bouton</a>
    </div>
3 couleurs: bouton-bleu, bouton-vert, bouton-rouge
## Couleurs
    color: var(--blue1);
* --blue1
* --blue2
* --blue3
* --blue4
* --green1
* --green2
* --green3
* --green4
* --red1
* --red2
* --red3
* --red4
* --orange1
* --orange2
* --purple1
* --purple2
* --black1
## Backgrounds
    background: var(--bgBlack);
* --bgBlack
* --bgWhite
* --bgWhite2
* --bgBlue
