# Screaming Frog Fixes — 2 High Issues (14 Nov 2026)

## Kya theek kiya gaya

### 1. Missing `<body>` tag — 4 live pages + paver
Driveway, Sidewalk, Roof aur Fence pages mein `<body>` khulne wala tag
ghaib tha (file `</head>` ke baad seedha `<header>` se shuru hoti thi).
Har file mein sirf 1 line add ki gayi hai: `</head>` ke baad `<body>`.
Koi aur change nahi hai. Paver wali file mein bhi yehi fix hai.

### 2. 404 images — 3 roof specimen photos
Roof page ki FIELD GUIDE quiz wali 3 photos server par nahi thin
(404): algae.jpg, lichen.jpg, moss.jpg. Ye 3 photos is zip mein
compressed hain (1920px -> 800px, ~3MB -> ~450kB total).

## Upload steps (ek hi push)

1. Zip ko extract karein.
2. 5 HTML files ko project folder (site name) mein copy karke REPLACE
   karein: driveway-concrete-cleaning.html, sidewalk-patio-cleaning.html,
   roof-soft-washing.html, fence-deck-cleaning.html,
   paver-cleaning-sealing.html
   - NOTE: paver wali file abhi live nahi hai — ye fixed copy rakh lein,
     jab review kar ke upload karein to yehi wali use karein.
3. 3 JPGs ko is folder mein copy karein:
   assets/images/roof-guide/algae.jpg
   assets/images/roof-guide/lichen.jpg
   assets/images/roof-guide/moss.jpg
   (agar roof-guide folder na ho to bana lein)
4. VS Code mein Source Control se commit + push karein.
5. Muse ko batayein — wo live check kar ke confirm karegi.

## Baaki issues (agle batch mein)
- 12 page titles 60 characters se lambe hain — shorten karne hain.
- 16 images 100 kB se bari hain — compress karni hain.
- 12 images mein width/height nahi hai — add karna hai.
- Screen Enclosure wali 1 H2 78 characters ki hai — shorten karni hai.
- Multiple H2s aur CSP header koi masla nahi hain — fix ki zaroorat nahi.
