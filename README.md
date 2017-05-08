# nrf-board-v1
Projeto PCB de módulo transceptor digital de 2.4GHz Nordic NRF24L01P

Projeto de placa de circuito impresso de tranceptor digital operando 
na faixa de 2,4GHz, baseado no chip da Nordic Semiconductor, NRF24L01P.
A placa possui conector de barras de pinos (2x4) para conexão com uC 
através dos sinais CSN, MOSI, MISO, SCK (interface SPI), /IRQ (interrupção)
, alem do VDD e GND.

Utilizou-se um conector SMA horizontal para conexão com a antena 
dipolo de 2,4GHz.

O circuito não foi projetado com regulador de tensão, com o objetivo de reduzir
custo e manter o baixo consumo de energia, sendo ideal para aplicações utilizem baterias.

A  princípio, o módulo pode ser alimentado com tensões de 1.9 a 3.6V (2 a 3 pilhas de NiMH)
A corrente de standby é de apenas 26uA.
