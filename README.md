Volební Scraper
Popis projektu
Tento skript umožňuje stáhnout výsledky parlamentních voleb z roku 2017 pro vybraný okres z konkrétní webové stránky. Uživatel si může vybrat okres ve sloupci "Výběr obce" a uložit výsledky do CSV souboru.

Jak na to?
Než spustíte projekt, nainstalujte si potřebné knihovny uvedené v souboru requirements.txt. Skript spustíte z příkazového řádku pomocí následujícího příkazu:

python WebScraper.py "https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=14&xnumnuts=8101" vysledky_Bruntal.csv "https://volby.cz/pls/ps2017nss/ps311?xjazyk=CZ&xkraj=14&xobec=551929&xvyber=8101"


Výstupem bude CSV soubor s výsledky voleb pro daný okres.

Příklad použití
Například pro okres Bruntál:

Odkaz: https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=14&xnumnuts=8101
Název výstupního souboru: vysledky_Bruntal

---

Pokud máte další dotazy nebo potřebujete pomoc, neváhejte mě kontaktovat!
