# Frontend voor designers - Eindoplevering

## De opdracht
Voor de eindopdracht van het vak Frontend voor Designers was het de bedoeling om een functionaliteit te ontwerpen waarbij zo goed als alle data van een extrene bron met Javascript wordt ingeladen.

## Opdrachtscriteria
De opdracht had enkele criteria's. 

1. De uitwerking van je ontwerp moet het doen in een browser en device naar keuze.
2. De data wordt van een externe bron ingeladen met Javascript
3. In de demo maak je gebruik van meerdere verschillende UI events zodat gebruikers je ontwerp op verschillende manieren kunnen bedienen.
4. Verschillende states van de UI stack worden opgevangen en zijn vormgegeven.
5. In de demo dien je rekening te houden met de interface design principles 04, 09 en 11 van Principles of User Interface Design.
6. Je ontwerp is aantoonbaar getest en verbeterd. Verslaglegging en resultaat publiceren op Github

## Aanpak van de opdracht

Voor dat ik begon met het coderen heb ik eerst lang nagedacht over wat voor functionaliteit ik wilde ontwerpen. Uiteindelijk besloot ik om iets met pokomons te doen. In eerste instantie had ik het idee dat je als gebruiker de optie kreeg om een pokemon te selecteren en dat je daarvan dan de evoluties kon bekijken. De evoluties zouden zowel textueel als visueel (met een gifje bijvoorbeeld) zichtbaar zijn. Dit idee liep in de soep en uiteindelijk ben ik gegaan voor de functionaliteit om meer details te bekijken van een pokemon. Als de gebruiker op een naam van de pokemon op de homepage klikt krijgt hij/zij verder details over de pokemon te zien. De verder details bestaan uit een afbeelding, naam, beschrijving en evoluties van de pokemon. Ook leuk om te vermelden is dat de JSON waarvan ik gebruik maak zelf heb gemaakt. 

## Versie 1

In de eerste versie heb ik op de homepage een grote header geplaats met daarin het doel van de functionaliteit. Dit heb ik gedaan zodat de gebruiker weet wat hij/zij kan doen in dit ontwerp. OP de homepage ziet de gebruiker drie namen van pokemons. De gebruiker kan er een kiezen. Als de gebruiker bijvoorbeeld op bulbasaur klikt dan krijgt hij/zij eerst een loading state te zien en vervolgens meer deatails over de bulbasaur. Dit geldt hetzelfde voor de andere 2 opties. Om terug te navigeren van de pagina met de details kan de gebruikern op escape op het toetesenbord drukken. 

[Versie 1 - voor testen](https://rodicornelisse.github.io/pokemonV1/)

## Versie 2 - Na Testen

Ik heb het ontwerp van mijn functionaliteit met mijn oma en moeder getest. De test resultaten zijn als volgt.
1. De buttons op de homepage waren erg klein volgens de testers. Me oma had ook moeite om met de muis op de button te klikken.
2. De testers wisten niet welke button er geselecteerd zou worden als er op een knop werd gedrukt. Mijn oma dacht bijvoorbeeld dat ze op charmender ging drukken. Op het moment dat ze op de muis klikte stond haar cursor helemaal niet op de button. Hieruit bleek dus dat alleen de cursor feedback niet genoeg was.
3. Om terug te navigeren via het toetsenbord lukte beide testers in eerste instantie niet. Zowel me oma als moeder drukte op backspace i.p.v. de escape toets.
4. De pagina met details werd door de testers als een lang stuk tekst waargenomen. 
5. Loading state duurt erg lang. Testers kijken om zich heen.

  ### Aanpassingen na testen
Na het testen heb ik ten eerste de buttons om een pokemon te selecteren groter gemaakt. Verder heb ik een hover aan de buttons toegevoegd, zodat de gebruiker weet welke knop geselecteerd is op het moment dat hij/zij wilt gaan klikken. Verder heb ik het terug navigeren gewijzigd naar de backspace toets i.p.v de escape toets. Uit de testen kwam dat de backspace namelijk logischer is voor het terug navigeren. Verder heb ik op de detail pagina de evoluties een highlight gegeven. Dit heb ik gedaan zodat er niet een lang stuk tekst op de detailpagina staat. Hierdoor oogt het voor de gebruiker makkelijker leesbaar. Ten slotte heb ik de duur van de loading state aangepast. Eerst duurde de loading state 5 seconden en nu 3 seconden.

[Versie 2 - na testen](https://rodicornelisse.github.io/pokemonV2/)

