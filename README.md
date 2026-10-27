# Dashboard de RH e Indicadores de Pessoas | HR Dashboard & People Analytics

[![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)](https://sheets.google.com/)
[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=googleappsscript&logoColor=white)](https://developers.google.com/apps-script)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Português:** Dashboard de Recursos Humanos desenvolvido com Google Sheets e Google Apps Script para organizar informações de funcionários, acompanhar movimentações de pessoal e visualizar indicadores de gestão de pessoas.

**English:** A Human Resources dashboard built with Google Sheets and Google Apps Script to organize employee information, track workforce movements, and visualize people management indicators.

---

## Índice | Table of Contents

- [Português brasileiro](#português-brasileiro)
  - [Sobre o projeto](#sobre-o-projeto)
  - [Funcionalidades](#funcionalidades)
  - [Demonstração visual](#demonstração-visual)
  - [Tecnologias e requisitos](#tecnologias-e-requisitos)
  - [Configuração](#configuração)
  - [Como utilizar](#como-utilizar)
  - [Estrutura do projeto](#estrutura-do-projeto)
  - [Capturas de tela](#capturas-de-tela)
  - [Demonstração em vídeo](#demonstração-em-vídeo)
  - [Autor e licença](#autor-e-licença)
- [English](#english)
  - [About the project](#about-the-project)
  - [Features](#features)
  - [Visual demonstration](#visual-demonstration)
  - [Technologies and requirements](#technologies-and-requirements)
  - [Setup](#setup)
  - [How to use](#how-to-use)
  - [Project structure](#project-structure)
  - [Screenshots](#screenshots)
  - [Video demonstration](#video-demonstration)
  - [Author and license](#author-and-license)

---

# Português brasileiro

## Sobre o projeto

O **Dashboard de RH e Indicadores de Pessoas** é um projeto de organização e análise de dados de Recursos Humanos que utiliza Google Sheets, Google Apps Script e JavaScript.

O objetivo é facilitar a organização dos registros de funcionários e o acompanhamento de informações relacionadas à gestão de pessoas por meio de uma planilha automatizada.

O projeto foi desenvolvido como prática de análise de dados, automação de tarefas e construção de indicadores. A versão documentada utiliza diferentes abas para organizar as informações.

## Funcionalidades

O script documentado contempla:

- Organização de registros de funcionários.
- Registro de movimentações de pessoal, incluindo admissões e desligamentos.
- Organização de informações relacionadas ao absenteísmo.
- Processamento de indicadores por meio do Google Apps Script.
- Atualização dos indicadores do dashboard.
- Validação de dados conforme as regras definidas no código.
- Menu personalizado para acessar funções do projeto.
- Gráficos para visualizar indicadores configurados na planilha.
- Dados fictícios para demonstração inicial.

> **Importante:** esta documentação descreve a versão com múltiplas abas. A versão de aba única ainda precisa ser implementada e validada no código para que suas instruções correspondam ao comportamento final.

## Demonstração visual

As imagens abaixo são espaços reservados. Substitua os caminhos pelos arquivos de capturas de tela reais do projeto antes de publicar o README.

### Dashboard de RH

![Dashboard de RH](screenshots/dashboard.png)

*Captura real do painel com os indicadores e gráficos disponíveis.*

### Funcionários

![Tabela de funcionários](screenshots/funcionarios.png)

*Captura real da tabela de funcionários, sem dados pessoais ou confidenciais.*

### Movimentações de pessoal

![Movimentações de pessoal](screenshots/movimentacoes.png)

*Captura real da área de movimentações, caso esteja presente na versão publicada.*

### Absenteísmo

![Controle de absenteísmo](screenshots/absenteismo.png)

*Captura real da área de absenteísmo, caso esteja presente na versão publicada.*

## Tecnologias e requisitos

### Tecnologias

| Tecnologia | Utilização |
|---|---|
| Google Sheets | Organização e armazenamento dos dados. |
| Google Apps Script | Automação e execução das funções da planilha. |
| JavaScript | Processamento dos dados e cálculo dos indicadores. |
| Gráficos do Google Sheets | Visualização gráfica dos indicadores configurados. |

### Requisitos

- Conta Google.
- Acesso ao Google Sheets.
- Acesso ao editor do Google Apps Script.
- Navegador atualizado com conexão à internet.
- Permissão para editar a planilha e autorizar a execução do script.

Não é necessário instalar um ambiente de desenvolvimento local para utilizar o projeto diretamente no Google Sheets.

## Configuração

### 1. Criar a planilha

1. Acesse [Google Sheets](https://sheets.google.com/).
2. Crie uma planilha em branco.
3. Defina um nome, como `Dashboard de RH`.

### 2. Abrir o editor do Apps Script

1. Na planilha, acesse **Extensões → Apps Script**.
2. O editor será aberto em outra guia.
3. Localize o arquivo de código do projeto.

### 3. Adicionar o código do projeto

1. Utilize o código-fonte correspondente à versão do projeto.
2. Cole o código no editor.
3. Salve as alterações.
4. Confirme que as funções utilizadas nas instruções estão presentes no código.

Este README documenta o projeto e não substitui o código-fonte.

### 4. Executar a configuração inicial

Na versão documentada, a função de configuração é:

```javascript
configurarProjetoRH()
```

1. Selecione a função na lista do editor.
2. Clique em **Executar**.
3. Siga as instruções de autorização do Google, se solicitadas.
4. Retorne à planilha e confira as abas criadas.

**Atenção:** a configuração pode limpar ou recriar abas do projeto. Faça uma cópia de segurança antes de executar o script em uma planilha que contenha informações importantes.

## Como utilizar

### Atualizar o dashboard

Depois da configuração:

1. Abra a planilha.
2. Aguarde o carregamento do menu personalizado **Gestão de RH**.
3. Selecione a opção de atualização dos indicadores.
4. Confira os valores e gráficos apresentados.

A função de atualização documentada é:

```javascript
atualizarDashboard()
```

### Validar os dados

A função de validação documentada é:

```javascript
validarDadosRH()
```

Execute-a pelo editor do Apps Script para realizar as verificações previstas no código.

### Boas práticas

- Utilize dados fictícios para testes e demonstrações.
- Revise os registros antes de atualizar os indicadores.
- Confirme se os gráficos representam os dados esperados.
- Não publique informações pessoais ou confidenciais de funcionários.
- Mantenha uma cópia de segurança antes de alterações importantes.

Os resultados dependem dos dados inseridos e das regras presentes no código. Este README não apresenta resultados empresariais reais.

## Estrutura do projeto

Estrutura sugerida para organizar o código e a documentação no GitHub:

```text
dashboard-rh/
├── README.md
├── Código.gs
└── screenshots/
    ├── dashboard.png
    ├── funcionarios.png
    ├── movimentacoes.png
    └── absenteismo.png
```

A pasta `screenshots/` e os arquivos de imagem são sugestões de organização. Adicione-os somente quando as capturas reais estiverem disponíveis.

### Abas da versão documentada

| Aba | Finalidade |
|---|---|
| `Painel de RH` | Exibição dos indicadores e gráficos. |
| `Funcionários` | Organização dos registros de funcionários. |
| `Movimentações` | Registro de admissões e desligamentos. |
| `Absenteísmo` | Organização de informações sobre ausências. |
| `Indicadores` | Dados processados para o dashboard. |

Esta tabela descreve a configuração com múltiplas abas. Se o código for atualizado para utilizar apenas uma aba, revise esta seção para refletir a estrutura final.

## Capturas de tela

Para adicionar imagens reais ao repositório:

1. Abra a planilha no Google Sheets.
2. Capture a tela do dashboard ou da área desejada.
3. Oculte informações pessoais e confidenciais.
4. Salve a imagem em PNG.
5. No GitHub, crie a pasta `screenshots/`.
6. Envie a imagem com o nome correspondente ao caminho usado no README.

Exemplo de Markdown:

```markdown
![Dashboard de RH](screenshots/dashboard.png)
```

O GitHub exibirá a imagem quando o arquivo existir nesse caminho no repositório.

## Demonstração em vídeo

Uma gravação real ainda não foi disponibilizada neste README.

Para adicionar uma demonstração posteriormente:

1. Grave a utilização da planilha.
2. Mostre a atualização dos indicadores e os gráficos existentes.
3. Oculte informações pessoais.
4. Publique o vídeo em uma plataforma de sua preferência.
5. Substitua o texto abaixo pelo link real.

**Vídeo de demonstração:** a adicionar.

## Autor e licença

**Autor:** Israel Vitor

**GitHub:** [@vitor1914](https://github.com/vitor1914)

Este projeto faz parte de um portfólio de estudos em análise de dados, automação e organização de informações.

**Licença:** nenhuma licença específica foi informada. Caso deseje distribuir o projeto como código aberto, adicione um arquivo `LICENSE` com os termos escolhidos.

---

# English

## About the project

**HR Dashboard & People Analytics** is a Human Resources data organization and analysis project built with Google Sheets, Google Apps Script, and JavaScript.

Its purpose is to organize employee records and help users monitor people management information through an automated spreadsheet.

The project provides practical experience in data analysis, task automation, and indicator development. The documented version uses multiple spreadsheet tabs to organize information.

## Features

The documented script includes:

- Organization of employee records.
- Workforce movement records, including hiring and terminations.
- Organization of absenteeism-related information.
- Indicator processing through Google Apps Script.
- Dashboard indicator updates.
- Data validation according to the rules defined in the code.
- A custom menu for accessing project functions.
- Charts for visualizing configured spreadsheet indicators.
- Fictional data for initial demonstrations.

> **Important:** this documentation describes the multiple-tab version. A single-tab version must be implemented and validated in the code before its instructions can accurately describe that behavior.

## Visual demonstration

The images below are placeholders. Replace the paths with actual project screenshots before publishing the README.

### HR dashboard

![HR Dashboard](screenshots/dashboard.png)

*Actual screenshot of the dashboard and its available indicators and charts.*

### Employee records

![Employee records](screenshots/funcionarios.png)

*Actual screenshot of the employee table, with personal and confidential information removed.*

### Workforce movements

![Workforce movements](screenshots/movimentacoes.png)

*Actual screenshot of the workforce movements area, if available in the published version.*

### Absenteeism

![Absenteeism tracking](screenshots/absenteismo.png)

*Actual screenshot of the absenteeism area, if available in the published version.*

## Technologies and requirements

### Technologies

| Technology | Purpose |
|---|---|
| Google Sheets | Data organization and storage. |
| Google Apps Script | Spreadsheet automation and function execution. |
| JavaScript | Data processing and indicator calculations. |
| Google Sheets charts | Visual representation of configured indicators. |

### Requirements

- A Google account.
- Access to Google Sheets.
- Access to the Google Apps Script editor.
- An up-to-date web browser with internet access.
- Permission to edit the spreadsheet and authorize script execution.

A local development environment is not required to use the project directly in Google Sheets.

## Setup

### 1. Create the spreadsheet

1. Open [Google Sheets](https://sheets.google.com/).
2. Create a blank spreadsheet.
3. Give it a name, such as `HR Dashboard`.

### 2. Open the Apps Script editor

1. In the spreadsheet, select **Extensions → Apps Script**.
2. The editor will open in a new tab.
3. Locate the project's source code file.

### 3. Add the project code

1. Use the source code corresponding to the project version.
2. Paste it into the editor.
3. Save your changes.
4. Verify that the functions mentioned in these instructions exist in the source code.

This README documents the project and does not replace its source code.

### 4. Run the initial setup

In the documented version, the setup function is:

```javascript
configurarProjetoRH()
```

1. Select the function in the editor.
2. Click **Run**.
3. Follow Google's authorization instructions if prompted.
4. Return to the spreadsheet and review the created tabs.

**Important:** the setup may clear or recreate project tabs. Back up the spreadsheet before running the script on a file containing important information.

## How to use

### Update the dashboard

After setup:

1. Open the spreadsheet.
2. Wait for the custom **Gestão de RH** menu to load.
3. Select the option to update the indicators.
4. Review the displayed values and charts.

The documented update function is:

```javascript
atualizarDashboard()
```

### Validate the data

The documented validation function is:

```javascript
validarDadosRH()
```

Run it from the Apps Script editor to perform the checks defined in the code.

### Best practices

- Use fictional data for testing and demonstrations.
- Review records before updating indicators.
- Confirm that charts represent the expected data.
- Do not publish personal or confidential employee information.
- Keep a backup before making important changes.

Results depend on the entered data and the rules implemented in the code. This README does not report real business results.

## Project structure

Suggested structure for organizing the source code and documentation on GitHub:

```text
hr-dashboard/
├── README.md
├── Código.gs
└── screenshots/
    ├── dashboard.png
    ├── funcionarios.png
    ├── movimentacoes.png
    └── absenteismo.png
```

The `screenshots/` directory and image files are suggested organizational elements. Add them only when real screenshots are available.

### Tabs in the documented version

| Tab | Purpose |
|---|---|
| `Painel de RH` | Display of indicators and charts. |
| `Funcionários` | Organization of employee records. |
| `Movimentações` | Hiring and termination records. |
| `Absenteísmo` | Organization of absence-related information. |
| `Indicadores` | Processed data for the dashboard. |

This table describes the multiple-tab setup. If the source code is updated to use only one tab, revise this section to match the final structure.

## Screenshots

To add actual screenshots to the repository:

1. Open the spreadsheet in Google Sheets.
2. Capture the dashboard or the desired area.
3. Hide personal and confidential information.
4. Save the image as a PNG file.
5. Create the `screenshots/` directory in the GitHub repository.
6. Upload the image using the filename referenced in the README.

Markdown example:

```markdown
![HR Dashboard](screenshots/dashboard.png)
```

GitHub will display the image when the file exists at the referenced path in the repository.

## Video demonstration

No actual video recording has been provided in this README.

To add a demonstration later:

1. Record the spreadsheet in use.
2. Show the indicator updates and existing charts.
3. Hide personal information.
4. Publish the video on your preferred platform.
5. Replace the placeholder below with the real link.

**Demonstration video:** to be added.

## Author and license

**Author:** Israel Vitor

**GitHub:** [@vitor1914](https://github.com/vitor1914)

This project is part of a learning portfolio focused on data analytics, automation, and information organization.

**License:** no specific license has been provided. If you intend to distribute the project as open-source software, add a `LICENSE` file containing your chosen terms.