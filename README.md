# ✅ Checkpoint – Projeto em Grupo: **Site da Vinharia Agnello**

## 👩🏻‍💻 Equipe

- **Brenda Santos** – Página Principal  
- **Clara Barboza Costa** – História e Galeria  
- **Lucas Santana Silva** – Sobre Nós  
- **Pedro Henrique Lamin Rodrigues** – Produtos  

---

## 🧠 Descrição

A **Vinharia Agnello** é uma empresa familiar que atua no mercado de vinhos em São Paulo há mais de 15 anos.  
Inicialmente, estabeleceu-se com apenas uma loja física, oferecendo aos seus clientes uma vasta seleção de rótulos de vinícolas nacionais e internacionais.

---

## 📕 Identidade Visual

### 🎨 Paleta de Cores

- **Cor Principal:** `#593627`  
- **Cor de Fundo:** `rgb(255, 245, 224)`  
- **Espaços Negativos:** `rgb(255, 255, 255)`

---

### 🖋 Tipografia

- **Títulos (`h1`)**: *Cinzel*  
- **Subtítulos (`h2` a `h6`)**: *Merriweather*

---

## ✨ Efeitos Utilizados no CSS

| Seletor / Regra                   | Onde foi usado                                     | O que faz                                                                 |
|----------------------------------|----------------------------------------------------|---------------------------------------------------------------------------|
| `@keyframes fadeSlideIn`        | .titulos-inicio                                    | Faz o título surgir suavemente deslizando da direita                      |
| `.menu a:hover`                 | Links do menu                                      | Muda a cor e adiciona borda inferior ao passar o mouse                   |
| `.grid-cartao:hover`           | Cartões de conteúdo                                | Aumenta levemente o tamanho e adiciona sombra no hover                   |
| `.galeria img:hover`           | Imagens da galeria                                 | Expande largura e altura ao passar o mouse                               |
| `.botao:hover`                 | Botão de login                                     | Muda a cor de fundo, aplica fonte e centraliza o conteúdo                |
| `.caixa-depoimento::placeholder`| Campos de texto                                    | Muda a cor do texto placeholder para cinza claro                         |
| `.cont_hist article`, `#caixa_colorida` | Seções da história                         | Aparecem com fade e deslize de baixo para cima ao rolar a página         |
| `.menu ul li a:hover`          | Links da seção "Sobre Nós"                         | Adiciona sublinhado ao passar o mouse                                    |
| `main figure.banner::after`    | Sobreposição no banner                             | Adiciona camada escura sem interferir nos cliques                        |
| `tbody tr:nth-child(even)`     | Linhas pares de tabelas                            | Aplica fundo alternado (efeito zebrinha)                                 |
| `tbody tr:hover`               | Linhas de tabelas                                  | Muda o fundo da linha ao passar o mouse                                  |
| `@media (max-width: 768px)`    | Tabelas em telas pequenas                          | Torna a tabela responsiva com blocos e rótulos exibidos via data-label|

---

