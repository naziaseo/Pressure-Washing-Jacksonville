# Image Size Attributes — Screaming Frog batch 4, LAST batch (14 Nov 2026)

## Kya theek kiya gaya
25 image tags mein width/height add ki gayi hai (7 files). Is se page
load hote waqt photos ki jagah pehle se reserve ho jati hai aur page
"jump" nahi karta (layout shift khatam). Photos ki dikhne wali size
mein koi farq nahi aayega — CSS wahi hai.

Files: index.html (4 tags), house-washing.html (3), driveway (3),
sidewalk (3), roof (6), fence (3), paver (3). Har file mein sirf
<img> wali lines badli hain — aur kuch nahi.

## Upload steps (ek hi push)
1. Zip ko extract karein.
2. 7 HTML files ko project folder (site name) mein copy karke REPLACE
   karein — files seedha root mein daalein, kisi subfolder mein nahi.
3. VS Code mein Source Control se commit + push karein.
4. Muse ko batayein — wo live check kar ke confirm karegi.

## Iske baad
Screaming Frog ke saare issues theek ho jayenge. Phir dobara
Screaming Frog crawl kar ke dekh sakte hain — sirf "Multiple H2s"
reh jayega jo koi masla nahi hai.
