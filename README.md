# Liga Mistrů - Turnajový systém

Komplexní webová aplikace pro organizaci, správu a archivaci sportovních turnajů. Tento repozitář obsahuje celoroční školní projekt, který propojuje frontend s databází MySQL pomocí PHP a JavaScriptu.

Klíčové vlastnosti

* **Role uživatelů:** *  *Administrátor* (plná správa turnaje, zadávání výsledků, ukládání do DB)
* **Automatizace turnaje:**
  * Generátor náhodných týmů.
  * Automatický rozpis zápasů ve skupině, každý s každým.
  * Real-time výpočet ligové tabulky: body, rozdíl a skóre.
  * Databázová perzistence: ukládání odehraných turnajů.
  * Automatické nasazení do vyřazovacího Play-off.

## Technologie

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+), Fetch API
* **Backend:** PHP 8+
* **Databáze:** MySQL (připojení řešeno bezpečně přes PDO)

## Instalace a spuštění (Lokální server)

1. Ujistěte se, že máte nainstalované lokální prostředí s Apache a MySQL (např. **XAMPP**).
2. Naklonujte tento repozitář nebo stáhněte ZIP soubor do složky pro vaše weby (např. `C:/xampp/htdocs/turnaj`).
3. Zapněte moduly **Apache** a **MySQL** v XAMPP Control Panelu.
4. Otevřete prohlížeč a spusťte inicializační skript, který automaticky vygeneruje databázi a tabulky: http://localhost/turnaj/init_db.php#
5. Pokud skript vrátí hlášku o úspěchu, přejděte na hlavní stránku aplikace: http://localhost/turnaj/
6.Přihlašovací údaje administrátora:
Jméno: admin
Heslo: admin123
