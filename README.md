Tento skript umožňuje načíst výsledky voleb z konkrétního regionu pro parlamentní volby 2017. Uživatel musí vybrat region a program uloží výsledky do souboru CSV.

Jak to použít?

Před spuštěním skriptu nainstalujte potřebné knihovny uvedené v souboru requirements.txt. Spusťte skript z příkazového řádku pomocí následujícího příkazu:

python Webscraper.py url_stranky_s_volbama nazev_souboru.csv

Výstupem bude CSV soubor s výsledky voleb za zadaný kraj.

Příklad použití

Chcete-li například získat výsledky voleb pro konkrétní okres: Prostějov

python Webscraper.py "https://volby.cz/…103" VysledkyProstejov.csv
