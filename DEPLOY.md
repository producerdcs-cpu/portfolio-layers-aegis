# Deploy completo — portfolio-layers-aegis

O repositório já contém README e Markdown.

## Para publicar a versão completa (HTML + assets)

O pacote completo está em:

`/home/workdir/artifacts/portfolio-layers-aegis/`

Contém:
- `index.html` (versão final com foto, logo, 3 QR Codes, seção Experiência)
- `portfolio-layers-aegis.md`
- `assets/` (dinoel-soares.jpg, logo-dcsproducer.jpg, qr-core-hub-aegis.jpg, qr-corpus-metarag.jpg, qr-whatsapp.png)

### Opção 1 — Upload via GitHub Web (mais rápido)
1. Abra https://github.com/producerdcs-cpu/portfolio-layers-aegis
2. Clique em **Add file** → **Upload files**
3. Arraste a pasta `assets/` e o arquivo `index.html`
4. Commit na branch `main`

### Opção 2 — Git local
```bash
git clone https://github.com/producerdcs-cpu/portfolio-layers-aegis.git
cd portfolio-layers-aegis
# copie o index.html e a pasta assets/ do artifacts
git add .
git commit -m "feat: HTML completo + assets de marca (foto, logo, QRs)"
git push origin main
```

### Depois no Vercel
Conecte o repositório `producerdcs-cpu/portfolio-layers-aegis` e faça o deploy.

---
Gate AEGIS · Brand Layer v1.0 final · 22 Nov 2026
