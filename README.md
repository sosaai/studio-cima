# Studio Cima — Sito web

Sito di **Studio Cima**, agenzia di marketing per ristoranti e attività ricettive della **Valtellina e Valchiavenna**.

🌐 **Online:** https://studio-cima.it

## Com'è fatto

Sito **statico** (HTML / CSS / JS) — nessun build necessario. Circa 30 pagine: home, chi siamo, servizi, blog, contatti e le landing SEO locali (`marketing-ristoranti-*`).

## Sviluppo in locale

Serve i file con un qualsiasi server statico, ad esempio:

```bash
python3 -m http.server 4555
# poi apri http://localhost:4555
```

## Come si pubblica (deploy)

L'hosting è su **Vercel**, collegato a questo repo GitHub.

> ⚡ Ogni `push` sul branch **`main`** va **online in automatico** su https://studio-cima.it — non serve fare altro.

Flusso di lavoro tipico:

```bash
git clone https://github.com/sosaai/studio-cima.git
cd studio-cima
# ...modifiche ai file...
git add -A
git commit -m "descrizione delle modifiche"
git push          # -> deploy automatico su studio-cima.it
```

Per scaricare le modifiche fatte dall'altro collaboratore: `git pull`.

## Contatti

- Tel / WhatsApp: +39 352 047 9947
- Email: info@studio-cima.it
