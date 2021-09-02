## EN
## Working with the log file
Exercises from the subject Web Mining on the topic *Working with a log file*.
Assignments are in Slovak, notes on solutions in English.

## Warning

The repository does not include the log file that was provided to us during the semester. You need to use your own log file. The program can only process a file in the format *Combined log file* `% h% l% u% t \"% r \ "%> s% b \"% {Referer} i \ "\"% {User-agent} i \ "`.
Otherwise, the parser will not work.

## Tasks

Task 1:
> Create a program to clean data from unnecessary data:
- modify the data file by identifying variables (IP, Cookie, user, DTime, RequestMethod, URL, StatusCode, Referrer, Agent),
- clear the data (RequestMethod / Version, StatusCode, URL).

Task 2:
> Examine the log file after cleaning up unnecessary data and consider deleting other records (repeating pages that are not needed = for analysis, eg navbar)

Task 3:
> Cleaning data from search engine robots:
- identify robots based on access to the robots.txt file (URL) - get robots IP addresses.

Task 4:
> Cleaning data from search engine robots:
- identify robots based on the User-Agent (Agent) field - keywords bot, crawl, spider.
- delete search engine robots based on IP and keyword accesses in the User-Agent.

> In my case it was the use of the repository * COUNTER-Robots *

Task 5:
> Create a UNIXTIME variable that you create from the access date and time.

Task 6:
> First arrange the entries by IP, User-Agent and Unixtime.
> Identify users based on the IP address and the User-Agent field. Create a new variable with a user ID.

Task 7:
> Create the variable Length based on User_ID and 60 min. SequenceID.

Task 8:
> Identify sessions based on the RLength heuristic (40% navigation page share).

Task 9:
> Find out if the variable Length has an exponential distribution.

Task 10:
> Identify sessions based on the average time window estimate (STT_MEAN).

Task 11:
> Identify sessions based on the quartile time window estimate (STT_Q). (= hornyQ + 1.5 * Qpatpatie)

Task 12:
> Identify sessions based on a 10-minute estimate of the session time (SLength).


Task 13:
> Fill in the paths to the cleaned log file in which users and sessions were identified using the STT_Mean method.

Task 14:
> Fill in the paths to the cleaned log file in which users and sessions were identified using the STT_Q method.

Task 15:
> Fill in the paths to the cleaned log file in which users and sessions were identified using the STT_Mean method.

## Contents

The repository contains:

- 15 exercises
- 14 solutions (Jupiter notebook)
- Assignment No. 9 was solved in the program statistica

## Kudos
Without the work of @jwodder and @atmire and other contributors to their work, my version of the solution would have been much more painful and stubborn.

Repositories of the mentioned projects:
- https://github.com/atmire/COUNTER-Robots
- https://github.com/jwodder/apachelogs

## SK
## Práca s logovacím súborom

Cvičenia z predmetu Web Mining na temu *Práca s logovacím súborom*.
Zadania sú v slovenčine, poznámky k riešeniam v angličtine.

## Upozornenie

V repozitári nie je priložený logovací súbor, ktorý nám bol poskytnutý počas semestra. Treba použiť vlastný logovací súbor. Program vie spracovať iba súbor vo formáte *Kombinovaného logovacieho súboru* `%h %l %u %t \"%r\" %>s %b \"%{Referer}i\" \"%{User-agent}i\"`.
V inom prípade parser nebude fungovať.

## Zadania

Zadanie 1:
>Vytvorte program na čistenie dát od nepotrebných dát:
- upravte dátový súbor identifikovaním premenných (IP, Cookie, user, DTime, RequestMethod, URL, StatusCode, Referrer, Agent),
- očistite dáta (RequestMethod/Version, StatusCode, URL).

Zadanie 2:
> Preskúmajte logovací súbor po očistení od nepotrebných dát a zvážte odstránenie ďalších záznamov (opakujúce sa stránky, ktoré nie sú potrebn= pre analýzu, napr. navbar)

Zadanie 3:
> Čistenie dát od robotov vyhľadávacích služieb:
- identifikujte robotov na základe prístupu k súboru robots.txt (URL) - získate IP adresy robotov.

Zadanie 4:
>Čistenie dát od robotov vyhľadávacích služieb:
- identifikujte robotov na základe poľa User-Agent (Agent) - kľúčové slová bot, crawl, spider.
- zmažte prístupy robotov vyhľadávacích služieb na základe prístupov z IP adries a kľúčových slov v User-Agent.

> V mojom prípade šlo o použitie repozitára *COUNTER-Robots*

Zadanie 5:
>Vytvorte premennú UNIXTIME, ktorú vytvoríte z dátumu a času prístupu.

Zadanie 6:
>Usporiadajte najprv záznamy podľa IP, User-Agent a Unixtime.
>Identifikujte používateľov na základe IP adresy a poľa User-Agent. Vytvorte novú premennú s ID používateľa.

Zadanie 7:
>Vytvorte premennú Length na základe User_ID a 60 min. SequenceID.

Zadanie 8:
>Identifikujte sedenia na základe heuristiky RLength (podiel navigačných stránok 40%).

Zadanie 9:
>Zistite, či má premenná Length exponenciálne rozdelenie.

Zadanie 10:
>Identifikujte sedenia na základe priemerného odhadu časového okna (STT_MEAN).

Zadanie 11:
>Identifikujte sedenia na základe kvartilového odhadu časového okna (STT_Q). (= hornyQ + 1.5*Qrozpatie)

Zadanie 12:
>Identifikujte sedenia na základe 10 minútového odhadu dĺžky času sedenia (SLength).


Zadanie 13:
>Doplňte cesty do očisteného logovacieho súboru, v ktorom boli identifikovaný používatelia a sedenia pomocou metódy STT_Mean.

Zadanie 14:
>Doplňte cesty do očisteného logovacieho súboru, v ktorom boli identifikovaný používatelia a sedenia pomocou metódy STT_Q.

Zadanie 15:
>Doplňte cesty do očisteného logovacieho súboru, v ktorom boli identifikovaný používatelia a sedenia pomocou metódy STT_Mean.

## Obsah

Repozitár obsahuje:

- 15 cvičení
- 14 riešení (Jupiter notebook)
- zadanie č.9 bolo riešené v programe statistica

## Kudos
Bez práce @jwodder a @atmire a ďalších prispievateľov k ich práci, by moja verzia riešení bola omnoho útrpnejšia a kostrbatejšia.

Repozitáre spomínaných projektov:
- https://github.com/atmire/COUNTER-Robots
- https://github.com/jwodder/apachelogs
