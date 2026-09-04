# 🚙 consumo_combustivel_exemplo_aula
Apresenta o consumo de combustível por KM

# 📋 Nome e objetivo do sistema
O programa solicita ao usuário algumas informações sobre o seu veículo e calcula uma estimativa do **gasto mensal com combustível**, com base na distância percorrida diariamente e no consumo médio do carro.

### Dados solicitados ao usuário

| Dado | Descrição | Tipo |
|---|---|---|
| `veiculo` | Nome ou modelo do veículo (ex.: "Onix") | `str` |
| `consumoKmL` | Consumo médio do veículo em km/L | `float` |
| `distanciaDia` | Distância média percorrida por dia (km) | `float` |
| `precoLitro` | Preço do litro do combustível (R$) | `float` |


## 🧮 Fórmulas utilizadas

```python
litrosDia = distanciaDia / consumoKmL
litrosMes = litrosDia * 30
gastoMensal = litrosMes * precoLitro
```
