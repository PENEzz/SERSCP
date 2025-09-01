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
