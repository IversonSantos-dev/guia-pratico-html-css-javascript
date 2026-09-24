# Guia Prático de HTML, CSS e JavaScript com NotebookLM

> Caderno temático desenvolvido como projeto de aprendizagem ativa da DIO, utilizando o NotebookLM para organizar fontes, formular perguntas, comparar respostas e consolidar conhecimentos fundamentais do desenvolvimento web.

## Sumário

- [1. Contexto](#1-contexto)
- [2. Objetivos](#2-objetivos)
- [3. Como utilizar este caderno](#3-como-utilizar-este-caderno)
- [4. Curadoria de fontes](#4-curadoria-de-fontes)
- [5. Engenharia de prompts e cicatrizes](#5-engenharia-de-prompts-e-cicatrizes)
- [6. Miniguia de estudo](#6-miniguia-de-estudo)
  - [HTML](#html)
  - [CSS](#css)
  - [JavaScript](#javascript)
  - [Integração entre as tecnologias](#integração-entre-as-tecnologias)
- [7. Glossário](#7-glossário)
- [8. Prompts reutilizáveis](#8-prompts-reutilizáveis)
- [9. Projeto prático sugerido](#9-projeto-prático-sugerido)
- [10. Conclusão e próximos passos](#10-conclusão-e-próximos-passos)

---

## 1. Contexto

HTML, CSS e JavaScript são as principais tecnologias utilizadas na construção de interfaces web. Embora sejam frequentemente estudadas em conjunto, cada uma possui uma responsabilidade diferente:

- **HTML** define a estrutura e o significado do conteúdo;
- **CSS** controla a apresentação visual, o layout e a responsividade;
- **JavaScript** adiciona comportamento, interação e lógica à página.

Este repositório organiza um guia prático para dúvidas e perguntas frequentes sobre as principais funções, conceitos e recursos dessas três tecnologias. O material foi estruturado com o apoio do **NotebookLM**, usado como ferramenta de aprendizagem ativa para consultar fontes, testar perguntas, identificar lacunas e revisar o conteúdo com mais criticidade.

### Tema escolhido

**Guia prático para dúvidas e perguntas sobre as principais funções de HTML, CSS e JavaScript.**

### Público-alvo

Pessoas iniciantes ou em fase de consolidação dos fundamentos do desenvolvimento front-end, especialmente quem deseja compreender como criar páginas semânticas, responsivas e interativas.

---

## 2. Objetivos

### Objetivo geral

Construir uma referência de estudo clara e reutilizável sobre os fundamentos de HTML, CSS e JavaScript, utilizando inteligência artificial de forma crítica e baseada em fontes.

### Objetivos específicos

- Entender a função de cada tecnologia no desenvolvimento web;
- Criar documentos HTML semânticos e acessíveis;
- Aplicar seletores, propriedades, box model e layouts com CSS;
- Compreender variáveis, funções, estruturas de controle e arrays em JavaScript;
- Manipular o DOM e responder a eventos do usuário;
- Relacionar estrutura, estilo e comportamento em um projeto integrado;
- Aprender a formular prompts mais objetivos e verificáveis;
- Registrar dificuldades, limitações e estratégias de melhoria nas consultas à IA;
- Criar uma base de prompts para futuras revisões.

---

## 3. Como utilizar este caderno

1. Leia o resumo do conceito que deseja revisar.
2. Consulte a fonte correspondente no NotebookLM.
3. Faça uma pergunta específica usando um dos prompts deste README.
4. Confira se a resposta apresenta referências e compare-a com a documentação ou material original.
5. Pratique o conceito escrevendo código, modificando exemplos e observando os resultados.
6. Registre dúvidas que permanecerem e reformule a pergunta com contexto adicional.

> **Regra de ouro:** a resposta da IA é um ponto de partida para investigação, não uma substituição da documentação oficial, da prática ou da análise crítica.

---

## 4. Curadoria de fontes

As fontes abaixo foram selecionadas para apoiar o estudo no NotebookLM. Elas combinam conteúdo audiovisual, material de referência em formato de livro e um repositório aberto com exemplos e trilhas de aprendizagem.

| Fonte | Tipo | Como foi utilizada |
|---|---|---|
| [Curso/aula sobre desenvolvimento web no YouTube](https://www.youtube.com/watch?v=J2TMoVYQzwI) | Vídeo | Apoio visual e explicações introdutórias sobre os fundamentos do desenvolvimento web. |
| [Livro sobre desenvolvimento web no Google Books](https://books.google.com.br/books?id=FFbNEAAAQBAJ&printsec=frontcover&hl=pt-BR&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false) | Livro/visualização online | Consulta conceitual e aprofundamento dos fundamentos de HTML, CSS e JavaScript. |
| [Guia do Frontend — arthurspk/guiadofrontend](https://github.com/arthurspk/guiadofrontend) | Repositório GitHub | Curadoria de links, referências e materiais para estudo de front-end. |
| [MDN Web Docs](https://developer.mozilla.org/pt-BR/) | Documentação aberta | Validação de sintaxe, comportamento de APIs e boas práticas de HTML, CSS e JavaScript. |
| [WHATWG HTML Living Standard](https://html.spec.whatwg.org/) | Especificação aberta | Consulta de referência para semântica e comportamento padrão do HTML. |

### Critérios de seleção

- Relevância para os fundamentos de front-end;
- Acesso aberto ou consulta pública;
- Complementaridade entre explicação, exemplos e documentação;
- Possibilidade de verificar as respostas geradas pelo NotebookLM;
- Atualidade e utilidade prática para quem está começando.

### NotebookLM utilizado

[**Abrir o caderno no NotebookLM**](https://notebook.google.com/notebook/ae03515f-6e36-4dd5-9e4d-319847149247)

> O acesso ao notebook pode depender da autorização da conta Google e das permissões de compartilhamento configuradas pelo proprietário.

---

## 5. Engenharia de prompts e cicatrizes

### Estratégia utilizada

Para obter respostas mais úteis, as perguntas foram construídas com cinco elementos:

1. **Contexto:** informar que o objetivo é estudar front-end.
2. **Escopo:** delimitar HTML, CSS ou JavaScript.
3. **Nível:** indicar que a explicação deve ser adequada a iniciantes.
4. **Formato:** pedir tabela, passo a passo, exemplo ou comparação.
5. **Verificação:** solicitar referências às fontes e alertas sobre possíveis limitações.

### Perguntas estratégicas

- Qual é a responsabilidade de HTML, CSS e JavaScript em uma aplicação web?
- Como escolher elementos HTML semânticos para estruturar uma página?
- Qual é a diferença entre `class` e `id` e quando cada um deve ser utilizado?
- Como funciona o box model do CSS?
- Qual é a diferença entre Flexbox e CSS Grid?
- Como criar um layout responsivo sem duplicar o HTML?
- O que são especificidade e cascata no CSS?
- Qual é a diferença entre `let`, `const` e `var`?
- Como funcionam funções, escopo e arrow functions em JavaScript?
- Como selecionar elementos, alterar conteúdo e modificar classes usando o DOM?
- Qual é a diferença entre `==` e `===`?
- Como tratar eventos de formulário e validar dados no navegador?

### Variações de prompts testadas

**Prompt amplo — primeira tentativa**

> Explique HTML, CSS e JavaScript.

**Resultado esperado:** resposta introdutória, mas genérica e sem necessariamente apresentar uma sequência de estudo ou exemplos verificáveis.

**Prompt com contexto e formato**

> Explique a diferença entre HTML, CSS e JavaScript para uma pessoa iniciante. Organize a resposta em uma tabela com responsabilidade, exemplos e erros comuns de cada tecnologia.

**Resultado esperado:** resposta mais organizada, comparável e adequada para revisão rápida.

**Prompt com fonte e validação**

> Com base nas fontes deste notebook, explique como o DOM funciona. Apresente um exemplo curto em JavaScript, indique quais conceitos da resposta estão apoiados nas fontes e destaque qualquer ponto que precise ser confirmado na documentação oficial.

**Resultado esperado:** maior rastreabilidade e menor risco de aceitar uma explicação sem contexto.

**Prompt para troubleshooting**

> Meu botão não responde ao clique. Analise este HTML e JavaScript, liste as hipóteses mais prováveis em ordem de prioridade e proponha testes pequenos para confirmar cada hipótese. Não reescreva tudo sem explicar a causa.

**Resultado esperado:** diagnóstico gradual, evitando soluções que apenas escondem o problema.

### Cicatrizes e dificuldades encontradas

- **Respostas muito amplas:** perguntas como “explique JavaScript” geram conteúdo extenso e pouco direcionado. A solução foi dividir o tema em conceitos menores.
- **Exemplos sem contexto:** um trecho de código isolado pode não informar onde deve ser inserido. Foi necessário pedir HTML, CSS e JavaScript completos ou indicar o arquivo de cada parte.
- **Diferença entre versões e práticas:** algumas fontes podem apresentar sintaxes antigas, como `var`, ou abordagens que não são as mais recomendadas atualmente. A solução foi comparar com a MDN e explicar a evolução.
- **Referências insuficientes:** nem toda resposta automaticamente aponta a origem de cada afirmação. Por isso, passou-se a solicitar citações, limitações e separação entre informação encontrada e inferência.
- **Termos parecidos:** conceitos como `class`/`id`, `margin`/`padding` e `==`/`===` podem ser confundidos. A estratégia foi pedir comparações lado a lado e exemplos de uso e não uso.
- **Depuração superficial:** pedir apenas “corrija meu código” pode gerar uma alteração sem aprendizado. O prompt passou a exigir hipóteses, causa provável, teste e correção mínima.

### Checklist para avaliar uma resposta do NotebookLM

- A resposta cita ou permite localizar a fonte?
- O conceito foi explicado com precisão e sem generalizações perigosas?
- Há um exemplo mínimo que pode ser executado?
- Foram indicados erros comuns ou limitações?
- A resposta diferencia fato da fonte, interpretação e sugestão da IA?
- O conteúdo foi conferido na documentação oficial?

---

## 6. Miniguia de estudo

### HTML

HTML (*HyperText Markup Language*) é uma linguagem de marcação. Ele organiza o conteúdo por meio de elementos e atributos.

#### Estrutura mínima

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha página</title>
  </head>
  <body>
    <h1>Olá, web!</h1>
    <p>Este é um conteúdo semântico.</p>
  </body>
</html>
```

#### Conceitos essenciais

- **Elementos:** representam partes do documento, como `h1`, `p`, `a`, `img` e `form`.
- **Atributos:** fornecem informações adicionais, como `href`, `src`, `alt`, `id` e `class`.
- **Semântica:** usar elementos pelo significado, como `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`.
- **Acessibilidade:** textos alternativos em imagens, hierarquia correta de títulos, labels em formulários e links descritivos.
- **Formulários:** `form`, `label`, `input`, `select`, `textarea` e `button` coletam dados do usuário.
- **Metadados:** `title`, `meta` e links para folhas de estilo ajudam o navegador e mecanismos de busca a interpretar a página.

#### Boas práticas de HTML

- Use uma única hierarquia lógica de títulos, sem escolher tags apenas pelo tamanho visual.
- Prefira elementos semânticos a excesso de `div`.
- Sempre que possível, associe `label` ao campo por meio de `for` e `id`.
- Use `alt` descritivo para imagens informativas e `alt=""` para imagens decorativas.
- Valide a estrutura e teste a navegação por teclado.

### CSS

CSS (*Cascading Style Sheets*) descreve como os elementos HTML serão apresentados.

#### Sintaxe básica

```css
.card {
  max-width: 32rem;
  margin: 0 auto;
  padding: 1.5rem;
  color: #1f2937;
  background-color: #ffffff;
  border: 1px solid #d1d5db;
  border-radius: 0.75rem;
}
```

#### Conceitos essenciais

- **Seletores:** identificam elementos, classes, IDs, atributos, estados e relações.
- **Cascata:** regras podem entrar em conflito; origem, especificidade e ordem influenciam o resultado.
- **Box model:** cada elemento possui `content`, `padding`, `border` e `margin`.
- **Display:** `block`, `inline`, `inline-block`, `flex` e `grid` alteram o comportamento do layout.
- **Flexbox:** ideal para organizar itens em uma dimensão, em linha ou coluna.
- **Grid:** ideal para layouts em duas dimensões, com linhas e colunas.
- **Responsividade:** media queries, unidades relativas e layouts fluidos adaptam a interface a diferentes telas.
- **Pseudo-classes e pseudo-elementos:** permitem estilizar estados e partes específicas, como `:hover`, `:focus` e `::before`.

#### Exemplo responsivo

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
}

@media (max-width: 48rem) {
  .container {
    grid-template-columns: 1fr;
  }
}
```

#### Boas práticas de CSS

- Prefira classes reutilizáveis e evite estilos inline sem necessidade.
- Use `box-sizing: border-box` para tornar os cálculos de tamanho mais previsíveis.
- Priorize `rem`, `%`, `fr`, `minmax()` e outras unidades adequadas ao contexto.
- Estilize também os estados `:focus` e `:focus-visible`.
- Organize o CSS por componentes e mantenha nomes de classes claros.

### JavaScript

JavaScript é uma linguagem de programação que permite adicionar lógica e interatividade à página.

#### Variáveis e funções

```javascript
const nome = "Pessoa estudante";

function criarSaudacao(usuario) {
  return `Olá, ${usuario}!`;
}

console.log(criarSaudacao(nome));
```

#### Conceitos essenciais

- **Tipos de dados:** string, number, boolean, null, undefined, bigint, symbol e object.
- **Variáveis:** prefira `const` quando a referência não será reatribuída e use `let` quando ela precisar mudar.
- **Operadores:** aritméticos, relacionais, lógicos e de atribuição.
- **Controle de fluxo:** `if`, `else`, `switch`, `for`, `while` e `for...of`.
- **Funções:** encapsulam comportamentos e podem receber parâmetros e retornar valores.
- **Arrays e objetos:** estruturam coleções e dados relacionados.
- **DOM:** representação do documento que pode ser lida e alterada pelo JavaScript.
- **Eventos:** permitem reagir a ações como clique, digitação e envio de formulário.
- **Escopo:** define onde variáveis e funções podem ser acessadas.

#### Manipulação do DOM e eventos

```html
<button id="botao-saudacao" type="button">Mostrar saudação</button>
<p id="mensagem" aria-live="polite"></p>
```

```javascript
const botao = document.querySelector("#botao-saudacao");
const mensagem = document.querySelector("#mensagem");

botao.addEventListener("click", () => {
  mensagem.textContent = "A interação funcionou!";
});
```

#### Boas práticas de JavaScript

- Use `===` e `!==` para comparações estritas, salvo quando houver um motivo documentado para fazer diferente.
- Separe funções com responsabilidades pequenas e nomes expressivos.
- Valide entradas de usuários e não confie cegamente em dados externos.
- Use `textContent` quando quiser inserir texto sem interpretar HTML.
- Evite variáveis globais e prefira escopo local.
- Utilize as ferramentas do navegador para observar erros, eventos e valores.

### Integração entre as tecnologias

Um fluxo comum é:

1. **HTML:** cria um formulário, botão ou área de conteúdo.
2. **CSS:** define aparência, espaçamento, estados e adaptação para telas diferentes.
3. **JavaScript:** captura uma ação, valida dados e atualiza o DOM.
4. **DevTools:** ajuda a inspecionar elementos, estilos, console e rede.
5. **Acessibilidade e testes:** confirmam se a solução pode ser utilizada por diferentes pessoas e dispositivos.

---

## 7. Glossário

| Conceito | Definição |
|---|---|
| **Acessibilidade** | Prática de tornar conteúdo e interfaces utilizáveis por pessoas com diferentes capacidades. |
| **Atributo** | Informação adicional incluída na tag HTML, como `href`, `alt` ou `class`. |
| **Box model** | Modelo que representa um elemento como conteúdo, preenchimento, borda e margem. |
| **Cascata** | Mecanismo que decide quais regras CSS serão aplicadas quando há conflitos. |
| **Classe** | Identificador reutilizável usado principalmente para selecionar elementos no CSS e JavaScript. |
| **DOM** | Estrutura em memória que representa o documento HTML e pode ser manipulada por scripts. |
| **Evento** | Acontecimento detectável, como clique, carregamento ou envio de formulário. |
| **Flexbox** | Modelo de layout CSS para organizar itens em uma dimensão. |
| **Grid** | Modelo de layout CSS baseado em linhas e colunas. |
| **HTML semântico** | Uso de elementos que expressam o significado de seu conteúdo. |
| **ID** | Identificador que deve ser único dentro de um documento HTML. |
| **JavaScript** | Linguagem que implementa lógica e interatividade em páginas e aplicações. |
| **Media query** | Regra CSS condicional usada, entre outras coisas, para responsividade. |
| **Responsividade** | Capacidade de uma interface adaptar-se a diferentes tamanhos e condições de tela. |
| **Seletor** | Padrão usado pelo CSS para escolher elementos que receberão estilos. |
| **Semântica** | Relação entre a estrutura utilizada e o significado do conteúdo. |
| **Viewport** | Área visível da página no dispositivo ou janela do navegador. |

---

## 8. Prompts reutilizáveis

### Para aprender um conceito

> Explique **[CONCEITO]** em **[TECNOLOGIA]** para uma pessoa iniciante. Use uma definição curta, um exemplo mínimo executável, um caso de uso e três erros comuns. Baseie a resposta nas fontes do notebook e indique quais referências foram utilizadas.

### Para comparar conceitos

> Compare **[CONCEITO A]** e **[CONCEITO B]** em uma tabela com definição, sintaxe, vantagens, limitações, exemplo e situação em que cada um deve ser preferido.

### Para revisar

> Crie um quiz com 10 perguntas sobre **[TEMA]**, misturando múltipla escolha e resposta curta. Faça uma pergunta por vez, aguarde minha resposta, corrija com explicação e cite a fonte relacionada.

### Para depurar HTML/CSS

> Analise este código HTML/CSS. O problema observado é **[DESCREVA O PROBLEMA]**. Liste as hipóteses em ordem de probabilidade, explique como testar cada uma e proponha a menor correção possível. Não altere partes que não estejam relacionadas ao problema.

### Para depurar JavaScript

> Analise este código JavaScript e o erro **[COLE O ERRO]**. Explique a causa em linguagem simples, aponte a linha ou comportamento responsável, mostre a correção mínima e sugira um teste para evitar que o problema volte.

### Para acessibilidade

> Avalie este HTML e indique problemas de acessibilidade relacionados a semântica, teclado, formulários, contraste, foco e textos alternativos. Separe os achados por prioridade e apresente correções justificadas.

### Para criar exercícios

> Crie três exercícios progressivos sobre **[TEMA]**: básico, intermediário e desafio. Para cada um, informe requisitos, critérios de conclusão, dicas sem entregar a solução e uma solução comentada para conferência posterior.

### Para consolidar o aprendizado

> Com base nas fontes do notebook, produza um resumo de **[TEMA]** em até 300 palavras, seguido de: conceitos indispensáveis, exemplo de código, armadilhas, perguntas para autoavaliação e referências utilizadas.

---

## 9. Projeto prático sugerido

Para aplicar os conhecimentos, desenvolva uma **página de perguntas frequentes sobre HTML, CSS e JavaScript** com os seguintes requisitos:

- Estrutura semântica com HTML;
- Cabeçalho, navegação, conteúdo principal e rodapé;
- Cards ou seções para os três temas;
- Layout responsivo com Flexbox ou Grid;
- Campo de busca ou filtro implementado com JavaScript;
- Botões para expandir e recolher respostas;
- Validação visual de estados de foco e interação;
- Uso de `aria-expanded` e `aria-live` quando necessário;
- README explicando decisões, dificuldades e fontes consultadas.

### Critérios de conclusão

- A página funciona em telas pequenas e grandes;
- O HTML possui hierarquia e semântica coerentes;
- O CSS está organizado e não depende de ajustes arbitrários;
- O JavaScript não apresenta erros no console;
- A interação funciona por mouse e teclado;
- O projeto contém instruções para execução e referências.

---

## 10. Conclusão e próximos passos

O estudo de HTML, CSS e JavaScript é mais eficiente quando combina leitura, consulta, prática e reflexão sobre os erros. O NotebookLM ajuda a organizar as fontes e acelerar a formulação de perguntas, mas a qualidade da aprendizagem depende da capacidade de verificar as respostas e transformar explicações em código executável.

### Próximos passos

- Revisar os conceitos usando o quiz e os prompts deste guia;
- Completar o projeto prático sugerido;
- Validar o HTML e testar a acessibilidade;
- Estudar JavaScript assíncrono, consumo de APIs e módulos;
- Aprofundar Flexbox, Grid, animações e arquitetura CSS;
- Aprender Git, testes, ferramentas de build e um framework front-end;
- Atualizar este README com novos exemplos, dúvidas e aprendizados.

---

## Licença e atribuição

Este material foi produzido para fins educacionais. As fontes externas pertencem aos seus respectivos autores e devem ser consultadas de acordo com suas licenças e termos de uso. Os links foram incluídos para estudo e referência.
