# As Aventuras de Nena e Pepê — HRCLN-GAMES

Jogo de labirinto inspirado na mecânica clássica de maze-chase, com identidade e personagens originais. Construído com HTML5, CSS3, JavaScript e Phaser 3.

## Incluído
- Portal de entrada responsivo.
- Cinco fases: Bosque Encantado, Vila das Nuvens, Cavernas de Cristal, Vulcão Dourado e Castelo das Sombras.
- Movimento por teclado e botões de toque.
- Pontuação, vidas, itens colecionáveis, power-ups, guardiões e saída desbloqueada ao limpar o labirinto.
- Sons sintetizados no navegador, recorde local e mensagens de progresso.
- Estética colorida com profundidade visual 2.5D. A arte de personagens é desenhada por código nesta versão-base; não é modelagem 3D real.

## Executar no VS Code
Abra a pasta e inicie um servidor local (por exemplo, extensão Live Server) ou execute `python -m http.server 8000`. Acesse `http://localhost:8000`.
Phaser é carregado de CDN, portanto a primeira execução precisa de internet.

## Publicar no GitHub
Dentro desta pasta:
```bash
git init
git add .
git commit -m "feat: jogo Nena e Pepê com cinco fases"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```
Troque a URL de exemplo pelo repositório real.

## Publicar na Hostinger
Envie o conteúdo da pasta para uma pasta pública como `public_html/games/`. O `index.html`, `style.css` e `game.js` devem permanecer juntos. Abra o URL publicado em HTTPS e teste computador e celular.

## Testes manuais antes de divulgar
1. Abrir a página e iniciar o jogo.
2. Testar setas, WASD e controles de toque.
3. Coletar itens e confirmar atualização da pontuação.
4. Tocar um guardião, perder vida e confirmar reinício do personagem.
5. Recolher todos os itens e alcançar a saída.
6. Completar as cinco fases e confirmar tela final.
7. Reiniciar e verificar persistência do recorde.
8. Testar áudio e layout em celular e desktop.

Esta entrega é uma base jogável de protótipo. Recomenda-se fazer uma rodada completa de QA nos navegadores e dispositivos de destino antes de anunciar como lançamento final.
