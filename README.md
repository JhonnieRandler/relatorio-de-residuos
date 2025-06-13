# 📄 Relatório de Resíduos Gerados

[![Licença MIT](https://img.shields.io/badge/Licen%C3%A7a-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 🚀 Sobre o Projeto

O "Relatório de Resíduos Gerados" é uma ferramenta web prática e gratuita desenvolvida para auxiliar na gestão de resíduos. Ela permite a extração de dados relevantes de arquivos PDF de MTR (Manifesto de Transporte de Resíduos) e a geração de relatórios e gráficos interativos para uma análise eficiente do histórico de resíduos.

O objetivo principal é simplificar o processo de acompanhamento e visualização dos dados de resíduos, tornando-o acessível e fácil de usar para qualquer pessoa ou empresa que precise gerenciar seus registros.

## ✨ Funcionalidades

- **Extração de Dados de PDFs:** Analisa arquivos PDF de MTR para extrair automaticamente informações como data de emissão, número do MTR, transportador, destinador, tipo de resíduo, ticket e quantidades (litros/toneladas).
- **Geração de Relatórios:** Apresenta os dados extraídos em uma tabela clara e organizada.
- **Visualização Gráfica:** Gera gráficos interativos (barras empilhadas) para visualizar a quantidade de resíduos por tipo (litros e toneladas).
- **Filtragem e Ordenação:** Permite filtrar dados por texto ou por mês e ordenar a tabela por qualquer coluna.
- **Copiar Dados:** Botão para copiar facilmente os dados da tabela para a área de transferência.
- **Download de Gráfico:** Opção para baixar o gráfico gerado como imagem (PNG).
- **Histórico Persistente:** Salva o histórico de dados processados no navegador (via `localStorage`), permitindo que você retome de onde parou e acompanhe seus registros ao longo do tempo.
- **Responsividade:** Design adaptável para funcionar bem em diferentes tamanhos de tela (desktops, tablets e celulares).

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura da página.
- **CSS3:** Estilização e layout responsivo.
- **JavaScript (ES6+):** Lógica da aplicação, extração de dados de PDF, manipulação do DOM e lógica de gráficos.
- **PDF.js:** Biblioteca JavaScript para renderizar e extrair texto de PDFs no navegador.
- **Chart.js:** Biblioteca JavaScript para criação de gráficos interativos.
- **Chartjs-plugin-datalabels:** Plugin para exibir rótulos de dados nos gráficos.
- **Font Awesome:** Ícones vetoriais.

## 🚀 Como Usar

### Instalação e Execução Local

Para executar este projeto em seu ambiente local:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/jhonnierandler/relatorio-de-residuos.git](https://github.com/jhonnierandler/relatorio-de-residuos.git)
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd relatorio-de-residuos
    ```
3.  **Abra os arquivos HTML:**
    - Você pode simplesmente abrir o arquivo `index.html` e `historico/index.html` em seu navegador.
    - Alternativamente, para uma melhor experiência de desenvolvimento (especialmente com caminhos de arquivos relativos), você pode usar uma extensão de servidor local como o `Live Server` para VS Code.

### Utilização da Aplicação

1.  **Página Inicial (`index.html`):**

    - Clique em "Selecionar PDFs" para carregar um ou mais arquivos PDF de MTR.
    - Os dados extraídos serão exibidos em uma tabela.
    - Clique em "Copiar" para copiar os dados da tabela.
    - Se houver dados salvos, um botão "Histórico" aparecerá para levá-lo à página de histórico.

2.  **Página de Histórico (`historico/index.html`):**
    - Visualize todos os dados de resíduos salvos no `localStorage` do seu navegador.
    - Use o campo "Filtrar..." para pesquisar dados específicos.
    - Use o seletor de mês para filtrar os dados por mês.
    - Clique nos cabeçalhos da tabela para ordenar os dados.
    - Clique em "Baixar Gráfico" para salvar o gráfico de resíduos como uma imagem PNG.
    - Clique em "Copiar" para copiar os dados da tabela atual.
    - Clique em "Apagar Histórico" para remover todos os dados salvos (com confirmação).
    - Use o botão "Voltar" para retornar à página inicial.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT.

## 📞 Contato

GitHub: [jhonnierandler](https://github.com/jhonnierandler)

Twitter: [@JhonnieRandler](https://twitter.com/JhonnieRandler)

LinkedIn: [jhonnierandler](https://linkedin.com/in/jhonnierandler/)

---

**Desenvolvido com 💚 por Jhon Randler**
