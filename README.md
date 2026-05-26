# Digital Patient Journal & Simulation Training System

Dette prosjektet er utviklet som en del av DAT154 Assignment 4 – System Architecture Project. Målet med prosjektet er å designe og bygge et digitalt pasientjournalsystem for bruk i sykepleiesimulering.

Systemet støtter hele simuleringsprosessen: fra opprettelse av pasientcase, til studentenes arbeid med pasientjournal under simulering, og til slutt lærerens vurdering og debrief etter gjennomført scenario.

## Kort om prosjektet

Prosjektet består av tre sammenkoblede applikasjoner:

1. **Case Setup – Web Application**  
   Brukes av lærer og studenter til å opprette, redigere og se pasientscenarioer.

2. **Simulation Interface – Desktop Application**  
   Brukes av studenter under simuleringen for å se pasientdata, registrere tiltak og følge utviklingen i vitale verdier.

3. **Assessment – Teacher View**  
   Brukes av lærer til å observere studentenes handlinger i sanntid, legge til notater og lage en debrief/evalueringsrapport.

## Teknologier

Prosjektet er bygget med .NET-teknologier og fokuserer på systemarkitektur, kommunikasjon mellom applikasjoner og delt forretningslogikk.

Brukte/planlagte teknologier:

- C#
- .NET
- ASP.NET Core
- WPF eller WinForms
- Entity Framework Core
- SQL Database
- REST API
- Shared Class Library

## Arkitektur

Systemet er laget som en distribuert løsning der flere applikasjoner kommuniserer med hverandre. Felles modeller, valideringsregler og simuleringslogikk er samlet i et delt bibliotek for å unngå duplisering av kode.

Data lagres i en database slik at pasientcase, simuleringer, tiltak og vurderinger kan brukes på tvers av økter.

## Formål

Prosjektet viser forståelse for:

- Distribuerte systemer
- Systemarkitektur
- .NET-basert applikasjonsutvikling
- Databasedesign
- Kommunikasjon mellom web-, desktop- og lærer-applikasjoner
- Gjenbruk av kode gjennom delt bibliotek

## Status

Prosjektet er under utvikling og fokuserer hovedsakelig på å få de tre applikasjonene til å kommunisere og fungere sammen som en helhet.
