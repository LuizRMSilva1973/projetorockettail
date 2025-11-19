# Rocket Tail — Diagnóstico de Propulsão (Landing Page)

Uma landing page moderna, rápida e responsiva para apresentar o “Diagnóstico de Propulsão” da Rocket Tail — Performance para negócios Pet. O projeto foi construído em HTML/CSS puro, focado em alta compatibilidade, carregamento leve e facilidade de publicação em hospedagens compartilhadas (como HostGator/cPanel).

![Hero](img/imagem12.png)

## Sumário

- Visão Geral
- Principais Recursos
- Estrutura de Pastas
- Como Rodar Localmente
- Personalização Rápida
- Publicação no HostGator (cPanel)
- Dicas de SEO e Performance
- Créditos e Licença

## Visão Geral

- HTML sem dependências de framework.
- CSS organizado e comentado em `css/style.css`.
- Imagens otimizadas na pasta `img/` (inclui ícones, fotos e fundo do hero).
- Conteúdo em português do Brasil e fontes via Google Fonts (Montserrat).

## Principais Recursos

- Hero com imagem de fundo e overlay em gradiente vermelho, cantos arredondados e botão de vídeo estilizado.
- Cartões em duas cores com alinhamento do bege até a metade do ícone (cálculo responsivo).
- Seções “Resultados”, “Quem”, “Atuação Brasil + EUA” e “Vagas” com estilos próximos ao mock.
- Responsividade refinada para tablets e celulares.
- Botão flutuante de WhatsApp.

## Estrutura de Pastas

```
/
├── index.html        # página principal
├── css/
│   └── style.css     # estilos do site
└── img/              # imagens e ícones (imagem6–imagem12, logo e ícones)
```

## Como Rodar Localmente

1. Baixe/clonar este repositório.
2. Abra `index.html` diretamente no navegador (duplo clique) ou sirva com um servidor estático.
   - Ex.: com Python 3: `python3 -m http.server 8080` e acesse `http://localhost:8080`.

## Personalização Rápida

- Cores: ajustáveis no `css/style.css`. Procurar por variáveis locais e cores hex (`#e31b0c`, `#0d2f4a`, `#25e6d6`, etc.).
- Ícones e imagens: substitua arquivos em `img/` mantendo os nomes para não alterar os caminhos.
- Texto/CTA: editável direto no `index.html`.
- Gradiente do hero: para aumentar/reduzir a visibilidade da imagem de fundo, ajuste as opacidades do gradiente em `.hero`.

## Publicação no HostGator (cPanel)

1. Compacte o projeto em `.zip` contendo `index.html`, a pasta `css` e a pasta `img`.
2. cPanel → Arquivos → Gerenciador de arquivos → abra `public_html` (ou a pasta do seu domínio/subdomínio).
3. Clique “Upload” e envie o `.zip` → “Extract”.
4. Confirme a estrutura final:
   - `public_html/index.html`
   - `public_html/css/style.css`
   - `public_html/img/...`
5. Permissões recomendadas: pastas `0755`, arquivos `0644`.
6. Acesse o domínio e faça um Hard Reload (Ctrl+F5) para limpar cache.

Dica: se publicar numa subpasta (ex.: `public_html/diagnostico`), a URL será `seudominio.com/diagnostico`.

## Dicas de SEO e Performance

- Títulos e descrições: ajuste `<title>` e meta tags no `<head>`.
- Alt text: todas as imagens possuem `alt` — mantenha descritivo.
- Tamanho das imagens: troque por versões otimizadas (WebP/PNG comprimido) quando possível.
- Cache: ative cache no seu host (ou via .htaccess) para `css`/`img`.

## Créditos e Licença

- Design e conteúdo: Rocket Tail — Performance para negócios Pet (cliente/projeto).
- Código: HTML/CSS simples, feito para ser facilmente adaptado.
- Licença: uso interno do projeto (sem licença open‑source automática). Ajuste conforme necessidade.

---

Se precisar, posso ajustar cores/tipografia/spacing para bater 100% com um novo mock, ou preparar um build com minificação das folhas de estilo.
