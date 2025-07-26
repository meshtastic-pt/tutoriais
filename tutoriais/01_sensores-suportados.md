# Sensores Compatíveis com Meshtastic

O firmware **Meshtastic** suporta uma variedade de sensores conectados via **I²C** para recolher dados ambientais e elétricos. Estes sensores são úteis para projetos que envolvem monitorização remota de temperatura, pressão, humidade, voltagem e corrente elétrica.

---

## 📋 Tabela de Sensores Suportados

| Sensor   | Endereço I²C     | Dados Fornecidos                                                       |
|----------|------------------|-------------------------------------------------------------------------|
| BMP280   | `0x76`, `0x77`   | Temperatura e pressão barométrica                                       |
| BME280   | `0x76`, `0x77`   | Temperatura, pressão barométrica e humidade                             |
| BME680   | `0x76`, `0x77`   | Temperatura, pressão, humidade e resistência do ar                      |
| MCP9808  | `0x18`           | Temperatura                                                             |
| INA260   | `0x40`, `0x41`   | Corrente e voltagem                                                     |
| INA219   | `0x40`, `0x41`   | Corrente e voltagem                                                     |
| LPS22    | `0x5D`, `0x5C`   | Pressão barométrica                                                     |
| SHTC3    | `0x70`           | Temperatura e humidade                                                  |
| SHT31    | `0x44`           | Temperatura e humidade                                                  |

> ℹ️ Certifique-se de que não há conflito de endereços I²C ao ligar múltiplos sensores.

---

## 🛠️ Como usar sensores com Meshtastic

1. Ligue o sensor aos pinos I²C (normalmente SDA e SCL) do seu dispositivo Meshtastic.
2. Verifique a alimentação correta (geralmente 3.3V).
3. Atualize o firmware Meshtastic para a versão mais recente.
4. O dispositivo detectará automaticamente os sensores compatíveis no arranque.

---

## ✅ Notas finais

- Alguns sensores, como o **BME680**, fornecem múltiplos tipos de dados úteis para aplicações em ambientes adversos.
- Sensores de corrente como o **INA260** são úteis em aplicações com painéis solares ou monitorização de bateria.
