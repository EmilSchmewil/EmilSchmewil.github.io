<html lang="de">
    <head>
        <title>Homepage</title>
    </head>
<body>
    <h1 id="Überschrift">Wilkommen auf meiner Homepage</h1>
    <button id="Button1">Projekte</button>
    <button onclick="location.href='3DModelle.html'">3D Modelle</button>

</body>
<script>
    document.getElementById("Button1").addEventListener("click", function() {
        document.write(
            '<h2>Meine Projekte</h2>' +
            '<ul>' +
            '<li><a href="Arduino.html">Projekt 1: Arduino Bauprojekte</a></li>' +
            '<li><a href="Web.html">Projekt 2: Wesitedevelopment</a></li>' +
            '<li><a href="Mod.html">Projekt 2: Minecraft Mod</a></li>' +
            '<li><a href="Gamez.html">Projekt 3: Spieleentwicklung</a></li>' +
            '</ul>'
        );
    });
</script>
