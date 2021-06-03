
<!---
### Alternativ 3: En enkel kalender

Det här är ett tredje förslag på hur veckodag kan kodas istället för att fråga användaren eller slumpa fram dagen. Det kommer finnas två pilar på skärmen så att användaren enkelt kan bläddra mellan de olika veckodagarna.

  ![image alt kalender](image_18.png)

  _Ungefär så här kommer kalendern se ut._

**Obs!** Du måste komma ihåg att välja dag innan du klickar på **Ja**-knappen.

1.	Skapa en **variabel** som heter **”idag”** och som inte ska visas på skärmen.

2.	Skapa en **lista** som heter **"veckodagar"**. Den ska inte visas på skärmen. Du hittar knappen för att skapa lista på fliken DATA.
    ![image alt knapp](image_17.png)

    En lista är som en variabel som kan innehålla flera värden. I din lista ska du lägga in namnet på alla veckodagarna.

3.	Markera scenen och skapa ett skript för den som säger

  * När START klickas på

  * **Ta bort allt** i **”veckodagar”**

  * **Lägg till ”Måndag" i ”veckodagar”**

  * Lägg till **”Tisdag"** i **”veckodagar”**

  * Lägg till **"Onsdag"** i **”veckodagar”**

  * Lägg till **"Torsdag"** i **”veckodagar”**

  * Lägg till **"Fredag"** i **”veckodagar”**

  * Lägg till **”Lördag"** i **”veckodagar”**

  * Lägg till **”Söndag"** i **”veckodagar”**

  * Sätt **”idag”** till ett **slumptal mellan 1 och 7**

  * Sätt **”Idag är det: ”** till **objekt ”idag”** i **”veckodagar”**

  ![image alt block](image_19.png)

  _Dessa block behöver du för koden ovan. Tänk på att du måste lägga till fler block för att lägga in alla dagar i listan._

4.	**Lägg till en sprajt** från biblioteket som ser ut som en pil, till exempel **Arrow2**.

5.	Förminska pilen så att den blir lagom stor och placera den till höger om variabeln **”Idag är det: ”**

6.	Skapa ett skript för **pilen** som säger:

  * Startar när sprajten klickas på

  * OM **”idag”** är **mindre än 7**: **ändra ”idag”** med **1**

  * ANNARS: **sätt ”idag"** till **1**

  * Sätt **”Idag är det: ”** till **objekt ”idag”** i **”veckodagar”**

  ![image alt block](image_20.png)

7.	**Kopiera sprajten** så att du har två pilar.

8.	**Ändra klädsen** på den andra sprajten så att den pekar åt vänster.

9.	Placera den till vänster om variabeln **”Idag är det: ”**

10.	Ändra i koden för **vänster-pilen** så den säger:

  * Startar när sprajten klickas på

  * OM **”idag”** är **större än 1**: **ändra ”idag”** med **-1**

  * ANNARS: **sätt ”idag"** till **7**

  * Sätt **”Idag är det: ”** till **objekt ”idag”** i **”veckodagar”**

> Testa! Vad händer om du klickar på de olika pilarna? Vad händer om det är söndag och du klickar på höger-pilen?
-->

