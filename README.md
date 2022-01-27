# FE_versionhantering_Examination
```

```
 _Innehållförteckning av README file._
 ```
 
```
 1.  Vad är versionhantering, Git och Github? Kort text som sammanfattar kurs material. 
 2.  Terminologi som använder markup språk för att arbeta med text
 3.  Lista med komando som användes för att skapa dokument igenom GIT från ett tomt fil.
 
```
VERSION HANTERING; GIT OCH GITHUB
```
- Versionhantering syftar på metod av arbete med filer; största fördelen är förmåga att sortera; förvara och "börja om" med filer inom olika branches; som kan sammanflätas tillbaka till huvud projekt.
- En annan fördel är att man kan sammarbeta i grupp i en och samma projekt; samtidigt och ha tillgång till hela projektet. Att kunna arbeta tillsammans har inte alltid varit en självklarhet. 
- 
-  Lokal versionhanteringsystem (LCS ) är en användare som arbetar i ett projekt; inom ett databas. Bara en person har tillgång till information. Det är väldigt svårt att bygga större projekt helt ensam och information kan raderas vid misstag.Tidigaste form av versionhantering. Exempel: RCS system som arbetade med hårdisk.
-   
-  Centrala versionshanteringssystem (CVCS) innebär att repository med projekt har flyttats till ett separat server. Vilket innebär att flera användare kan samarbeta på samma projekt men bara en i taget och projektet är känslig för tekniska fel inom server verksamhet.Fördelen med central organisation är att alla inblandade i projekt; kan se alla ändringar som genomförs.
-  
- Distribuerade versionshanteringssystem (DVCS) system är den vanligaste sätt att arbeta med kod i programering och till stor del existerar på grund av den tekniska utvecklingen; och hur enskilda datorer kan arbeta med betydligt mer information än tidigare. Metoden går ut på att huvud-branch av projekt ligger på en server i form av en repository. Enskild användare som är inte begränsade i antal kan göra en "reach" genom t.ex Git till server och plocka ut en kopia som en bibliotek bok på den mest aktuella versionen av projekt som finns i repository. Repository i sig själv är som en projekt pärm som absorberar ändringar från flera användare som lämnar kommentärer och bygger olika område med enskilda kopior. 
- Om fem personer arbetar fram en hemsida; då kan det vara att en arbetar på mobil optimering; en annan sköter CSS, någon strukturerar JavaScript och övriga två; kan hoppa in och göra små ändringar inom alla område genom att till exempel lägga till bilder eller video; utan att behöva avbryta arbete som pågår i hela filen. Man arbetar i olika brancher; som är från början tvilling kopior av varandra; men ändringar kan sammanflatas till ett nytt updaterat version av projektet.
Att ha flera versioner av projekt innebär att man kan ha översikt över hela projektet innan ändringar genomförs.Grupp av programerare kan godkänna varandras arbete och gå fram och tillbaka till senast fungerande versioner; vilket är omöjligt att göra med en publicerad central version. Fler kopior av projektet hos flera användare innebär även trygghet, då det är osannolikt att hela projektet raderas av misstag.
-
**Upplägget av destrubuerad versionhanteringsystem**
1. Origin Repository, är huvud projekt som kontaktas med pull,push och merge.Origin befinner sig på en server.
2. User repository; är kopia av huvudprojekt som befinner sig hos den aktuella programerare.
3. I processen av arbete; user repository är en working-copy som updateras med commit, update och kommentärer för ändringar.  
 
```
TERMINOLOGI INOM VERSION HANTERING  
```

# Terminologi
- för 
- ***Git och Github***. :+1:

- [ ] **Repository** = Fil inom vilket man kan förvara information.
- [ ] **Upstream/Downstream** = Om man visualiserar programering som en flod med information; i konstant
rörelse; när delar av kod fungerar enligt samma princip; skrivna med samma språk eller liknar varandra i
funktion då rör sig kod inom samma riktning; då kan man hämta fungerande kod från förvaring med
pull/push i Upstream. Downstream; är buggar och problematisk kod.
- [ ] **Branch**; main/master = Github fungerar ut ifrån gren förvaring av information. Main och Master är
vanliga benämningar för huvud grenar av information. Genom att arbeta med grenar man kan göra
ändringar i test-version utan att riskera att förlora kod som fungerar i fundamental gren av ett projekt.
- [ ] **Clone** = När man kopierar en repository; t.ex från en gren till en annan. Dessa grenar kan kommunisera
med varandra med olika komando. Clone; kan även vara benämd som remote; en kopia som kan ändras
och kommunisera med branch och med andra kloner och kopior.
- [ ] **Fork** = Kommando; skapar en kopia av repository.
- [ ] **Commit** = Kommando, som sänder information till repository.
- [ ] **Add** = Vanlig kommando som lägger till en liten ändring.
- [ ] **Push** = Kommando, uppdaterar branch innehåll.
- [ ] **Pull** = Kommando; hämtar innehåll från branch.Används ofta för överblick och dev arbete för att göra
ändringar. Man gör en pull; kommenterar och förändrar innan man skickar tillbaka repo till merge.
- [ ] **Merge** = Kommando, sammanflätar innehåll från flera källor i ett fil.
- [ ] **Stash** = Kommando, som pausar ändringar och lägger undan arbete; man i princip rensar arbetsyta för
att arbeta på ett annat projekt. Man kan göra endast ett stash i taget; för att inte hamstra oavklarade
projekt mitt i Git arbetsprocess. Git stash pop/ Git stash drop.
- [ ] **Fetch** = Kommando; där man laddar ner en kopia till en enhet.Flera brancher kan överhöras
samtidigt.Används inom säkerhets förvaring av hela projekt.
- [ ] **HEAD/Heading**; tags; Index = Organisation verktyg för att kommentera kod. Referens till huvudområde
av dina senaste ändringar. Tillsammans ger möjlighet att kommentera projekt och kod inom Git översikt
samt används av Github för att beskriva innehåll i kod sekvenser på ett visuellt sätt.
- [ ] **Origin** = Första version av repository; git push origin master refererar till att hämta original kod från
master branch med hjälp av git och push-kommando som sträcker sig in i kod.
- [ ] **Revert** - Kommando som används för att ångra senaste ändring i repository.Genomförs vid fel. Säker
metod.
- [ ] **Reset** - Kommando som hoppar tillbaka till senaste sparade kopia av repository.
- [ ] **Working directory** = Alla filer i din pågående projekt; alla filer och pärmar potentiella bilder och ikoner.
- [ ] **Staging** = ex: Kommando git add används på en staged fil: index.html. Ändringar flyttas till rätt
organiserad fil i projekt.
- [ ] **(Local) repository / (Remote) repository** = Lokal repo är repo man arbetar med på ett lokalt maskin;
t.ex dator. Remote repo är repo som kommer från en förvaring server.
- [ ] **Tags** = Markering inne i Github som hjälper att organisera innehåll i kod i olika partier; särskild viktigt om man jobbar tillsammans och kan sätta en tag på moment som behöver ses över av en kollega eller vidarebifogas till en annan avdelning. 

```
GIT OCH GIT KOMMANDO
```

Git är decentraliserad version control system; som underlättar kommunikation och sammarbete mellan flera individer.Git är populär på grund av korta komando som gör det enkelt att kontrolera status av projekt och fil som man arbetar med. Dessa komando kan kombineras för att genomföra arbete med fil. Fildokument i denna uppgift är skapat helt i Git och skickades till server GitHub med hjälp av Git kommando. 

1. git --version ger information om vilken version av git som finns installerat på dator.
2. git config --global user.name "evgeniatrudova" informerar namn på filägare  
git config --global user.email "evgeniatrudova@gmail.com" informerar kontakt email på ägare
3. git init index.html skapar en osynlig repository .git som antecknar alla ändringar i fil index.html.
4. git status är vanligaste kommando till .git fil; för att ändringar man gör i stunden behöver läggas till versionen man arbetar med; för att existera på ett git- förteckning.
5. git add index.html  och git add . (all) lägger till en eller flera ändringar i fil
6. git clone google.com kopierar ett url av projekt, till personlig server, t.ex man kan kopiera en repo till personlig Github.
7. git branch namnpåbranch skapar ett branch av huvud projekt
8. git push och git pull används för att dra ut(pull) och trycka in(push) ändringar i working-repo till original repo. 
9. git checkout kontrollerar vilken branch man befinner sig på
10. git commit -m lägger till en meddelande;byter namn på filändring från filnamn till vilken konkret ändring har genomförts; vilket gör det lättare att gå tillbaka; då varje sådan "staged" ändring har en kod som man kan använda för att återvända tillbaka.
11. git log  loggar ändringar 
12. git merge sammankopplar flera brancher 

Mer git koder finns här:   https://www.git-tower.com/blog/git-cheat-sheet
