# BoilerRoom-v39-Gothenburgo
Boiler room v39
<!-- Planering och genomförande -->
__Planering__
- Vi la upp grundläggande komponenter / uppgifter i Trello och delade ut ansvaret till gruppmedlemmar
    - Upplagt enligt Scrum, som vi valt att kalla “Scrum light”
- Hemsidans övergripande layout och tema diskuterades i en större grupp och ett gemensamt beslut togs
- Ansvaret för att implementera layout och förse teamet med grundläggande info om temat lades på en gruppmedlem
- Ansvaret delades upp för de olika sidorna (4st) samt header + nav och footer


__Genomförande & Möten__
1. Uppstartsmöte med en del av teamet
2. Eget arbete
3. Check-in/Stand-up med resten av teamet
4. Eget arbete
5. Stand-up med hela teamet
6. Eget arbete
7. Avsluta-dagen-möte
8. Eget arbete över helg/måndag
9. Check-in med team (Måndag)
10. Retrospective


__Uppdelning av css__
- styles.css för index
- en css för varje undersida

__Problem__
- En commit råkade ta bort 210 inserts med bl.a. media queries
Lösning: 
- Vi letade i GitHub:s historik och såg till att det synkade över ett möte

<!-- Mötesanteckningar -->
__stand up 1__
Vi mergade alla cloner. Då kunde vi se hur långt vi har kommit och planera framåt. 
Home: Behöver fixa CSS
product: Ska lägga till media queries och anpassa texten till bilden. Tar bort aside på min sida.
about: alignment-ändringar
Header/footer: små ändringar på header. 
Vi sätter mål att bli klara innan kl17. Stand up 2  kl:16.55

__Stand up 2__
Alla hann inte med sina delar av sidorna. Vi får fortsätta jobba vidare på det och commita ändringarna så snabbt som möjligt. Vi delar upp det sista arbetet som behöver göras tills på måndag och planerar nästa träff på måndag.


<!-- Flödesschema -->
Flödesschema i text:
1.Visa "skapa konto-sida" – Användaren presenteras med en textbox för att skriva in en e-postadress.
    Om användarnamnet är upptaget visas ett felmeddelande som säger det.
    Om användarnamnet inte är upptaget går du vidare till nästa sida.

2.Ny sida, "välj lösenord" – Användaren skriven in ett lösenord.    
    om lösenordet inte uppfyller kravet kommer ett felmeddelande upp
    om lösenordet godkänns så går man vidare till nästa sida.

3.Ny sida, välj födelsedatum
    Om indata fattas kommer ett felmeddelande, info saknas.
    Om all info fylls i går du vidare till nästa steg.

4. Ny sida, bot-test - du kommer till en sida som säkerställer att det inte är en bot. Först har du en knapp som du kan trycka på för att gå vidare till bot-testet. När du klickat på den så kommer testet upp som består av 5 test. Testet är en bild till vänster med ett nummer och en ikon som du ska härma, till höger har du en liknande bild men med flera nummer och ikoner som du kan byta plats på. För att klara testet behöver bilden till höger matcha bilden till vänster.
    om du inte klarar testet kommer ett felmeddelande som säger att du inte klarat testet.
    om du klarat testet kommer det upp en text som säger att du klarat testet och du går vidare.
5. Du har nu skapat kontot och kommer tillbaks till startsidan inloggad på kontot.



<!-- Flödesschema -->
flödesschema:
[Se flödesschema](flödesschema.html)