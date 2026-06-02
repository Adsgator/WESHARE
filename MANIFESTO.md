> **Como usar:** Abra o Claude Code na raiz do projeto clonado e cole o prompt abaixo seguido do conteúdo deste arquivo.

**Prompt para o Claude Code:**
```
Você está implementando o site do cliente Renato Rosa do Nascimento (segmento: Escritórios Compartilhados, Endereço Fiscal).
Leia este documento do início ao fim antes de começar. Depois siga passo a passo:

1. Preencha `src/styles/tokens.css` com as cores da seção "Direção de Arte" (apenas os valores — os nomes são fixos)
2. Atualize o `<link>` de fonte serifada no `BaseLayout.astro` conforme a tipografia indicada
3. Preencha `src/pages/index.astro` com imports dos componentes e ordem das seções
4. Para cada seção, substitua os textos placeholder pela copy indicada neste documento
5. Preencha `.env` com WhatsApp, GTM e domínio — o template já lê essas variáveis
6. Preencha o `defaultSchema` no `BaseLayout.astro` com os dados do Schema.org
7. Preencha os TODOs em `politica-de-privacidade.astro` e `termos-de-uso.astro` com dados reais
8. Garanta: Hero com `id="hero-section"`, Footer com `id="footer"`, main com `id="main-content"`
9. Rode `npm run build` para validar — corrija qualquer erro antes de considerar pronto

Regras absolutas:
- NUNCA hardcode cor, fonte ou tamanho — sempre `var(--t-*)` ou classes utilitárias Tailwind
- `<Image />` do Astro, nunca `<img>` nativo
- Sem `any` no TypeScript, sem `!important` no CSS
- Tema padrão: claro (padrão)
```

---

# Documento do Projeto — Renato Rosa do Nascimento
**Studio:** Astroteca Studio
**Gerado em:** 02/06/2026
**Segmento:** Escritórios Compartilhados, Endereço Fiscal
**Tipo:** servico

---

## Briefing do Cliente

| Campo | Valor |
|-------|-------|
| Nome do cliente | Renato Rosa do Nascimento |
| Nome da marca | WeShare Escritórios Compartilhados |
| Segmento | Escritórios Compartilhados, Endereço Fiscal |
| Tipo de negócio | servico |
| Proposta de valor | Uma estrutura completa a serviço do seu negócio. |
| Domínio | wesharescritorios.com.br |
| WhatsApp | 5512982710971 |
| Email | contato@wesharescritorios.com.br |
| Horários | 24 horas por dia, 7 dias por semana |
| Instagram | https://www.instagram.com/wesharescritorios |
| Objetivo de conversão | Captar clientes para o serviço de endereço fiscal e comercial, e para locação dos espaços físicos (escritório privativo, sala de reunião, escritório compartilhado). |
| GTM ID |  GTM-NJMWCS39 |
| Schema tipo | LocalBusiness |
| Serviço principal | Endereço Fiscal e Comercial |
| Público primário | Profissionais e empreendedores que buscam um espaço para sediar reuniões e eventos, trabalhar de forma individual ou compartilhada, e empresas que precisam de um endereço fiscal e comercial de prestígio. |
| Resultado esperado | Agilidade no atendimento, espaço sempre limpo, internet de qualidade, ambiente reservado e salas confortáveis e sóbrias. No serviço de endereço fiscal, o cliente posiciona sua empresa na melhor região do Jardim Aquárius, transmitindo status e confiança. |
| Frase de impacto | Nosso diferencial é a exclusividade: clientes utilizam nosso espaço como se dele fosse, um compartilhamento do meu próprio escritório. |
| Diferencial | Serviço de autoatendimento, exclusividade na utilização de um escritório completo sem associação explícita a coworking, ambiente mais reservado que proporciona maior sentimento de pertencimento. |
| Google nota | 5 |
| Google avaliações | 54 |

### História / Sobre

Temos recebido bons feedbacks do nosso modelo de negócio, com alguns compartilhados no Google, destacando a eficácia e satisfação dos clientes.

### FAQ

Faz um faq mais genérico usando o que temos de informação, só não inventa nada

### Planos e Preços

**Endereço Fiscal e Comercial:** R$ 119,90/mês
Incluso gestão de correspondência e 20% de desconto na reserva do espaço físico.



---

## Estrutura da Página

### 1. Header

| Campo | Texto |
|-------|-------|
| logoAlt | WeShare Escritórios Compartilhados |
| ctaTexto | Fale pelo WhatsApp |
| ctaUrl | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| logo | WeShare Escritórios Compartilhados |
| menu_item_1 | Serviços |
| menu_item_2 | Como Funciona |
| menu_item_3 | Preços |
| menu_item_4 | Localização |

### 2. Hero

| Campo | Texto |
|-------|-------|
| titulo | Seu CNPJ com endereço de prestígio no Jardim Aquárius |
| subtitulo | Registre ou transfira sua empresa por R$ 119,90 por mês. Documentação liberada no mesmo dia da assinatura, sem prazo de fidelidade e com gestão de correspondência inclusa. |
| ctaTexto | Quero meu endereço fiscal agora |
| ctaUrl | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| ctaSecundarioTexto | (12) 98271-0971 |
| servico1Titulo | Documentação imediata para abertura ou transferência de CNPJ |
| servico2Titulo | Gestão de correspondência inclusa no plano |
| servico3Titulo | Sem prazo de fidelidade. Cancele com 30 dias de aviso. |

### 3. Serviços

| Campo | Texto |
|-------|-------|
| titulo | O espaço certo para cada momento do seu negócio |
| subtitulo | De um endereço fiscal com prestígio a uma sala para a reunião mais importante do mês. Tudo no mesmo lugar. |
| servio_1_nome | Endereço Fiscal e Comercial |
| servio_1_badge | Mais contratado |
| servio_1_descrio | Posicione sua empresa na melhor região de São José dos Campos. Documentação liberada no mesmo dia para abertura ou transferência de CNPJ, gestão de correspondência inclusa e 20% de desconto em qualquer reserva de sala física. |
| servio_1_cta | Contratar agora |
| servio_1_cta_url | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| servio_2_nome | Escritório Privativo |
| servio_2_descrio | Sala planejada para atender clientes ou trabalhar sozinho com total privacidade. Ambiente climatizado, café expresso, água mineral e impressora colorida inclusos no valor da reserva. |
| servio_2_cta | Reservar agora |
| servio_2_cta_url | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| servio_3_nome | Sala de Reunião |
| servio_3_descrio | Espaço para até 7 pessoas com smart TV, flip-chart, iluminação natural e vista da cidade. O ambiente certo para apresentações e negociações que precisam causar boa impressão. |
| servio_3_cta | Reservar agora |
| servio_3_cta_url | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| servio_4_nome | Escritório Compartilhado |
| servio_4_descrio | Três estações de trabalho em ambiente climatizado. Café expresso, água mineral e impressora colorida inclusos. Para quem precisa de um espaço produtivo sem o custo de um escritório fixo. |
| servio_4_cta | Reservar agora |
| servio_4_cta_url | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |

### 4. Como Funciona

| Campo | Texto |
|-------|-------|
| titulo | Do primeiro contato ao acesso, tudo pelo seu celular |
| subtitulo | Sem filas, sem burocracia e sem depender de horário comercial. Reserve, pague e use quando quiser. |
| passo_1_ttulo | Fale pelo WhatsApp |
| passo_1_descrio | Escolha o serviço, tire suas dúvidas e faça a reserva direto pelo WhatsApp. Atendimento ágil e sem enrolação. |
| passo_2_ttulo | Confirme o pagamento |
| passo_2_descrio | Após a confirmação do pagamento, seu cadastro é feito na recepção do prédio e tudo fica pronto para o seu acesso. |
| passo_3_ttulo | Acesse quando quiser |
| passo_3_descrio | Você recebe um código exclusivo de entrada. O espaço funciona 24 horas por dia, 7 dias por semana. Acesse e use como se fosse seu. |
| cta_final | Falar agora e reservar meu espaço |
| ctaUrl | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |

### 5. Diferenciais

| Campo | Texto |
|-------|-------|
| titulo | Você não aluga uma mesa num coworking. Você usa um escritório completo. |
| subtitulo | Aqui não há filas na impressora, sala lotada nem ambiente de feira. É o espaço do Renato, compartilhado com quem realmente precisa de estrutura profissional. |
| diferencial_1_ttulo | Autoatendimento 24 horas por dia |
| diferencial_1_descrio | Acesse o espaço a qualquer hora sem depender de recepcionista ou horário de atendimento. Seu código de acesso é gerado logo após a confirmação do pagamento. |
| diferencial_2_ttulo | Ambiente reservado e sóbrio |
| diferencial_2_descrio | Sem o barulho típico de coworking cheio. Um espaço discreto, climatizado e organizado que transmite profissionalismo para quem entra pela primeira vez. |
| diferencial_3_ttulo | Endereço no bairro certo |
| diferencial_3_descrio | O Jardim Aquárius é a região mais valorizada de São José dos Campos. Sua empresa registrada aqui já comunica credibilidade antes mesmo de você abrir a boca. |
| diferencial_4_ttulo | Tudo incluso, sem surpresa na fatura |
| diferencial_4_descrio | Café expresso, água mineral, impressora colorida, Wi-Fi de qualidade e ambiente climatizado. Nada cobrado à parte. O que está na reserva é o que você paga. |

### 6. Preços

| Campo | Texto |
|-------|-------|
| titulo | Um endereço de prestígio por menos do que você imagina |
| subtitulo | Sem taxa de adesão, sem prazo de fidelidade e com tudo que você precisa para manter seu CNPJ em ordem. |
| plano_nome | Endereço Fiscal e Comercial |
| plano_preo | R$ 119,90 |
| plano_perodo | por mês |
| plano_item_1 | Endereço comercial no Jardim Aquárius, São José dos Campos |
| plano_item_2 | Documentação imediata para abertura ou transferência de CNPJ |
| plano_item_3 | Gestão de correspondência inclusa |
| plano_item_4 | 20% de desconto em reservas de sala física |
| plano_item_5 | Rescisão com 30 dias de aviso. Sem multa. |
| plano_cta | Contratar agora pelo WhatsApp |
| plano_cta_url | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| nota_rodap | Valores das reservas de sala disponíveis em wesharescritorios.com.br |

### 7. Avaliações Google

| Campo | Texto |
|-------|-------|
| titulo | Quem já usou, aprovou |
| subtitulo | Confira as avaliações de quem já reservou espaço ou contratou o endereço fiscal da WeShare. |
| nota_google | 5 estrelas |
| total_avaliacoes | 54 avaliações no Google |
| ctaTexto | Ver avaliações no Google |
| ctaUrl | https://www.google.com/search?q=WeShare+Escritórios+Compartilhados+São+José+dos+Campos |

### 8. CTA Final

| Campo | Texto |
|-------|-------|
| titulo | Sua empresa com endereço de prestígio a partir de hoje |
| subtitulo | Sem burocracia, sem prazo de fidelidade e sem complicação. Fale agora pelo WhatsApp e receba a documentação no mesmo dia da assinatura. |
| ctaTexto | Falar com a WeShare agora |
| ctaUrl | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| ctaSecundarioTexto | contato@wesharescritorios.com.br |
| servico1Titulo | Atendimento pelo WhatsApp todos os dias |
| servico2Titulo | Documentação liberada no mesmo dia |
| servico3Titulo | Cancele quando quiser, sem multa |

### 9. Footer

| Campo | Texto |
|-------|-------|
| copyright | 2026 WeShare Escritórios Compartilhados. Todos os direitos reservados. |
| marca | WeShare Escritórios Compartilhados |
| endereco | Av. Alfredo Ignácio Nogueira Penido, 335, Ed. Medison Tower, Sala 706, Jardim Aquárius, São José dos Campos, SP, CEP 12246-000 |
| telefone | (12) 98271-0971 |
| email | contato@wesharescritorios.com.br |
| whatsapp_cta | Fale pelo WhatsApp |
| whatsapp_url | https://wa.me/5512982710971?text=Ol%C3%A1!%20Vi%20o%20site%20e%20quero%20saber%20mais. |
| instagram_label | @wesharescritorios |
| instagram_url | https://www.instagram.com/wesharescritorios |
| horario | Reservas pelo WhatsApp, todos os dias. Acesso ao espaço 24h por dia, 7 dias por semana. |



---

## Direção de Arte

### Tema Padrão
**Claro**

### Cores — `src/styles/tokens.css`

Preencha **apenas os valores** (os nomes são fixos entre projetos):

```css
:root {
  --t-primary:      #274C3B;
  --t-primary-dark: #002244;
  --t-secondary:    #3b634f;
  --t-background:   #F8F8F8;
  --t-surface:      #FFFFFF;
  --t-surface-alt:  #EEEEEE;
  --t-dark:         #222222;
  --t-text-main:    #333333;
  --t-text-soft:    #666666;
  --t-text-muted:   #999999;
  --t-border:       #CCCCCC;
}

.dark {
  --t-background:  #1A1A1A;
  --t-surface:     #2C2C2C;
  --t-surface-alt: #3F3F3F;
  --t-text-main:   #F0F0F0;
  --t-text-soft:   #BBBBBB;
  --t-text-muted:  #888888;
  --t-border:      #555555;
}
```

### Tipografia

| Papel | Fonte |
|-------|-------|
| Heading (`font-serif`) | Poppins |
| Body (`font-sans`) | Montserrat |

### Mood & Referências

Um ambiente visual que transmite profissionalismo, exclusividade e modernidade, com um toque de aconchego e inovação, utilizando uma paleta de cores sóbrias e elegantes com um acento de cor vibrante.

**Referências visuais:** https://coworking-space-128.webflow.io/ Gostei desse site para usarmos de base, mas precisamos de trazer o diferencial Adsgator com um design aprimorado e personalizado para o brinfing e estrutura desse cliente


---

## Regras de Copy — DNA do Negócio

## DNA: Prestador de Serviço

**Tom:** Confiante, direto, focado em resultado tangível.
**Perspectiva:** "Eu resolvo seu problema" — não "eu ofereço um serviço".
**Foco:** Transformação antes/depois. O visitante deve sentir que o problema dele tem solução aqui.

**Copy que funciona:**
- Hero: atacar a dor principal no título. Subheadline com o resultado esperado.
- CTA: verbos de ação imediata — "Agende agora", "Fale comigo hoje", "Quero resolver isso".
- Sobre: credenciais rapidamente, depois voltar ao cliente — não fazer monólogo sobre si.
- Depoimentos: resultado específico + prazo + nome real. Ex: "Resolvi em 3 dias o que levava semanas".

**Evitar:** Jargão técnico, parágrafos longos, muito sobre o processo e pouco sobre o resultado.

---

## Checklist Final

- [ ] `npm run build` sem erros de TypeScript/Astro
- [ ] `src/styles/tokens.css` preenchido com cores reais do cliente
- [ ] Fontes carregadas: `<link>` no `BaseLayout.astro` + import `@fontsource` no `global.css`
- [ ] `.env` preenchido: `PUBLIC_WA_NUMBER`, `PUBLIC_WA_MESSAGE`, `PUBLIC_GTM_ID`, `PUBLIC_SITE_URL`
- [ ] `BaseLayout.astro`: title, description, OG, canonical, Schema.org JSON-LD
- [ ] Hero com `id="hero-section"`; Footer com `id="footer"`; main com `id="main-content"`
- [ ] Header: esconde ao rolar para baixo; link ativo por IntersectionObserver
- [ ] WhatsApp flutuante: some quando Hero ou Footer estão visíveis; número real no `.env`
- [ ] Dark mode: toggle no Footer; persiste localStorage; sem flash na primeira carga
- [ ] Todas as seções com copy real (sem placeholder genérico)
- [ ] Responsivo em mobile (375px): texto ≥ 20px, botões ≥ 44px, padding lateral ≥ 20px
- [ ] `politica-de-privacidade.astro` e `termos-de-uso.astro`: TODOs preenchidos
- [ ] Schema tipo: `LocalBusiness`
- [ ] GTM configurado (ID:  GTM-NJMWCS39)
- [ ] WhatsApp (número: 5512982710971)