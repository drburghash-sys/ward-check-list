# Ward Round · Group A

Mobile-first surgical consultant ward round checklist with WardTrack-inspired colors and urgency sorting.

## Features
- Ward-by-ward list showing patient name, number, ward, room/bed, diagnosis and priority only.
- Custom ward creation in a pop-up placed before the room field.
- Per-patient **consultant checklist only** with statuses reviewed / action / not applicable and an action-entry field below each item.
- Live action totals, combined summary and WhatsApp draft for assigned resident (never auto-sent).
- Print an individual consultant checklist or a blank A4 checklist.
- Local offline-capable PWA for phones.

## Publish with GitHub Pages
In the repository select **Settings > Pages > Deploy from a branch > main / (root)**. 
Expected site address once enabled: https://drburghash-sys.github.io/ward-check-list/

## Safety and limitations
This is a **pilot/demo**, not a clinical EHR system. Data is stored only in browser localStorage, **unencrypted and unsynchronized**, and can be lost when browser data is cleared. Do not enter identifiable real patient details without hospital IT and governance approval. Do not send clinical details through WhatsApp unless this use and channel are approved by your hospital. WhatsApp messages can be identifiable even if the app omits names and MRNs. Clinical orders and progress notes must be entered in the approved EHR. Urgent clinical escalation must use approved direct-contact processes.
