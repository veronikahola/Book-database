# Book-database
Group project in C#

Aplikace pro správu oblíbených knih a jejich kategorizaci. Aplikace bude umožňovat ukládání informací o autorech, knihách a jejich kategorizaci. Uživatel má možnost hodnotit knihy, přidávat je do seznamu oblíbených, přečtených. Může si také vytvořit seznam oblíbených autorů a prohlížet jejich knihy.

Funkce aplikace:
- Registrace nových knih + jejich editování: Aplikace by měla umožňovat registrovat nové knihy do databáze. 
- Kategorizace knih: Aplikace by měla umožňovat uživateli přidávat knihy do  seznamů oblíbené, přečtené.
- Přidání hodnocení: Uživatel by měl mít možnost přidávat hodnocení k již přečteným knihám. Hodnocení by mělo zahrnovat různé atributy, jako je hodnocení hvězdičkami, textový komentář, datum atd.
- Vyhledávání oblíbených knih: Aplikace by měla umožňovat vyhledávat knihy podle různých kritérií, jako jsou název, autor, žánr atd.
## Kniha
- název
- originální název
- autor
- žánry
- rok vydání (první vydání originálu)
- počet stran
- knižní série
- stručný popis děje
- tagy (např. 20. století, druhá světová válka, queer, podle skutečných událostí, zfilmováno atd.)
- obálka
- hodnocení (průměr hodnocení všech uživatelů)
- moje hodnocení
### Vyhledávání podle
- názvu (česný i originální)
- autora
- žánru
- roku vydání
### Řazení
- řazení podle hodnocení (nejlepší/nejhorší, nejvíce hodnocení)
- řazení podle toho, kolik uživatelů má knihu v oblíbených
- a-z
- z-a
- rok vydání originálu (vzestupně, sestupně)

## Knižní série
- název
- autor
- žánr (podle knih v sérii)
- knihy v sérii
- počet knih v sérii
- hodnocení (podle hodnocení knih ze série)
### Vyhledávání podle
- názvu (česný i originální)
- autora
- žánru
- roku vydání první knihy
### Řazení
- řazení podle hodnocení knih v sérii (nejlepší/nejhorší, nejvíce hodnocení)
- řazení podle toho, kolik uživatelů má knihy ze série v oblíbených
- a-z
- z-a
- rok vydání originálu (vzestupně, sestupně) - podle první knihy ze série

## Autor
- jméno
- životopis
- knihy
- knižní série
- národnost
- rok narození
- rok úmrtí
- žánry knih
- tagy knih
### Vyhledávání podle
- jména
- národnosti
- žánru
- roku narození
### Řazení
- řazení podle toho, kolik uživatelů má autora v oblíbených
- a-z
- z-a
- rok narození

## Uživatel
- email (musí být jedinečný)
- uživatelské jméno
- hodnocení knih
- oblíbené knihy
- oblíbení autoři
- přečtené knihy (u nich si bude moct přidat od kdy do kdy ji četl; pokud nevyplní, vyplní se aktuální měsíc jako do; komentář)
## Žebříčky
- top 10 uživatelů za poslední rok (podle toho, kolik knížek přečetli)
- top 10 knížek za poslední rok (podle toho kolik lidí si knihu přidalo do přečtených za minulý rok)
- top 10 autorů za poslední rok
