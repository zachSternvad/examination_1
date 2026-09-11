# examination_1
Om projektet:
En fiktiv sida om en spel mässa som är skapt med HTML och CSS. Gjord på egen hand då gruppen vart som den vart. 

Highlights bilderna tagna från pixabay.com, Färger tagna från colorhunt.co.

Sidan innehåller:
- Navigation
- Hero sektion med datum, plats och namn/titel
- Sjuuuukt cool logga
- Schema/tidstabell
- Highlights
- Kontakt info och sponsorer (fiktiva såklart)
- Responsiv design för mobil


Teori:

1. Vad innebär semantisk HTML och varför har ni använt det på er eventsida?
    Semantisk HTML är att man strukturerar grejerna så att koden blir mer läsbar istället för att bara köra 700 paragraf taggar på hela sidan så man förstår mer varje tags syfte i koden.

2. Hur fungerar arv i CSS? Ge ett exempel från er egen kod.
    Att vissa egenskaper förs vidare genom "arv" till andra grejor tex 
    body {
        color: white; 
    }
    Gör så att all text på sidan "ärver" text färgen vit om inte annat specifeceras

3. Vad är den största skillnaden mellan Flexbox och CSS Grid, och när ska man använda vilket verktyg? Motivera utifrån hur ni fördelade dem på er sida.
    Den största skillnaden är att Flexbox främst används för att placera saker i en riktning, till exempel på en rad eller i en kolumn. CSS Grid kan hantera både rader och kolumner samtidigt. På sidan använder jag Flexbox till highlights eftersom korten ska placeras bredvid varandra och kunna flytta ner när skärmen blir mindre. Jag använder CSS Grid till schemat eftersom schemat har både rader och kolumner med tider och olika hallar.