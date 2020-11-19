# Što je Git?

Kontrola verzija se koristi kod održavanja većeg broja različitih verzija izvornoga koda. Ovaj pristup omogućava praćenja promjena u kodu tijekom dužeg vremenskog perioda. Kontrola verzija osim navedenog omogućva suradnju među većim brojem osoba koje se mogu nalaziti na različitim lokacijama, te slanje izvornog koda s lokalnog uređaja na testni, a potom i na produkcijski server. 

# Git omogućava sljedeće: 

- praćenje promjena u kodu
- sinkronizaciju koda među različitim korisnicima
- testiranje promjena u kodu bez gubitka originala
- vraćanje starijih verzija koda

# GitHub

GitHub je mrežno sjedište koje omogućava pohranu Git repozitorija na internetu. Git omogućava upravljanje privatnim i javnim repozitorijima koji se mogu dijeliti s drugih korisnicima. 

GitHub Pro je besplatan za sve studente, te nudi brojne dodatne pogodnosti. Studentski račun možete otvoriti na sljedećoj adresi: 
[https://education.github.com/students](https://education.github.com/students)
ili 
[https://education.github.com/discount_requests/student_application](https://education.github.com/discount_requests/student_application)

Studentski račun vam, Između ostalog, omogućava neograničenu objavu privatnih repozitorija koji nisu dostupni neautoriziranim korisnicima. 

# Instalacija Git-a

Prvo provjerite na svom računalu da li je Git već instaliran – command line na Windowsima ili terminal na Mac/Linuxu.

```
git --version
git version 2.29.2
```
Ako Git nije instaliran, otvorite [Git-SCM](https://git-scm.com/downloads/) i preuzmite izvršnu datoteku za instalaciju sustava na vaše računalo.

# Otvaranje novog repozitorija
- Otvorite [github](https://github.com/)
- Logirajte se u svoj račun
- Odaberite gum [novi repozitorij](https://github.com/new) – otvorit će vam se opcija za inicijalizaciju novog repozitorija s `README` datotekom, ali ovaj put možete preskočiti izradu navedene datoteke. 
- Odaberite gumb `Create repository`

# Osnovne Git naredbe

**git init**

Zamislite da ste od kolege primili mail s nekim bitnim podacima, dokumentima ili kodom. Sve što trebate u tom trenutku učiniti jest sljedeće: 
1. otvorite na lokalnom računalu novi direktorij (npr. `mkdir test`)
2. pozicionirajte se u navedeni direktorij (npr. `cd test`)
3. unesite naredbu `git init`
4. unesite kod ili izradite novu datoteku (npr. `nano README.md`)

