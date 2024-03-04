CSS cascade style sheet

posso applicare il CSS:
- in maniera inline
- in maniera embededded
- dichiarando un file esterno

sintassi:
selettore {
    proprietà: valore;  /* regola */
    proprietà: valore;  /* regola */
    proprietà: valore;  /* regola */
}

selettori:
1) universal selector * (ALT GR + SHIFT + è, option + shift + è)
2) tag selector
3) class selector .
4) id selector #

specificità dei selettori passa dal meno specifico al più specifico nel seguente ordine:
meno specifico) universal selector * (ALT GR + SHIFT + è, option + shift + è)
2) tag selector
3) class selector .
4) id selector #
più specifico) css inline -> l'attributo style

font-weight:
100 thin
300 light
400 normal (regular)
700 bold
900 bolder


combinare i selettori:
- descendant selector -> spazio
- child selector