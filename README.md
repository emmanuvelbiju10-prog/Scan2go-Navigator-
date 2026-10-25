# Scan2go Navigator

Offline-first QR wayfinding web app for large institutions. First prototype: Government Engineering College, Idukki (Administration / Mechanical Engineering building, Workshops 1 and 2, and the 2nd floor).

Vishwakarma Awards 2026-27 | Application ID: VK26-AU-HCI-0100 | Track: HCI

## Team
Emmanuvel Biju (Captain), V M Sabarinath, Athul Sajay, Anjo Jose, Neeraj Dev K
Faculty mentor: Praveen Raja JR, Assistant Professor, Mechanical Engineering

## What is here
- `index.html` - the whole app in one file (maps, route data, voice clips and code).
- `maps/` - the campus map and the 2nd-floor plan the routes were drawn on.
- `audio-original/` - the 12 recorded voice clips (6 Malayalam, 6 English) before processing.
- `qr/` - QR code image. Regenerate it for the final hosted address.

## Status (honest)
Built: destination screen, 3 outdoor routes, 11 indoor destinations on the 2nd floor, step text, recorded Malayalam and English voice, mute and language switch, approximate GPS follow (calibrated from 4 field GPS pins).
Not built yet: offline caching (service worker), admin interface, other departments and floors, QR checkpoints, destination search box.
GPS follow has not yet been verified in the field: the preview host blocked location access. To be retested from the GitHub Pages address.

## Run it
Open `index.html` in Chrome. For GPS, serve it over https (for example GitHub Pages) because browsers block location on plain files.

## Host free on GitHub Pages
Repository Settings > Pages > Deploy from branch `main`, folder `/ (root)`. The address will be `https://<username>.github.io/<repository>/`.

## License
The source code is under the MIT License (see `LICENSE`). The campus map, floor plan, college photo and voice recordings are not covered by it.

## Credits and AI assistance
The concept, maps, GPS pins, voice recordings and field testing are by the team. The app code was written with help from Claude (an AI assistant by Anthropic). The QR images were generated with AI-assisted tools and are labelled AI Generated in the submission.
Campus map and floor plan: Government Engineering College Idukki. College photo: add the source here.
