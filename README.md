# Pslib movie ratings

## O aplikaci

Tato aplikace se bude zabývat hodnocením vybraných filmů. Aplikaci by měli především hodnotit pouze studenti SPŠSE. Tato aplikace by znázorňovala oblíbenost filmů a filmových žánrů mezi studenty. Aplikace by obsahovala více žebříčků, jeden hlavní se všemi vybranými filmy, další například pouze s filmy jedné filmové série atd. 

## Princip aplikace

Princip této webové aplikace je jednoduchý. Jednalo by se tedy o stránku, na které by si každý student mohl zhodnotit filmy podle svého názoru. Na stránce by byl jeden hodnotící žebříček, ve kterém by se nacházely vybrané filmy. V tomto žebříčku by se jednotilvé filmy hodnotily hvězdičkami 1-10. Data z tohoto žebříčku by se následně u každého filmu načítala a celkové hodnocení (počet hvězdiček) by se průměroval počtem uživatelů, kteří film hodnotili (počet hodnocení). Na základě těchto údajů by se automaticky vytvářel žebříček nejlépe hodnocených filmů. Dále by bylo možné vybrat z předurčených dalších menších žebříčků, týkajících se jedné filmové série. V této sérii by se řadili podle hodnocení pouze předurčené filmy.

## Design aplikace

Apliace je designována do tmavého pozadí s kontrastními barvami pro písmo. V pozadí je použit gradient přecházející z černé #000000 až do tmavě modré #003459. Písmo je světlé barvy #F1FAEE. Zbylé prvky jsou v barvách modrozelené - #A5CCD1, #42697C.

Návrh celé aplikace je vytvořen jak pro mobilní tak pro desktopové zobrazení. Při zobrazení na mobilních telefonech se menu s rozhraním v horní částí obrazovky zabalí do hamburger menu. Na stránce se nachází ještě jedno menu, které je fixní a je možné ho kdykoliv rozkliknout i po scrollování. Jedná se o menu s výběrem konkrétních tématických žebříčků. Menu je možné schovat po kliknutí na šipku.

![](./images/Paleta_barev.jpg)

## Princip hodnocení

Každý film v hodnotícím seznamu bude obsahovat obrázek pro znázornění (nejčastěji plakát), jméno filmu, jméno režiséra a dvou herců. Pod těmito informacemi se bude nacházet 10 hvězdiček určených k hodnocení filmů. Když by uživatel chtěl dát filmu hodnocení 9 kliknul by na devátou hvězdičku zprava. Tím by se všech devět hvězdiček zabarvilo do žluta a film by byl považován jako ohodnocený. Hodnocení by bylo možné kdykoliv změnit kliknutím na jinou hvězdičku.
Jak již bylo zmíněno, tak ze všech hodnocení se budou vypočítávat průměrná hodnocení filmů. Ta se budou propisovat do "žebříčku nejoblíbenějších filmů", ve kterém se od nejlepšího hodnocení budou filmy řadit až po to nejhorší. Filmy v žebříčku bude možné nastavit od nejlepších po nejhorší, ale také obráceně a to pomocí tlačítka v pravé části obrazovky.

## Filmy k hodnocení

- stránka s filmy, kde dochází k hodnocení filmů
- filmy jsou náhodně seřazeny
- možnost vyhledání filmu

![](./images/Stranka_pro_hodnoceni_filmu_1920.jpg)

## Žebříček nejoblíbenějších filmů

- ohodnocené filmy, které jsou seřazeny od nejlépe hodnoceného
- možnost vyhledání filmu

![](./images/Zebricek_1920.jpg)

## Filmové série 

- vybraná série a porovnání jednotlivých filmů

![](./images/Zebricek_filmova_serie_1920.jpg)

## Přihlašovací stránka 

- odkaz na přihlášení přes školní účet
- alternativní možnost při nepropojení se školním účtem (vytvoření účtu)

![](./images/login_page-skolni_1920.jpg)
![](./images/login_page-obecna_1920.jpg)



