# Git gebruiken

In de eerste les leerden we wat Git is en hoe we Git kunnen gebruiken. 

## Wat is Git en GitHub?

Git is een manier om te delen wat je maakt, om samen te werken en te communiceren. Je kan er gemakkelijk ook versies van documenten bijhouden. Via Git wordt samenwerken een stuk gemakkelijker.
Git is een open-source version control system. Het houdt dus bij welke aanpassingen er zijn gebeurd. Je kan ook steeds terug gaan naar een vorige versie.

Er zijn verschillende providers van Git, waaronder GitHub (MicroSoft), GitLab, Bitbucket...

_Specifieke woordenschat_:

**Repositories (repo)** = je project, elke repo is een apart project

**Snapshot** = een aanduiding dat deze versie belangrijk is

**Commit** = het maken van een snapshot, dit heeft drie stukken informatie

> 1. Informatie over hoe je bestand is veranderd.
> 2. Een link naar je vorige commit (parent commit).
> 3. Een code (kan zoiets worden: fb2d2ec5069fc)

**Cloning** = een exacte kopie van je repo maken

Er hoeft ook niet altijd internet te zijn. Want je kan wijzigingen maken op je computer, via een code-editor, zoals brackets, notepad++... en dan die wijzigen 
**pushen** naar je **remote server**. Wijzigingen die op de **remote server** maakt, moet je **pullen** om de nieuwste versie op je **working directory** te hebben.
**Pull** = je online versie opvragen en naar je computer trekken
**Push** = je versie op je computer naar je online versie duwen
**Remote server** = online, vb. GitHub
**Working directory** = je computer

**Branches** = vertakkingen om bijvoorbeeld iets anders uit te proberen

> _Bijvoorbeeld_: Je bent een T-shirt aan het ontwerpen en je wilt uitproberen hoe het er uit zal zien met lange en met korte mouwen. Dan maak je een **branche** van die met korte mouwen, op je origineel werk je verder met lange mouwen. Op het einde kan je dan kiezen welke je de beste vindt.

**Master** = je hoofdvertakking

**Head** = huidige actieve branche, je head wordt telkens verplaatst over de verschillende branches afhankelijk van waar je aan werkt

**Merging** = samenvoegen

> C2  <- C4  <----------- C6 
>     <- C3  <-  C5  <---
>
> Je hebt je tweede versie (C2), daarin maak je twee **branches** (C4 en C3). Deze **branches** verwijzen naar de vorige versie (C2), want daar zijn ze van afkomstig. Vanuit C3 maak je een nieuw commit, dat wordt dan C5 (want C4 bestaat al). Daarna **merge** je C4 en C5, dat wordt C6. 


