BY-7 Fuel Bunkering Calculator v60 - PWA Package
By N. Kalodoukas

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

Deployment:
1. Upload all files to the same folder in GitHub Pages or any HTTPS web server.
2. Open index.html from the published URL.
3. Chrome/Edge: menu -> Install app.
4. iPhone/iPad Safari: Share -> Add to Home Screen.

Note:
- PWA install/offline caching normally requires HTTPS or localhost.
- If opened directly from disk, the calculator can run, but service worker caching may not activate.

Header update: added signature line: Prepared by N. Kalodoukas — Chief Engineer / Electronics Engineer / Instructor.

Print update: Print / Save PDF is configured so each company form prints on a separate A4 landscape page.


Analytics update v60:
- Added Plausible Analytics script for kalodoukas.github.io.
- Added anonymous app_open event for BunkerReport_v57_CapeAkritas.
- Added anonymous events for calculate, add_to_report, export_xls, export_csv, print_pdf, save_json, load_json, clear_reports, install_pwa.
- The analytics block does not send names, emails, vessel names, tank data, quantities, measurements, densities, or any form-entered values.
- Browser, operating system, device type, country and page path are provided by the Plausible dashboard.

Header label fix: visible application header now shows v60.

Update v60.2: VS.TEC 015 BARGE READINGS tank measurement blank rows reduced by 3 rows (from 8 to 5).

Update v60.2.3:
- Protected/locked build regenerated.
- VS.TEC 015 BARGE READINGS blank tank rows remain reduced by 3 rows: 8 -> 5.
- app.js SHA-256 checksum recalculated and written to index.html.
- New checksum: 060a602df5709e638a3f72159d027090874ab26e53bf7adc0807fe8e2db5d993
