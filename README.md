# CSS Version Fix - 15 pages (service heroes ko live dikhane ke liye)

Asal masla: service pages abhi bhi `styles.css?v=20261106-gallery` load kar rahe the.
Browser ne us purane link wali CSS ko 1 saal ke liye save kar rakha hai, is liye nayi CSS
(paint roller hatane wali fix) un pages par lag hi nahi rahi thi. Homepage par fix aa gaya
tha kyunki index.html mein naya version tha, lekin service pages par purana version tha.

Fix: in 15 files mein CSS version `?v=20261108-service-heroes` kar diya hai, taake
browser nayi CSS fresh load kare. Sirf version badla hai - text, hours, 7-Day sab waisa hi hai.
Saath mein service-areas.html aur quote.html ki hero photo bhi theek kar di hai
(dono par bhi paint roller wali purani photo lagi thi):
- service-areas.html -> driveway-concrete.jpg
- quote.html -> house-washing.jpg

## Upload karne ka tareeqa
1. Is folder ki 15 HTML files ko project ke root folder mein copy karke replace karein.
2. Commit karein: "Load fresh styles on all service pages"
3. Push karein. Phir mujhe batayein, main live check kar dungi.

Note: index.html aur styles.css pehle hi push ho chuke hain, unko dobara upload karne ki
zaroorat NAHI hai. Photos bhi pehle hi upload ho chuki hain.
