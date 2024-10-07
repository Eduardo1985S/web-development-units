# 🎨 Comparação de Unidades de Medida no CSS

Este projeto demonstra, de maneira visual e prática, como diferentes **unidades de medida** em CSS (absolutas e relativas) afetam o layout de uma página web. Através de **quadrados coloridos**, você poderá observar o comportamento dessas unidades ao alterar o **zoom** da página ou ao redimensionar a janela do navegador.

## 📋 Objetivo do Projeto

O principal objetivo deste projeto é ajudar desenvolvedores e estudantes de **desenvolvimento web** a compreenderem como as diferentes unidades de medida em CSS se comportam em relação ao layout de uma página. Isso inclui o uso de unidades **absolutas** como pixels e centímetros, e **relativas**, como `em`, `rem`, e `vw`.

----------

## 🚀 Funcionalidades

-   🟥 **Visualização prática** de unidades absolutas (`px`, `cm`, `mm`, `in`, `pt`, `pc`).
-   🟩 **Demonstração de unidades relativas** (`em`, `rem`, `%`, `vw`, `vh`), mostrando como elas respondem ao zoom e redimensionamento da janela.
-   🟦 **Layout dinâmico e responsivo** com exemplos fáceis de entender para cada tipo de unidade.
-   🔍 **Interatividade**: Teste o comportamento dos elementos ajustando o zoom ou o tamanho da janela.

----------

## 📚 Unidades Utilizadas

### 🔵 **Unidades Absolutas:**

-   **px (Pixel):** Unidade fixa e padrão. Não muda com o zoom.
-   **cm (Centímetro):** Unidade baseada no tamanho físico real.
-   **mm (Milímetro):** Um milésimo de um metro, mais preciso que centímetros.
-   **in (Polegada):** Unidade física, onde 1 polegada equivale a 2,54 cm.
-   **pt (Ponto):** Tradicionalmente usado em tipografia, 1pt = 1/72 de polegada.
-   **pc (Pica):** Outra unidade tipográfica, onde 1 pica = 12 pontos.

### 🟡 **Unidades Relativas:**

-   **em:** Relativo ao tamanho da fonte do elemento pai.
-   **rem:** Relativo ao tamanho da fonte do elemento raiz (`html`).
-   **% (Porcentagem):** Relativo ao tamanho do elemento pai.
-   **vw (Viewport Width):** Relativo à largura da janela do navegador.
-   **vh (Viewport Height):** Relativo à altura da janela do navegador.

----------

## 🛠️ Tecnologias Utilizadas

-   **HTML5**: Para estruturação do conteúdo da página.
-   **CSS3**: Para estilização e layout, utilizando diversas unidades de medida.
-   **Flexbox**: Para organização dos elementos em um layout responsivo e flexível.

----------

## 📂 Estrutura do Projeto

`comparacao-unidades-css/
├── index.html      # O arquivo principal com o código HTML e CSS integrado
└── README.md       # Instruções e informações do projeto` 

----------

## 🔧 Como Usar

1.  **Clone o repositório**:
       
    `git clone https://github.com/usuario/comparacao-unidades-css.git` 
    
2.  **Abra o arquivo HTML**: Navegue até o diretório clonado e abra o arquivo `index.html` no seu navegador de preferência:
    
    `cd comparacao-unidades-css
    open index.html` 
    
3.  **Explore o comportamento das unidades**:
    
    -   **Ajuste o zoom** (Ctrl + ou Ctrl -) e observe como os quadrados que usam **unidades relativas** mudam de tamanho.
    -   **Redimensione a janela** para ver como as unidades de `vw` (largura da viewport) e `vh` (altura da viewport) reagem.

----------

## 👀 Exemplos Práticos

### 🎯 Unidades Absolutas:

-   **Pixel (`px`)**: Não é afetado por zoom. Ótimo para elementos que exigem tamanhos fixos, como ícones.
-   **Centímetros (`cm`)**: Útil para impressões ou documentos físicos, mas raramente usado em layouts web.

### ⚡ Unidades Relativas:

-   **Em (`em`)**: Escala com o tamanho da fonte do elemento pai. Excelente para componentes que precisam ser adaptáveis ao contexto.
-   **Rem (`rem`)**: Escala com base no tamanho de fonte do elemento raiz. Proporciona maior consistência em layouts.
-   **Viewport Width (`vw`) e Viewport Height (`vh`)**: Muito úteis em **designs responsivos**. Eles se ajustam automaticamente ao tamanho da tela, tornando layouts fluídos.

----------

## 📖 Recursos Adicionais

### 🎓 Leitura Recomendada:

-   [Documentação oficial do CSS sobre unidades de medida](https://developer.mozilla.org/pt-BR/docs/Web/CSS/length)
-   Guia completo de flexbox

### 🛠 Ferramentas Online:

-   CSS Units Converter - Converta entre diferentes unidades de medida no CSS.

----------

## ❓ Perguntas Frequentes (FAQ)

### 1. **Qual a diferença entre `em` e `rem`?**

-   **`em`** é relativo ao tamanho da fonte do elemento pai. Por exemplo, se o elemento pai tem `font-size: 16px`, 1em será igual a 16px.
-   **`rem`** é relativo ao tamanho da fonte do elemento raiz (`html`). Ele é mais previsível, pois o valor base de `rem` não muda dentro de elementos aninhados.

### 2. **Quando usar `vw` e `vh`?**

Essas unidades são ideais para criar layouts que se ajustam ao tamanho da janela do navegador, como em designs responsivos que precisam cobrir uma porcentagem da tela independentemente do dispositivo.

----------

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Veja como você pode contribuir:

1.  Faça um **fork** deste repositório.
2.  Crie uma **branch** com sua feature: `git checkout -b minha-feature`.
3.  Faça o **commit** das suas alterações: `git commit -m 'Minha nova feature'`.
4.  **Envie para o repositório**: `git push origin minha-feature`.
5.  Abra um **Pull Request**.

----------

## 📝 Licença

Este projeto está licenciado sob a Licença MIT.

----------

### ✨ Inspiração

Este repositório foi criado com o objetivo de proporcionar uma maneira interativa e simples para desenvolvedores e estudantes aprenderem sobre o comportamento das unidades de medida no CSS. Esperamos que este projeto ajude você a entender melhor o impacto das diferentes unidades no layout e na responsividade!

----------

### 👨‍🏫 Autor

**Eduardo Correia**  
Docente no curso técnico em Desenvolvimento de Sistemas, especializado em Linguagens de Marcação e desenvolvimento front-end.

----------

### 📩 Contato

Se tiver dúvidas, sugestões ou feedback, fique à vontade para entrar em contato:  
📧 Email: seunome@email.com  
🌐 LinkedIn: [Eduardo Correia](https://www.linkedin.com/in/eduardo-correia-dev/)
