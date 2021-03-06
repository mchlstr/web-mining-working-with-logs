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
Without the work of [@jwodder](https://github.com/jwodder) and [@atmire](https://github.com/atmire) and other contributors to their work, my version of the solution would have been much more painful and stubborn.

Repositories of the mentioned projects:
- https://github.com/atmire/COUNTER-Robots
- https://github.com/jwodder/apachelogs

## SK
## Pr??ca s logovac??m s??borom

Cvi??enia z predmetu Web Mining na temu *Pr??ca s logovac??m s??borom*.
Zadania s?? v sloven??ine, pozn??mky k rie??eniam v angli??tine.

## Upozornenie

V repozit??ri nie je prilo??en?? logovac?? s??bor, ktor?? n??m bol poskytnut?? po??as semestra. Treba pou??i?? vlastn?? logovac?? s??bor. Program vie spracova?? iba s??bor vo form??te *Kombinovan??ho logovacieho s??boru* `%h %l %u %t \"%r\" %>s %b \"%{Referer}i\" \"%{User-agent}i\"`.
V inom pr??pade parser nebude fungova??.

## Zadania

Zadanie 1:
>Vytvorte program na ??istenie d??t od nepotrebn??ch d??t:
- upravte d??tov?? s??bor identifikovan??m premenn??ch (IP, Cookie, user, DTime, RequestMethod, URL, StatusCode, Referrer, Agent),
- o??istite d??ta (RequestMethod/Version, StatusCode, URL).

Zadanie 2:
> Presk??majte logovac?? s??bor po o??isten?? od nepotrebn??ch d??t a zv????te odstr??nenie ??al????ch z??znamov (opakuj??ce sa str??nky, ktor?? nie s?? potrebn= pre anal??zu, napr. navbar)

Zadanie 3:
> ??istenie d??t od robotov vyh??ad??vac??ch slu??ieb:
- identifikujte robotov na z??klade pr??stupu k s??boru robots.txt (URL) - z??skate IP adresy robotov.

Zadanie 4:
>??istenie d??t od robotov vyh??ad??vac??ch slu??ieb:
- identifikujte robotov na z??klade po??a User-Agent (Agent) - k??????ov?? slov?? bot, crawl, spider.
- zma??te pr??stupy robotov vyh??ad??vac??ch slu??ieb na z??klade pr??stupov z IP adries a k??????ov??ch slov v User-Agent.

> V mojom pr??pade ??lo o pou??itie repozit??ra *COUNTER-Robots*

Zadanie 5:
>Vytvorte premenn?? UNIXTIME, ktor?? vytvor??te z d??tumu a ??asu pr??stupu.

Zadanie 6:
>Usporiadajte najprv z??znamy pod??a IP, User-Agent a Unixtime.
>Identifikujte pou????vate??ov na z??klade IP adresy a po??a User-Agent. Vytvorte nov?? premenn?? s ID pou????vate??a.

Zadanie 7:
>Vytvorte premenn?? Length na z??klade User_ID a 60 min. SequenceID.

Zadanie 8:
>Identifikujte sedenia na z??klade heuristiky RLength (podiel naviga??n??ch str??nok 40%).

Zadanie 9:
>Zistite, ??i m?? premenn?? Length exponenci??lne rozdelenie.

Zadanie 10:
>Identifikujte sedenia na z??klade priemern??ho odhadu ??asov??ho okna (STT_MEAN).

Zadanie 11:
>Identifikujte sedenia na z??klade kvartilov??ho odhadu ??asov??ho okna (STT_Q). (= hornyQ + 1.5*Qrozpatie)

Zadanie 12:
>Identifikujte sedenia na z??klade 10 min??tov??ho odhadu d????ky ??asu sedenia (SLength).


Zadanie 13:
>Dopl??te cesty do o??isten??ho logovacieho s??boru, v ktorom boli identifikovan?? pou????vatelia a sedenia pomocou met??dy STT_Mean.

Zadanie 14:
>Dopl??te cesty do o??isten??ho logovacieho s??boru, v ktorom boli identifikovan?? pou????vatelia a sedenia pomocou met??dy STT_Q.

Zadanie 15:
>Dopl??te cesty do o??isten??ho logovacieho s??boru, v ktorom boli identifikovan?? pou????vatelia a sedenia pomocou met??dy STT_Mean.

## Obsah

Repozit??r obsahuje:

- 15 cvi??en??
- 14 rie??en?? (Jupiter notebook)
- zadanie ??.9 bolo rie??en?? v programe statistica

## Kudos
Bez pr??ce [@jwodder](https://github.com/jwodder) a [@atmire](https://github.com/atmire)  a ??al????ch prispievate??ov k ich pr??ci, by moja verzia rie??en?? bola omnoho ??trpnej??ia a kostrbatej??ia.

Repozit??re spom??nan??ch projektov:
- https://github.com/atmire/COUNTER-Robots
- https://github.com/jwodder/apachelogs
