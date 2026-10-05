# Software Requirements Specification (útgáfa fyrir verkefni 2)
## Númer teymis og höfundar
Hópur 0, Ebba Þóra Hvannberg

## Heiti kerfis
Pöntunarkerkfi fyrir mötuneyti - Cafeteria Ordering System 

## 1. Inngangur

### 1.1 Gildissvið (Scope)
Pöntunarkerfið gerir starfsfólki fyrirtækis kleyft að panta mat úr mötuneyti og fá hann afhentan.
Seinna mun kerfið þróast yfir í að geta pantað mat frá veitingastöðum. Notendur eru starfsmenn fyrirtækis, sendlar, matráðar / kokkar og annað starfsfólk mötuneytisins

Meginmarkmið kerfisins er að með nýjum sjálfvirkum ferlum megi geri pantanir skilvirkari (hraðvirkari og með minni mannafla), og villufrírri. Markmið kerfisins er að draga úr sóun birgða. Markmið kerfisins er að veita notendum þjónustu til að panta 24/7 í staðinn fyrir frá 8-16
### 1.2 Tilvísanir
- IEEE 29148 staðall
- COS Vision & Scope (fyrirmynd) eða aðrar fyrirmyndir sem þið notið

## 2. Lýsing á hagsmunaaðilum og notendahópum
Hagsmunaaðilar skiptast í notendur, viðskiptavin og aðra hagsmunaaðila. Helstu notendahópar eru starfsmenn fyrirtækisins, starfsfólk mötuneytis og sendlar. Fyrirtækið sem rekur mötuneytið er viðskiptavinur.
Aðrir hagsmunaaðilar eru stjórnendur fyrirtækisins, öryggisstjóri fyrirtækisins, starfsfólk launadeildar, mannauðsdeild og vottunaraðilar fyrir grænar lausnir.
Sjá nánar hér [Hagsmunaaðilar](CONFLICTS.md)

## 3. Greining á mögulegum árekstrum og tillögu að úrlausnum

Eftirfarandi árekstrar voru greindir. Sjá nánar hér [Árekstrar og úrlausnir](CONFLICTS.md)

| Árekstur | Tillaga að úrlausn |
|---|---|
| **Afhending matar og félagsleg tengsl** | **Skapandi lausn:** Halda möguleikanum á afhendingu matar en styðja félagsleg tengsl starfsmanna með öðrum hætti, t.d. heimsóknum eða viðburðum milli deilda. |
| **Markmið um minni matarsóun** | **Samningaleið:** Fyrirtækið sem rekur mötuneytið og starfsfólk þess komast að sameiginlegri niðurstöðu um aðgerðir, m.a. að nýta forpantanir til að áætla fjölda skammta betur og fræða neytendur um matarsóun. |
| **Aðgengi kerfis utan afhendingartíma** | **Skapandi lausn:** Leyfa starfsmönnum að panta allan sólarhringinn en takmarka afhendingu við skilgreinda afhendingartíma. |
| **Innskráning á kiosk** | **Skapandi lausn:** Einfalda örugga innskráningu, t.d. með starfsmannakorti eða síma, tryggja útskráningu eftir notkun og takmarka aðgerðir sem eru í boði án innskráningar. |
| **Þátttaka launadeildar í kröfusöfnun** | **Samningaleið:** Semja um fáa og markvissa fundi með launadeild á tímum þegar álag er minna, þannig að nauðsynleg þekking fáist án óraunhæfs tímaálags. |



### 4. Vinnuferli 

Aðlögun á eldri lausn. Fyrstu drög af texta voru  skrifuð af höfundi. Yfirlestur, yfirferð á samræmi á milli skjala og útdráttur á lista voru gerð með aðstoð gervigreindar. 