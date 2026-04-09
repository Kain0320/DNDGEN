🛡️DnD 5e Character Creator & Illustrator
Komplexní nástroj pro tvorbu postav do hry Dungeons & Dragons (5. edice). Tento generátor nejen vypočítá statistiky a dovednosti, ale pomocí Stable Diffusion dokáže vygenerovat unikátní portrét vaší postavy přímo během procesu tvorby.

✨ Funkce
Kompletní Generátor: Výběr rasy, třídy (včetně podtříd) a zázemí (Background).

Inteligentní Statistiky: Podpora pro Standard Array, Point Buy nebo animované házení kostkou (4d6 drop lowest).

Dynamický Inventář a Kouzla: Automatický výběr startovního vybavení a interaktivní výběr kouzel s popisy.

Export do PDF: Automatické vyplnění oficiálního D&D Character Sheetu včetně portrétu.

Deník postavy: Integrovaný textový editor pro psaní historie a poznámek k postavě.

🚀 Rychlý start
Prerekvizity
Python 3.9+w


Instalace
Klonování projektu:

Bash
git clone [https://github.com/vittasv/dnd-generator.git](https://github.com/Kain0320/DNDGEN.git)
Instalace knihoven:

Bash
pip install -r requirements.txt
Poznámka: Projekt vyžaduje customtkinter, PyPDF2, reportlab, Pillow a requests.

Spuštění aplikace:

Bash
python generator(2vr).py


📁 Struktura projektu
base.py: Jádro logiky – definice ras, tříd, kouzel a předmětů.

generator(2vr).py: Hlavní spustitelný soubor s moderním GUI.

dnd_character_sheet.pdf: Šablona deníku, která se automaticky vyplňuje.

portraits/: Galerie předpřipravených i vygenerovaných portrétů.

🛠️ Použité technologie
GUI: CustomTkinter (Moderní vzhled)

PDF Manipulace: ReportLab & PyPDF2


Vytvořeno pro všechny milovníky RPG! 🎲
Pokud se ti projekt líbí, nezapomeň dát ⭐!
