# Oppgave 1
* Gå til krt.im/gh og kopier klone-kommando

* Åpne opp en mappe i VSC

* Lim inn og kjør kommandoen inne i terminalen (dra opp fra bunnen). Dette vil kopiere min kode over til en mappe på maskinen

* Gjør en endring i koden (index.html)

# Oppgave 2
* Bruk GitHub Desktop-appen til å legge til eksisterende repository (Hostingkurs)

* Gå inn på github.com, finn repository og gå inn på Pages under innstillinger

* Under branch, velg main og save instillinger. GitHub vil automatisk deploye nettsiden din  

# Gå inn på nettsiden
* GitHub Pages bruker domenet github.io. Din side ligger på [brukernavn].github.io, der brukernavnet er et subdomene

* Nettsidene vises som mapper i URL-en, basert på navnet til repoet. Husk riktig små og store bokstaver
https://aleksanderekman.github.io/Hostingkurs/

* Test å gå inn på andres nettsider

# Ekstra: Vercel
* GitHub Pages gir deg ikke tilgang til serveren som hoster nettsiden. Siden vil vises til brukeren på lik måte som et word-dokument med knapper (kun client-side)

* For å hoste en backend, kan du bruke en gratis hosting-plattform som Vercel

* Lag en bruker på Vercel, koble til GitHub, legg til prosjekt og importer et Git Repository

* Nettsiden vil hostes på [prosjektnavn].vercel.app, trikset er å lage et unikt prosjektnavn

# Ekstra ekstra: Cloudflare
* Cloudflare gir deg mulighet til å hoste nettsider på ditt eget domene

* Domene kjøper du oss en domeneregistrar (GoDaddy, DomeneShop etc.), og kan deretter kobles til Cloudflare med nameservers

* Opprett konto på Cloudflare og gå inn på dashboard

* Klikk på "Add a domain", skriv inn et eksisterende domene og scan for DNS records

* Undersøk oppføringene (A-record er IPv4-adresse, AAAA-record er IPv6-adresse, CNAME er alias og MX er mail exhange)
