# Site — Corrida do Meio Ambiente

Landing page institucional única, animada, reproduzindo o portfólio da Corrida do Meio Ambiente (SEMA-DF / Instituto Conexão do Bem) com o vídeo dos três percursos.

## Como abrir
Abra `index.html` no navegador (Chrome/Edge). Tudo é local e autocontido — não precisa de servidor.
Para publicar (Netlify, hospedagem, etc.), suba a pasta `site/` inteira; o `index.html` é a raiz.

## Estrutura
- `index.html` — página completa (HTML + CSS + JS inline, sem build)
- `assets/`
  - `percursos.mp4` — vídeo unido 5K+10K (embutido na seção Percursos)
  - `v_5k.mp4` · `v_10k.mp4` — vídeos individuais (abrem no lightbox ao clicar no percurso)
  - `croqui_3k/5k/10k.png` — croquis oficiais dos percursos
  - `poster.jpg` — capa do vídeo principal
  - `hero_runners.jpg` — foto de abertura
  - `mascote_tandu_ficha.png` — ficha do mascote TANDU

## Conteúdo
Reproduz as 11 páginas do PDF `Portfolio_Corrida_do_Meio_Ambiente_atualizado_com_croquis_v2.pdf`,
harmonizado em seções: Hero, Visão geral, Propósito, **Percursos (vídeo + croquis)**,
Experiência, Sustentabilidade, Inclusão, Entrega, Viabilização, Mascote e chamada final.

## Identidade
- Cores: verde-floresta, azul-marinho, areia do Cerrado, verde-lima (paleta oficial TANDU/SEMA)
- Tipografia: Archivo (títulos/texto), Anton (números das distâncias), IBM Plex Mono (rótulos)
- Assinatura visual: trilha de percurso (rail) que desce a página com o ponto correndo conforme o scroll

## Efeitos
Reveal on scroll, contador do investimento, trilha animada com ponto, parallax de folhas no hero,
hover nos cards, lightbox de vídeo por percurso, menu mobile. Respeita `prefers-reduced-motion`.

## Trocar conteúdo
- Textos: direto no `index.html` (cada seção é comentada).
- Vídeo dos percursos: substituir `assets/percursos.mp4` (16:9) e `assets/poster.jpg`.
- Mascote: se a escolha final não for o TANDU, trocar `assets/mascote_tandu_ficha.png` e a seção `#mascote`.
- Contato/CNPJ/telefone: seção `#viabilizacao` e rodapé (reproduzidos exatamente como no PDF).
