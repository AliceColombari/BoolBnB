<br>
<div align="center" href="https://imgur.com/xo4arsL">
	<img width="400"  src="https://i.imgur.com/xo4arsL.png"  title="source: imgur.com"/ >
</div>

<br>
<p align="center">BoolBnB è una web app che permette di trovare e gestire l’affitto di appartamenti. </p>

<a href="https://imgur.com/NBH2wn6"><img src="https://i.imgur.com/NBH2wn6.jpg" title="source: imgur.com" /></a>

## La struttura della Web App BoolBnB

All'interno della pagina principale puoi  **cercare appartamenti** in una città specifica, personalizza al meglio la ricerca in base alle tue esigenze attraverso i diversi **filtri** presenti come: la distanza dalla città selezionata, il numero di stanze e dei letti oppure i servizi di cui hai bisogno.

## SINCRONIZZARE CON ALTRI BRANCH
1. git remote add upstrem code_github_repo (da fare solo la prima volta)
2. git fetch upstream
3. git rebase upstream/master oppure git merge upstream/master
4. sincronizza modifiche con btn Sync Changes
5. lancia da terminale php artisan migrate

Se possiedi un appartamento che non utilizzi, inseriscilo all'interno del nostro database e tramite BoolBnB potrai affittarlo e gestirlo tramite l'**area amministrativa**, uno spazio per i tuoi appartamenti: per crearne dei nuovi, modificarli o se necessario eliminarli. 
Grazie al servizio di **messaggistica** interno di BoolBnB, puoi contattare il proprietario dell' appartamento che ti piace per chiedere informazioni aggiuntive o **visualizzare** i messaggi ricevuti.

<div href="https://imgur.com/yb6kscp"><img src="https://i.imgur.com/yb6kscp.jpg" title="source: imgur.com" /></div>

<br>

<div align="center" href="https://imgur.com/TMNeL4v"><img width="400" src="https://i.imgur.com/TMNeL4v.png" title="source: imgur.com" /></div>

##  BoolBnB su diversi dispositivi

Grazie all' **Homepage** completamente responsive, 
naviga tranquillamente sia su desktop che su mobile

L'interfaccia grafica è stata studiata in riferimento al **target** e agli **obiettivi** di BoolBnB, 
la **navigazione fluida** e **dinamica** della Web Application è responsive, l'utente naviga per un'esperienza uniforme sia su desktop che su mobile .

<a href="https://imgur.com/s9stxwl"><img src="https://i.imgur.com/s9stxwl.jpg" title="source: imgur.com" /></a>
  <br>
 <div align="center" href="https://imgur.com/NbtRPNN">
 <img width="400"  src="https://i.imgur.com/NbtRPNN.png" title="source: imgur.com" /></div>
  
  ## Installazione 
1. Clona la repository da GitHub 
2. Inizializza la repository installando i pacchetti e configurandola con le tue impostazioni:
    
    - `composer install` 
    - `npm install` 
	- `cp .env.example .env` 
	- `php artisan key:generate`
     
3. Collega il tuo database e lancia le [migrations](database/migrations) e i [seeder](database/seeds): 
	- `php artisan migrate`
	- `php artisan db:seed` 
4. Crea il collegamento alla cartella [storage](storage): 
	- `php artisan storage:link` 
5. Lancia il sito: 
	- `npm run watch` 
	- `php artisan serve`

<br><br>

<div align="center" href="https://imgur.com/aQQXQIB"><img width="400" src="https://i.imgur.com/aQQXQIB.png" title="source: imgur.com" /></div>
<div align="center"> <img src="https://img.shields.io/github/languages/count/MarcoSandri/BoolBnB"> </div>

### Alice

<img src="https://i.imgur.com/omfijaQ.png" width="200" ></img>
    - GitHub
    - LinkedIn

### Angela

<img src="https://i.imgur.com/OgcPAGJ.png" width="200"></img>
    - GitHub
    - LinkedIn

### Paolo

<img src="https://i.imgur.com/o4HNDGt.png" width="200"></img>
    - GitHub
    - LinkedIn

### Marco

<img src="https://i.imgur.com/hTdQUtM.png" width="200"></img>
    - GitHub
    - LinkedIn

### Demetrio

<img src="https://i.imgur.com/AXeg2Fq.png" width="200"></img>
    - GitHub
    - LinkedIn