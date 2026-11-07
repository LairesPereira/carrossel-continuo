# Carrossel Contínuo

App web para montar colagens panorâmicas de carrossel do Instagram (estilo SCRL).
Roda inteiro no navegador: sem login, sem banco de dados, as fotos nunca saem do aparelho.

## O que faz
- Recebe várias fotos e monta a colagem automaticamente; **Reembaralhar** gera novas composições.
- Linhas de corte e numeração mostram onde cada post termina.
- Formatos 3:4 (1080×1440), 4:5 (1080×1350) e 1:1 (1080×1080).
- Sobreposição de fotos, contorno e sombra opcionais.
- Arrastar, redimensionar, girar 90°, trocar de lugar, trazer à frente/enviar para trás.
- Páginas inteiras automáticas (0%, 20%, 40% ou 60% das fotos; padrão 40%), com enquadramento e zoom ajustáveis.
- Botão para sortear mais uma foto como página inteira.
- Cadeado por página: páginas travadas não mudam ao reembaralhar; as fotos que já estavam nelas ficam protegidas, mas outras fotos podem entrar por cima ou por baixo.
- Efeitos por foto: granulação, desfoque, desfoque de movimento com direção, preto e branco com intensidade.
- Seleção de várias fotos (toque ou retângulo arrastando o mouse) para mover, redimensionar juntas na mesma proporção, girar, excluir ou aplicar efeitos (com Desfazer).
- Botão para embaralhar só uma página, com as fotos que estão nela.
- Botão de lixeira em cada página para excluir todas as fotos dela; se a página ficar vazia, ela é removida.
- Exporta cada página em JPG na resolução final (no celular, abre o compartilhamento para salvar na galeria; no computador, baixa um .zip).

## Rodar localmente
Abra `index.html` no navegador. Não há build nem dependências.

## Deploy
Site estático: na Vercel, importe o repositório com o preset **Other**, sem comando de build e com a pasta raiz como saída.
