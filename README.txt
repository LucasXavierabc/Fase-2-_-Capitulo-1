# 📋 Modelo de Relações: Plantação, Quadrantes e Sensores

## 📊 **Relações do Modelo**

1. **Plantação ↔ Quadrantes**
   - Cada **Plantação** possui **4 Quadrantes**.
   - Cada **Quadrante** pertence a **apenas uma Plantação**.

2. **Quadrante ↔ Sensores**
   - Cada **Quadrante** possui um **Sensor de cada tipo**:
     - **S1**, **S2**, **S3**.
   - Cada **Sensor** pertence a **apenas um Quadrante**.

---

## 🔍 **Outras Informações**

1. **Plantação**
   - Atributos:
     - **Cultura** (tipo de cultivo, ex.: milho, soja, trigo).
     - **Área** (tamanho em hectares).

2. **Sensor**
   - Coleta os seguintes dados:
     - **Data e Hora** da coleta.
     - **Dado específico** do tipo de sensor (ex.: temperatura, umidade, etc.).

---