# Design System: Portfolio Rifki Nur Fahrezi Ahmad

## Product Context
Portfolio pribadi developer untuk recruiter & calon klien. Konten: hero dengan foto profil, 4 pengalaman kerja (timeline), tech stack 3 kolom, 7 proyek klien (dengan screenshot), 13 sertifikat (thumbnail + PDF), kontak (email/GitHub/Instagram/WA). Bahasa Indonesia.

## Visual DNA (Linear-inspired)
- Background: #08090a (marketing black), panel #0f1011, surface #191a1b
- Text: #f7f8f8 primary, #d0d6e0 secondary, #8a8f98 muted, #62666d subtle
- Brand accent SATU-satunya: #5e6ad2 (indigo), hover #828fff
- Border: rgba(255,255,255,0.05) subtle, rgba(255,255,255,0.08) standard
- Font: Inter dengan font-feature-settings "cv01","ss03"; mono JetBrains Mono
- Weight: 400 (baca), 510 (emphasis/navigasi), 590 (announce). JANGAN pakai 700
- Letter-spacing: negatif agresif di display (-0.03em), normal di body
- Radius: 6px (button), 8px (input), 12px (panel/kartu)
- Elevation via background luminance steps (0.02 -> 0.04 -> 0.05), BUKAN shadow gelap

## Constraints
- Bahasa Indonesia semua UI copy
- Tanpa em-dash, tanpa gradient ungu generik, tanpa 3 kartu identik
- Foto profil asli: profile.jpeg. Screenshot proyek asli di projects/. Thumb sertifikat di certificates/thumbs/
- Responsive mobile-first, prefer-reduced-motion dihormati
