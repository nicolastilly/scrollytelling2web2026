# Explications

Le projet s'appuie sur CSS Grid pour la mise en page. Les interactions de scroll sont faites avec la librairie AOS.

Ajoutez le code ci-dessous avant `</head>` :

```
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
```

Ajoutez le code ci-dessous avant `</body>` :

```
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

    <script>
        AOS.init();
    </script>
```

Ensuite, rendez-vous dans la page d'AOS et utlisez un `data-aos` pour utiliser une animation au scroll. Exemple :

```
 <div class="div1s03" data-aos="fade-left" data-aos-delay="300" data-aos-duration="900">
    <p>Nulla facilisi. Donec eu tempus lorem. Maecenas faucibus mollis vehicula.</p>
</div>
```