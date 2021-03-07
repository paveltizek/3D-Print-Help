1. Zjistíme si aktuální kroky motorů všech os
   - příkazem M503 z příkazové řádky (Pronterface, OctoPrint)
   - v menu tiskárny
   - ve firmwaru v položce **DEFAULT_AXIS_STEPS_PER_UNIT**
2. Vytiskneme kalibrační kostku 20x20x20 mm ([link](https://www.thingiverse.com/thing:1278865))
3. Změříme šířku kostky ve všech osách
4. Kroky zadáme to tiskárny
   - příkazem **M92 Sxx**, kde _S_ je osa (X, Y, Z) a _xx_ jsou nové nové kroky extruderu
   - v menu tiskárny
   - ve firmwaru v položce **DEFAULT_AXIS_STEPS_PER_UNIT**

