# Changelog

Heartbeat uses version numbers in the form major.minor.patch. The current version is also shown at the bottom of the app's Help page.

## 1.4.0 (26 November 2026)
- "Doctor's target" is now "Recommended target". The app works out a home blood pressure target from the person's age and ticked health conditions (high blood pressure, diabetes, kidney disease, heart disease, stroke, frailty).
- Under 80: 120–129/70–79. From 80, or frail: top number 130–144. No number under 18 or in pregnancy.
- Follows the Danish Society of Cardiology guideline (NBV chapter 27, revised May 2026), which matches the 2024 European (ESC) guideline. Sources are listed under Help.
- A personal target from your own doctor can still be entered, and is used instead.

## 1.3.0 (25 November 2026)
- Optional PIN lock per person, set in Edit details. Only a salted hash of the PIN is stored.
- The app locks again after 2 minutes in the background, and when you switch person.
- After 5 wrong PINs, you must wait 30 seconds.
- The emergency note at the bottom of the page now names the selected country.

## 1.2.0 (25 November 2026)
- New logo, remembers the last person, works offline.

## 1.1.0 (25 November 2026)
- Logo, mind and sleep activities, country-first guidance sources, licence, code fixes.

## 1.0.0 (25 November 2026)
- First standalone web app on GitHub Pages.
