# KEST1VL - Tímaverkefni talnakerfi H22 (15%)

**Athugið að verkefnið er einstaklingsverkefni** ef tveir eða fleiri skila sömu lausninni verður gefið 0 (núll) fyrir allar þær lausnir.

## Talnakerfisbreytirinn

Skrifaðu forrit sem getur breytt tölum á milli tvíunda-, áttunda-, tuga- og sextándakerfisins. Dæmi um virkni:

![](https://gist.githubusercontent.com/gestskoli/2410275f6ec2feac7f95a959ae98227b/raw/537547383aefce119ae89ba87c3ce1b6dbd41ea4/KEST1VL_talnakerfi_H22.gif)

Notandi skal geta slegið inn streng eins t.d. `bin 10011 dec` og á þá forritið að breyta tvíundartölunni 10011 í tugakerfið og birta töluna á skjánum.

Notandi skal geta slegið inn orðið `hjálp` og fengið leiðbeiningar um notkun forritsins.

Ef notandi slær inn annað orð en `bin`, `oct`, `dec` eða `hex` á forritið að birta viðeigandi villuskilaboð og biðja notanda að reyna aftur.

Til að hætta í forritinu slær notandinn inn orðið `hætta`.

Reikna má með að notandinn slái alltaf inn tölu úr réttu talnakerfi.

### Að greina setningu í orð

```python
texti = "abc def ghi"

fyrsta_ordid = texti.split()[0]
# breytan fyrsta_ordid inniheldur abc
annad_ordid = texti.split()[1]
# breytan annad_ordid inniheldur def
thridja_ordid = texti.split()[2]
# breytan thridja_ordid inniheldur ghi
```

