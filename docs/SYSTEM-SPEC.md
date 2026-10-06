### 03 — Ajánlatkészítő rendszer

**Eredmény:** a konzultációból vagy igényből rendezett, ellenőrizhető és verziózott ajánlat készül.

**Bemenet:** jegyzet/ügyféligény, jóváhagyott szolgáltatások és árak, terjedelem, kizárások, ütemezés, érvényesség és fizetési feltételek. Hiányzó pénzügyi adat nem pótolható modellbecsléssel.

**MVP:** igénybevitel → AI terjedelemvázlat → szolgáltatássorok kézi kiválasztása → determinisztikus összegzés → szerkeszthető ajánlat → jóváhagyás → nyomtatható/PDF export → kézi küldésjelölés és emlékeztető. Az ajánlat sorai és exportja egyazon adatforrást használják.

**Ajánlatblokkok:** ügyféligény; elérendő eredmény; vállalt feladatok; ami nincs benne; ütemezés; díjak és feltételek; következő lépés. Határidő csak megadott vállalásból, különben tisztázandó.

**Képernyők:** ajánlatlista; input; szerkesztő előnézettel; változatok; tervezett követés. Állapotok: vázlat, hiányos, ellenőrzendő, jóváhagyott, elküldött, elfogadott, elutasított, lejárt. A PDF-export önmagában nem jelent elküldést vagy elfogadást.

**Bekötött verzió:** ellenőrzött e-mail-küldés, fogadóoldali válaszok, elfogadás emberi rögzítése. **Egyedi:** csomagvariációk, külön elektronikus aláíró integráció. Számlázás, adómegállapítás és szerződéses tanácsadás nem része.

**AI feladata:** megfogalmazás és scope-összerendezés. Az árakat, kedvezményt, adót és végösszeget kód számolja a felhasználó által megadott szabályokból. A pénznemek nem adódhatnak össze átváltási forrás nélkül.

**Mérés:** ajánlatelkészítési idő; kiküldött és elfogadott ajánlatok; terjedelemjavítások. Ajánlat értéke nem bevétel.

**Elfogadási esetek:** 03-A: 2×100 000 Ft + 50 000 Ft, megadott 0 adó → 250 000 Ft. 03-B: ismeretlen ár/adókezelés → hiányos, véglegesítés tiltva. 03-C: jóváhagyás után szöveg/ár változik → új jóváhagyás kell. 03-D: export és felület összege egyezik. 03-E: lejárt ajánlat nem indul automatikusan onboardingként.


Tényleges készültség: CAPABILITIES.md. A specifikáció nem készültségi állítás.
