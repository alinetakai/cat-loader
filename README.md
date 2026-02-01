# 🐱 Cat Loader – CSS Animation

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)

Este é um projeto para fins educacionais, desenvolvido para estudo e experimentação de **animações avançadas em CSS**, utilizando **HTML semântico**, **metodologia BEM** e **@keyframes** para criar um loader animado em formato de gato. O projeto explora conceitos visuais, animação contínua e composição gráfica utilizando apenas CSS, sem JavaScript.

---

## 🎯 Objetivo do Projeto

O objetivo deste projeto é aprofundar o conhecimento em animações CSS, explorando transformações, delays, pseudo-elementos e organização de código com BEM. A ideia é criar um loader criativo, visualmente interessante e reutilizável para aplicações web.

---

## 🧠 Conceitos Utilizados

### 🎨 CSS Reset e Layout Base

O projeto inicia com um reset básico para garantir consistência entre navegadores, além do uso de Flexbox para centralização perfeita do loader na tela.

### 🎞️ Animações com CSS

A animação principal é criada com `@keyframes`, utilizando rotações combinadas com `translateX`, gerando o efeito de movimento contínuo dos segmentos do gato.

### 🧱 Metodologia BEM (Block, Element, Modifier)

A organização das classes segue o padrão BEM para manter o código legível e escalável.

- **Block**: `.cat`
- **Element**: `.cat__segment`
- **Modifier**: aplicado por meio de seletores estruturais como `:first-of-type`, `:last-of-type` e `:nth-of-type`

---

## 🧩 Estrutura do Projeto

```text
├── index.html
└── style.css
```

O arquivo `index.html` contém a estrutura do loader e a repetição dos segmentos do gato.  
O arquivo `style.css` concentra todos os estilos, animações, gradientes e transformações responsáveis pelo efeito visual.

---

## 🖼️ Descrição da Interface

A interface apresenta uma tela com fundo sólido e um texto centralizado indicando o estado de carregamento. No centro da tela, um gato estilizado é animado em loop infinito, simulando movimento circular fluido. Cada segmento do corpo possui um pequeno atraso na animação, criando o efeito de onda e continuidade.

O rosto e a cauda do gato são construídos exclusivamente com gradientes CSS e pseudo-elementos, sem imagens externas.

---

## 🐾 Funcionamento da Animação

Cada segmento do gato é posicionado radialmente e animado individualmente com pequenos atrasos utilizando `animation-delay`. O efeito final é um movimento contínuo e suave, ideal para telas de carregamento.

A animação utiliza `cubic-bezier` para suavizar o movimento e `will-change` para melhorar a performance.

---

## 🚀 Como Executar o Projeto

1. Faça o download ou clone este repositório  
2. Abra o arquivo `index.html` em qualquer navegador moderno  
3. Observe a animação do loader em execução contínua  

Não é necessário instalar dependências, bibliotecas externas ou utilizar JavaScript.

---

## 🧪 Possíveis Evoluções

Adicionar controle de velocidade da animação.  
Criar variações de cor do gato.  
Transformar o loader em componente reutilizável.  
Integrar o loader em aplicações reais como tela de carregamento.

---

## 📄 Licença

- **Permissão de Uso:** O código pode ser usado somente para fins educacionais. Sinta-se livre para estudar, adaptar e evoluir o código, citando a autoria quando aplicável.
- **Modificação e Distribuição:** Qualquer pessoa pode modificar o código e redistribuí-lo, seja na forma original ou modificada, desde que citando autores.
- **Inclusão da Licença:** Ao redistribuir o software, a licença original e o aviso de direitos autorais devem ser incluídos no código fonte ou na documentação, garantindo que futuros usuários conheçam seus direitos.
- **Isenção de Garantia:** O software é fornecido "como está", sem garantias de qualquer tipo, explícitas ou implícitas. Os autores não são responsáveis por quaisquer danos decorrentes do uso do software.
