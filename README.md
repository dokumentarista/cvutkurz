# Jak na to napsat jak na to?

## aneb Jak přežít dobu dokumentační

### Lukáš Růžička
lruzicka@redhat.com


duben 2020

---

## Úvodní slovo

---

## Žádná dokumentace, dobrá dokumentace?

Dokumentace není potřebná, když je všem hned jasné, jak daný produkt funguje,
co je s ním možné provádět, a co si počít, když zase tak dobře nefunguje.

Tedy:

* věc lze použít jediným způsobem
* vždy to dopadne stejně
* nikdy se to nerozbije, nebo alespoň ne tak, aby nebylo jasné, že se to
  rozbilo a proč.

Takže? Třeba **džbán**? Ale věděli jste, že tak dlouho se chodí se džbánem pro
vodu, až se ucho utrhne?

---

## 21. století nazýváme stoletím dokumentace

Nevěříte? 

Za rok 2019 bylo průměrně cca 70000 hledání za vteřinu. **Proč to tak je?**


Jaké informace ale vlastně lidé na internetu nejvíce hledají? 

Podle https://trends.google.com hledali Češi a Češky nejvíce následující informace:

---

## Top 10 kategorie "Jak" za rok 2019 v Česku

1. Jak se plete pomlázka
2. Jak zamrazit houby
3. Jak vyndat klíště
4. Jak ochladit byt
5. Jak vyfouknout vejce
6. Jak na octomilku
7. Jak vyvolat menstruaci
8. Jak vyplnit daňové přiznání
9. Jak vydělat peníze
10. Jak začít běhat

---

## Top 10 kategorie "Jak" za rok 2018 v Česku

1. Jak naladit
2. Jak vyrobit sliz
3. Jak vyplnit daňové přiznání
4. Jak volit prezidenta
5. Jak zhubnout břicho
6. Jak vyndat klíště
7. Jak vyplnit přihlášku na střední školu
8. Jak volili vaši sousedé
9. Jak uvázat kravatu
10. Jak zhubnout stehna

---

## Top 10 kategorie "Jak" za rok 2017 v Česku

1. Jak uplést pomlázku
2. Jak zamrazit houby
3. Jak volit
4. Jak upéct husu
5. Jak vyplnit daňové přiznání
6. Jak vyfouknout vejce
7. Jak vyrobit máslo
8. Jak stahovat z YouTube
9. Jak naladit Prima Love
10. Jak zhubnout stehna

---

## Dá se z toho něco usuzovat?

Je možné, že lidé s přístupem na internet

* raději hledají na internetu než ve svém okolí?
* spoléhají se, že tam tyto informace najdou?
* věří, že jsou internetové informace správné?
* neradi si pamatují?

---

## Dokumentace je prostě všude ...

... protože život je zkrátka příliš složitý.

---

## Co běžně vnímáme jako dokumentaci?

* Návody k použití
* Popis vlastností
* Seznam částí

A takovou dokumentací se budeme zabývat.

---

## Co všechno však lze vnímat jako dokumentaci?

* YouTube
* diskusní servery a blogy
* infografiky
* vysvětlivky
* školní výuka a učebnice
* rada od přátel
* a mnoho dalších

---

## Dokumentace v teorii

---

## Jakým způsobem můžeme dokumentovat?

Existují čtyři základní přístupy k dokumentaci:

* konceptuální

* procedurální

* referenční

* výukový

---

## Konceptuální dokumentace

Konceptuální dokumentace se snaží vysvětlit uživatelům danou problematiku (koncept)  tak, aby tito pochopili princip fungování a potřebné souvislosti. 

Například:

* na jakém principu funguje Wankelův motor

* jaký rozdíl je mezi vektorovou a rastrovou grafikou

* jak pracuje rekuperace v elektromobilu

* jak zhubnout stehna

---

## Procedurální dokumentace

Procedurální dokumentace poskytuje jasný návod, většinou rozdělený na jednotlivé kroky (procedura), ke splnění uživatelského záměru (user case). Mimo jiné:

* jak nainstalovat aplikaci **X**.

* jak vytvořit nového uživatele v systému Fedora

* jak si vyjednat slevu u mobilního operátora

* jak upéct husu

---

## Referenční dokumentace

Referenční dokumentace nabízí ucelený přehled (referenci) vlastností, voleb, nastavení a způsobů použití, aby si uživatel mohl sám objevit vlastní přístup a sestavit si své vlastní postupy:

* manuálové stránky v Linuxu

* přehled typů žárovek pro osvětlení vozidla

* přehled voleb příkazu `dnf` ve Fedoře

* vysvětlení významu jednotlivých polí daňového přiznání

---

## Výuková dokumentace

Výuková dokumentace, tzv. **tutoriály**, je spojení konceptuální a procedurální stránky dokumentace, takže výsledkem není jenom splněný uživatelský záměr, ale také částečné pochopení problematiky a kontextu.

Je velmi důležité, abychom z konceptuálního hlediska vysvětlili pouze tolik, kolik je **nezbytně nutné**. Chceme-li pomocí tutoriálů vysvětlit širší problematiku, pak volíme několik na sebe navazujících.

---

## Správný styl dokumentace

* jednoznačné výrazy

* jednoduché a krátké formulace

* neutrální výrazy

* genderově neutrální prvky

* v případě pochybností je lepší více informací než méně

* rozkazovací způsob (procedury)

---

## Nesprávný styl dokumentace

* estetické formy jazyka (metafory, přirovnání, nadsázka)

* hovorové výrazy

* ironie a sarkasmus

* humor

* zlehčování problémů

* utěšování uživatelů

---

## Porušování pravidel

Někdy můžeme uznat za vhodné pravidla porušit a získáme tak jinou formu dokumentace, jež je 

* zajímavá

* neotřelá

* vtipná

* parodická

Je však nutné si uvědomit, kdo budou čtenáři naší dokumentace a jsou-li tito ochotni takový přístup snášet.

---

## Technické zpracování

Dokumentaci můžeme psát ve spoustě různých formátů. Záleží, co přesně od dokumentace očekáváme:

* obtížnosti tvorby dokumentace (WYSIWYG, markdown, markup, . . . )

* metody zobrazení (web, čtečka, tištěné médium, audiovizuální metody)

* možnosti spolupráce (žádná, cvs, git, Google)

* možnosti publikace (ručně, automaticky (CI))

* dostupnosti metadat textu (sémantický markup)

Dále se budeme zabývat pouze **psanou** dokumentací.

---

## Co to je *sémantický* markup?

To je popisování textu tak, abychom kromě formálních znaků zapsali také významové a funkční souvislosti.

---

## Několik příkladů formálního markupu:

Například:

* `** tučné **` (Markdown)
* `<b>tučné</b>` (HTML)
* `\textbf{tučné}` (LaTeX)
* `* tučné *` (Asciidoc)

---

## Několik příkladů sémantického markupu:

Například:

* `<b class="command">rm -rf *</b>` (HTML)
* `<command>rm -rf *</command>` (DocBook)
* `'command':*ls -a *` (Asciidoc)
* `\begin{enumerate}` (LaTeX)

---

## Formáty

Pokud se v souvislosti s dokumentací mluví o formátech, pak máme na mysli v podstatě dva typy a to:

* zdrojové formáty, tedy ty, ze kterých se dokumentace překládá

* cílové formáty, tedy ty, do kterých se překládá

Některé souborové formáty mohou být jak zdrojové, tak cílové (HTML).

---

## Některé zdrojové formáty

* čistý text

* markdown (Markdown, AsciiDoc)

* markup (HTML, XML, DocBook, Mallard, reST, LaTeX)

* nativní formáty WYSIWYG aplikací (doc, docx, fm, odt, indd)

---

## Některé cílové formáty

* HTML (web)

* epub, mobi a další (ebooky)

* pdf (tiskárna)

---

## Nejčastěji používané formáty

* Markdown (Github)

* AsciiDoc (Red Hat)

* reST (Python)

* Mallard (Gnome)

* TeX, LaTeX (vydavatelské domy)

* DocBook (SuSE, IBM)

---

## Výběr vhodného formátu

Před výběrem formátu pořádně zamyslet, co od něj přesně chceme, neboť špatný výběr formátu může celou tvorbu dokumentace zkomplikovat.
Ptejme se na:

* formu spolupráce

* obtížnost psaní

* automatizované testování a publikování

* formy výstupu

* přenositelnost do jiných formátů

* budoucnost projektu

Obecně platí, že čím složitější formát, tím více možností použití.

---

## Dokumentace v praxi

---

## Postup při vytváření dokumentace

Dokumentace obvykle vzniká následujícím postupem:

1. zjišťování potřeb uživatelů

2. plánování a alokace zdrojů

3. stanovení formy spolupráce a formátu

4. tvorba zdrojových dokumentů

5. překlad do cílových dokumentů

6. publikování

7. vyhledání a opravení chyb

8. znovu přeložení a publikování (nová subverze)

---

## Dokumentace v Red Hatu z hlediska organizace

Red Hat v současné době udržuje mnoho dokumentačních projektů. Organizační struktura dokumentačního oddělení má několik **pilířů**:

* obsahový stratég (content strategist)

* technický manažer (pillar lead)

* manager pro lidské zdroje (people manager)

* programový manažer (document program manager)

* dokumentátor (technical writer)

Každý z nich je zodpovědný za jinou oblast vývoje dokumentace.

---

## Dokumentace v Red Had z hlediska použitých metod

* Většina dokumentačních projektů v Red Hatu používá **AsciiDoc** jako hlavní syntaxi pro vytváření zdrojových textů.

* Totéž se týká dokumentace **Fedory**.

* Mnoho projektů používá tzv. **modulární přístup** a upřednostňuje jej před klasickým přístupem.

* Systém **Docs-as-code**

---

## Modulární výhody

* výstup lze poskládat pro každého jinak (customizace)

* jednou napsaný modul lze použít na více místech textu (reusability)

* lepší orientace v textu

---

## Šedivá je teorie a zelený je strom života

* naprogramovat mechanismus pro customizaci není jednoduché a v současné době se žádný takový nepoužívá

* použít modul na více různých místech je obtížné až nemožné bez řádných metadat, avšak psaní metadat velmi prodlužuje dobu vývoje modulu

* bez systémů, které dokážou mezi moduly hledat, je ruční hledání zdlouhavé

* modularizace dělaná ručně není škálovatelná

* lidské ego se nerado dělí --- je v povaze člověka zkoušet *vynalézat neustále kolo* s myšlenkou, že to *moje* bude teprve to pravé.

---

## Docs-As-Code

Tohle je poměrně moderní, ale už dost rozšířený, způsob, kdy s dokumentací zacházíme jako s kódem a používáme:

1. popisovací jazyk (Markdown, AsciiDoc, LaTeX, Docbook)

2. sdílený repozitář (Gitlab, Github)

3. správu verzí (Git, SVN)

4. kontinuální integraci (CI)

5. automatické publikování (web)

---

## Praktická ukázka Docs-As-Code

---

### Využití Githubu

GitHub (github.com) dokáže překládat  soubor `README.md` příslušného projektu a ten zobrazovat v HTML formátu na adrese `uzivatel.github.io/repositar`.

Tato prezentace je také na Githubu jako repozitář `cvutkurz` a je mimojiné dostupná přímo na http://dokumentarista.github.io/cvutkurz.

---

## Opravujeme a vytváříme

1. Klonování Git repozitáře
   `git clone https://github.com/dokumentarista/cvutkurz.git`

2. Vytvoření lokální větve pro vývoj
   `git checkout -b novy_slide`

3. Změny v nové větvi

4. Přidat změny do gitu
   `git add .`
   `git commit -m "Provedene zmeny"`

5. Nahrát změny na server.
   `git push [--set-upstream origin novy_slide]`

6. Pokračovat ve změnách a opakovat kroky 4 a 5 dle potřeby.

---

## Správa verzí

1. Verze se uchovávají ve **větvích** (branch)

2. V nich probíhá vývoj.

3. Posléze se změny převedou do `master` větve (merge).
   `git merge novy_slide` 

8. Nahrání upraveného *masteru* na server
   `git push --force`

9. Za chvilku se změny projeví (tzv. *continuous integration*) a v hlavní větvi se objeví obsah vývojové větve.


---

## Hustě nahuštěná pneumatika

Správné použití vzduchového kompresoru:

1. Odpojte hadici od kola a smotejte ji ke kompresoru.

1. Našroubujte kryt ventilku.

1. Stisknutím a přidržením tlačítka **Plus** zvyšte tlak na požadovanou hodnotu, nebo jej pomocí tlačítka **Minus** snižte.

1. Zajeďte s autem co nejblíže kompresoru, abyste tlakovou hadici dosáhli na každé kolo.

1. Z manometru na kompresoru odečtěte současný tlak v pneumatice.

1. Rozmotejte tlakovou hadici a připojte ji na ventilek.

1. Odšroubujte kryt ventilku.

---

## Pište dokumentaci pro Fedoru

Fedora je komunitní distribuce Linuxu, na jejímž vývoji se může podílet kdokoliv. Tak i na její dokumentaci.

* repozitáře na pagure.io (Git)

* využívá projekt Antora (antora.org)

* vydána na docs.fedoraproject.org

Přispět můžete po přečtení návodu https://docs.fedoraproject.org/en-US/fedora-docs/contributing/

---

## Otázky a odpovědi

Proč, když líná pes, tak mu padají chlupy, ale když **líná huba**, tak je **holé neštěstí** a ne ta huba, která líná?
