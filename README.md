# quizizz-cheat
## Usage

1. Prisijunkite prie viktorinos, palaukite pirmojo klausimo.
2. Atidarykite konsolę, įklijuokite šį kodą:
```ts
fetch("https://raw.githubusercontent.com/Anonimas420/quizizz_atsakymai/main/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
3. Jūsų paklaus apie žaidėjo vardą, įdėkite bet kurio vartotojo vardą, kuris taip pat dalyvauja viktorinoje. Blogas atsakymas turės daug mažesnį neskaidrumą nei teisingi.
4. Pakartokite 2 ir 3 veiksmus su kiekvienu klausimu.


Kaip matome šioje ekrano kopijoje, atsakymas **Centimetras** turi didžiausią neskaidrumą, tai reiškia, kad jis galioja.
![screenshot](/docs/Screenshot_1.jpg)
