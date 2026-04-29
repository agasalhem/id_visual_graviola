# Graviola — Feira Musical Brasileira
## Resumo Completo do Projeto de Identidade Visual

**Última atualização:** 28 de abril de 2026

---

## O que é este projeto

Pitch deck digital e sistema de identidade visual completo para a **Graviola — Feira Musical Brasileira**, evento cultural em Salvador/BA com foco em pagotrap, samba-reggae e ragga. O pitch é uma proposta de patrocínio via **Lei Rouanet (Art. 18 / LIC)** endereçada à PetroReconcavo, com PRONAC 495329.

---

## O que foi feito

### 1. Design System (`graviola-design-system.md`)

Documento de identidade visual completo criado, cobrindo:

- **Logo:** Wordmark principal e variações (sobre marrom, laranja, monocromático)
- **Paleta de cores:**
  - Laranja Tropicália `#FF7838` — cor principal vibrante
  - Creme / Off-white `#FFF4E9` — fundo claro
  - Azul Céu `#89C0FF` — complementar fria
  - Amarelo Sol `#FFD05D` — destaque quente
  - Verde Folha `#43A574` — elemento natural
  - Marrom Terra `#562D2A` / Deep `#321818` — tons escuros
- **Tipografia:** Lilita One (display/títulos) + Montserrat (corpo, subtítulos)
- **Escala tipográfica:** H3 32px/800 até Caption 10px/500
- **Spacing:** Grid de 8px, Border Radius de 6px (sm) a 9999px (pill)
- **Brand Patches:** 4 formatos bordados — Circular (coco), Hexagonal (sol), Retangular (violão), Oval (laranja)
- **Patterns e texturas:** tiles, jornal rasgado, papel kraft, faixa tropical
- **Backgrounds:** amarelo, azul, verde, vermelho, papel
- **Componentes:** botões, badges/stamps, washi tapes, selos, cards (evento, escuro, promocional, brinde)
- **Voz & Tom:** calorosa, popular, brasileira de verdade, leve e com atitude
- **Templates de social media:** 6 variações (posts 1:1)

### 2. Assets Visuais (`src/assets/`)

Conjunto completo de assets produzidos e organizados:

| Asset | Arquivo |
|-------|---------|
| Logo principal | `logo.png` |
| Patch coco (circular) | `patch_coco_final.png` |
| Patch sol (hexagonal) | `patch_sol_final.png` |
| Patch violão (retangular) | `patch_violao_final.png` |
| Patch laranja (oval) | `patch_laranja_final.png` |
| Background amarelo | `bg_amarelo.jpg` |
| Background azul | `bg_azul.jpg` |
| Background verde | `bg_verde.png` |
| Background vermelho | `bg_vermelho.jpg` |
| Background papel | `bg_papel.jpg` |
| Copo Graviola | `copo_220.png` |
| Pulseira | `pulseira_220.png` |
| Lambe-lambe OOH | `brand_app_lambe_lambe.jpg` |
| Padrão jornal rasgado | `pattern_jornal_rasgado.png` |
| Padrão papel kraft | `pattern_papel.png` |
| Borda rasgada | `texture_torn_paper.png` |
| Faixa tropical | `pattern_main_strip.png` |
| Tile banana+sol | `tile_banana_sol_v3.png` |
| Tile citrus+folha | `tile_citrus_folha.png` |
| Padrão cavalete | `pattern_cavalete.png` |
| Citrus slice | `pattern_citrus_slice.png` |
| Folha | `pattern_folha.png` |
| Tiles corretos | `pattern_tiles_correct.png` |
| Templates sociais (6x) | `template_social_1a/1b/2a/2b/3a/3b.jpg` |

### 3. Estrutura do Pitch (`estrutura_slides.md`)

Documento de conteúdo com os **30 slides** do pitch deck estruturados:

1. Capa (Logo + Tagline + PRONAC)
2. Conceito (O que é o Graviola)
3. Manifesto
4. Storytelling
5. Vídeo 1 — Conceito
6. Pilares do projeto
7. Território de marca (Keywords)
8. ROO — Return on Objectives
9. Fotos de autoridade
10. Informações técnicas
11. Lei Rouanet — simulação fiscal
12. Valores de marca
13. Artistas / Line-up
14. Visual do line-up (cartaz)
15. Clipping — header
16. Clipping — mídia
17. Vídeo 2 — Legado social
18. Prova social (quote)
19. Contrapartidas — divider
20. Convites e experiência VIP
21. Cotas de patrocínio — divider
22. Tabela de cotas
23. Resultados e medição
24. Vídeo 3 — Energia
25. Co-criação
26. Marca na divulgação
27. Presença on-stage
28. Ativação 1 — "Sintonia On-shore"
29. Ativação 2 — "Spoiler Coletivo Recôncavo"
30. Encerramento (contato)

### 4. Pitch Deck HTML (`graviola-pitch.html` + `graviola-pitch-styles.css`)

Apresentação digital profissional construída com **Reveal.js** (CDN) seguindo as filosofias das skills `revealjs` e `frontend-slides`:

**Tecnologia:**
- Reveal.js 5.1.0 via CDN
- Font Awesome 6.5.1 para ícones
- Google Fonts: Lilita One + Montserrat
- CSS com variáveis semânticas da marca
- Transição: `fade` suave
- 30 slides, zero overflow detectado (verificado com puppeteer)

**Componentes CSS criados:**
- `.chip` / `.chip-azul` / `.chip-amarelo` / `.chip-verde` / `.chip-marrom` — tags coloridas
- `.card-dark` — card fundo marrom creme
- `.card-laranja` — card fundo laranja
- `.card-creme` — card fundo claro com borda
- `.stat-box` / `.stat-number` / `.stat-label` — caixas de métricas numéricas
- `.pilar-card` — card com borda lateral laranja
- `.kw-badge` — badge de palavra-chave
- `.ativacao-card` — card especial para ativações com efeito circular
- `.video-placeholder` — placeholder elegante para vídeos
- `.washi` — faixa decorativa estilo washi tape rotacionada
- `.pronac-badge` — badge amarelo para PRONAC
- `.section-eyebrow` — label de categoria acima do título
- `.patch-deco` / `.patch-deco-lg` — imagens de patches decorativos

**Slides de destaque:**
- **Capa:** fundo `#321818`, logo invertido branco, 4 patches, PRONAC badge
- **Manifesto (slide 3):** fundo escuro, dois cards lado a lado resistência / transformação
- **Lei Rouanet (slide 11):** fundo escuro, breakdown fiscal visual com custo R$ 0,00 em destaque
- **Tabela de cotas (slide 22):** tabela HTML estilizada, coluna master em laranja, valores em destaque
- **Ativações (slides 28/29):** cards especiais com imagens dos assets, chips de benefício
- **Encerramento (slide 30):** fundo laranja, logo, patches, dados de contato em cards

---

## Status Atual

| Item | Status |
|------|--------|
| Design System documentado | ✅ Completo |
| Assets organizados em `src/assets/` | ✅ Completo |
| Estrutura dos slides (conteúdo) | ✅ Completo |
| CSS da apresentação (identidade Graviola) | ✅ Completo |
| HTML dos 30 slides | ✅ Completo |
| Verificação de overflow (puppeteer) | ✅ Zero problemas |
| Revisão visual (screenshots decktape) | ✅ 30 slides revisados |
| Abertura no browser | ✅ Funcionando |

**A apresentação está pronta para uso imediato.** Abrir `graviola-pitch.html` no navegador e navegar com setas do teclado.

---

## Próximos Passos

### Prioridade Alta — Finalização de Conteúdo

#### 1. Inserir os 3 vídeos (slides 5, 17, 24)
Os slides de vídeo têm placeholders visuais elegantes. Para ativar:

**Opção A — Vídeo local:**
```html
<!-- Substituir o div.video-placeholder por: -->
<video src="caminho/do/video.mp4" controls style="width:100%; border-radius:20px; max-height:420px;"></video>
```

**Opção B — YouTube embed:**
```html
<iframe src="https://www.youtube.com/embed/SEU_VIDEO_ID"
  style="width:100%; height:420px; border-radius:20px; border:none;" allowfullscreen></iframe>
```

#### 2. Inserir arte final do cartaz (slide 14)
O slide do line-up visual tem um placeholder escuro indicando onde colocar o cartaz oficial. Quando a arte estiver pronta:
- Salvar como `src/assets/cartaz_graviola_2026.jpg`
- Substituir o `div` placeholder por `<img src="src/assets/cartaz_graviola_2026.jpg" ...>`

#### 3. Inserir fotos do evento / referências (slide 9)
O slide de "Fotos de Autoridade" tem 3 cards com ícones e backgrounds de cor. Substituir cada card por uma foto real quando disponível.

#### 4. Confirmar nome da empresa e logo da PetroReconcavo (slides 6, 8, 11, 14, 25, 28, 29)
O nome "PetroReconcavo" aparece diversas vezes. Se a grafia oficial for diferente (ex: "PetroRecôncavo"), fazer busca e substituição global no HTML.

Para adicionar o logo da PetroReconcavo onde indicado (slide 14 — "Apresenta"):
- Salvar logo como `src/assets/logo_petroreconcavo.png`
- Inserir acima do logo Graviola no slide 14

---

### Prioridade Média — Refinamentos Visuais

#### 5. Ajustar foto/imagem da capa
A capa atual usa fundo sólido `#321818` com os patches. Opções para elevar o impacto:
- Adicionar `bg_papel.jpg` como textura de fundo semitransparente
- Adicionar foto de público / festa em overlay escuro

#### 6. Adicionar foto real de público ao slide 4 (Storytelling)
O slide tem uma coluna da direita com patch e washi tape. Uma foto de público jovem em show de axé/samba-reggae ao entardecer tornaria o slide muito mais emocional.

#### 7. Personalizar slides 13/14 com artistas confirmados
Quando o line-up estiver fechado, substituir os chips genéricos de gênero pelos nomes dos artistas no slide 13.

---

### Prioridade Baixa — Distribuição

#### 8. Exportar como PDF
Para enviar por e-mail ou WhatsApp:
```bash
cd /Users/gabrielmagalhaes/BREEZE/id_visual_graviola
npx decktape reveal "graviola-pitch.html" graviola-pitch.pdf --size 1280x720
```

#### 9. Publicar em URL compartilhável (opcional)
Para enviar um link que funcione em qualquer dispositivo, incluindo celular, fazer deploy no Vercel:
```bash
npx vercel /Users/gabrielmagalhaes/BREEZE/id_visual_graviola/graviola-pitch.html
```
O link gerado pode ser enviado para a PetroReconcavo e abre diretamente no navegador.

#### 10. Edição de texto no browser
Para ajustar qualquer texto sem abrir o código:
```bash
node /Users/gabrielmagalhaes/.claude/plugins/cache/revealjs-skill/revealjs/1.0.0/skills/revealjs/scripts/edit-html.js graviola-pitch.html
```
Clicar em qualquer texto para editar inline, depois salvar.

---

## Estrutura de Arquivos

```
id_visual_graviola/
├── graviola-pitch.html          ← Apresentação principal (30 slides)
├── graviola-pitch-styles.css    ← CSS completo com identidade Graviola
├── graviola-design-system.md    ← Design System documentado
├── estrutura_slides.md          ← Conteúdo original dos slides
├── resumo.md                    ← Este arquivo
└── src/
    └── assets/                  ← Todos os assets visuais da marca
        ├── logo.png
        ├── patch_coco_final.png
        ├── patch_sol_final.png
        ├── patch_violao_final.png
        ├── patch_laranja_final.png
        ├── bg_amarelo.jpg / bg_azul.jpg / bg_verde.png / ...
        ├── copo_220.png / pulseira_220.png
        ├── pattern_*.png / texture_torn_paper.png
        └── template_social_*.jpg
```

---

## Navegação na Apresentação

| Ação | Tecla |
|------|-------|
| Próximo slide | `→` ou `Espaço` |
| Slide anterior | `←` |
| Menu de slides | `Esc` |
| Tela cheia | `F` |
| Notas do orador | `S` |
| Visão geral | `O` |
