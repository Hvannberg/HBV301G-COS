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
| ID  | Lýsing | Issue |
|-----|--------|-------|
| BR1 | [Lýsing á viðskiptakröfu] | [#12](../../issues/12) |
| BR2 | [Lýsing á viðskiptakröfu] | [#13](../../issues/13) |

### 3.2 Kerfiskrafa
| ID  | Lýsing | Issue |
|-----|--------|-------|
| SR1 | [Lýsing á kerfiskröfu] | [#14](../../issues/14) |

### 3.3 Fídusar (Features)
| ID  | Lýsing | Issue |
|-----|--------|-------|
| F1  | [Lýsing á fídusi] | [#15](../../issues/15) |
| F2  | [Lýsing á fídusi] | [#16](../../issues/16) |
| F3  | [Lýsing á fídusi] | [#17](../../issues/17) |

### 3.4 Notendakröfur
| ID  | Lýsing | Fídus | Issue |
|-----|--------|-------|-------|
| UR1 | [Notendakrafa 1] | F1 | [#18](../../issues/18) |
| UR2 | [Notendakrafa 2] | F1 | [#19](../../issues/19) |
| UR3 | [Notendakrafa 3] | F2 | [#20](../../issues/20) |
| UR4 | [Notendakrafa 4] | F2 | [#21](../../issues/21) |
| UR5 | [Notendakrafa 5] | F3 | [#22](../../issues/22) |
| UR6 | [Notendakrafa 6] | F3 | [#23](../../issues/23) |

### 3.5 Virknikröfur
| ID  | Lýsing | Notendakrafa | Issue |
|-----|--------|--------------|-------|
| FR1 | [Virkni sem styður notendakröfu] | UR1 | [#24](../../issues/24) |
| FR2 | [Önnur virkni] | UR1 | [#25](../../issues/25) |
| FR3 | [Önnur virkni] | UR1 | [#26](../../issues/26) |
| FR4 | [Virkni] | UR2 | [#27](../../issues/27) |
| FR5 | [Virkni] | UR2 | [#28](../../issues/28) |
| FR6 | [Virkni] | UR2 | [#29](../../issues/29) |
| FR7 | [Virkni] | UR3 | [#30](../../issues/30) |
| FR8 | [Virkni] | UR3 | [#31](../../issues/31) |
| FR9 | [Virkni] | UR3 | [#32](../../issues/32) |
| FR10 | [Virkni] | UR4 | [#33](../../issues/33) |
| FR11 | [Virkni] | UR4 | [#34](../../issues/34) |
| FR12 | [Virkni] | UR4 | [#35](../../issues/35) |
| FR13 | [Virkni] | UR5 | [#36](../../issues/36) |
| FR14 | [Virkni] | UR5 | [#37](../../issues/37) |
| FR15 | [Virkni] | UR5 | [#38](../../issues/38) |
| FR16 | [Virkni] | UR6 | [#39](../../issues/39) |
| FR17 | [Virkni] | UR6 | [#40](../../issues/40) |
| FR18 | [Virkni] | UR6 | [#41](../../issues/41) |

### 3.6 Viðskiptareglur
| ID  | Lýsing | Issue |
|-----|--------|-------|
| BRG1 | [Viðskiptaregla] | [#42](../../issues/42) |
| BRG2 | [Viðskiptaregla] | [#43](../../issues/43) |

### 3.7 Óvirknikröfur
| ID  | Lýsing | Issue |
|-----|--------|-------|
| NFR1 | [Óvirknikrafa] | [#44](../../issues/44) |
| NFR2 | [Óvirknikrafa] | [#45](../../issues/45) |
| NFR3 | [Óvirknikrafa] | [#46](../../issues/46) |
| NFR4 | [Óvirknikrafa] | [#47](../../issues/47) |
| NFR5 | [Óvirknikrafa] | [#48](../../issues/48) |
| NFR6 | [Óvirknikrafa] | [#49](../../issues/49) |

### 3.8 Gæðaeiginleikar
| ID  | Lýsing | Issue |
|-----|--------|-------|
| QR1 | [Gæðaeiginleiki] | [#50](../../issues/50) |
| QR2 | [Gæðaeiginleiki] | [#51](../../issues/51) |

### 3.9 Takmarkanir
| ID  | Lýsing | Issue |
|-----|--------|-------|
| C1 | [Takmörkun] | [#52](../../issues/52) |
| C2 | [Takmörkun] | [#53](../../issues/53) |

### 3.10 Ytri skil (Interfaces)
| ID  | Lýsing | Issue |
|-----|--------|-------|
| IF1 | [Ytra skil] | [#54](../../issues/54) |
| IF2 | [Ytra skil] | [#55](../../issues/55) |

---

## 4. Viðaukar
### 4.1 Orðalisti
- Skilgreina lykilhugtök.

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: ____________________
