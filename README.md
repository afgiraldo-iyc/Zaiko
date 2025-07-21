# Zaiko
Agente Financiero especializado en el análisis de proveedores en Colombia. Analizarla información financiera** de proveedores identificados por su **RUT o NIT**, utilizando como base de conocimiento una serie de archivos de Excel que contienen los Estados Financieros para el año 2024.

# 🤖 Agente GPT - Analizador Financiero de Proveedores

Este repositorio contiene la configuración y los archivos fuente para un **Agente GPT personalizado** diseñado para **analizar información financiera de proveedores en Colombia**. El análisis se realiza a partir del número de NIT/RUT del proveedor, utilizando como base de conocimiento estados financieros en formato Excel correspondientes al año 2024.

---

## 📌 Funcionalidad

El agente GPT:
- Saluda al usuario y solicita el número de NIT o RUT.
- Busca en los archivos cargados toda la información financiera disponible del proveedor.
- Realiza análisis financieros automáticos, incluyendo:

### 🔍 Análisis realizado
- **Rentabilidad:**
  - Margen bruto
  - Margen neto
  - ROE (Return on Equity)
  - ROA (Return on Assets)
- **Liquidez y Endeudamiento:**
  - Razón corriente
  - Nivel de endeudamiento total
- **Clasificación del proveedor:**
  - Pyme o Empresa Plena
- **Comparación de desempeño:**
  - Frente al promedio del segmento (Pymes vs Plenas)
- **Ranking financiero:**
  - Posición relativa basada en utilidad neta o rentabilidad

---

## 🗂 Archivos de entrada requeridos

Los siguientes archivos Excel deben cargarse al agente GPT:

- `EFE 2024 Pymes individuales.xlsx`
- `EFE Plenas Individuales 2024.xlsx`
- `EFE Plenas Separadas 2024.xlsx`
- `EFE Pymes Separadas 2024.xlsx`
- `ERI 2024 Pymes individuales.xlsx`
- `ERI Plenas Individuales 2024.xlsx`
- `ERI Plenas Separadas 2024.xlsx`
- `ESF 2024 Pymes individuales.xlsx`
- `ESF Pymes Separadas 2024.xlsx`

Cada archivo contiene registros de múltiples proveedores, identificados por su número de **NIT**.

---

## 💬 Ejemplo de uso

```plaintext
👤 Usuario: Hola

🤖 GPT: ¡Hola! Bienvenido al Analizador Financiero de Proveedores. Por favor, indícame el número de NIT o RUT del proveedor que deseas consultar.

👤 Usuario: 800000241

🤖 GPT:
Proveedor: CERERIA EL SAGRADO CORAZÓN LTDA  
Tipo: Pyme  
Año: 2024

📈 Rentabilidad:
- Margen Bruto: 48.4%
- Margen Neto: 4.3%

💧 Liquidez:
- Razón Corriente: 2.65

📊 Endeudamiento:
- Nivel: 38%

📉 Comparación con otras PYMES:
- Rentabilidad superior al promedio

🏅 Ranking:
- Posición 45 de 200
