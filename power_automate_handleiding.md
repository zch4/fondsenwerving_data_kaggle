# Power Automate - verkennende handleiding
## Flow: nieuwe donateur registreren via formulier

**Doel:** verkennen hoe een eenvoudige fondsenwervingsflow eruit kan zien waarbij een formulierreactie automatisch in Excel wordt vastgelegd en een bevestigingsmail wordt verstuurd.

Deze handleiding is bedoeld als conceptuele aanvulling op het notebook. Het is dus geen bewijs van een volledige productie-implementatie, maar een kleine oefening om te begrijpen hoe procesautomatisering in deze context kan werken.

## Wat je nodig hebt
- Gratis Microsoft-account (outlook.com volstaat)
- OneDrive
- Toegang tot Power Automate: https://make.powerautomate.com
- Toegang tot Microsoft Forms: https://forms.office.com

## Globale stappen
1. Maak een Excel-bestand in OneDrive met een tabel voor donateurregistraties.
2. Maak een formulier in Microsoft Forms voor nieuwe donateurs.
3. Bouw in Power Automate een flow die:
   - een nieuwe formulierreactie ontvangt;
   - de gegevens ophaalt;
   - een rij toevoegt aan Excel;
   - een bevestigingsmail verstuurt.
4. Test de flow met voorbeeldgegevens.

## Wat dit laat zien
- Hoe formuliergegevens automatisch kunnen worden vastgelegd
- Hoe een eenvoudige importstroom eruit kan zien
- Hoe geautomatiseerde communicatie gekoppeld kan worden aan invoerdata

## Belangrijke beperking
In een echte organisatie zou zo'n proces meestal gekoppeld zijn aan een CRM of donateursdatabase, bijvoorbeeld Dynamics 365. Deze handleiding gebruikt Excel en Forms als laagdrempelig oefenvoorbeeld.

## Hoe je dit het beste kunt benoemen
Een veilige formulering is bijvoorbeeld:

> "Ik heb verkend hoe een eenvoudige Power Automate-flow kan worden ingericht om formuliergegevens automatisch vast te leggen en een bevestigingsmail te versturen. Daardoor heb ik beter inzicht gekregen in hoe datastromen en procesautomatisering in een fondsenwervingscontext kunnen werken."
