# SERSCP

# Individual Household Electric Power Consumption — Análise e Tarefas

Este repositório contém um notebook no estilo do **"Cópia_de_NovoSERS.ipynb"**,
resolvendo um conjunto de tarefas sobre o dataset **Individual household electric power consumption** (IHEPC).

## 📦 Dataset
- **Fonte (UCI Machine Learning Repository):** https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption  
- **Arquivo principal:** `household_power_consumption.txt` (cerca de 2M linhas; período 2006-12-16 a 2010-11-26).  
- **Delimitador:** `;`
- **Decimais:** `.`
- **Valores ausentes:** `'?'`

> Colunas principais:
> - `Date` (dd/mm/yyyy), `Time` (HH:MM:SS)
> - `Global_active_power` (kilowatts)
> - `Global_reactive_power` (kilowatts)
> - `Voltage` (volts)
> - `Global_intensity` (ampere)
> - `Sub_metering_1`, `Sub_metering_2`, `Sub_metering_3` (watt-hour of active energy)

## 🗂️ Estrutura
```
IHEPC_Repo/
├─ README.md
├─ requirements.txt
└─ IHEPC_Tarefas.ipynb
```

## 🚀 Como executar
1. Baixe o arquivo **`household_power_consumption.txt`** do link da UCI e coloque-o na mesma pasta do notebook **ou** informe um caminho absoluto no parâmetro `data_path` da primeira célula.
2. Crie um ambiente e instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o notebook:
   ```bash
   jupyter lab IHEPC_Tarefas.ipynb
   ```

## 🧭 Guia das Tarefas (no estilo *NovoSERS*)
O notebook está dividido em partes com células de **Markdown** e **código** com cabeçalhos:
- **Parte 0 — Setup & Carregamento**
- **Parte 1 — Limpeza e Entendimento**
- **Parte 2 — Exploração Temporal**
- **Parte 3 — Agregações & Perfis de Consumo**
- **Parte 4 — Modelagem Baseline & Salvamento**

Cada **Tarefa** vem comentada em português, com explicações curtas e passos objetivos.
Sempre que possível, há validações, `assert`s e gráficos para interpretar os resultados.

## 📝 Observações
- O notebook tenta baixar automaticamente o dataset via URL. Caso a rede esteja bloqueada, faça o download manual e ajuste `data_path`.
- Gráficos são feitos com **matplotlib** (sem estilos customizados).
- O notebook salva saídas úteis em `./_out/`.
