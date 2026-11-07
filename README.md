# Purane 6 service pages — hours + 7-Day fix — Jacksonville Pressure Wash

## Kyun zaroori hai
Homepage aur 7 naye service pages par hours aur 7-Day Satisfaction Check live hain,
lekin purane 6 service pages par abhi bhi kuch nahi hai. Live check (7 Nov 2026,
~10:04 UTC) mein har purane page par "7-Day" 0 baar, "9:00 AM" 0 baar aur "Monday"
0 baar mila. Jo visitor homepage se in pages par jata hai, use hours aur guarantee
nazr nahi aati.

## Files (sirf 6 files upload karein — sitemap dobara nahi)
1. `house-washing.html`
2. `driveway-concrete-cleaning.html`
3. `sidewalk-patio-cleaning.html`
4. `roof-soft-washing.html`
5. `fence-deck-cleaning.html`
6. `paver-cleaning-sealing.html`

Update 7 Nov 2026, ~11:05 UTC: `sitemap.xml` is folder mein abhi bhi hai, lekin usko dobara upload karne ki zaroorat NAHI — user ne updated sitemap (17 URLs) pehle hi push kar diya hai aur live sitemap mein 17 links verify ho chuke hain. Is folder wali sitemap us se identical hai.

## Har page mein sirf 3 chhoti changes hain (baaki content bilkul waisa ka waisa)
1. Final CTA mein ye line add hui: "Working hours: Monday to Friday, 9:00 AM to
   4:00 PM Eastern Time. 7-Day Satisfaction Check: if a spot remains within 7 days,
   we will re-clean that spot free."
2. FAQ mein ek naya sawal add hua: "What are your working hours and guarantee?"
   — usi jawab ke saath, plus 24-hour reply.
3. Final CTA ka "Request a Quote" button ab `quote.html` par jata hai (pehle
   `./#contact` tha, jo koi page nahi hai — contact.html abhi bhi nahi bana).

Har page mein ab "7-Day" 2 baar aur "9:00 AM" 2 baar hai. Section tags balanced
hain, aur koi Licensed/Insured claim, fake review, fake photo ya price add nahi
hua — sab kuch user ke confirmed facts se hai (Mon–Fri 9:00 AM–4:00 PM ET;
7-Day Satisfaction Check).

## Upload kaise karein (wahi tareeqa, ek step at a time)
1. Ye 6 files VS Code project folder mein copy karke Replace karein (sitemap.xml dobara nahi).
2. Commit message: `Add hours and 7-day guarantee to 6 original service pages`
3. GitHub par push karein, phir Vercel par check karein ke naya deployment bana hai.
4. Test: kisi purane service page par jaa kar "7-Day" search karein, aur
   "Request a Quote" button dabaa kar dekhein ke quote.html khulta hai ya nahi.

## Jo abhi bhi baqi hai (is batch mein nahi)
- `service-areas.html` par bhi hours/guarantee nahi hain (live check mein 0 matches).
- About aur Contact ke alag pages abhi bhi nahi hain (nav/footer ke #about / #contact
  anchors waisi ki waisi hain) — ye agla kaam ho sakta hai, jab user chahe.
- Quote form: Step 1 mein service tick kiye baghair Next nahi khulta — ye form ka
  rule hai, kharabi nahi. Pehle service tick karein, phir Next dabayein.

Source: GitHub raw main (naziaseo/Pressure-Washing-Jacksonville), 7 Nov 2026.
Built from the live/GitHub source, not from memory.
