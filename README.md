# Dr Vikash Dental – Website

Single-file website (HTML, CSS, vanilla JS) for Dr Vikash Dental, Gorakhpur.

## Files
- `index.html` – complete website
- `supabase/migrations/001_appointments.sql` – appointments table with RLS (public insert only)
- `netlify.toml` – Netlify config

## Deploy
1. Netlify: drag and drop this folder, or connect the Git repo.
2. Open the live URL and check images, booking form and WhatsApp.

## Edit
All editable values are at the top of the `<script>` in `index.html`:
- `IMG` – photo URLs (currently Pexels stock photos; replace with real clinic photos)
- `PHONE`, `INSTA` – WhatsApp number and Instagram link
- `HOURS` – weekly business hours
- `SB_URL`, `SB_KEY` – Supabase project URL and publishable key (never put a secret key here)

## Supabase
Run the SQL in `supabase/migrations/` once (already applied to project `nrcayfgpegbnqripakzp`).
View bookings in Supabase Dashboard > Table Editor > `appointments`.

## Notes
- Stock photos are temporary and are not photographs of the clinic.
- Doctor bio, qualifications and treatment availability must be confirmed by the clinic.
- Appointments are requests only; the clinic confirms them.
