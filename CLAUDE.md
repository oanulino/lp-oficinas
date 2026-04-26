# Landing Page GA Ads — Para Oficinas

**URL:** `C:/Users/Gustavo Anulino/Desktop/Claudião/projects/lp-oficinas/`
**Status:** Ativo (git main branch — sem remote)
**Tipo:** HTML estático (single-page app)

## Estrutura da Página

1. **Nav** — Logo GA.Ads + CTA "Falar com Gustavo" (WhatsApp)
2. **Hero** — Tagline + proposta + CTA primária
3. **Seção Dor** — 4 pain points (dependência indicação, fluxo irregular, invisibilidade, ticket baixo)
4. **Método ADF** — 3 cards (Atração / Decisão / Faturar)
5. **Planos** — Prata (R$1.800) e Ouro (R$2.997) com features list
6. **Sobre** — Gustavo + números (50+ clientes, 3 anos, 90 dias)
7. **CTA Final** — "Bora colocar sua oficina no mapa de verdade?"
8. **Footer** — Links
9. **WhatsApp Flutuante** — Botão verde fixo no canto

## Design

- **Cores:**
  - Laranja (#f97316) — primária, CTAs
  - Preto (#0a0a0a) — backgrounds escuros (hero, planos)
  - Cinza (#f5f5f5) — backgrounds neutros
  - Verde (#22c55e) — checkmarks nos planos
  - Branco — texto, cards

- **Tipografia:** Inter (vários pesos)
- **Responsive:** Mobile-first (breakpoint 600px)
- **CSS:** Inline, sem dependências externas

## CTAs e Conversão

Todos os botões linkam pro WhatsApp do Gustavo — 12 98206-4549 — com mensagens pré-preenchidas diferentes por contexto:
- Nav: "Olá! Quero mais clientes..."
- Hero: "Quero parar de depender de indicação..."
- Plano Prata: "Tenho interesse no Plano Prata..."
- Plano Ouro: "Tenho interesse no Plano Ouro..."
- CTA Final: "Quero uma conversa para entender..."
- FloatingButton: "Vim pela LP e quero saber mais..."

## Próximas Melhorias Possíveis

- [ ] Integrar com Vercel (deploy automático)
- [ ] Adicionar tracking (GTM, pixel do Facebook)
- [ ] Form de email (em vez de WhatsApp direto)
- [ ] Imagem real do Gustavo (em vez de 👨‍💻)
- [ ] Depoimentos de clientes
- [ ] Video sobre o Método ADF
- [ ] FAQ
- [ ] Integrar com CRM pra qualificar leads
