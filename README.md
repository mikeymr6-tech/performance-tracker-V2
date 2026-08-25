# AWS Performance Tracker — Clean Rebuild

This is a ground-up rebuild of the iPhone PWA.

Important:
- The app ALWAYS starts on the passwordless login screen on a new install/browser.
- Name and email are mandatory.
- After a shift is started, the current shift is intentionally remembered in local storage so refreshing the page does not erase the tally.
- There is an explicit "END SHIFT WITHOUT PDF / START OVER" control to clear the session.
- The nine metrics are large two-column buttons.
- Each tap adds exactly one tally.
- A minus button is available for corrections.
- End Shift opens a confirmation sheet and then the iPhone print/save flow for the PDF.
- The All-Weather Seal logo appears in the app and the printed report.
- Service worker cache is versioned so this rebuild can replace the previous broken cached version.

Upload these files to the root of the existing GitHub Pages repository, replacing the old index.html, manifest, sw.js, and logo.
