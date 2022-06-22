# Comunicação com ESP32 via SPI - Master

Este código usa o exemplo da ESP-IDF `spi_slave/sender` como base. Ele configura o ESP32 para se comunicar com outras ESP32 via SPI.

## Como Usar

### Hardware Requerido

Este exemplo foi feito para e testado em placas ESP32-C3.

### Configurar o projeto

```
idf.py menuconfig
```

### Build e Flash

```
idf.py build
idf.py -p PORT flash monitor
```

(Toggle do monitor serial: ``Ctrl-]``)