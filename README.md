# Turnee Fotbal

Site pentru turnee de fotbal pentru copii: înscrierea școlilor, program, scoruri și clasament live.
Publicat pe https://turneefotbal.ro (GitHub Pages).

- `index.html` – aplicația (un singur fișier, fără pas de build)
- `vendor/supabase.js` – biblioteca supabase-js 2.117.3 (MIT)
- `fonts/`, `fonts.css` – fonturile Barlow (OFL), găzduite local
- Datele sunt într-un proiect Supabase separat; cheia din `index.html` este cheia publică (anon). Accesul îl hotărăsc regulile RLS din baza de date.
