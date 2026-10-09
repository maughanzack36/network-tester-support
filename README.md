# Network Tester public support website

Static privacy and support pages for iOS/macOS. Only this directory’s public files belong
in the separate network-tester-support GitHub repository; never copy app source, backend
configuration, credentials, logs or project data. No build dependencies or analytics.

Preview: python3 -m http.server 8765 --directory Website (from the app checkout).
Edit privacy/index.html, support/index.html and style.css, review factual changes, then
publish those website files to the separate repository’s main branch. GitHub Pages serves
the main branch root. App URLs must remain stable.

Owner review before App Store submission: confirm provider log/backup retention, support
inbox monitoring, legal publisher identity, privacy labels and production deletion behavior.
Apple sign-in is not described as available until enabled and tested.
