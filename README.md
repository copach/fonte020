# - Projeto Fonte de Tensão entre 3V a 12V
Projeto referente a matéria de Elêtronica para Computação (SSC0180), ministrada no primeiro semestre de 2020 pelo professor Eduardo do Valle Simões, na Universidade de São Paulo, campus São Carlos. A proposta do projeto foi criar uma fonte que receberá 127V da tomada e uma corrente alternada e os transformará em uma tensão variável de 3V a 12V com capacidade de 100mA.


# - Circuíto
### Diagrama
![image1](https://github.com/copach/fonte020/blob/master/circt0.JPG?raw=true)

### PCB e EAGLE
![image2](https://github.com/copach/fonte020/blob/master/circt1.JPG?raw=true)

![image3](https://github.com/copach/fonte020/blob/master/circuitocorrigido.JPG?raw=true)

### Função de Cada Componente
- Transformador Abaixador: reduzir a tensão de 127V para o intervalo de 3V a 12V.
- Ponte Retificadora (4 Diodos Retificadores): transformar a tensão alternada em tensão contínua e cada diodo sozinho tem a função de determinar um sentido para a corrente.
- Capacitor: armazenar pequenas quantidades de carga elétrica, de modo a estabilizar a tensão no circuito.
- Resistores: são responsáveis por limitar a corrente elétrica em um circuito através do efeito joule (conversão energia elétrica em térmica através da colisão entre os elétrons e a camada do resistor).
- Potenciômetro: tem a mesma função de um resistor, a única diferença é que ele possui resistência váriavel.
- Diodo Zener: é responsável pela regulação da tensão no circuíto.
- Transistor NPN: regula a resistência do potenciômetro, de modo a alterar a tensão do circuíto. 

### Link para o Falstad
[Circuito no Falstad](http://tinyurl.com/y7rp7byz)

### Link para o Youtube


# - Preços e Especificações
| Componente             | Especificações | Preço |
|------------------------|----------------|-------|
| Transformador          | 15V e 300mA    | R$26,7|
| Diodo Retificador (x4) | 400V e 3A      | R$1,44|
| Capacitor              | 270uF e 25V    | R$2,00|
| Diodo Zener            | 15V e 0.5W     | R$0,12|  
| Resistor               | 120Ω e 0.5W    | R$0,08|   
| Resistor               | 470Ω 0.5W      | R$0,08|  
| Resistor               | 820Ω e 0.5W    | R$0,08|     
| Potenciômetro          | 2000Ω e 0.2W   | R$1,09| 
| Transistor NPN         | 2N2222         | R$0,22|  
| **Total**              |                | R$31,8|

# - Integrantes do Grupo
- Thiago Cardoso    - 11796594

- Guilherme Pacheco - 11797091

- Ciro Falsarella   - 11795593

- Pedro Martelleto  - 11795641

# - Agradecimentos
Agradecemos ao professor Eduardo do Valle Simões, por tamanha simplicidade, humildade e empenho em ensinar.

