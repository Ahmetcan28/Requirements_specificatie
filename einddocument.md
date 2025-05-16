# Requirements specificatie
![Software Requirement Specification](Software-Requirement-Specification.jpg)


**Namen:** Ahmetcan Akin, Melih Danismaz, Kaan Akgurbuz, Bilal Chernobi  
**Docent:** Jeroen van Gils  
**Opdracht:** Requirements Specificatie  

---

### Versieoverzicht

| Versienummer | Datum              | Auteur             | Wijziging                     | Gecontroleerd door |
|--------------|--------------------|---------------------|-------------------------------|---------------------|
| 0.1          | 13-05-2025         | Ahmetcan Akin       | Opzet document                | Kaan Akgurbuz       |
| 0.1          | 13-05-2025         | Ahmetcan Akin       | Organisatorische context      | Kaan Akgurbuz       |
| 0.1          | 14-05 & 15-05-2025 | Ahmetcan Akin       | Actoren                       | Kaan Akgurbuz       |
| 0.1          | 13-05-2025         | Bilal Chernoubi     | Bedrijfsprocesanalyse         | Melih Danismaz      |
| 0.1          | 14-05 & 15-05-2025 | Bilal Chernoubi     | Productvisie                  | Melih Danismaz      |
| 0.1          | 13-05-2025         | Melih Danismaz      | Userstories                   | Bilal Chernoubi     |
| 0.1          | 14-05 & 15-05-2025 | Melih Danismaz      | Domeinmodel incl. UML-diagram | Bilal Chernoubi     |
| 0.1          | 13-05-2025         | Kaan Akgurbuz       | Sitemap                       | Ahmetcan Akin       |
| 0.1          | 14-05 & 15-05-2025 | Kaan Akgurbuz       | Wireframes                    | Ahmercan Akin       |

---
## Inhoudsopgave

1. [Organisatorische context](#10-organisatorische-context)  
    1.1 [Missie](#11-missie)  
    1.2 [Visie](#12-visie)  
    1.3 [Strategie](#13-strategie)  
    1.4 [Doelstellingen](#14-doelstellingen)  
    1.5 [Organogram](#15-organogram)  
2. [Stakeholderanalyse](#20-stakeholderanalyse)  
    2.1 [Stakeholdergroepen](#21-stakeholdergroepen)  
    2.2 [Power-Interest Matrix](#22-power-interest-matrix)  
3. [Actoren](#30-actoren)  
4. [Bedrijfsprocesanalyse (SIPOC)](#40-bedrijfsprocesanalyse-sipoc)  
    - [SIPOC-tabel](#sipoc-tabel)  
    - [Strategisch verband met SIPOC](#strategisch-verband-met-sipoc)  
5. [Productvisie](#50-productvisie)  
6. [User Stories – Gebruikerszijde](#60-user-stories--gebruikerszijde-klanten)  
    6.1 [User Stories – Organisatie en partners](#61-user-stories--organisatie-en-partners)  
7. [Domeinmodel](#70-domeinmodel)  
8. [UML-klassendiagram](#80-uml-klassendiagram)  
9. [Sitemap](#90-sitemap)  
10. [Wireframes](#100-wireframes)

## 1.0 Organisatorische context

In dit hoofdstuk lichten we toe dat we van plan zijn een vernieuwende mobiele applicatie te ontwikkelen die gericht is op het verbeteren van de klantervaring en het versterken van klantloyaliteit. Deze applicatie draagt bij aan het realiseren van onze missie en visie. Bovendien maken we hiermee duidelijk op welke manier we deze ambities willen waarmaken – met andere woorden, wat onze strategie inhoudt. Daarnaast formuleren we concrete doelstellingen die we als organisatie willen behalen.

### 1.1 Missie

Onze missie is om gebruikers een toegankelijke en gebruiksvriendelijke mobiele applicatie te bieden die hun digitale dagelijkse leven vereenvoudigt. De applicatie die wij ontwikkelen, bundelt al onze diensten en producten op één centrale plek, waardoor het voor klanten eenvoudiger wordt om te vinden wat ze nodig hebben. Daarnaast streven we ernaar om hoogwaardige service en klantgerichte ondersteuning te leveren.

### 1.2 Visie

Onze visie is om een innovatieve app te maken waarbij de klant echt centraal staat. We willen inspelen op de wensen en behoeften van de gebruiker, zodat zij via hun mobiel een persoonlijke en efficiënte ervaring krijgen. Dit doen we bijvoorbeeld met functies zoals gepersonaliseerde aanbevelingen, die zijn afgestemd op wat de klant belangrijk vindt. Ook bevat de app een functie voor probleemoplossing, zodat klanten snel geholpen worden en de app prettig blijft in gebruik.

### 1.3 Strategie

- **Klantervaring:** We willen de klantervaring zo goed mogelijk maken door een app te ontwikkelen die eenvoudig in gebruik is en handige functies biedt. Denk hierbij aan productregistratie, garantiebeheer, persoonlijke aanbevelingen en klantenservice. Met deze functies willen we de klanttevredenheid verhogen en tegelijkertijd een sterke relatie opbouwen met onze gebruikers.
- **Innovatie:** In onze app willen we gebruikmaken van moderne technologieën zoals kunstmatige intelligentie (AI), pushmeldingen en data-analyse. Hierdoor wordt de app slimmer en persoonlijker.
- **Efficiënte processen:** Door de app te koppelen aan een ERP-systeem kunnen we efficiënter werken en klantgegevens centraal beheren. Dit helpt ons om sneller te groeien en indien nodig nieuwe functies toe te voegen.

### 1.4 Doelstellingen

1. **Klantervaring verbeteren:** Binnen het eerste jaar een klanttevredenheidsscore van minimaal 80% behalen.
2. **Klantloyaliteit versterken:** 25% stijging in terugkerende klanten.
3. **Efficiëntie verhogen:** 30% minder hulpverzoeken via AI en selfservice.
4. **Innovatie stimuleren:** Ieder jaar minstens 3 nieuwe functies toevoegen.
5. **Groei bevorderen:** Binnen twee jaar gebruikt 70% van de klanten actief de app.

### 1.5 Organogram

![Procesdiagram](https://github.com/Ahmetcan28/Requirements_Specificatie/blob/main/Schermafbeelding%202025-05-16%20om%2014.46.56.png?raw=true)



---

## 2.0 Stakeholderanalyse

### Identificatie van stakeholders

Voordat we een stakeholderanalyse uitvoeren met behulp van de **Power-Interest Matrix**, is het belangrijk om eerst te bepalen wie onze stakeholders zijn en waarom zij als stakeholder worden beschouwd. Stakeholders zijn personen of groepen die invloed uitoefenen op ons bedrijf, of zelf beïnvloed worden door de activiteiten van Nexa.

- **Managementteam**  
Het managementteam bestaat uit o.a. de CEO, COO, CMO, CFO en HR-manager. Ze nemen belangrijke strategische beslissingen en hebben grote invloed op het bedrijf.

- **Investeerders / Bank**  
De bank fungeert als investeerder. Ze hebben invloed via financiële voorwaarden zoals rente en aflossing.

- **Externe partners**  
Marketingbureaus, IT-dienstverleners en onderhoudsbedrijven. Hun kwaliteit beïnvloedt direct onze dienstverlening.

- **Medewerkers**  
Hun inzet en werkkwaliteit hebben directe invloed op prestaties en klantbeleving.

- **Klanten**  
Zij bepalen het succes via hun tevredenheid, gedrag en feedback.

- **Leverancier**  
Nexa werkt met één vaste leverancier. Deze partij is cruciaal voor voorraad en levering.

- **Concurrenten**  
Beïnvloeden onze marktpositie via prijzen, innovaties en marketing.

- **Overheid**  
Heeft invloed via wetgeving (belasting, privacy, productveiligheid).

- **Media**  
Beïnvloedt de reputatie van Nexa via publicaties (positief of negatief).

---

### 2.1 Stakeholdergroepen

**Interne stakeholders:**

- Managementteam (CEO, COO, CFO, CMO, HRM)  
- Investeerder / Bank  
- Externe partners  
- Medewerkers  
- IT-afdeling  
- Klantenservice  
- HRM-afdeling  
- Financiële afdeling  
- Research & Analyse-afdeling

**Externe stakeholders:**

- Klanten  
- Leverancier  
- Concurrenten  
- Overheid  
- Media

---

### 2.2 Power-Interest Matrix

We maken gebruik van de **Power-Interest Matrix** om te bepalen hoe we met stakeholders omgaan.

**Categorieën:**
- **Manage closely** – Veel invloed én belang  
- **Keep satisfied** – Veel invloed, minder belang  
- **Keep informed** – Weinig invloed, veel belang  
- **Monitor** – Weinig invloed en weinig belang

**Toelichting:**

- **Manage closely:**  
  - *Managementteam* – strategisch stuur  
  - *Klanten* – directe gebruikers en bron van inkomsten  

- **Keep satisfied:**  
  - *Overheid* – wet- en regelgeving  
  - *Externe partners* – belangrijk voor uitvoering, minder voor strategie  

- **Keep informed:**  
  - *Investeerder / Bank* – financieel belang, minder directe invloed  
  - *Leverancier* – belangrijk, maar vervangbaar  

- **Monitor:**  
  - *Media* – indirecte reputatie-invloed  
  - *Concurrenten* – wederzijdse marktinvloed, beperkt  

---

> *Waarom deze matrix?*  
De Power-Interest Matrix biedt inzicht in zowel invloed als betrokkenheid. Het helpt bij het stellen van prioriteiten in communicatie en samenwerking.

## 3.0 Actoren

Binnen ons bedrijf zijn er verschillende actoren die invloed uitoefenen op het bedrijf. Hieronder volgt een overzicht van de belangrijkste actoren:

| **Actoren**        | **Beschrijving** |
|--------------------|------------------|
| **Klanten**        | Personen die smartphones of aanverwante producten kopen via Nexa. Ze vormen de belangrijkste bron van inkomsten en zijn direct betrokken bij het gebruik van de mobiele applicatie. |
| **Concurrentie**   | Andere bedrijven binnen de telecom- of techbranche die vergelijkbare producten of diensten aanbieden. Zij beïnvloeden de markt waarin Nexa opereert. |
| **Medewerkers**    | Werknemers binnen Nexa die betrokken zijn bij o.a. promotiebeheer, productaanbevelingen via de app, en technische ondersteuning (inclusief ontwikkelaars). |
| **Externe partners** | Bedrijven die Nexa ondersteunen bij diensten zoals reparatie, onderhoud of marketing. |
| **Managementteam** | De directie en het management van Nexa sturen de organisatie aan en nemen strategische beslissingen. |
| **Overheid**       | Beïnvloedt Nexa via wet- en regelgeving op het gebied van privacy, consumentenrecht, belasting en productveiligheid. |
| **Leveranciers**   | Leveren de benodigde producten of onderdelen. Nexa is afhankelijk van één hoofdleverancier. |
| **Investeerders / Bank** | Financieren Nexa via leningen en verwachten rendement of stabiliteit. |
| **Media**          | Beïnvloedt de publieke perceptie van Nexa via publicaties. |

---

## 4.0 Bedrijfsprocesanalyse (SIPOC)

We gebruiken de **SIPOC-methode** om een duidelijk overzicht te geven van de huidige (IST) en gewenste (SOLL) situatie, en de knelpunten daartussen (GAPs).

### SIPOC-tabel

| **SIPOC**   | **IST (Huidige situatie)** | **SOLL (Toekomstige situatie)** | **Gap (Knelpunten)** |
|------------|----------------------------|----------------------------------|------------------------|
| **Suppliers** | - Klant levert productinformatie handmatig<br>- Medewerker helpt bij registratie<br>- IT/support doen diagnose handmatig | - Klant levert gegevens via app<br>- AI legt problemen automatisch vast<br>- Informatie via CRM/ERP-integratie | Klanten zijn afhankelijk van handmatige ondersteuning, beperkt technologisch gebruik |
| **Inputs** | - Serienummers via e-mail<br>- Losse garantie-aanvragen<br>- Handmatige interactie vereist | - Invoer via QR/barcode of app<br>- Realtime updates via gekoppelde systemen<br>- Automatisch klantgedrag volgen | Handmatige input kost tijd en is foutgevoelig |
| **Process** | - Klant belt/mailt voor hulp<br>- Handmatige registratie<br>- Trage supportafhandeling | - Registratie in app<br>- App toont garanties/status<br>- Feedback- en communityfunctie | Geen centrale toegang, geen proactieve klantinteractie |
| **Outputs** | - E-mailbevestiging<br>- Oplossing na wachttijd<br>- Handmatige terugkoppeling | - Direct dashboardinzicht<br>- Pushmeldingen<br>- Beloningen via gamification | Trage terugkoppeling, geen personalisatie |
| **Customers** | - Wachten op reactie<br>- Hoge werkdruk op support | - AI/selfservice voor snelle hulp<br>- Medewerkers focussen op complexere vragen | Lage klanttevredenheid, hoge werkdruk, gemiste loyaliteitskansen |

---

### Strategisch verband met SIPOC

| **Strategisch doel** | **Relatie met SIPOC** |
|----------------------|------------------------|
| **Missie**: Toegankelijke app | App centraliseert registratie en support (SOLL) |
| **Visie**: Klant centraal, efficiëntie | SIPOC toont selfservice en personalisatie |
| **Strategie**: Klantervaring, innovatie, efficiëntie | SIPOC maakt dit concreet via AI, ERP, meldingen |
| **Doelstellingen**: 80% tevredenheid, 25% loyaliteit, 30% minder hulpvragen, jaarlijkse innovaties, 70% adoptie | SIPOC geeft inzicht hoe deze doelen via procesverandering bereikt worden |
## 5.0 Productvisie 
## 6.0 User Stories – Gebruikerszijde (klanten)

- **Als klant wil ik** mijn Nexa-smartphone kunnen koppelen via een QR-code of barcode,  
  → zodat ik snel toegang krijg tot productinformatie en garantie.

- **Als klant wil ik** afspraken kunnen maken voor onderhoud, reparaties of adviesgesprekken,  
  → zodat mijn apparaat goed blijft functioneren.

- **Als klant wil ik** een overzicht van alle geregistreerde apparaten met aankoopdatum, garantie en softwareversie,  
  → zodat ik mijn gegevens overzichtelijk kan inzien.

- **Als klant wil ik** handleidingen, uitlegvideo’s en tips bekijken,  
  → zodat ik weet hoe ik mijn toestel optimaal kan gebruiken.

- **Als klant wil ik** via een AI-chatbot vragen kunnen stellen,  
  → zodat ik ook buiten werktijden hulp krijg.

- **Als klant wil ik** suggesties krijgen voor accessoires en updates,  
  → zodat ik mijn gebruikservaring kan verbeteren.

- **Als klant wil ik** een melding ontvangen voor een afspraak,  
  → zodat ik deze niet vergeet.

- **Als klant wil ik** tweefactorauthenticatie instellen,  
  → zodat mijn gegevens beter beschermd zijn.

---

## 6.1 User Stories – Organisatie en partners

- **Als medewerker wil ik** actuele klant- en productinformatie kunnen inzien,  
  → zodat ik klanten sneller kan helpen.

- **Als bedrijf willen we** meldingen sturen naar klanten,  
  → zodat we betrokken blijven.

- **Als bedrijf willen we** een loyaliteitssysteem aanbieden,  
  → zodat klanten punten kunnen sparen.

- **Als bedrijf willen we** statistieken over gebruikersgedrag bekijken,  
  → zodat we beter begrijpen wat klanten nodig hebben.

- **Als manager wil ik** rapporten over klanttevredenheid en klachten inzien,  
  → zodat ik tijdig kan bijsturen.

- **Als leverancier wil ik** een melding krijgen bij lage voorraad,  
  → zodat ik op tijd kan bijvullen.

- **Als externe partner wil ik** mijn diensten promoten in de app,  
  → zodat ik nieuwe klanten bereik.

---

## 7.0 Domeinmodel

**Entiteiten:**

- Klant – eindgebruiker van de app  
- Smartphone – geregistreerd toestel van klant  
- Garantie – gekoppeld aan toestel (periode/status)  
- Afspraken – voor onderhoud/advies/reparatie  
- Chatgesprek – met AI-chatbot  
- Medewerker – support en klantbeheer  
- Pushmelding – berichten naar klant  
- Loyaliteitspunt – spaarsysteem per klant  
- Leverancier – ontvangt voorraadmeldingen  
- Partner – adverteert in app

**Relaties:**

- Een klant kan meerdere smartphones registreren  
- Een smartphone heeft één garantie  
- Een klant kan meerdere afspraken en chatgesprekken hebben  
- Medewerkers beheren meerdere afspraken  
- Pushmeldingen gaan naar klanten  
- Loyaliteitspunten zijn gekoppeld aan klantactiviteit  
- Leveranciers leveren producten en ontvangen meldingen  
- Partners beheren advertenties en content in app

---

## 8.0 UML-klassendiagram

_(Afbeelding niet opgenomen)_

---

## 9.0 Sitemap

## 10.0 Wireframes
