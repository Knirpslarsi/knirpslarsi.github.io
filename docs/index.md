---
layout: default
---

{% if site.maintenance %}
<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Wartungsmodus</title>
  <style>
    html,body{height:100%;margin:0}
    body{display:flex;align-items:center;justify-content:center;background:#0f172a;color:#e6edf3;font-family:Inter,system-ui,Segoe UI,Roboto,Arial,sans-serif}
    .card{text-align:center;padding:2rem;border-radius:12px}
    h1{font-size:2.25rem;margin:0 0 .5rem}
    p{margin:0;color:#cbd5e1}
  </style>
</head>
<body>
  <div class="card" role="main" aria-live="polite">
    <h1>Out of service</h1>
    <p>Work in progress — Seite wird gerade bearbeitet.</p>
  </div>
</body>
</html>
{% else %}
{% include original_index.html %}
{% endif %}