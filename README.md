# Paragon Quote Pipeline

Public page published by Netlify at https://paragonpipeco-pipeline.netlify.app.

`index.html` is the whole site. The pipeline data lives inside it in
`<script type="application/json" id="qp-data">…</script>` and is refreshed
by Michael's Project Desk scheduled task on weekday runs. Netlify redeploys on every push to `main`.
