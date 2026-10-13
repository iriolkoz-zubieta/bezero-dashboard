## Ariketa: Eman funtzionaltasuna Daylight dashboardari

Abiapuntuko fitxategian interfaze grafikoa eta osagai nagusiak prest daude: erlojua, focus timerra, todo zerrenda eta gai iluna/argia aldatzeko botoia. Zure lana da JavaScript erabiliz osagai horiei funtzionaltasuna ematea, diseinua aldatu gabe.

Erabili `index.html` fitxategia abiapuntu gisa. JavaScriptaren barruan `localStorage` erabiltzeko laguntza-funtzioak eta gako-izenak aurkituko dituzu.

### Egin beharrekoak

1. **Erlojua**
   - Uneko ordua etengabe erakutsi, segundo bakoitzean eguneratuta.
   - Data eta ordu-eremua ere erakutsi.
   - Uneko orduaren arabera, agurraren testua eguneratu.

2. **Focus timerra**
   - Erabiltzaileak minutuak eta segundoak ezarri ahal izan behar ditu.
   - **Start focus** botoiak atzerako kontaketa abiarazi behar du.
   - Abian dagoenean, botoiak gelditzeko edo pausatzeko aukera eman behar du.
   - **Reset** botoiak hasierako baliora itzuli behar du.
   - Kontaketa zerora iristean, egoera hori timerreko mezuan jakinarazi.
   - Saihestu balio baliogabeak: adibidez, segundoak 0 eta 59 artean egon behar dira.

3. **Todo zerrenda**
   - Ataza berriak gehitu formularioaren bidez; hutsik edo zuriune hutsez osatutako atazak ez dira onartu behar.
   - Atazak eginda markatu eta ezabatu ahal izan behar dira.
   - Erakutsi zenbat ataza dauden.
   - Atazen egoera eta zerrenda `localStorage`-n gorde, orria berriro irekitzean lehengo egoera berreskuratzeko.

4. **Gai aldaketa**
   - Botoiak gai argiaren eta ilunaren artean txandakatu behar du.
   - Hautatutako gaia `localStorage`-n gorde eta orria berriro irekitzean aplikatu.
   - Botoiaren ikonoak eta testuak uneko gaia adierazi behar dute.

### Baldintzak eta probak

- Erabili emandako HTMLko `id`-ak eta estiloak; ez berridatzi interfazea.
- Ez erabili zerbitzaririk edo kanpoko liburutegirik.
- Probatu funtzionaltasunak orria freskatuta eta nabigatzailea itxi eta berriro irekita ere.
- Egiaztatu diseinuak pantaila txikietan ondo jarraitzen duela.
- Mantendu kodea irakurgarria: banatu erlojuaren, timeraren, atazen eta gaiaren logika funtzio argietan.

**Amaierako emaitza:** dashboarda bisualki berdina izango da, baina osagai guztiek behar bezala funtzionatuko dute; atazak eta hautatutako gaia nabigatzailearen `localStorage`-n gordeko dira.