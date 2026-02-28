# STM32 LWIP PROJECT
Hiện tại có các chương trình: *TCP Raw API(server/client)*, *TCP Netconn API (server)*

Ghi chú note được đặt trong [config_note](./config_note)

## Pinout
[pinout.xlsx](./pinout.xlsx)
| Nhóm         | STM32F407              | DP83848 |
|-------------|------------------------|----------|
| ETH         | 3V                     | VCC      |
|             | GND                    | GND      |
|             | ETH_MDIO (PA2)         | MDIO     |
|             | ETH_MDC (PC1)          | MDC      |
|             | ETH_REF_CLK (PA1)      | OSCIN    |
|             | ETH_CRS_DV (PA7)       | CRS      |
|             | ETH_RXD0 (PC4)         | RX0      |
|             | ETH_RXD1 (PC5)         | RX1      |
|             | ETH_TX_EN (PB11)       | TX_EN    |
|             | ETH_TXD0 (PB12)        | TX0      |
|             | ETH_TXD1 (PB13)        | TX1      |
| OSC         | RCC_OSC_IN (PH0)       |          |
|             | RCC_OSC_OUT (PH1)      |          |
| USART(debug)| USART2_TX (PD5)       |          |
|             | USART2_RX (PD6)        |          |