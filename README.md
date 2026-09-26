# NT 2026 eller NT 1981?

Ett litet webbspel: två svenska översättningar av samma bibelvers visas bredvid varandra, och du ska klicka på den som är nya **NT 2026**. Efter varje svar får du veta vad som är nytt i versen.

**Spela:** https://rikardroitto.github.io/nt2026-eller-nt1981/

- *10 verser* drar tio slumpvisa verser bland de 60 mest kända i urvalet, *100 verser* ger hela urvalet i slumpvis ordning.
- Den äldre texten är Nya testamentet i Bibel 2000, som bygger på NT 81.
- Resultatet delas med en länk av typen `r/9-av-10.html`. Den sidan har en egen förhandsbild för Facebook och andra tjänster och skickar sedan besökaren vidare till `?r=9-10`, där startsidan visar vännens resultat.

## Teknik

Helt statisk sida utan backend: `index.html` innehåller all data, all stil och allt skript. Mappen `r/` innehåller en liten omdirigeringssida per möjligt resultat, och `og/` innehåller delningsbilderna.

## Upphovsrätt

Bibeltexter: NT 2026 © Svenska Bibelsällskapet 2026. Bibel 2000 © Svenska Bibelsällskapet. Texterna citeras för att visa skillnaderna mellan översättningarna.
