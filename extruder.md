1. Zjistíme si aktuální kroky motoru extruderu
   - příkazem M503 z příkazové řádky (Pronterface, OctoPrint)
   - v menu tiskárny
   - ve firmwaru v položce **DEFAULT_AXIS_STEPS_PER_UNIT**
2. Zapíšeme hodnotu do kalkulačky
3. Nahřejeme trysku podle zvoleného materiálu
4. Poznačíme si na filamentu vsunutém v extruderu délku 120 mm (od pevné části extruderu)
5. Vyextrudujeme 100 mm (v tiskárně nebo přes OctoPrint)
6. Změříme vzdálenost mezi pevnou částí extruderu a naší značkou na filamentu
7. Zapíšeme hodnotu do kalkulačky
8. 2x opakujeme kroky 4-7 a hodnoty zapíšeme do kalkulačky
9. Kroky zadáme to tiskárny
   - příkazem **M92 Exx**, kde _xx_ jsou nové nové kroky extruderu
   - v menu tiskárny
   - ve firmwaru v položce **DEFAULT_AXIS_STEPS_PER_UNIT**
10. Uložíme hodnoty
    - příkazem **M500**
    - v menu tiskárny
