# 📄 Software Requirements Specification (SRS)

## 1. Inngangur
### 1.1 Tilgangur
Meginmarkmið kerfisins er að með nýjum sjálfvirkum ferlum megi geri pantanir skilvirkari (hraðvirkari og með minni mannafla), og 
villufrírri. Markmið kerfisins er að veita notendum þjónustu til að panta 24/7 í staðinn fyrir frá 8-16. Í núverandi kerfi eyða starfmenn umtalsverðum tíma
í að fara í mötuneytið, velja, panta, bíða eftir matnum og greiða fyrir hann. Að meðaltali tekur það um 65 mínútur. Sumir starfsmenn hringja inn pöntun í síma. Umtalsverðar birgðir fara til spillis. 
Þegar starfsmenn borða út í bæ tekur það allt að 90 mínútur. 


### 1.2 Umfang
Kerfið á að senda inn pantanir í mötuneyti, afgreiða pantanir, afhenda pantanir og útbúa matseðla

### 1.3 Skilgreiningar
| Hugtak | Skýring |
|--------|---------|
| SRS | Software Requirements Specification |
| Issue | Umræða/atriði í GitHub sem tengist ákveðinni kröfu |

### 1.4 Tilvísanir
- [ISO/IEC/IEEE International Standard - Systems and software engineering -- Life cycle processes -- Requirements engineering," in ISO/IEC/IEEE 29148:2018(E) , vol., no., pp.1-104, 30 Nov. 2018, doi: 10.1109/IEEESTD.2018.8559686.ISO/IEC/IEEE 29](https://ieeexplore.ieee.org/document/8559686)
- Cafeteria and Ordering System, Wiegers & Beatty 

---

## 2. Almenn lýsing
### 2.1 Notendahópar
Helstu notenahópar eru eftirfarandi 
-  Starfsmenn, velja af matseðli, panta matinn, greiða fyrir matinn og fá hann afhentan. Pöntunin fer fram á innra netinu. Stundum pantar starfsfólk mat fyrir viðburði fyrir
   hópa starfsmanna og eða gesti 
-  Starfsfólk í mötuneyti afgreiðir pöntun úr kerfinu, eldar matinn, pakkar honum inn og sendir inn beiðni um afhendingu 
-  Sendlar fá beiðni um afhendingu pantana í app í síma. Sendlar ná í matinn úr mötuneyti og afhenda starfsmönnum 
-  Matreiðslufólk útbýr matseðla  og bjóða einnig upp á rétt dagsins. Ekki verður hægt að bjóða upp á alla rétti til að borða utan mötuneytis (take a way)

### 2.2 Viðskiptaávinningur
- Starfsmenn eyða minni tíma í að panta mat,greiða fyrir hann og fá hann afhentan. 
- Starfsfólk í mötuneyti eyðir minni tíma í að taka við pöntunum, t.d. í síma. 
- Minni sóun á matarbirgðum 
- Sendlar geta stytt tímann með því að safna saman pöntunum á deildir eða byggingar fyrirtækisins. 
---

## 3. Kröfur fyrir kerfið

### 3.1 Viðskiptakröfur
| ID  | Lýsing                                                                    | Issue                                                   |
|-----|---------------------------------------------------------------------------|---------------------------------------------------------|
| BR1 | [Lækka kostnað vegna matarúrgangs í mötuneyti um 40% innan 6 mánaða]      | [#1](https://github.com/Hvannberg/HBV301G-COS/issues/1) |
| BR2 | [Auka meðal raunvinnutíma starfsmanns sem notar mötuneytið um 15 mínútur] | [#2](https://github.com/Hvannberg/HBV301G-COS/issues/2) |

### 3.2 Kerfiskrafa
| ID  | Lýsing | Issue                                                   |
|-----|--------|---------------------------------------------------------|
| SR1 | [Notendaviðmót kerfisins er á vef, snjallsíma og kiosk] | [#9](https://github.com/Hvannberg/HBV301G-COS/issues/9) |

### 3.3 Fídusar (Features)
| ID  | Lýsing | Issue                                                     |
|-----|--------|-----------------------------------------------------------|
| F1  | [Búa til, skoða, breyta og hætta við máltíðaáskriftir fyrir fastar eða endurteknar máltíðapantanir eða fyrir daglegar sérmáltíðir] | [#10](https://github.com/Hvannberg/HBV301G-COS/issues/10) |
| F2  | [Panta og greiða fyrir máltíðir frá veitingastöðum sem verða afhentar] | [#11](https://github.com/Hvannberg/HBV301G-COS/issues/11) |
| F3  | [Panta og greiða fyrir máltíðir frá matseðli í mötuneyti] | [#12](https://github.com/Hvannberg/HBV301G-COS/issues/12) |

### 3.4 Notendakröfur
| ID  | Lýsing          | Fídus | Issue                                                    |
|-----|-----------------|-------|----------------------------------------------------------|
| UR1 |   Viðskiptavinur fær aðgang að pöntunarkerfi mötuneytisins úr innraneti fyrirtækisins, skoðar matseðla, velur, pantar máltíð sem á að senda              | F3    | [#13](https://github.com/Hvannberg/HBV301G-COS/issues/13) |
| UR2 |                 |       |                                                          |
| UR3 |                 |       |                                                          |
| UR4 |                 |       |                                                          |
| UR5 |                 |       |                                                          |
| UR6 |                 |       |                                                          |


### 3.5 Virknikröfur
| ID   | Lýsing          | Notendakröfur | Issue                                                   |
|------|-----------------|---------------|---------------------------------------------------------|
| FR1  | [Panta máltíð] | UR1           |  [#16](https://github.com/Hvannberg/HBV301G-COS/issues/16)
| FR2  | [Önnur virkni]  | UR1           | [#]() |
| FR3  | [Önnur virkni]  | UR1           | [#](../../issues/26)                                  |
| FR4  | [Virkni]        | UR2           | [#](../../issues/27)                                  |
| FR5  | [Virkni]        | UR2           | [#](../../issues/28)                                  |
| FR6  | [Virkni]        | UR2           | [#](../../issues/29)                                  |
| FR7  | [Virkni]        | UR3           | [#](../../issues/30)                                  |
| FR8  | [Virkni]        | UR3           | [#](../../issues/31)                                  |
| FR9  | [Virkni]        | UR3           | [#](../../issues/32)                                  |
| FR10 | [Virkni]        | UR4           | [#](../../issues/33)                                  |
| FR11 | [Virkni]        | UR4           | [#](../../issues/34)                                  |
| FR12 | [Virkni]        | UR4           | [#](../../issues/35)                                  |
| FR13 | [Virkni]        | UR5           | [#](../../issues/36)                                  |
| FR14 | [Virkni]        | UR5           | [#](../../issues/37)                                  |
| FR15 | [Virkni]        | UR5           | [#](../../issues/38)                                  |
| FR16 | [Virkni]        | UR6           | [#](../../issues/39)                                  |
| FR17 | [Virkni]        | UR6           | [#](../../issues/40)                                  |
| FR18 | [Virkni]        | UR6           | [#](../../issues/41)                                  |

### 3.6 Viðskiptareglur
| ID  | Lýsing | Issue                                                   |
|-----|--------|---------------------------------------------------------|
| BRG1 | [Afhendingagluggi er 15 mínútur] | [#3](https://github.com/Hvannberg/HBV301G-COS/issues/3) |
| BRG2 | [Verð fyrir pöntun] | [#4](https://github.com/Hvannberg/HBV301G-COS/issues/4) |


### 3.7 Gæðaeiginleikar
| ID  | Lýsing | Issue                                                     |
|-----|--------|-----------------------------------------------------------|
| QR1 | [95% nýrra notenda skulu geta pantað máltíð án villna í fyrstu tilraun.] | [#15](https://github.com/Hvannberg/HBV301G-COS/issues/15) |
| QR2 | [Fjölda notenda, samtímis notendur á háannatíma og meðaltími lotu #Gæðaeiginleiki] | [#18](https://github.com/Hvannberg/HBV301G-COS/issues/18) |
| QR3 | [Notendur skulu skrá sig inn á COS til að framkvæma allar aðgerðir nema til að skoða valmynd] |  [#19](https://github.com/Hvannberg/HBV301G-COS/issues/19)
### 3.8 Takmarkanir
| ID  | Lýsing | Issue                                                   |
|-----|--------|---------------------------------------------------------|
| C1 | [Oracle gagnagrunnur] | [#5](https://github.com/Hvannberg/HBV301G-COS/issues/5) |
| C2 | [Viðkvæm gögn skulu dulkóðuð með 256-birta dulritun] | [#6](https://github.com/Hvannberg/HBV301G-COS/issues/6) |

### 3.9 Ytri skil (Interfaces)
| ID  | Lýsing | Issue                                                   |
|-----|--------|---------------------------------------------------------|
| IF1 | [Tenging við launakerfið] | [#7](https://github.com/Hvannberg/HBV301G-COS/issues/7) |
| IF2 | [Tengingar við eigið pöntunarkerfi mötuneytis] | [#8](https://github.com/Hvannberg/HBV301G-COS/issues/8) |

---

## 4. Viðaukar
### 4.1 Orðalisti
- Skilgreina lykilhugtök.
- Máltíð
- Pöntun
- Launakerfi
- Áskrift
- Mötuneyti
- Pöntunarkerfi
- Afhendingagluggi
- Frestur 
- 
- TODO - gera töflu

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: ____________________
