# Bug Bounty Portfolio — Gustavo Okamoto (gugaokamoto1)

**Gustavo Okamoto (gugaokamoto1)**  
Pesquisador de segurança / bug bounty hunter — foco em auditoria de APIs, CORS, autorização e testes de lógica de negócio. Público: evidências redacted e metodologia reprodutível.

---

## Objetivo
Portfólio destinado a demonstrar habilidades práticas para vagas júnior em Cybersecurity (Application Security / API Security / Bug Bounty). Aqui eu documento relatórios e evidências redacted, sempre seguindo divulgação responsável.

---

## Conteúdo deste repositório
- `reports/` — relatórios individuais (POC minimizada + evidências redacted).  
- `evidence/` — capturas e arquivos de header (redacted).  
- `README.md` — este arquivo com objetivo e instruções de contato.

## Destaque (exemplo)
- **2025-09-25 — CORS Misconfiguration @ pixel.astrontracker.com.br** — Misconfiguration (Informative).  
  - Metodologia: DevTools → Sources → Network → copy-as-cURL → reproduzir via `curl` → evidências redacted.  
  - Resultado: política CORS permissiva (`Access-Control-Allow-Origin: *` + `Access-Control-Allow-Credentials: true`).  
  - Arquivos: `reports/2025-09-25-cors-pixel-astrontracker.md` (POC) e `evidence/*` (redacted).

---

## Metodologia (resumida)
1. Recon no front-end (DevTools → Sources / Network).  
2. Requisições reproduzíveis via `curl` / PowerShell (com placeholders).  
3. Capturas (DevTools → Headers, HAR) e redaction.  
4. Report claro: Resumo / Passos / Evidência / Recomendação.

---

## Skills demonstradas
- API testing (curl, PowerShell)  
- Front-end recon (DevTools Sources/Network)  
- CORS, CSRF awareness, IDOR testing methodology  
- Responsible disclosure / evidence redaction

---

## Contato profissional
- GitHub: https://github.com/gustavo89587  
- LinkedIn: https://linkedin.com/in/gustavo-okamoto-de-carvalho-ti
- Email: <gugaokamoto1@gmail.com>

---

## Nota sobre divulgação responsável
Evidências sensíveis foram redacted. Caso um time queira reprodução completa, fornecerei HAR ou logs **por canal seguro** após verificação.

