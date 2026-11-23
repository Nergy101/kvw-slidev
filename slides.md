---
theme: default
title: 'KVW De Meern — Ruimte!'
info: |
  KinderVakantieWeek De Meern — thema Ruimte
  Presentatie voor kinderen van 4 t/m 12 jaar.
class: text-center
highlighter: shiki
lineNumbers: false
css: unocss
---


---
layout: center
class: text-center
transition: fade
---

<div class="nebula" style="--c1: rgba(238,143,32,.16); --c2: rgba(45,76,155,.4); --c3: rgba(100,179,51,.14);"></div>
<div class="warp"></div>
<img src="/assets/kvw-logo.svg" class="w-[30rem] max-w-[80%] mx-auto float-slow relative" />

<div class="text-4xl mt-10 relative"><span class="title-gradient font-bold pulse-glow">Thema: RUIMTE!</span> 🚀🌌</div>
<div class="text-xl mt-4 opacity-80 relative">Een week vol avonturen, spelletjes, sport en knutselen!</div>

<img src="/assets/star.svg" class="twinkle-img absolute w-10" style="top: 12%; left: 12%;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-8" style="top: 20%; right: 14%; animation-delay: .9s;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-12" style="bottom: 14%; right: 10%; animation-delay: 1.6s;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-7" style="bottom: 20%; left: 16%; animation-delay: .4s;" />
<div class="shooting" style="top: 30%; animation-delay: 2s;"></div>
<div class="shooting" style="top: 65%; animation-delay: 5.5s;"></div>

<!--
Hoofdslide met het officiële KVW De Meern-logo (kvwdemeern.nl) + warp-ring.
-->

---

# 🚀 KVW De Meern

## <span class="title-gradient pulse-glow">THEMA: RUIMTE!</span> 🌌

<img src="/assets/galaxy.svg" class="spin-slow absolute w-72 opacity-70" style="top: 8%; right: 6%;" />
<img src="/assets/rocket.svg" class="float absolute w-40" style="bottom: 10%; left: 8%;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-10" style="top: 18%; left: 22%;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-7" style="bottom: 24%; right: 20%; animation-delay: 1.2s;" />
<div class="shooting" style="top: 45%; animation-delay: 3s;"></div>

<div class="mt-10 text-xl opacity-80" v-motion :initial="{ y: 30, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 400 } }">Reis mee door het heelal!</div>

<!--
Welkom bij de KVW! Vraag de kinderen: wie is er wel eens naar de maan geweest? (grapje!)
-->

---
transition: slide-left
---

# 👋 Welkom astronauten!

<div class="nebula" style="--c1: rgba(52,211,153,.22); --c2: rgba(59,130,246,.25);"></div>
<img src="/assets/star.svg" class="twinkle-img absolute w-12" style="top: 12%; right: 10%;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-8" style="bottom: 14%; left: 8%; animation-delay: .8s;" />

Wat gaan we doen?

<div class="grid grid-cols-2 gap-8 mt-8 text-2xl text-left w-3/4 mx-auto">
<div v-motion :initial="{ x: -80, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 100 } }">🔭 Sterren kijken</div>
<div v-motion :initial="{ x: -80, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 250 } }">🪐 Planeten ontdekken</div>
<div v-motion :initial="{ x: 80, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 400 } }">🚀 Een raket lanceren</div>
<div v-motion :initial="{ x: 80, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 550 } }">🎮 Groepsspelletjes</div>
<div v-motion :initial="{ y: 40, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 700 } }">🎨 Ruimte knutselen</div>
<div v-motion :initial="{ y: 40, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 850 } }">🏆 Quiz & diploma</div>
</div>

---
transition: slide-up
---

# 🤔 Wat is de ruimte eigenlijk?

<div class="nebula" style="--c1: rgba(139,92,246,.4); --c2: rgba(236,72,153,.25); --c3: rgba(59,130,246,.2);"></div>
<div class="shooting" style="top: 20%; animation-delay: 1s;"></div>

<div class="text-3xl mt-10 space-y-8 relative">
<div v-motion :initial="{ scale: 0.6, opacity: 0 }" :enter="{ scale: 1, opacity: 1, transition: { delay: 150 } }">✨ Alles boven de dampkring van de aarde</div>
<div v-motion :initial="{ scale: 0.6, opacity: 0 }" :enter="{ scale: 1, opacity: 1, transition: { delay: 400 } }">🌍 Daar zweven planeten, manen en sterren</div>
<div v-motion :initial="{ scale: 0.6, opacity: 0 }" :enter="{ scale: 1, opacity: 1, transition: { delay: 650 } }">🕳️ En er is <span class="text-yellow-300 font-bold">helemaal geen lucht</span> — dus geen geluid!</div>
</div>

<!--
In de ruimte hoor je niks, want geluid heeft lucht nodig om te reizen.
-->

---
transition: zoom
---

# ☀️ Eerst: onze eigen ster

## De <span class="title-gradient pulse-glow">Zon</span>

<div class="nebula" style="--c1: rgba(251,191,36,.3); --c2: rgba(249,115,22,.25);"></div>
<div class="absolute" style="top: 16%; right: 8%;">
  <div class="sun-pulse w-56 h-56" style="top: 0; left: 0;"></div>
  <img src="/assets/sun.svg" class="float w-56 relative" />
</div>

<div class="text-left text-2xl space-y-4 mt-6 w-3/5">
<div v-motion :initial="{ x: -60, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 150 } }">🔥 Een enorme, hete bal gas</div>
<div v-motion :initial="{ x: -60, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 350 } }">📏 109× zo groot als de aarde</div>
<div v-motion :initial="{ x: -60, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 550 } }">🌡️ 15 miljoen graden in het midden!</div>
<div v-motion :initial="{ x: -60, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 750 } }">💡 Zonder zon geen leven op aarde</div>
</div>

<!--
De zon is een ster, net als alle andere sterren aan de hemel — alleen staat hij heel dichtbij.
-->

---
transition: slide-left
---

# 🪐 De 8 planeten

<div class="nebula" style="--c1: rgba(59,130,246,.3); --c2: rgba(139,92,246,.3);"></div>
<img src="/assets/saturn.svg" class="float-slow absolute w-52 opacity-90" style="top: 6%; right: 4%;" />
<img src="/assets/earth.svg" class="float absolute w-20 opacity-90" style="bottom: 8%; right: 12%;" />

<div class="text-2xl mt-4 space-y-2 text-left w-3/4">
<div v-click>☿️ Mercurius — <span class="opacity-70">klein en snel</span></div>
<div v-click>♀️ Venus — <span class="opacity-70">heet en wolkendek</span></div>
<div v-click>🌍 Aarde — <span class="opacity-70">onze thuis!</span></div>
<div v-click>🔴 Mars — <span class="opacity-70">de rode planeet</span></div>
<div v-click>🟠 Jupiter — <span class="opacity-70">de grootste, met de Grote Rode Vlek</span></div>
<div v-click>🪐 Saturnus — <span class="opacity-70">met zijn prachtige ringen</span></div>
<div v-click>🔵 Uranus — <span class="opacity-70">ligt op zijn kant</span></div>
<div v-click>🔷 Neptunus — <span class="opacity-70">de verste, winderige planeet</span></div>
</div>

<!--
Ezelsbruggetje: Mijn Vriendin Anke Maakt Jam Sandwiches Under Nette Pannen
-->

---
transition: slide-up
---

# 🌍 Onze aarde

<div class="nebula" style="--c1: rgba(34,197,94,.25); --c2: rgba(59,130,246,.35);"></div>

<div class="absolute" style="top: 50%; right: 6%; transform: translateY(-50%);">
  <div class="relative inline-block">
    <img src="/assets/earth.svg" class="float w-64" />
    <div class="orbit-ring"><img src="/assets/moon.svg" /></div>
  </div>
</div>

<div class="text-left text-2xl space-y-5 mt-8 w-3/5">
<div v-click>💧 71% water — de blauwe planeet</div>
<div v-click>🌱 De enige planeet waarvan we weten dat er leven is</div>
<div v-click>🌙 Met één trouwe maan die om ons heen cirkelt!</div>
</div>

---
transition: fade
---

# 🌕 De maan

<div class="nebula" style="--c1: rgba(203,213,225,.22); --c2: rgba(99,102,241,.3);"></div>
<div class="absolute" style="top: 50%; right: 7%; transform: translateY(-50%);">
  <img src="/assets/moon.svg" class="float-slow w-60" />
</div>

<div class="text-5xl mt-6">
<span class="twinkle-img inline-block">🌕</span>
<span class="twinkle-img inline-block" style="animation-delay:.3s">🌖</span>
<span class="twinkle-img inline-block" style="animation-delay:.6s">🌗</span>
<span class="twinkle-img inline-block" style="animation-delay:.9s">🌘</span>
<span class="twinkle-img inline-block" style="animation-delay:1.2s">🌑</span>
<span class="twinkle-img inline-block" style="animation-delay:1.5s">🌒</span>
<span class="twinkle-img inline-block" style="animation-delay:1.8s">🌓</span>
<span class="twinkle-img inline-block" style="animation-delay:2.1s">🌔</span>
</div>

<div class="text-2xl mt-8 space-y-5 text-left w-3/5">
<div v-click>🚶 384.400 km van de aarde vandaan</div>
<div v-click>⏱️ Draait in ongeveer een maand om de aarde</div>
<div v-click>👨‍🚀 In 1969 liepen mensen voor het eerst op de maan!</div>
</div>

<!--
Laat de kinderen de maanfases met hun handen nadoen.
-->

---
transition: slide-left
---

# ⭐ Sterren en sterrenbeelden

<div class="nebula" style="--c1: rgba(250,204,21,.2); --c2: rgba(139,92,246,.35);"></div>
<img src="/assets/star.svg" class="twinkle-img absolute w-14" style="top: 14%; left: 10%;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-9" style="top: 30%; right: 14%; animation-delay: .6s;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-11" style="bottom: 16%; left: 18%; animation-delay: 1.1s;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-7" style="bottom: 30%; right: 8%; animation-delay: 1.7s;" />
<div class="shooting" style="top: 55%; animation-delay: 4s;"></div>

<div class="text-2xl mt-10 space-y-6">
<div v-click>⭐ Een ster is een enorme hete gasbol, net als de zon</div>
<div v-click>🦁 Sterrenbeelden: Leeuw, Grote Beer, Orion…</div>
<div v-click>🔭 Met een telescoop zie je er miljoenen!</div>
</div>

<!--
Vraag: wie kent het sterrenbeeld de Grote Beer (de steelpan)?
-->

---
transition: zoom
---

# 🕳️ Zwarte gaten

<div class="nebula" style="--c1: rgba(88,28,135,.5); --c2: rgba(249,115,22,.25); --c3: rgba(56,189,248,.15);"></div>

<div class="flex items-center justify-center gap-16 mt-6">
  <div class="blackhole float-slow"></div>
  <div class="text-left text-2xl space-y-5 w-2/5">
    <div v-motion :initial="{ x: 80, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 200 } }">🕳️ Een plek waar de zwaartekracht héél sterk is</div>
    <div v-motion :initial="{ x: 80, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 450 } }">💫 Alles wat te dichtbij komt, wordt opgeslokt</div>
    <div v-motion :initial="{ x: 80, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 700 } }">✨ Zelfs licht kan niet ontsnappen!</div>
  </div>
</div>

<!--
In het midden van ons melkwegstelsel zit een superzwaar zwart gat: Sagittarius A*.
-->

---
transition: slide-up
---

# 🛰️ Satellieten

<div class="nebula" style="--c1: rgba(56,189,248,.25); --c2: rgba(99,102,241,.3);"></div>
<div class="absolute" style="top: 50%; right: 5%; transform: translateY(-50%);">
  <img src="/assets/satellite.svg" class="float w-72" />
</div>

<div class="text-left text-2xl space-y-5 mt-8 w-3/5">
<div v-click>📡 Zweven om de aarde in een baan</div>
<div v-click>📺 Zorgen voor tv, internet en gps</div>
<div v-click>🌦️ Maken foto's van het weer</div>
<div v-click>🛰️ Er zweven er al meer dan 10.000!</div>
</div>

---
transition: zoom
---

# 🚀 TELLEN MAAR: de raketlancering!

<div class="nebula" style="--c1: rgba(249,115,22,.3); --c2: rgba(239,68,68,.22); --c3: rgba(253,224,71,.15);"></div>
<img v-click src="/assets/rocket.svg" class="launch absolute w-52" style="bottom: 6%; left: 6%;" />

<div class="text-center relative">
<div class="text-7xl font-bold mt-14">
<span v-click class="bounce inline-block">3...</span>
<span v-click class="bounce inline-block">2...</span>
<span v-click class="bounce inline-block">1...</span>
<span v-click class="pop text-orange-400 inline-block" style="text-shadow: 0 0 34px rgba(251,146,60,.9);">LIFTOFF! 🎉</span>
</div>
</div>

<!--
Tel samen met de hele groep af — bij LIFTOFF vliegt de raket het scherm uit!
-->

---
transition: slide-left
---

# 👨‍🚀 Word astronaut!

<div class="nebula" style="--c1: rgba(56,189,248,.28); --c2: rgba(34,197,94,.2);"></div>
<div class="absolute" style="top: 50%; right: 6%; transform: translateY(-50%);">
  <img src="/assets/astronaut.svg" class="float w-60" />
</div>

Wat moet je daarvoor kunnen?

<div class="text-2xl mt-8 space-y-5 text-left w-3/5">
<div v-click>💪 Sterk en gezond zijn</div>
<div v-click>📚 Goed leren (wiskunde, Engels, techniek)</div>
<div v-click>🤝 Goed samenwerken in een team</div>
<div v-click>😄 En een beetje durven!</div>
</div>

<!--
Nederlandse astronauten: André Kuipers — en wie weet straks een van de kinderen zelf!
-->

---
transition: slide-up
---

# ❓ Ruimte-quiz!

<div class="nebula" style="--c1: rgba(163,230,53,.2); --c2: rgba(139,92,246,.3);"></div>
<div class="absolute" style="top: 50%; right: 8%; transform: translateY(-50%);">
  <img src="/assets/alien.svg" class="wiggle w-48" />
</div>

<div class="text-2xl mt-6 space-y-6 text-left w-3/4">
<div v-click class="bounce">1️⃣ Hoeveel planeten draaien om de zon? <span class="text-yellow-300 font-bold">(8)</span></div>
<div v-click class="bounce">2️⃣ Hoe heet de rode planeet? <span class="text-yellow-300 font-bold">(Mars)</span></div>
<div v-click class="bounce">3️⃣ Kun je in de ruimte geluid horen? <span class="text-yellow-300 font-bold">(Nee!)</span></div>
<div v-click class="bounce">4️⃣ Welke planeet heeft ringen? <span class="text-yellow-300 font-bold">(Saturnus)</span></div>
</div>

<!--
Laat de kinderen hun hand opsteken bij elk antwoord. Prijzen voor de winnaars!
-->

---
transition: slide-up
---

# 🎮 Spelletjestijd!

<div class="nebula" style="--c1: rgba(52,211,153,.28); --c2: rgba(249,115,22,.22); --c3: rgba(139,92,246,.2);"></div>
<img src="/assets/ufo.svg" class="float-slow absolute w-56" style="top: 8%; right: 6%;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-10" style="bottom: 12%; left: 8%;" />

Welke spellen spelen we met de hele groep?

<div class="text-2xl mt-8 space-y-4 text-left w-4/5">
<div v-motion :initial="{ x: -100, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 100 } }">🚀 1. Ballonraket-race</div>
<div v-motion :initial="{ x: -100, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 220 } }">🌕 2. Maanwandeling-estafette</div>
<div v-motion :initial="{ x: -100, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 340 } }">☄️ 3. Meteorieten-inslag</div>
<div v-motion :initial="{ x: -100, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 460 } }">🪐 4. Planeet-rondje (stopdans)</div>
<div v-motion :initial="{ x: -100, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 580 } }">🧑‍🚀 5. Astronautentraining-parcours</div>
<div v-motion :initial="{ x: -100, opacity: 0 }" :enter="{ x: 0, opacity: 1, transition: { delay: 700 } }">🛸 6. Ruimteschip redden</div>
</div>

---
transition: slide-left
---

# Spel 1: Ballonraket-race 🚀

<div class="nebula" style="--c1: rgba(249,115,22,.3); --c2: rgba(239,68,68,.2);"></div>
<img src="/assets/rocket.svg" class="float-fast absolute w-40" style="bottom: 8%; right: 8%;" />

**Zo werkt het:**

<div class="text-xl mt-4 space-y-3 text-left w-4/5">
<div v-click>1️⃣ Maak groepjes van 4–5 kinderen</div>
<div v-click>2️⃣ Span een lange draad; schuif een rietje erdoorheen</div>
<div v-click>3️⃣ Plak een opgeblazen ballon aan het rietje en laat los!</div>
<div v-click>4️⃣ Welke raket haalt als eerste de maan (finish)? 🌕</div>
</div>

<div class="mt-6 text-lg opacity-80" v-click>👥 8–20 kinderen · ⏱️ 15–20 min · 🎒 rietjes, ballonnen, draad, tape</div>

---
transition: slide-up
---

# Spel 2: Maanwandeling-estafette 🌕

<div class="nebula" style="--c1: rgba(203,213,225,.22); --c2: rgba(99,102,241,.3);"></div>
<img src="/assets/moon.svg" class="float absolute w-44" style="top: 12%; right: 8%;" />

**Zo werkt het:**

<div class="text-xl mt-4 space-y-3 text-left w-4/5">
<div v-click>1️⃣ Verdeel de groep in 2 teams bij een start- en maanlijn</div>
<div v-click>2️⃣ Spring in een zak (of met voeten aan elkaar gebonden) naar de maan</div>
<div v-click>3️⃣ Tik de volgende teamgenoot aan en ga terug</div>
<div v-click>4️⃣ Variant: neem een "maansteen" (bal) mee op een lepel!</div>
</div>

<div class="mt-6 text-lg opacity-80" v-click>👥 6–24 kinderen · ⏱️ 10–15 min · 🎒 zakken of doeken, bal, lepels</div>

---
transition: zoom
---

# Spel 3: Meteorieten-inslag ☄️

<div class="nebula" style="--c1: rgba(239,68,68,.25); --c2: rgba(250,204,21,.22);"></div>
<img src="/assets/star.svg" class="twinkle-img absolute w-12" style="top: 14%; right: 10%;" />
<img src="/assets/star.svg" class="twinkle-img absolute w-8" style="bottom: 16%; left: 10%; animation-delay: 1s;" />
<div class="shooting" style="top: 40%; animation-delay: 2.5s;"></div>

**Zo werkt het:**

<div class="text-xl mt-4 space-y-3 text-left w-4/5">
<div v-click>1️⃣ Zet 3 kraters neer: 10, 20 en 50 punten (hoe kleiner, hoe meer punten)</div>
<div v-click>2️⃣ Teams gooien om de beurt met zachte "meteorieten"</div>
<div v-click>3️⃣ Tel de punten per team op een scorebord</div>
<div v-click>4️⃣ Team met de meeste punten wint! 🏆</div>
</div>

<div class="mt-6 text-lg opacity-80" v-click>👥 6–20 kinderen · ⏱️ 15 min · 🎒 3 kratten/doeken, zachte ballen of pittenzakjes, scorebord</div>

---
transition: slide-left
---

# Spel 4: Planeet-rondje 🪐

<div class="nebula" style="--c1: rgba(139,92,246,.35); --c2: rgba(59,130,246,.3);"></div>
<img src="/assets/saturn.svg" class="float absolute w-44 opacity-90" style="bottom: 8%; right: 6%;" />

**Zo werkt het (stopdans in de ruimte):**

<div class="text-xl mt-4 space-y-3 text-left w-4/5">
<div v-click>1️⃣ Zet een kegel neer als de <b>zon</b> in het midden</div>
<div v-click>2️⃣ Terwijl de muziek draait, "draaien" de planeten (kinderen) rond de zon</div>
<div v-click>3️⃣ Muziek stopt → iedereen bevriest als zijn planeet!</div>
<div v-click>4️⃣ Wie beweegt, is af — of: wie het langst stilstaat wint</div>
</div>

<div class="mt-6 text-lg opacity-80" v-click>👥 10–30 kinderen · ⏱️ 10–15 min · 🎒 muziekbox, kegel als zon</div>

---
transition: slide-up
---

# Spel 5: Astronautentraining-parcours 🧑‍🚀

<div class="nebula" style="--c1: rgba(56,189,248,.28); --c2: rgba(52,211,153,.22);"></div>
<img src="/assets/astronaut.svg" class="float absolute w-44" style="top: 10%; right: 8%;" />

**Zo werkt het:**

<div class="text-xl mt-4 space-y-3 text-left w-4/5">
<div v-click>1️⃣ Kruipt onder de <b>laserstralen</b> (crêpepapier)</div>
<div v-click>2️⃣ Spring over de <b>maankraters</b> (hoepels)</div>
<div v-click>3️⃣ Slalom tussen de <b>planeten</b> (pionnen)</div>
<div v-click>4️⃣ Gooi als laatste een meteoriet in de krater!</div>
</div>

<div class="mt-6 text-lg opacity-80" v-click>👥 1 per keer of estafette · ⏱️ 20 min · 🎒 crêpepapier, hoepels, pionnen, zachte bal, stopwatch</div>

---
transition: zoom
---

# Spel 6: Ruimteschip redden 🛸

<div class="nebula" style="--c1: rgba(244,114,182,.28); --c2: rgba(99,102,241,.3);"></div>
<img src="/assets/ufo.svg" class="float absolute w-52" style="top: 8%; right: 6%;" />

**Zo werkt het (teamwork!):**

<div class="text-xl mt-4 space-y-3 text-left w-4/5">
<div v-click>1️⃣ De hele groep staat op "ruimte-eilanden" (kranten)</div>
<div v-click>2️⃣ De vloer is de ruimte — aanraken = game over!</div>
<div v-click>3️⃣ Telkens valt er een meteoriet: een eiland verdwijnt</div>
<div v-click>4️⃣ Blijf met z'n allen op de overgebleven eilanden staan — hoera! 🎉</div>
</div>

<div class="mt-6 text-lg opacity-80" v-click>👥 8–20 kinderen · ⏱️ 10–15 min · 🎒 krantenpapier per kind</div>

---
transition: fade
---

# 🎨 Knutseltijd: maak je eigen planeet!

<div class="nebula" style="--c1: rgba(244,114,182,.28); --c2: rgba(56,189,248,.25);"></div>
<img src="/assets/ufo.svg" class="ufo-fly absolute w-40" style="top: 12%;" />
<img src="/assets/saturn.svg" class="float absolute w-36 opacity-90" style="bottom: 8%; left: 6%;" />

<div class="text-2xl mt-10 space-y-6 relative">
<div v-click>🖌️ Schilder een planeet op een ballon of papier-maché bol</div>
<div v-click>⭐ Plak sterren op zwart papier</div>
<div v-click>🚀 Knutsel een raket van een wc-rol</div>
</div>

---
transition: zoom
---

# 🏆 Gefeliciteerd, ruimte-helden!

<div class="nebula" style="--c1: rgba(250,204,21,.3); --c2: rgba(249,115,22,.25);"></div>
<div class="confetti">
  <span style="left:5%;  background:#f472b6; animation-duration:3.2s;"></span>
  <span style="left:12%; background:#fde68a; animation-duration:2.7s; animation-delay:.4s;"></span>
  <span style="left:20%; background:#34d399; animation-duration:3.6s; animation-delay:.9s;"></span>
  <span style="left:28%; background:#60a5fa; animation-duration:2.9s; animation-delay:.2s;"></span>
  <span style="left:36%; background:#f87171; animation-duration:3.4s; animation-delay:1.1s;"></span>
  <span style="left:44%; background:#a78bfa; animation-duration:2.6s; animation-delay:.6s;"></span>
  <span style="left:52%; background:#fde68a; animation-duration:3.8s; animation-delay:.1s;"></span>
  <span style="left:60%; background:#4ade80; animation-duration:3s;   animation-delay:1.3s;"></span>
  <span style="left:68%; background:#f472b6; animation-duration:2.8s; animation-delay:.5s;"></span>
  <span style="left:76%; background:#60a5fa; animation-duration:3.5s; animation-delay:.8s;"></span>
  <span style="left:84%; background:#f87171; animation-duration:3.1s; animation-delay:.3s;"></span>
  <span style="left:92%; background:#a78bfa; animation-duration:2.9s; animation-delay:1s;"></span>
</div>
<img src="/assets/trophy.svg" class="float absolute w-48 mx-auto mt-4 left-0 right-0" />

## Jullie krijgen allemaal een <span class="title-gradient pulse-glow">Ruimte-Diploma</span>!

<div class="text-2xl mt-6" v-click>
Bedankt voor het meereizen — en wie weet zien we elkaar <span class="text-yellow-300 font-bold">ooit in het echt, in de ruimte!</span> ✨
</div>

---
transition: slide-left
---

# 🌌 Tot ziens, astronauten!

<div class="nebula" style="--c1: rgba(139,92,246,.4); --c2: rgba(59,130,246,.35); --c3: rgba(236,72,153,.2);"></div>
<div class="absolute w-80 opacity-60" style="top: 50%; left: 50%; transform: translate(-50%, -50%);">
  <img src="/assets/galaxy.svg" class="spin-slow w-full" />
</div>
<img src="/assets/rocket.svg" class="float absolute w-28" style="top: 12%; right: 12%;" />
<div class="shooting" style="top: 25%; animation-delay: 1.5s;"></div>
<div class="shooting" style="top: 70%; animation-delay: 4.5s;"></div>

<div class="text-7xl mt-16 relative">
<span class="twinkle-img inline-block">👋</span>
<span class="twinkle-img inline-block" style="animation-delay:.5s">🚀</span>
<span class="twinkle-img inline-block" style="animation-delay:1s">🌟</span>
</div>

<div class="text-2xl mt-8 opacity-80 relative">KVW De Meern — Thema Ruimte</div>

<!--
Sluit af met een liedje over de ruimte of een groepsfoto.
-->
