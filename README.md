# 1C ScreenTime Insight — Static Full-Frontend Edition

A responsive, forest-inspired academic dashboard built with plain HTML, CSS and JavaScript. No framework, build step, API key, or paid service is required.

## Open on your Samsung tablet
1. Download and extract the ZIP file.
2. Open the extracted `1C_ScreenTime_Insight` folder in Acode or another HTML editor.
3. Open `index.html` and use Preview. If previewing locally is blocked, upload the files to the GitHub repository and enable GitHub Pages (Settings → Pages → Deploy from a branch → `main` → `/ (root)`).
4. Keep `index.html`, `styles.css`, and `app.js` in the same folder.

## Included modules
- Home dashboard and three-day comparison
- About Me profile editor, optional personal image, MARA logo and MRSM logo slots
- Discussion & Findings with interpretation and table
- Interactive Chart Gallery (line/bar/area) with PNG and CSV export
- Heatmap Studio (weekday values beyond the core three-day averages are illustrative placeholders)
- Class & Lab Layout Explorer with selectable seats and arrangement settings
- Feedback form and local discussion comments
- Nine theme presets, text sizing, light/dark appearance, compact density and local settings backup
- Admin Panel preview and local demo management
- Responsive navigation for mobile/tablet/desktop

## Important scope note
This is a **static frontend**, not a hosted multi-user backend. The research figures are simulated and labelled as such. Profile images, settings, comments and feedback are stored locally in the browser where storage allows; they are not shared with other users. There is no secure account authentication, server-enforced Student/Teacher/Admin role system, shared database, approval workflow, live notifications, email delivery, or remote backup in this package. Those require a backend and security rules. The Admin Panel explicitly describes this limitation rather than pretending those features are live.

## Image and branding slots
Upload your profile photo and optional MARA/MRSM logos on About Me. Use only images you have permission to use. They remain on the device/browser unless you separately commit image files into the public repository.

## Data values
- Friday mean: 5.37 hours
- Saturday mean: 8.33 hours
- Sunday mean: 8.49 hours

These values are simulated examples for educational demonstration, not verified measurements from real students. Heatmap values for days beyond Friday–Sunday are illustrative visual placeholders.


## Demo login and OTP
The updated edition includes an interactive sign-in screen, role selection, a six-digit simulated OTP step, resend-code action, session persistence, and logout. For this static demo, enter any non-empty username/email and any non-empty demo password; the OTP is displayed on-screen. **It is not sent by email or SMS and is not secure authentication.** Anyone can inspect or alter client-side JavaScript on a public GitHub Pages site. Do not use real passwords or private data. Secure accounts and real OTP delivery require a backend authentication provider and server-side role permissions.

## Interaction scope
This is still a static browser-only website. Theme, chart, heatmap, seating, profile, export, and local feedback interactions run in the browser. They do not create shared accounts or server-side data. Some language labels are preference-only and not every page is fully translated.

## Class Research Hub update
- Added a presenter mode with five navigable slides for classroom display.
- Added a class interpretation poll and reflection/exit-ticket capture.
- Polls and reflections are currently stored only in this browser. They do **not** appear on classmates' devices. Multi-device participation requires a shared database/backend (a free-tier service such as Supabase may be suitable, subject to its current limits and setup).
- Heatmap intensity and label controls now persist locally and reset to defaults; reduced-motion preference now changes animation behavior. The language selector currently records the preference but does not fully translate every page.
- Classroom layout selections are visual planning aids and do not represent real student data.
- Demo OTP is generated in the browser and shown on screen. It is not sent by email/SMS and is not secure authentication.
