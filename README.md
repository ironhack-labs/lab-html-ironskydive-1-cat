![logo_ironhack_blau 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Exercici guiat - IronSkydive 💪 - elements de nivell de bloc i en línia

<br/>

## Introducció

Durant aquest mòdul, us familiaritzareu amb HTML i CSS. Ambdues tecnologies combinades us ofereixen totes les eines que necessiteu per crear un lloc web. HTML sense CSS és lleig, i CSS sense HTML és... bé, res!

És per això que treballareu aquest exercici en diverses ocasions durant aquest mòdul. El nostre objectiu final és crear un lloc web bàsic HTML i CSS, on practicaràs els diferents conceptes a mesura que els vagis aprenent.

<br/>

## IronSkydive | El lloc web de l'empresa

A Ironhack li encanta programar, però també ens agrada practicar esports extrems. En una nova línia de productes, hem creat una nova empresa anomenada _IronSkydive_ . Oferim una experiència completa de paracaigudisme.

Esperem que ens ajudeu a crear el nostre lloc web perquè estem inundats de començar l'empresa i d'assegurar-nos que tots els nostres documents s'ajustin a les normes. :see_no_evil:

Com hem esmentat anteriorment, treballareu en aquest exercici durant les properes lliçons, però al final, el vostre objectiu és:

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_1f30ebb21258466ca36702d7cdaa0cad.png)

<br/>

Treballareu en un llapis nou, així que aneu a [CodePen](https://codepen.io/) i creeu un llapis nou ara. Preparat per fer el salt?

<br/>

![](https://media.giphy.com/media/xT5LMrGIfLuDtRSAMg/giphy.gif)

<br/>

### Part 1 - Elements del bloc

En aquesta part de l'exercici, treballareu amb els elements del bloc que heu après. Heu vist com els elements del bloc semàntic ens ajuden a entendre millor la composició del nostre lloc web. Comencem per crear l'estructura HTML bàsica, que serà la següent:

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br/>

Més endavant, en l'exercici, distingirem els diferents apartats que tenim. Ara, afegim uns quants elements de bloc més dins de cada element.

### Nav

Dins de`<nav>`, creeu una etiqueta `<ul>` amb tres elements:

- Estructura de la jornada
- Equip
- Horari

Aquestes seran les nostres opcions de menú.

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ace26745798b17492d307e0d0c817ea4.png)

<br/>

### Capçalera

Heu de crear dues coses diferents aquí:

- primer, creeu una etiqueta `<h1>` amb el text "IronSkydive" i després
- sota aquesta etiqueta, creeu una etiqueta`<h2>`amb el text "Let the trip begin" i finalment
- sota aquestes etiquetes, creeu una etiqueta `<aside>` que contindrà una cita.

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3c0c7f97d3804c728475f52c89f0ec85.png)

<br/>

### Secció 1

Aquesta secció té un fons fosc que cobrirà tota l'amplada del lloc web. Més tard afegireu el color al fons, així que de moment, no cal que us preocupeu per això.

Contindrà tres etiquetes `<article>`per afegir la informació sota la capçalera.

Dins de cada `<article>`, afegeix una etiqueta`<h3>`per als diferents títols i un paràgraf per al text blanc. El resultat seria una cosa així:

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_f004e36a2b2bb0dfc02ac008e5d5c97e.png)

<br/>

### Secció 2

Aquesta secció és força semblant a l'anterior. En aquest cas, la secció contindrà un títol `<h3>`amb el text "Com estructurem el dia?", i després un `<div>` amb quatre etiquetes `<article> ` diferents.

Dins de cada etiqueta d' _article_ , de moment, tindrem una etiqueta `<h4>` amb el títol de l'article i una etiqueta `<p>` amb el contingut de l'article.

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c810d2f904e4c4e72ad8b9ed055e4b37.png)

<br/>

### Secció 3

Aquest cas és el mateix que la **Secció 1** : tindrà un fons fosc i, com en els apartats anteriors, cal afegir un títol `<h3>` i un `<p>` amb una breu descripció.

Aleshores, creareu l'etiqueta `<div>` i afegireu tres etiquetes `<article>` buides que contindran la informació de cada membre de l'equip. N'hi ha prou amb tenir un text que indiqui els diferents articles:

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4bf21e881db9707b671a812c022db35f.png)

<br/>

### Secció 4

En aquesta secció, tenim una taula que conté la programació.

Comencem afegint dos encapçalaments `<h3>` diferents amb el text:

- Horari
- Programeu una franja horària

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cdeeac1a34e5b4f5785ec6f203632b7c.png)

<br/>

Ara afegiu una taula sota la primera etiqueta `<h3>`, que conté el text "Programació". De fet, aquesta taula contindrà l'horari d'IronSkydive per a la setmana. El format de la taula és el següent:

| Temps         | dilluns | dimarts | dimecres | dijous | divendres | dissabte |
| ------------- | ------- | ------- | -------- | ------ | --------- | -------- |
| 9:00 - 11:00  |         |         | X        |        | X         | X        |
| 12:00 - 14:00 |         |         |          |        | X         | X        |
| 15:00 - 17:00 |         |         | X        | X      | X         | X        |

Creeu la taula i afegiu el contingut necessari per obtenir aquest resultat:

<br/>

![](/Users/sarah/Development/IronHack/vue-bootcamp/lessons/images/lab-ironskydive-1/upload_5c089d05a9df991db3784ba81a880835.png)

<br/>

Recordeu que, a més de l'etiqueta `<table>`, hauríeu d'utilitzar `<thead>` amb sis etiquetes `<th>` per a les files de capçalera (sis dies que opera IronSkydive), i després dins del cos de la taula (`<tbody>`) hauríeu de definir files amb etiquetes `<tr>`. Al final, hauríeu d'utilitzar etiquetes `<td>` per al contingut dins de les files.

### Peu de pàgina

Finalment, però no menys important, la secció de peu de pàgina ha de contenir només una etiqueta`<footer>`. Dins de la`<footer>`, heu d'afegir diverses coses (descrites en l'ordre correcte):

- `<h5>` amb el títol "Informació de contacte".
- Element `<address>`, amb la informació correcta: IronSkydive 33 Rue la Fayette, 75009 París, França +33 (0) 619 193 088
- `<h5>` amb el títol "Segueix-nos".
- `<ul>` llista amb tres elements:
  - Twitter.
  - Facebook.
  - Instagram.


<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_661b4572e673afb0ce5a419ae78b9ce8.png)

<br/>

### Part 2 - Elements en línia

A la segona iteració del nostre exercici, treballareu amb els elements en línia que heu après. Heu vist que fem servir diferents etiquetes amb diferents objectius. Recordeu que aquesta és l'estructura del nostre projecte actual:

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br/>

Afegireu diferents elements en línia a totes les seccions que ja tenim.

### Nav

L'etiqueta `<nav> s'utilitza per embolicar enllaços al nostre lloc web. Ara mateix, només tenim una llista d'elements. Canviem això afegint enllaços a cada element de la llista.

Heu de crear tres enllaços diferents, que apuntaran a `#structure`, `#team` i `#schedule`, respectivament:

:bulb: Spoiler: els enllaços són etiquetes d'ancoratge i es representen amb l'etiqueta `<a>` i han de tenir l'atribut href. :wink:

```html
<a href="#structure">Day Structure</a>
```

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_53837d5c2b9d5e3c537a87079080151e.png)

<br/>

### Capçalera

La capçalera del projecte està incompleta. Primer, heu d'afegir un logotip a la capçalera. A més, afegiu una cita d'estil testimonial on actualment teniu text de farciment.

Primer, el logotip. Afegiu una imatge dins del `<h1>` que carregui la imatge següent:

https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironhack-skydive-logo.png.

Recordeu afegir un text alternatiu descriptiu, per si la imatge no es carrega. Una bona opció seria "IronSkydive Logo".

És habitual trobar cometes en cursiva en diferents llocs, així que això és el que farem. Afegiu la cita en cursiva (utilitzant elements en línia) dins de l'element `<aside>`, amb el text "La millor experiència de les nostres vides". En una línia nova, aquesta vegada utilitzant un element de nivell de bloc (`<p>`), afegiu els noms dels autors. Els noms seran "Ariel Quiónes & Gonzalo Manrique, Ironhack Founders".

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_0f0563ef2d64bd9a7bdf5d401bca9c16.png)

<br/>

### Secció 1

A la primera secció, tenim tres articles diferents. Cadascun té una `<h3>` i una `<p>`dins. Afegim un enllaç sota cada paràgraf. Aquest enllaç no ha d'apuntar enlloc.

<br/>

:::info

Podem crear un enllaç sense cap URL específic proporcionant un hash a l'atribut `href` :<br/>

```html
<a href="#">Link text</a>
```

:::

<br/>

Afegiu tres enllaços, un a cada secció, en aquest ordre:

- Aprèn més
- Mira el vídeo
- Registra't

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_016b92205b14c5a93d86d324547cf86e.png)

<br/>

### Secció 2

En aquesta secció, tenim quatre articles diferents que contenen informació sobre com s'estructura un dia típic a IronSkydive. Afegim algunes icones descriptives a cada secció.

Les diferents icones, en l'ordre correcte, són:

- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-training.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-get-ready.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-fly.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-jump.png`

Recordeu afegir un text descriptiu alternatiu a l'atribut `alt` . Cadascun dels apartats tindrà aquest format amb diferents imatges:

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3aa54eab8bec42f35381b704d5c7b06e.png)

<br/>

### Secció 3

Afegim la informació de l'equip a la secció. Hauríeu de tenir tres articles diferents sense cap informació. Dins de cada article, afegireu el nom del membre de l'equip al text en **negreta** (però això és una cosa que us preocuparà quan arribem a l'estil). Podeu utilitzar l'etiqueta de nivell _de bloc_ ,`<h4>`per embolicar cada nom. Sota el nom, hauràs d'afegir la foto del membre de l'equip. Podeu trobar les imatges aquí:

- **Harold Rothstein** , `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c18b1c463b80090894237a262dfdfbad.jpg`
- **Susan Phillips** , `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_a18d6123a7c8e75f7e70a4e59b941093.jpg`
- **Taylor Roberts** , `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7104a331530d1b0611da55093b7dc421.jpg`

No oblideu afegir text alternatiu en cas que la imatge no es carregui. Aquestes imatges són bastant grans, però ho gestionarem més endavant mitjançant CSS.

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_845dbf46e21d7bb275bdb5b23ff17aa6.gif)

<br/>

Per acabar aquesta secció, afegim un`<hr>`entre el paràgraf i la informació dels membres de l'equip.

### Secció 4

_Res a afegir_ !

### Peu de pàgina

Primer, formem l'adreça. Ara mateix, tota la informació està en una línia. Utilitzem les etiquetes `<br>`per separar les diferents seccions de l'adreça.

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cf1a7806a1a921e018aa46c428d67a17.png)

<br/>

Finalment, afegir enllaços a totes les xarxes socials on els usuaris poden seguir IronSkydive. Podeu crear enllaços buits (amb el hash a l'atribut `href` ) o afegir enllaços a les xarxes socials. En ambdós casos, s'ha d'obrir una nova pestanya quan els usuaris facin clic als enllaços.

<br/>

:::info

:bulb: Utilitzeu l'atribut [`target`](https://html.com/attributes/a-target/) de l'àncora per obrir un enllaç en una pestanya nova. (la paraula _objectiu_ es pot fer clic, així que no dubteu a explorar una mica; recordeu, no heu de memoritzar res, sabeu on trobar les respostes que necessiteu.)

:::

<br/>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_27057afe7732d2b6f26ce69eb00a63ec.png)

<br/><br/>

:heart: **Feliç codificació!**