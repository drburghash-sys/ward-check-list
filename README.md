# Consultant Ward Round

Mobile-first consultant surgical ward-round checklist, using the WardTrack color scheme and urgency-based sorting. The UI, printouts, and generated resident messages are in **English**. The app does not hard-code a team or group name.

## Features
- Patient overview: name, MRN, ward, room, bed, diagnosis, and color-coded priority.
- Custom ward creation in a modal, before room selection.
- Patient detail shows **only the consultant checklist**; choices: Reviewed, Action, N/A.
- One action-entry field under each review item, with an automatically consolidated resident action summary.
- WhatsApp draft now includes the patient's **name, MRN, ward, room, bed, diagnosis and action items**. The user must confirm before it opens; the app does not send automatically.
- Consultant checklist printing for a selected patient, plus blank A4 printable forms.
- Local-first PWA with offline caching and a premium application icon.

## GitHub Pages
In Settings > Pages choose Deploy from branch > `main` > `/(root)`. When enabled, the URL is https://drburghash-sys.github.io/ward-check-list/

## Important safety limitations
This is a **prototype** and not an authorized clinical record or an EHR. Patient data is stored in browser localStorage without encryption or synchronization and can be lost by clearing site data. Do not use for identifiable patients unless approved, secured and governed by the hospital's IT, privacy and clinical teams.

The WhatsApp draft **includes directly identifiable patient information**. Using an unapproved communication channel for these data may violate confidentiality policies or legal requirements. The app warns before opening WhatsApp; use only a hospital-approved secure channel. The team must document patient care and orders in the official clinical record and escalate urgent issues through approved routes.
