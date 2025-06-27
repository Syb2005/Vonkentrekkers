# Vonkentrekkers

## samenvatting

De achtergrond van dit project begint bij Bart Snijder, docent elektrotechniek. Bart had een probleem, hij wou namelijk elektromagnetische interferentie (EMI) op een interessante manier demonstreren in zijn lessen netwerktheorie 3. Hiervoor wou hij een simpele opstelling die in staat was om bepaalde schakelingen zowel software als hardware matig te kunnen “storen”. Van daar dat de doelstelling van dit project is om een robuust en educatief apparaat te maken die de effecten van elektromagnetische interferentie aan kan tonen. Daarom luidt de hoofdvraag: “Hoe zou elektromagnetische interferentie op een interessante manier aangetoond kunnen worden doormiddel van een apparaat die uitstraalt en een ander schema dat de interferentie ontvangt?”

Voor dit project is de werkwijze gegaan via een vooraf opgestelde planning, dit begon eerst met een stukje theoretisch en praktisch onderzoek, daarna zijn er simulaties en prototypes opgesteld en uiteindelijk is daar een PCB en een eindproduct uitgekomen. Een voorbeeld van een aantal randvoorwaarden van dit project zijn: budget, gebruik van apparatuur en veiligheid.
Ondanks dat het project ongeveer een periode later begon dan gepland, verliep het hele proces van onderzoek tot eindproduct relatief vlekkeloos. Er is eerst begonnen met onderzoek naar hoe er op een relatief makkelijke manier een grote hoeveelheid EMI gegenereerd kan worden. Uiteindelijk bleek dat dat theoretisch goed behaalt kan worden door simpel vonken in de open lucht over te laten slaan. Hierdoor is een voornamelijk doel van het project ook geweest om te kijken naar hoe een robuust systeem gemaakt kan worden die in staat is om hoogspanning te genereren. Er is gekeken naar verschillende mogelijkheden. Bijvoorbeeld een tesla spoel, een Van de Graaff generator en   CRT-TV flyback transformatoren. de conclusie daaruit is dat de makkelijkste manier om hoogspanning te kunnen genereren is door een flyback transformator te gebruiken, en een systeem te ontwerpen die in staat is om die transformator aan te sturen. CRT-TV flyback transformatoren zijn in het algemeen in staat om spanning van rond de 25Kv te maken, voor dit project is dat voldoende. Het uiteindelijke design van het eindproduct bestond uit een PCB die de transformator aanstuurt, de transformator die voedt een stel spanningsvermenigvuldigers waarbij de uiteindelijke uitgang van het systeem een instelbare vonkbrug is. Voor dat systeem zijn meerdere LTspice simulaties uitgevoerd, en er zijn meerdere prototypes op gaatjesprint neergezet.

De uiteindelijke conclusie op de hoofdvraag luidt dan ook: door een systeem te maken wat in staat is om hoogspanning te laten vonken, waarvan het belangrijkst onderdeel in het systeem een flyback transformator is die een spanningsvermenigvuldiger voedt.

Indien dit project wordt nagemaakt dan wordt het zeer aanbevolen om altijd op uw hoede te zijn rond hoogspanning, als dit fout wordt behandeld dan kan dat mogelijk lethaal zijn. Daarnaast wordt het ook aanbevolen om alle hoogspanning afgeschermd en apart te houden van de rest van de schakeling en de buitenwereld, dit is om ongelukken te voorkomen.

Voor wat meer inzicht staat hieronder de poster van dit project, is dat nog niet genoeg dan staat alle informatie over dit project in detail beschreven in de wiki.

![image](https://github.com/user-attachments/assets/44bd38d7-e82e-4e82-82dd-81033dd1ed0d)


