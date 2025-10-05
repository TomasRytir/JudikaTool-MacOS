# JudikaTool 1.0 - macOS verze

Rychlé a spolehlivé stahování rozhodnutí z českých soudů.

## Podporované soudy

- **NS** - Nejvyšší soud
- **NSS** - Nejvyšší správní soud
- **ÚS** - Ústavní soud
- **SDEU** - Soudní dvůr EU

## Instalace

```bash
chmod +x install.sh
./install.sh
```

Nebo manuálně:

```bash
python3 -m pip install -r requirements.txt
```

## Spuštění

```bash
python3 judika_tool.py
```

## Použití

1. Zadejte URL rozhodnutí nebo číslo jednací (např. "20 Cdo 1234/2023") - testovano s url https://sbirka.nsoud.cz/sbirka/23581/
2. Vyberte soud
3. Zvolte výstupní složku
4. Klikněte na "Stáhnout"

## Funkce

- Automatické stahování rozhodnutí ve formátu PDF
- Podpora více soudů
- Generování QR kódů s odkazem na originál
- Přehledné GUI s logem průběhu
- Automatické pojmenování souborů podle čísla jednacího

## Systémové požadavky

- macOS 10.14 nebo novější
- Python 3.8 nebo novější
- Připojení k internetu

## Převedeno z Windows verze

Tato aplikace je přepsaná verze původního JudikaTool_1_0.exe pro macOS.
Veškerá funkčnost byla zachována a optimalizována pro macOS.
