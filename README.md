# Missão Respeito — Consciência Negra

Site educativo em HTML, CSS e JavaScript, pronto para publicação.

## Estrutura
- `index.html`: aplicação completa (estilos e lógica incluídos).
- `vercel.json`: configuração simples para deploy estático.

## Publicar na Vercel
1. Envie esta pasta para um repositório no GitHub.
2. Na Vercel, selecione **Add New → Project** e importe o repositório.
3. Framework Preset: **Other**.
4. Build Command: deixe vazio; Output Directory: `.`.
5. Clique em **Deploy**.

## Publicar no GitHub Pages
1. Envie os arquivos para a raiz de um repositório.
2. Abra **Settings → Pages**.
3. Em Build and deployment, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)`, salve.

## Recursos
- Etapa 1: jogo da memória com seis personalidades negras brasileiras.
- Etapa 2: labirinto RESPEITO com MediaPipe Hands (CDN), mouse e toque.
- Etapa 3: cruzadinha com interseções reais e seis palavras de origem africana.
- Etapa 4: enigma com senha `20 de novembro`.

## Observações técnicas e pedagógicas
- Para usar a câmera, acesse por HTTPS (Vercel/GitHub Pages já fornecem) ou `localhost`.
- O MediaPipe é carregado por CDN; a primeira abertura exige internet.
- Se a câmera não funcionar, arraste o marcador com mouse ou toque.
- O jogo registra o progresso durante a sessão; recarregar reinicia a partida.
- As cartas usam iniciais e ilustrações gráficas próprias, evitando dependência de imagens externas.
- A cruzadinha aceita letras sem acentos.
- A senha final pode ser digitada como `20 de novembro` ou `20/11`.

## Referências para aprofundamento
- Fundação Cultural Palmares: https://www.gov.br/palmares/pt-br
- Memorial do MPF — Consciência Negra: https://memorial.mpf.mp.br/nacional/consciencianegra
- Agência Brasil / Academia Brasileira de Letras — vocabulário de origem africana: https://agenciabrasil.ebc.com.br/cultura/noticia/2026-05/dengo-axe-samba-conheca-palavras-africanas-no-dia-a-dia-do-brasil

Material para mediação docente. Recomenda-se finalizar com uma roda de conversa sobre atitudes concretas de respeito e enfrentamento ao racismo.
