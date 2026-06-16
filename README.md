# Guia da lesão do joelho — Rotura do LCA

Site informativo, em português, que explica em linguagem simples o laudo de
ressonância magnética do joelho direito: o mecanismo da lesão (com diagramas),
os achados item por item, as opções de tratamento, a linha do tempo de
recuperação e o que fazer agora.

> ⚠️ **Conteúdo educativo.** Não substitui avaliação médica. Todas as decisões
> devem ser tomadas com o ortopedista de joelho que acompanha a paciente.

O site é **um único arquivo** (`index.html`), sem dependências instaláveis.
Todas as ilustrações são SVG embutido (não há links de imagem que possam quebrar).

---

## Como ver o site no seu computador

Basta abrir o arquivo `index.html` com qualquer navegador (Chrome, Safari, Firefox).
Dois cliques no arquivo já funciona.

---

## Como publicar no GitHub (GitHub Pages) — passo a passo

1. Entre em https://github.com e faça login (ou crie uma conta gratuita).
2. Clique no botão **New** (novo repositório).
3. Dê um nome, por exemplo: `guia-joelho`. Marque como **Public** e clique em
   **Create repository**.
4. Na página do repositório, clique em **Add file → Upload files**.
5. Arraste o arquivo **`index.html`** (e este `README.md`, se quiser) para a área
   de upload e clique em **Commit changes**.
6. Vá em **Settings** (engrenagem, no menu do repositório).
7. No menu lateral, clique em **Pages**.
8. Em **Source**, escolha **Deploy from a branch**. Em **Branch**, selecione
   **main** e a pasta **/ (root)**. Clique em **Save**.
9. Aguarde cerca de 1 minuto e recarregue a página. Vai aparecer o endereço do
   site, algo como:

   ```
   https://SEU-USUARIO.github.io/guia-joelho/
   ```

Pronto — esse link pode ser compartilhado com a família e abre em qualquer celular.

---

## Como editar

Para mudar qualquer texto, abra o `index.html` num editor de texto, faça a
alteração e suba o arquivo novamente (passo 4 e 5 acima). O GitHub atualiza o
site automaticamente em poucos instantes.

## Arquivos

- `index.html` — o site completo (HTML + CSS + diagramas SVG).
- `README.md` — estas instruções.
