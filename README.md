# 💻 Portfólio de Projetos - Shadowlkj

Bem-vindo ao meu portfólio! Aqui você encontra uma vitrine dos principais sistemas que desenvolvi. 
**Nota:** Por questões de segurança e propriedade intelectual, os códigos-fontes e executáveis de todos os sistemas são mantidos em repositórios privados. Abaixo, você pode ver as descrições técnicas e visuais do meu trabalho.

---

## 1. 🏬 Site Lojas Ditudo - E-commerce e Agendamento

Um sistema web completo desenvolvido para centralizar operações de uma rede de lojas de utilidades domésticas.

### 🛠️ Tecnologias Utilizadas
*   **Backend:** Java (Spring Boot)
*   **Frontend:** HTML5, CSS3, JavaScript
*   **Banco de Dados:** MySQL / MariaDB
*   **Integração:** Robô de WhatsApp desenvolvido em Node.js (`whatsapp-web.js`)

### 📌 Funcionalidades Principais
*   **Portal do Fornecedor:** Agendamento de entregas de forma automatizada.
*   **Robô Integrado:** Notificações via WhatsApp vinculadas diretamente ao painel.
*   **Painel Administrativo:** Gestão de filiais (Itapevi, Jandira, Osasco).

### 📸 Imagens do Projeto
![Tela Principal Lojas Ditudo](images/ditudo_site.png)

---

## 2. 📊 Programa de Conferência (Sistema Arius)

Um aplicativo desktop leve voltado para a conferência de divergências de estoque e transferência de arquivos, otimizado para o Sistema Arius.

### 🛠️ Tecnologias Utilizadas
*   **Plataforma:** Aplicação Web empacotada / Python (`inspect_xlsx.py`)
*   **Interface:** HTML, CSS, JavaScript (Processamento local)

### 📌 Funcionalidades Principais
*   **Comparador de Notas (EAN & QTD):** Ferramenta que cruza dois arquivos de texto padrão (`EAN;VALOR`), identificando itens faltantes ou divergência de quantidades.
*   **Processamento Offline:** Toda a lógica de comparação é executada diretamente no navegador/computador local, garantindo 100% de privacidade (nenhum dado de faturamento sobe para nuvem).
*   **Cálculo Matemático Embutido:** Conversão automática de unidades (divisão por 10.000 no formato do Arius).

---

## 3. 🧾 Calculadora de Nota Fiscal

Uma ferramenta web focada na automação do cálculo de impostos (com ênfase em ICMS-ST e Difal) para notas fiscais de entrada (compras interestaduais).

### 🛠️ Tecnologias Utilizadas
*   **Frontend:** HTML5, CSS3, Vanilla JavaScript (Local)
*   **Banco de Dados:** LocalStorage (Offline Data)
*   **Integração e Parsers:** Extração nativa de arquivos `.xml` da NF-e e planilhas de preços (XLSX/CSV) via SheetJS.

### 📌 Funcionalidades Principais
*   **Processamento de XML:** Preenche os itens da nota automaticamente através do upload do XML do fornecedor.
*   **Motor de Auto-aprendizado Tributário:** Calcula e armazena de forma persistente a MVA e Alíquotas Internas (São Paulo). Identifica sozinho os produtos que precisam de ST e ajusta a carga tributária conforme o ICMS de origem.
*   **Relatórios e Carga de Preços:** Importa os preços antigos via Excel, atualiza e gera arquivos prontos (JSON e CSV) para impressão ou arquivamento, sem depender de banco de dados externo ou servidores.

### 📸 Imagens do Projeto
![Ícone Calculadora de Nota Fiscal](images/calculadora_icon.png)
*(Recomendo adicionar um print da tela principal e salvar como `calculadora_nf.png` na pasta images!)*

---
*Para dúvidas ou contato profissional, entre em contato.*
