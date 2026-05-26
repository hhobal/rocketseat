# Documentação do projeto — reposição "rocetseat"

## Resumo do projeto

Projeto simples front-end com arquivos principais: `index.html`, `style.css`, `script.js` e uma pasta `assets` com recursos. Objetivo: paginação/experimentos estáticos (ex.: exercícios da Rocketseat).

## Estrutura de pastas

- root/
  - [index.html](index.html): Página principal em HTML.
  - [style.css](style.css): Estilos CSS globais do projeto.
  - [script.js](script.js): Comportamento JavaScript.
  - assets/: arquivos de mídia (imagens, ícones, etc.).
  - anotações rocketseat.txt: notas locais do autor.

## Resumo por arquivo

### index.html

- Propósito: marcação da página principal e inclusão dos recursos (`style.css`, `script.js`).
- Padrões: estrutura HTML simples (header, main, footer possíveis), referências a classes/IDs usadas no CSS e no JS.
- Pontos de estudo:
  - Identificar elementos que o `script.js` manipula (IDs, classes).
  - Verificar uso de tags semânticas (header, nav, main, section, footer).

### style.css

- Propósito: regras visuais e layout do site.
- Prováveis conteúdos: reset/normalize, variáveis CSS, estilos para layout responsivo, classes usadas por `index.html`.
- Pontos de estudo:
  - Procurar por seletores complexos e entender especificidade.
  - Identificar responsividade (`@media`) e variáveis CSS.

### script.js

- Propósito: adicionar interatividade ao DOM — manipulação de eventos, validação, animações simples.
- Padrões comuns a buscar: uso de `querySelector`/`addEventListener`, funções de callback, modularização mínima.
- Pontos de estudo:
  - Localizar funções principais e entender o fluxo (inicialização → handlers → atualizações DOM).
  - Identificar dependências globais (variáveis no escopo global) e possíveis melhorias (IIFE / módulos).

### assets/

- Propósito: armazenar imagens, fontes, ícones e outros binários usados pela página.
- Dica: revisar nomes e formatos (preferir SVG para ícones quando possível) e otimizar imagens para web.

## Dicas de estudo

- Comece pela `index.html` para entender a árvore DOM.
- Leia `script.js` seguindo o fluxo de execução: encontre o ponto de entrada (ex.: código que roda ao carregar) e trace eventos.
- Abra `style.css` enquanto inspeciona a página no navegador para ver quais regras afetam cada elemento.
- Use as ferramentas do DevTools (Elements, Sources, Network) para acompanhar carregamento e scripts.

## Checklist de revisão

- [ ] Verificar links relativos/paths estão corretos.
- [ ] Testar a página em diferentes tamanhos de tela.
- [ ] Rodar `script.js` no console para checar erros.
- [ ] Otimizar imagens na pasta `assets`.

## Notas finais

Este projeto parece ser um boilerplate/um exercício. A documentação aqui resume a intenção e pontos de estudo. Se quiser, posso:

- Gerar um sumário mais detalhado por função no `script.js`.
- Converter a documentação para PDF ou MD com links internos.
- Adicionar comentários inline nos arquivos de código.

---

Gerado automaticamente como guia de estudo.

- [ ] não determinística; probabilistica;
- [ ] contexto
- [ ] LLM: Large Language Model
- [ ] autocomplete
- [ ] active recall
- [ ] explicações
  - [ ] cuidados: nem sempre tudo é verdade
  - [ ] alucinação
- [ ] agentes: Agente, Ask (tirar dúvidas, pensar junto, ter ideias, explicar...)
- [ ] Planejar então gerar (Plan)
- [ ] Gerar então explicar (Agent)
- [ ] Motivação com micro vitórias
- [ ] Tree of Thought: árvore de pensamento
- [ ] Documentação
- [ ] PARE: Pergunte, Anote, Revise, Explique, PARE
- [ ] Reescreva!
- [ ] Entender, Escrever, Resolver
