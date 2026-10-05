Architekury a princip fungovania PHP : 

- Hypertext Preprocessor je open-source skriptovaci jazyk beziaci na strane servera (Server-Side)
- nespusti sa nam echo kym neni Mamp, ktory ponuka sluzby Apahce (webovy server), PHP (jazyk),     databazovy server (ukladanie dat)

Architektura Klient-Server : 
- kod sa vykona na serveri a klientovi (prehliadacu) sa odosle uz len vygenerovany a cisty HTML. CSS alebo JSON vystup
- APi rozhrani - komnikacia s databazami a pracovanie formularov

Syntax - kazdy PHP skript musi nachazdat vo vnutriznaciek <php a ?>
       - kazdy prikaz alebo dotaz ma koncit ;

VYtup,premenne a datove typy
 - Vystup (PHP Echo / Print) - na zobrazenie dat klientovy sa pouzivaju konstrukcie echo a print. V praxi sa preferuje echo, pretoze je o zlomok ryhclejsi a dokaze prijat viacero parametorv naraz.

 -Premenne(PHP Variables) - deklaruju sa znakom dolara a ,musia zacinat pismenom
 -Datove typy - string (viacero zankov), integer(cele cislo) a float, boolean (pravda/nepravda)

-  (.) je na spajanie textu

Data a pretypovanie 
praca s retazmi - (Strings) - v php vieme nielen spajat, upravovat pomocou stoviek zabudovanyych funkcii (napr zistenie dlzky, vyhladavanie podretazca, nahradfzovanie slov)

Cisla a matematika (PHP Number,, Math) - okrem zakladnych operacii ponuka PHP fuknice pre zaokruhlovanie (round()) , generovanie nahodnych cisel, (rand())

Konstany a Operatory : 
Konstanty (PHP conctants) - identifikatory pre hodnoty, ktore sa na rozdiel od premnnych pocas behu skriptu nesmu a nedaju zmenit.
Magicke konstanty (PHP magic constant) - specialne konstanty zacinaju a koncia dboma podciarkovnikmi
Operatory - nastroja na anipulaciu s datami - aritmicke (matematika), priradovacia(+=), porovnavacie (===), logicke(&&, ||)
