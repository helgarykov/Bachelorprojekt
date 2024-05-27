# Bachelor Project in Information Systems 2023

## Professor
**Simon Bruntse Andersen**

## Resume
The BA thesis at hand presents an IT design project conducted within the field of information systems. It employs the MUST method as its theoretical and methodological framework, adhering to its core concepts and principles.

The project explores the “20 minutes a day” reading practice, introduced by The Ministry of Children and Education following concerning results from PIRLS and PISA, which showed a decline in literacy among Danish primary school pupils.

The study focuses on Danish primary school pupils and their parents, aiming to understand actual reading practices in Danish homes. This exploration aids in developing a minimal viable product (MVP) – a reading application targeted at Danish children aged 6 to 10, designed to motivate and enhance their reading skills in Danish and alleviate the burden on their parents.

The culmination of this study is the conceptualization of an innovative reading platform that combines elements of computer games and cartoons with the educational objectives of Danish primary school students (“de danske indskolingsbørns uddannelsesmål”). The thesis showcases several IT design solutions, demonstrated through storyboards, a prototype, and an attrape.

Regarding the business strategy, the MVP is envisioned to be developed within a startup, operated by a single individual, and distributed through the App Store and Google Play. The ultimate goal, however, is to offer the application free of charge to all primary school children in Denmark via SkoleTube.

## Indhold
0. [Resumé](#resumé)
1. [Forberedelsesfasen — projektetablering](#forberedelsesfasen--projektetablering)
   1.1. [Forundersøgelsens baggrund og formål](#forundersøgelsens-baggrund-og-formål)
   1.2. [Planen over forundersøgelsesprojektet](#planen-over-forundersøgelsesprojektet)
2. [Fokuseringsfasen — strategianalyse](#fokuseringsfasen--strategianalyse)
   2.1. [Dokumentanalyse: Fra fælles mål til digitale medier](#dokumentanalyse-fra-fælles-mål-til-digitale-medier)
     2.1.1. [Fælles mål for læsning i danskfaget (indskoling)](#fælles-mål-for-læsning-i-danskfaget-indskoling)
     2.1.2. [Tilgange til staveundervisning i folkeskolen](#tilgange-til-staveundervisning-i-folkeskolen)
     2.1.3. [Analog vs. digitale enheder](#analog-vs-digitale-enheder)
   2.2. [Funktionsanalyse af eksisterende læseapps](#funktionsanalyse-af-eksisterende-læseapps)
     2.2.1. [Maneno](#maneno)
     2.2.2. [BookBites](#bookbites)
     2.2.3. [Tales](#tales)
   2.3. [Brugerundersøgelse](#brugerundersøgelse)
     2.3.1. [Spørgeskemaundersøgelse](#spørgeskemaundersøgelse)
     2.3.2. [Resultaterne](#resultaterne)
       2.3.2.1. [Udfordringer og mønstre i daglig læsning blandt 1.-3. klasseselever](#udfordringer-og-mønstre-i-daglig-læsning-blandt-1-3-klasseselever)
       2.3.2.2. [Forældrenes perspektiv på børns forhold til daglig læsning](#forældrenes-perspektiv-på-børns-forhold-til-daglig-læsning)
       2.3.2.3. [Forældres holdninger til brugen af læseapps i børns læseudvikling](#forældres-holdninger-til-brugen-af-læseapps-i-børns-læseudvikling)
       2.3.2.4. [Hovedkonklusioner fra spørgeundersøgelsen](#hovedkonklusioner-fra-spørgeundersøgelsen)
3. [Fordybelsesfasen — dybdeanalyse](#fordybelsesfasen--dybdeanalyse)
   3.1. [Observationer](#observationer)
     3.1.1. [Referat](#referat)
       3.1.1.1. [Forælder-barn interaktion](#forælder-barn-interaktion)
       3.1.1.2. [Børnenes engagement](#børnenes-engagement)
       3.1.1.3. [Forældrenes rolle](#forældrenes-rolle)
       3.1.1.4. [Hovedkonklusioner fra observationerne](#hovedkonklusioner-fra-observationerne)
   3.2. [Interviews](#interviews)
     3.2.1. [Affinitetsdiagram](#affinitetsdiagram)
     3.2.2. [Hovedkonklusioner fra interviews’ene](#hovedkonklusioner-fra-interview’sene)
   3.3. [Opsummering](#opsummering)
     3.3.1. [Diagnostistisk kort](#diagnostistisk-kort)
     3.3.2. [Forslag til prioritering](#forslag-til-prioritering)
4. [Fornyelsesfasen — visionsudvikling](#fornyelsesfasen--visionsudvikling)
   4.1. [Virtuel kortlægning](#virtuel-kortlægning)
   4.2. [Udvikling og visualisering af løsningsforslag](#udvikling-og-visualisering-af-løsningsforslag)
     4.2.1. [Integration af spilbaserede læringselementer 1](#integration-af-spilbaserede-læringselementer-1)
     4.2.2. [Integration af spilbaserede læringselementer 2](#integration-af-spilbaserede-læringselementer-2)
     4.2.3. [Integration af spilbaserede læringselementer 3](#integration-af-spilbaserede-læringselementer-3)
     4.2.4. [Personlig tilpasning af brugeroplevelsen](#personlig-tilpasning-af-brugeroplevelsen)
   4.3. [Forretningsstrategianalyse for en startup enmandsvirksomhed](#forretningsstrategianalyse-for-en-startup-enmandsvirksomhed)
   4.4. [SWOT-analyse](#swot-analyse)
5. [Kritisk refleksion over metodologi](#kritisk-refleksion-over-metodologi)
   5.1. [MUST-metoden](#must-metoden)
   5.2. [Vurdering af validiteten i forundersøgelsen](#vurdering-af-validiteten-i-forundersøgelsen)
   5.3. [Vurdering af reliabiliteten i forundersøgelsen](#vurdering-af-reliabiliteten-i-forundersøgelsen)
6. [Konklusion](#konklusion)

## Resumé
The BA thesis at hand presents an IT design project conducted within the field of information systems. It employs the MUST method as its theoretical and methodological framework, adhering to its core concepts and principles.

The project explores the “20 minutes a day” reading practice, introduced by The Ministry of Children and Education following concerning results from PIRLS and PISA, which showed a decline in literacy among Danish primary school pupils.

The study focuses on Danish primary school pupils and their parents, aiming to understand actual reading practices in Danish homes. This exploration aids in developing a minimal viable product (MVP) – a reading application targeted at Danish children aged 6 to 10, designed to motivate and enhance their reading skills in Danish and alleviate the burden on their parents.

The culmination of this study is the conceptualization of an innovative reading platform that combines elements of computer games and cartoons with the educational objectives of Danish primary school students (“de danske indskolingsbørns uddannelsesmål”). The thesis showcases several IT design solutions, demonstrated through storyboards, a prototype, and an attrape.

Regarding the business strategy, the MVP is envisioned to be developed within a startup, operated by a single individual, and distributed through the App Store and Google Play. The ultimate goal, however, is to offer the application free of charge to all primary school children in Denmark via SkoleTube.

## Forberedelsesfasen — projektetablering
### Forundersøgelsens baggrund og formål
...

### Planen over forundersøgelsesprojektet
...

## Fokuseringsfasen — strategianalyse
### Dokumentanalyse: Fra fælles mål til digitale medier
...

#### Fælles mål for læsning i danskfaget (indskoling)
...

#### Tilgange til staveundervisning i folkeskolen
...

#### Analog vs. digitale enheder
