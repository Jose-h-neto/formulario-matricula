# Formulário de Matrícula - Estrelas do Amanhã

Projeto front-end desenvolvido com HTML e CSS que apresenta um formulário de matrícula para a escola de educação infantil Estrelas do Amanhã, com foco em experiência do usuário.

## Visão geral

Este projeto simula um formulário completo de matrícula em uma instituição de educação infantil. A aplicação coleta informações sobre a criança, dados médicos, documentação e endereço residencial de forma organizada e intuitiva.

O foco está na construção de um layout intuitivo, formulários bem estruturados e apresentação visual profissional com feedback visual ao usuário.

## Objetivos

* Reforçar fundamentos de HTML semântico e formulários
* Praticar construção de layouts com CSS avançado
* Implementar validações e feedback visual em formulários
* Simular interfaces reais de aplicações web
* Melhorar a organização e modularização de código front-end
* Criar componentes reutilizáveis (inputs, selects, checkboxes, etc)

## Estrutura do projeto

```
FORMULARIO-MATRICULA
├── assets/
├── styles/
│   ├── fields/
│   │   ├── buttons.css
│   │   ├── checkbox.css
│   │   ├── droparea.css
│   │   ├── index.css
│   │   ├── input.css
│   │   └── radio.css
│   ├── forms.css
│   ├── global.css
│   ├── index.css
│   └── layout.css
└── index.html
```

## Funcionalidades

* Formulário de matrícula com múltiplas seções
* Coleta de informações da criança (nome, data de nascimento, sexo)
* Campo de informações médicas
* Upload de documentação
* Coleta de endereço residencial
* Validação de campos obrigatórios
* Estados visuais para inputs (focus, invalid, disabled)
* Componentes visuais bem definidos com ícones SVG

## Tecnologias utilizadas

* HTML5
* CSS3

## Organização do CSS

O projeto utiliza separação de estilos por responsabilidade e componentes:

* `global.css`: estilos base e variáveis
* `layout.css`: estrutura geral da página
* `forms.css`: estilos de formulários
* `fields/input.css`: inputs e textareas
* `fields/buttons.css`: botões
* `fields/checkbox.css`: checkboxes
* `fields/radio.css`: radio buttons
* `fields/droparea.css`: área de upload
* `index.css`: importação centralizada dos estilos

## Como executar

1. Abra o arquivo `index.html` no navegador

ou

2. Utilize um servidor local (recomendado)

   * Ex: Live Server no VS Code

## Aprendizados

Durante o desenvolvimento, foram reforçados conceitos como:

* Estruturação semântica de formulários
* Estilização de inputs e elementos de formulário
* Uso de pseudo-classes (`:focus`, `:invalid`, `:disabled`)
* Separação de responsabilidades no CSS
* Organização de projeto front-end modular
* Construção de interfaces acessíveis
* Validação e feedback visual para o usuário

## Autor

José Neto
