Vite pakendustööriista peale ehitatud projekt
===============================

Vite (prantsuse sõna "kiire") on ehitustööriist,
mille eesmärk on pakkuda kaasaegsetele veebiprojektidele kiiremat
ja kergemat arenduskogemust. Kui esbuild keskendub ehitamise etapile
ja Snowpack keskendub arendusserverile, siis pakub Vite mõlemat -
nii täielikku arendusserverit, kui ka optimeeritud ehitamise käsurida,
kasutades selleks Rollup’i. Vite koosneb kahest suurest osast:

- Arendusserver, mis pakub rikkalikke funktsioonide täiustusi võrreldes kohalike ES -moodulitega, näiteks Hot Module Replacement (HMR).

- Ehitamise käsurida, mis komplekteerib koodi Rollup’iga ja on eelkonfigureeritud tootmiseks, et väga optimeeritud staatilisi faile väljastada.


## Projekti taust

Seoses KILP 2021 tehniliste töödega on vaja ressursside halduse
front-end arenduse stacki uuendada ja üle minna vanadelt
tehnoloogiatelt uutele.

Lisaks Reacti uuendamisele on vaja üle minna ka kaasaegsele
ehitus- ja pakendustööriistale.


- [Nõuded ehitus- ja pakendustööriistale](#nõuded-ehitus--ja-pakendustööriistale)
- [Kuidas kasutada](#kuidas-kasutada)


## Nõuded ehitus- ja pakendustööriistale

### 1. Kuidas mõjutab arenduse kiirust?
Ehitamise protsessi kiirus, Hot Module Replacement.

### 2. Peab toetama:

- React
- JSX
- TypeScript
- SCSS (ka CSS mooduleid)

### 3. Peab olema võimalikult lihtsalt konfigureeritav.

### 4. Lisavõimalused (tuleviku arendusi silmas pidades):

- Tree shaking
- Code splitting
- Automaatne formattimine (eslint, Prettier)


## Kuidas kasutada

Ehitamiseks 
```
npm run build
```

Jooksutamiseks

```
npm run start
```

Juurdepääs ```http://localhost:3000```
