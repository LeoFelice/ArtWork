# Menger Sponge
## Video Download
[Menger Sponge Animation](https://github.com/LeoFelice/ArtWork/raw/main/MengerSponge/Video/SpongeFin.mp4)

## Tools
- blender

## Motiv
Beim  **Menger Sponge** handelt es sich um eine Fraktal Struktur [Wiki: Menger Schwamm](https://de.wikipedia.org/wiki/Menger-Schwamm). 
Hierbei handelt es sich um eine diskrete Darstellung, da sich der Menger Sponge aus einer begrenzten Anzahl Würfeln zusammen setzt.

## Technic
**Geometry Nodes** 
ist eine Node (Knoten) bassierte blender spezifische Programmiersprache die es ermöglicht Geometrien zu manipulieren. Dabei können komplexe Programme erstellt ähnlich wie die Nodebasierten Materialien.

## Verschieden Basis Würfel  
Der Menger Sponge wird itterativ mit Geometry Nodes aus einem Basis Würfel erzeugt. Für die Lichtquellen wurde ein Set aus drei verschiedenen Leuchtelementen verwendet das ebefalls iterativ in die den zwischen Räumen des Menger Sponge erzeugt werden. 

Folgende Bilder zeigen drei Beispiele für verschiedene Materialien und Beleuchtung. 

**Milchglas**
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/Render03.png?raw=true)
**Glas**
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/Render01.png?raw=true)
**Metal**
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/Render02.png?raw=true)

## Verschiedene Transformationen
In diesem Schritt sieht man verschiedene Techniken mit dennen man die Transformation der erzugten Würfel manipulieren kann. 
Das Ziel war es den Menger Sponge möglichst ästhetisch explodieren zu lassen. Der Schwamm sollte an verschiedenen Stellen aufbrechen ohne dabei zuviel Struktur zu verlieren. 

![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/Render04.png?raw=true)
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/Render05.png?raw=true)
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/Render06.png?raw=true)

## Itterative Animation
FÜr Animation werden die Transformation einzelnen Würfel abhängig vom aktuellen Frame berechnet. Dabei wird aus jeder Iterationsstufe des Würfels eine zufällige Anzahl an würfeln ausgewählt die Transformiert werden. Durch weitere Zufällig generierten Parameter wie die Geschwindigkeit oder Rotation wird die Animation dynamischer. Die Lichtquellen Bewegen sich ebefalls mit den Würfeln mit. 

**
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/renderCubeAnim.png?raw=true)
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/renderCubeAnimBigLight.png?raw=true)
![Menger Sponge](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Images/renderCubeAnimwith%20light.png?raw=true)

## Test Video Download
[Animation 1 It](https://github.com/LeoFelice/ArtWork/blob/main/MengerSponge/Video/SpongeFin.mp4)
