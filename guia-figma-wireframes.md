# Guia rápido — recriar os 5 wireframes no Figma (30–45 min)

> Por que fazer isso: o critério exige "prototipagem de telas feita no Figma". Se o professor pedir o arquivo do Figma, os PNGs precisam ter origem lá. O caminho mais rápido: **importe os 5 PNGs atuais no Figma como referência (opacidade 30%) e desenhe por cima**, depois delete as imagens de referência e exporte.

## Setup (5 min)

1. Novo arquivo Figma: **CueVident Acadêmico — Wireframes MVP**.
2. Crie 5 frames Desktop (1440 × 1000). Nomeie exatamente:
   - `01-dashboard`
   - `02-nova-analise`
   - `03-processamento`
   - `04-editor-sugestoes`
   - `05-exportacao-plano`
3. Estilo único de baixa fidelidade (não perca tempo com cor):
   - Fundo: branco. Blocos: cinza `#E5E5E5`, borda `#999`, cantos 8.
   - Texto: Inter. Títulos 24 Bold, labels 14 Regular, botões 14 Medium.
   - Botão primário: retângulo preto, texto branco. Secundário: contorno.
   - Imagens/vídeo: retângulo cinza com um **X** de canto a canto (2 linhas).

## Componentes reutilizáveis (crie 1x, copie sempre)

- **Topbar**: barra 1440×64 no topo com logo "CueVident" à esquerda e avatar (círculo) à direita.
- **Card de clipe**: retângulo 320×180 com: título (14 Bold), linha "Início 00:00 → Fim 00:00", badge "Score 87", texto "Motivo: ..." (12), 2 tags, botões `Aceitar` / `Rejeitar`.

## Frame 1 — `01-dashboard`

- Topbar.
- H1: "Minhas análises".
- Botão primário no canto superior direito: **+ Nova análise**.
- 3 cards de resumo lado a lado: "Aguardando: 1", "Processando: 1", "Concluídas: 3".
- Lista/tabela com 4 linhas: nome do projeto fictício ("Podcast Ep. 12", "Live de terça", "Aula 04", "Entrevista Convidado X"), status (badge), data, ação "Abrir".
- Rodapé opcional: texto pequeno "Dados fictícios — versão acadêmica".

## Frame 2 — `02-nova-analise`

- Topbar + link "← Voltar".
- H1: "Nova análise".
- Formulário centralizado (largura 560):
  - Label "Nome do projeto" + input.
  - Label "URL do vídeo" + input. Abaixo, texto de erro em vermelho: "Informe uma URL válida" (mostra o estado de erro).
  - Label "Objetivo da análise" + select/dropdown ("Cortes para redes sociais").
- Botão primário: **Criar análise**. Secundário: "Cancelar".

## Frame 3 — `03-processamento`

- Topbar + nome do projeto como subtítulo.
- H1: "Processando análise".
- Stepper horizontal com 3 etapas: `Aguardando` ✓ → `Processando` (ativo) → `Concluído` (cinza).
- Barra de progresso (~60%) + texto "Analisando o vídeo... isso pode levar alguns minutos (simulado)".
- Caixa discreta de erro (estado alternativo): "Não foi possível concluir a análise. Tentar novamente."
- Botão desabilitado: "Ver sugestões" (com nota: habilita ao concluir).

## Frame 4 — `04-editor-sugestoes` (tela mais importante)

Layout em 3 colunas:
- **Esquerda (~30%)**: retângulo de player com X + timeline (barra horizontal com marcadores) abaixo.
- **Centro (~30%)**: bloco "Transcript" com 6–8 linhas de texto cinza (lorem curto), com um trecho destacado.
- **Direita (~40%)**: coluna "Sugestões (5)" com 3 cards de clipe visíveis + contador no topo: "Aceitos: 2 · Rejeitados: 1".
  - No 1º card, mostre os campos de início/fim como inputs editáveis (representa US05).
- Botão primário no topo direito: **Exportar plano**.

## Frame 5 — `05-exportacao-plano`

- Topbar + H1: "Plano de cortes".
- Lista dos clipes aceitos (3 linhas): título, início→fim ajustados, motivo resumido.
- Bloco de texto simulando o plano exportável (caixa cinza monoespaçada).
- Botões: **Copiar plano** (primário) e "Baixar .txt" (secundário).
- Estado vazio (pequeno, no rodapé ou frame anexo): "Nenhum clipe aceito ainda. Volte ao editor e aceite sugestões."

## Exportação (5 min)

1. Selecione os 5 frames → painel Export → PNG, 1x.
2. Confirme os nomes de arquivo: `01-dashboard.png` ... `05-exportacao-plano.png`.
3. Substitua os arquivos na pasta `wireframes/` do repositório.
4. (Opcional, 1 min) Deixe o arquivo Figma com link "anyone with the link can view" — não é exigido, mas é uma prova de origem barata.
