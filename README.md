# WKOF donateursdata - hobbyproject

## Over dit project
Dit project gebruikt een publieke mock-dataset van Kaggle over fondsenwerving en donateursdata. Het doel is om te laten zien hoe donor- en transactiedata kunnen worden ingelezen, gecontroleerd, verrijkt en omgezet naar rapportageklare bestanden.

De nadruk ligt op:
- imports en exports;
- datakwaliteitschecks;
- samenvoegen van tabellen;
- Excel-rapportage als basis voor verdere analyse.

## Dataset
Bron: [Mock Nonprofit Fundraising Data op Kaggle](https://www.kaggle.com/datasets/grantstancliff/mock-nonprofit-fundraising-data)

Belangrijke kanttekening: dit is mock data. Het project simuleert dus een fondsenwervingscontext, maar is geen echte productieomgeving met Dynamics 365, Mailchimp of een operationele Power BI-omgeving.

## Inhoud
- `wkof_donateursdata.ipynb` - hoofdnotebook met bronze/silver/gold-structuur
- `data/bron/` - bron-CSV's voor de notebook
- `power_automate_handleiding.md` - optionele verkenning van een eenvoudige Power Automate-flow
- `requirements.txt` - minimale Python-afhankelijkheden

## Wat dit project laat zien
- CSV-bronbestanden inladen en structureren
- transacties en donateursdata controleren op datakwaliteit
- tabellen verrijken via joins
- rapportageklare exports maken voor Excel of verdere analyse

## Wat dit project niet direct bewijst
- uitgebreide ervaring met Dynamics 365
- praktijkervaring met Mailchimp-audiences
- gevorderde Power BI-kennis

## Extra rapportages (optioneel)
Het notebook bevat ook twee extra rapportages die nog directer aansluiten op operationeel databeheer:
- datakwaliteitsoverzicht;
- reviewlijst transacties.

Deze extra rapportages zijn bedoeld als praktische aanvulling op de basisanalyse.

## Power Automate
De handleiding in `power_automate_handleiding.md` is bedoeld als eenvoudige verkenning van procesautomatisering in een fondsenwervingscontext. Zie dit vooral als conceptuele aanvulling op het Python/Excel-project, niet als volledig productievoorbeeld.

## Lokaal draaien
1. Maak een virtual environment aan.
2. Installeer de dependencies met `pip install -r requirements.txt`.
3. Start Jupyter Notebook of JupyterLab.
4. Open `wkof_donateursdata.ipynb` en run de cellen van boven naar beneden.

Na het draaien maakt het notebook zelf de mappen `data/bronze/`, `data/silver/`, `data/gold/` en `exports/` aan.
