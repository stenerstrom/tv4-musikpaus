# Musikpaus

En sida som spelar musikvideor från YouTube medan en reklampaus pågår i en direktsändning i TV4 Play Community, en egen LG webOS-app. Appen visar sidan i en iframe och styr den med `postMessage`. YouTube kräver att spelaren bäddas in från en riktig webbadress, därför ligger sidan här.

Parametrar: `?v=id1,id2` för egna videor, `?list=PL…` för en YouTube-spellista, `?mute=1` för att starta utan ljud.
