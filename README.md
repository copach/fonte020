# - Projeto Fonte de Tensão entre 3V a 12V
Projeto referente a matéria de Elêtronica para Computação (SSC0180), ministrada no primeiro semestre de 2020 pelo professor Eduardo do Valle Simões, na Universidade de São Paulo, campus São Carlos. A proposta do projeto foi criar uma fonte que receberá 127V da tomada e uma corrente alternada e os transformará em uma tensão variável de 3V a 12V com capacidade de 100mA.


# - Circuito
### Diagrama no Falstad
![image1](https://github.com/copach/fonte020/blob/master/circt0.JPG?raw=true)

### Link para o Falstad
[Circuito no Falstad](http://tinyurl.com/y7rp7byz)

### Link para o Youtube
[Circuito no Youtube](http://www.youtube.com/watch?v=NRp7nlJM8PE "Circuito no Youtube")

### Diagramas no Eagle

Esquema do circuito no eagle, com os respectivos componetes e ligações.
![image3](https://github.com/copach/fonte020/blob/master/circuitocorrigido.JPG?raw=true)


&nbsp;

Disposição dos itens na placa PCB, facilitando a aplicação real.
![image2](https://github.com/copach/fonte020/blob/master/circt1.JPG?raw=true)

### Função de Cada Componente
- Transformador: reduzir a tensão da corrente.
- Ponte Retificadora (4 Diodos Retificadores) e Capacitor: transformar a tensão alternada em tensão próxima a contínua.
- Resistores: são responsáveis por limitar a corrente elétrica em um circuito através do efeito joule (conversão energia elétrica em térmica através da colisão entre os elétrons e a camada do resistor).
- Potenciômetro: tem a mesma função de um resistor, a única diferença é que ele possui resistência váriavel.
- Diodo Zener: é responsável pela regulação da tensão no circuíto.
- Transistor NPN: controla a intensidade da corrente, permitindo a economia da mesma. 

# - Preços e Especificações
| Componente             | Especificações | Preço |
|:------------------------:|:----------------:|:-------:|
| Transformador          | 15V e 300mA    |[R$26,7](https://produto.mercadolivre.com.br/MLB-802952898-transformador-primario-0110-0110-secundario-015v-300ma-_JM?matt_tool=82322591&matt_word&gclid=EAIaIQobChMIhsubx8z_6QIVjoSRCh005QUsEAkYCiABEgKHK_D_BwE&quantity=1)|
| Diodo Retificador (x4) | 400V e 3A      |[R$1,44](https://www.baudaeletronica.com.br/diodo-1n5404.html)|
| Capacitor              | 270uF e 25V    |[R$2,00](https://produto.mercadolivre.com.br/MLB-1036667817-capacitor-eletrolitico-270uf-x-25v-10-pecas-_JM?quantity=1#position=1&type=item&tracking_id=d288094d-4743-4eed-913e-8593b674b2f7)|
| Diodo Zener            | 15V e 0.5W     |[R$0,12](https://www.baudaeletronica.com.br/diodo-zener-1n5245-15v-0-5w.html)|  
| Resistor               | 120Ω e 0.5W    |[R$0,08](https://www.baudaeletronica.com.br/resistor-120r-5-1-4w.html)| 
| Resistor               | 470Ω 0.5W      |[R$0,08](https://www.baudaeletronica.com.br/resistor-470r-5-1-4w.html)| 
| Resistor               | 820Ω e 0.5W    |[R$0,08](https://www.baudaeletronica.com.br/resistor-820r-5-1-4w.html)|     
| Potenciômetro          | 2000Ω e 0.2W   |[R$1,09](https://www.baudaeletronica.com.br/potenciometro-linear-de-2k-2000.html)| 
| Transistor NPN         | 2N2222         |[R$0,22](https://www.baudaeletronica.com.br/transistor-npn-2n2222.html)|  
| **Total**              | -------------- | R$31,8|

# - Integrantes do Grupo
~~~
Thiago Cardoso    - 11796594
Guilherme Pacheco - 11797091
Ciro Falsarella   - 11795593
Pedro Martelleto  - 11795641
~~~

# - Agradecimentos
Agradecemos ao professor Eduardo do Valle Simões, por tamanha simplicidade, humildade e empenho em ensinar.

