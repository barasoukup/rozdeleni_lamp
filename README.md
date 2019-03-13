# rozdeleni_lamp

Skript na spravedlivé rozdělení lamp mezi politické strany. Nejprve je sestaveno pořadí stran podle:

a) cílového počtu lamp (pokud není zadán, je brán počet preferovaných)

b) podle počtu preferovaných lamp

Strany s nižšími počty jsou zvýhodněny v pořadí.

Podle pořadí jsou stranám postupně vybírány lampy dle jejich preference. Pokud lampa již není dostupná, je straně přiřazena další v jejím pořadí preference. Přiřazování pokračuje, dokud není u všech stran vyčerpán seznam preferovaných lamp, případně není dosažen maximální počet vybraných pro danou stranu.
