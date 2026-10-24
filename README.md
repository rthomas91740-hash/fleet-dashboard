# fleet-dashboard

Static dashboard for Fleet Wolf clients. Reads only from Supabase (login required; row-level security decides what each person sees).

- `index.html`: the whole app (map, summary tiles, charts, truck table).
- `config.js`: Supabase URL and anon key. Both are public by design.
- Brand colors live in the `:root` block at the top of `index.html`.
- Data comes from the `dashboard_*` database functions (see the Supabase migrations).

Host on GitHub Pages (Settings > Pages > Deploy from branch `main`, folder `/`).
