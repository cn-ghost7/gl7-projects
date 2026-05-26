# gl7-projects

Hub público de entregáveis HTML da **Ghost Lab7** — briefings, gestão de criativos, reports e documentos renderáveis no browser. Servido via **GitHub Pages**.

> **Estrutura:** 1 pasta por cliente. Arquivos seguem nomenclatura `YYYY-MM-DD_[MARCA]_[canal]_<slug>.html`.

## Como acessar

URL pública base:

```
https://cn-ghost7.github.io/gl7-projects/
```

Cada documento tem URL própria. Exemplo:

```
https://cn-ghost7.github.io/gl7-projects/ph-praia/2026-05-26_PH-PRAIA_meta_gestao-criativos-inverno26.html
```

## Como publicar um novo briefing

1. Criar pasta do cliente se não existir (`bota-cucina/`, `olv/`, `sup/`, `ita-fogo/`, `ldo/`, etc)
2. Adicionar HTML seguindo a convenção `YYYY-MM-DD_[MARCA]_[canal]_<slug>.html`
3. `git add` + `git commit` + `git push`
4. Aguardar 30-60s — GitHub Pages republica automaticamente
5. Compartilhar a URL pública

## O que NÃO commitar aqui

Repo é **público**. Nunca subir:

- ❌ Tokens, API keys, credenciais
- ❌ Account IDs / customer IDs de clientes em texto puro (`act_xxx`, customer ids)
- ❌ E-mails, telefones, CPF, dados pessoais
- ❌ Dados financeiros internos GL7 (margens, custos, faturamento)
- ❌ Captures de painéis com dados ainda não-aprovados pra ver externo

✅ OK: copy aprovado, briefings já validados com o cliente, materiais que iriam pra WhatsApp/email do cliente de qualquer forma.

## Convenção de nomenclatura

```
YYYY-MM-DD_[MARCA-EM-UPPER]_[canal-em-lower]_<slug-kebab-case>.html
```

Exemplos válidos:
- `2026-05-26_PH-PRAIA_meta_gestao-criativos-inverno26.html`
- `2026-06-12_BOTA-CUCINA_google-ads_audit-q2.html`
- `2026-07-01_OLV_seo_plano-conteudo-jul26.html`

Canais aceitos: `meta`, `google-ads`, `ga4`, `gtm`, `seo`, `email`, `crm`, `landing`.

## Autoria

GL7 Performance · Celso Netto (Head of Performance) + Claudiney 🪐 (AI co-pilot)
