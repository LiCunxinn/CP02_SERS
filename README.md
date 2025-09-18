# Checkpoint 02: Casos de Uso de ML - Energia Eólica e Energia Solar

## Instruções da Entrega
- A atividade pode ser desenvolvida em grupo.  
- Apenas um integrante deve submeter o arquivo.  
- **Enviar apenas o link do repositório.** Não envie arquivos .txt ou .pdf.  

---

## Integrantes

- Guilherme Spranger dos Santos  | 564059
- Gustavo Lemos Diógenes         | 565579 
- Pedro Paulo Barbosa Ross       | 563038
- Samuel de Souza Jorge          | 558966

---

## Dataset 1: Solar Radiation Prediction

**Descrição**:  
Este dataset contém registros de condições climáticas e medições de radiação solar. Ele pode ser utilizado para prever níveis de radiação solar ou realizar análises de fatores climáticos que influenciam na geração de energia solar.

- **Número de registros:** 32.686  
- **Número de atributos:** 11  

**Colunas principais**:
- `UNIXTime` → Timestamp no formato UNIX.  
- `Data` → Data completa em formato string.  
- `Time` → Hora da medição.  
- `Radiation` → Nível de radiação solar (variável alvo em tarefas de previsão).  
- `Temperature` → Temperatura (°F).  
- `Pressure` → Pressão atmosférica (inHg).  
- `Humidity` → Umidade relativa do ar (%).  
- `WindDirection(Degrees)` → Direção do vento em graus.  
- `Speed` → Velocidade do vento (mph).  
- `TimeSunRise` → Horário do nascer do sol.  
- `TimeSunSet` → Horário do pôr do sol.  

**Exemplo de registros**:

| UNIXTime   | Data                 | Time     | Radiation | Temperature | Pressure | Humidity | WindDirection(Degrees) | Speed | TimeSunRise | TimeSunSet |
|------------|----------------------|----------|-----------|-------------|----------|----------|-------------------------|-------|-------------|------------|
| 1475229326 | 9/29/2016 12:00:00 AM | 23:55:26 | 1.21      | 48          | 30.46    | 59       | 177.39                  | 5.62  | 06:13:00    | 18:13:00   |

---

## Dataset 2: Wind Turbine Scada Dataset

**Descrição**:  
Este dataset contém dados de produção de energia eólica, com informações sobre velocidade do vento, potência gerada e direção do vento. Ele é adequado para prever potência de turbinas eólicas ou comparar desempenho com base em condições atmosféricas.

- **Número de registros:** 50.530  
- **Número de atributos:** 5  

**Colunas principais**:
- `Date/Time` → Data e hora da medição.  
- `LV ActivePower (kW)` → Potência ativa gerada (kW).  
- `Wind Speed (m/s)` → Velocidade do vento (m/s).  
- `Theoretical_Power_Curve (KWh)` → Curva teórica de potência (KWh).  
- `Wind Direction (°)` → Direção do vento (graus).  

**Exemplo de registros**:

| Date/Time        | LV ActivePower (kW) | Wind Speed (m/s) | Theoretical_Power_Curve (KWh) | Wind Direction (°) |
|------------------|----------------------|------------------|-------------------------------|---------------------|
| 01 01 2018 00:00 | 380.05              | 5.31             | 416.33                        | 259.99              |

---
