# Min webbplats

## Beskrivning

Det här projektet är en personlig webbplats som skapades som en del av kursen. Webbplatsen innehåller information om mig, mina intressen och hobbyer samt min kärlek till hundar. Det finns även sidor för kontakt och hobbyer.

## Tekniker

- HTML5
- CSS3
- Git
- GitHub

## Publicerade versioner

- GitHub Pages: LÄNK KOMMER HÄR
- Netlify: LÄNK KOMMER HÄR

## Git-frågor

### Vad är skillnaden mellan `git add` och `git commit`?

`git add` används för att lägga till ändrade filer i Git:s staging area. `git commit` sparar ändringarna i staging area som en ny version i Git-historiken med ett meddelande.

### Varför använder man branches istället för att jobba direkt i `main`?

Branches gör det möjligt att utveckla och testa förändringar utan att påverka huvudversionen. Man kan använda `dev` för nya funktioner och sedan mergea ändringarna till `main` när de är färdiga.

### Vad händer rent praktiskt när man gör en merge?

Ändringarna från en branch kombineras med den branch man står på. I detta projekt fördes ändringarna från `dev` in i `main`.

### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på exempelvis Netlify?

Att pusha till GitHub skickar projektets filer och versionshistorik till GitHub-repot. Att publicera på Netlify gör webbplatsen tillgänglig på internet.

### Hur exkluderar man en fil från versionshanteringen?

Man lägger filnamnet i en `.gitignore`-fil. Till exempel:

```text
hemlig-fil.txt
.env
node_modules/
