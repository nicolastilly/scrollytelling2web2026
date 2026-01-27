# Explications ScrollyVideo

ScrollyVideo fonctionne avec des fichiers .mp4.

Dans le `body` vous devez ajouter ce code :

```
<div id="scrolly-video"></div>
```

Qui va contenir la vidéo

Et celui-ci avant la fermeture du `body`

```
<script src="https://cdn.jsdelivr.net/npm/scrolly-video@latest/dist/scrolly-video.js"></script>
  <script type="text/javascript">
    new ScrollyVideo({
      scrollyVideoContainer: "scrolly-video",
      src: "https://scrollyvideo.js.org/goldengate.mp4"
    });
  </script>
```