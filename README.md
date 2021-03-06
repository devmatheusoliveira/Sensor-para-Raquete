# Sensor raquete tênis de mesa

# Introdução ao tema

Esse projeto surgiu da vontade e da impossibilidade de praticar o tênis de mesa durante a pandemia da covid-19 em meádos de 2020 e 2021. Com a dificuldade de praticar o esporte real uma alternativa viável para se movimentar sem sair de casa seria o tênis de mesa virtual. Porém, alguns problemas foram surgindo durante a criação do jogo com o Kinect.

Um dos grandes problemas foi a falta de precisão da raquete, uma vez que o Kinect não detecta corretamente a rotação do punho, tornando o jogo quase impossível de se jogar, para isso desenvolvemos um controle em formato de raquete.

# Objetivos

- Desenvolver um controle em formato de raquete com a finalidade de jogar tênis de mesa virtualmente.
- Melhorar a precisão do movimento da "raquete" percebida pelo kinetc.
- Aplicar a placa ESP8266 EPS-12F no controle para que seja possível a melhor captação do movimento de rotação feito pelo punho do jogador.

# Desafios:

- Simular o acelerômetro no TinkerCad
- Não disponibilizar de um ESP 8266 para testes;
- Não poder validar a ideia fisicamente;
- A pandemia não possibilita o contato direto entre os participantes do grupo, o que afeta a comunicação entre os membros e a organização do projeto.

# Materiais utilizados

- Placa Eletronica ESP8266 ESP-12F (similar ao Arduino, com wifi);
- Sensor mpu6050 (sensor de rotação);
- Botão;
- Impressão 3d;
- LED bicolor;
- Tinkercad.

# Diagrama Elétrico

![img/1.png](img/1.png)

# Implementação Final do Projeto

Nesta etapa conclusiva do projeto, observaremos a implementação final do sistema
automatizado e acessível. O diferencial técnico do projeto inicial e final, reside na ideia da
confecção de um sistema automático e acessível ao usuário, ou seja, um sistema que controle
as variáveis amostradas e possibilite ao usuário o acesso à essas variáveis e o controle paralelo
destas.

# Informações Adicionais

Para fazer o teste, foi utilizado a placa ESP8266 e o sensor MPU6050. Já para a simulação, utilizamos o Arduino no Tinkercad.
O ESP8266 ESP12F é um equipamento de desenvolvimento open source que auxilia na prototipagem do produto voltado a IOT, necessitando de apenas de um script escrito por poucas linhas em LUA, ou mesmo programando na IDE Arduino.
O módulo possui internamente um poderoso processador, suficiente para a integração com sensores e outras aplicações específicas usandos seus GPIOs, necessitando de pouco desenvolvimento. Por se tratar de um chip relativamente completo, ele requer pouquíssimos componentes na placa, o que o torna um dispositivo de tamanho reduzido, permitindo desta forma uso de pouco espaço em seu projeto, (você pode executar seus programas diretamente no módulo, dispensando microcontrolador externo). A comunicação do Módulo Wireless ESP-12F com o Arduino ou Raspberry Pi pode ser feita via serial através dos pinos RX e TX, podendo ser configurada através de comandos AT.

![img/2.png](img/2.png)

O sensor MPU-6050 contém em um único chip um acelerômetro e um giroscópio tipo MEMS. São 3 eixos para o acelerômetro e 3 eixos para o giroscópio, sendo ao todo 6 graus de liberdade (6DOF). Além disso esta placa tem um sensor de temperatura embutido no CI MPU6050, permitindo medições entre -40 e +85 ºC. Possui alta precisão devido ao conversor analógico digital de 16-bits para cada canal. Portanto o sensor captura os canais X, Y e Z ao mesmo tempo.

![img/3.png](img/3.png)

O Arduino é uma plataforma de prototipagem eletrônica de código aberto, na qual o usuário pode personalizar o hardware e criar aplicativos específicos para rodar em um circuito eletrônico. Em outras palavras, podemos conectar dispositivos, sensores, tudo através de uma conexão USB, que podemos apenas conectar ao computador, instalar um driver e desenvolver programas. Há também outro modo de alimentação, podendo ser alimentado com uma bateria pequena, de 9V. A plataforma é toda configurada através de pinos, que se dividem em pinos analógicos, digitais, alimentação, reset e ground.

![img/4.png](img/4.png)

A linguagem do arduino é uma linguagem própria, que é uma linguagem bem similar ao ANSI C. O controle deste microcontrolador é feito através da programação. Além disso, o mesmo possui a característica de ser uma máquina de estado, que armazena o último dado que foi ordenado, caso seja retirada a sua alimentação. Em termos da teoria de circuitos digitais, podemos dizer que os registradores que compõem os CI’s do arduino, são registradores não voláteis.

# Resultados

Apesar das condições dispostas e dos desafios encontrados, o resultado do teste final do projeto foi efetivamente satisfatório, como pode ser visto no vídeo anexado. No futuro, queremos implementar o protótipo na raquete podendo testar e medir sua eficiência dentro do jogo. Na simulação do Tinkercad, aparentou um bom funcionamento

## Imagens

---

![img/5.png](img/5.png)

![img/6.png](img/6.png)

![img/7.png](img/7.png)

![img/8.png](img/8.png)

## Testes do projeto - videos:

---

[![](http://img.youtube.com/vi/T-6aFNm-0eg/0.jpg)](http://www.youtube.com/watch?v=T-6aFNm-0eg "")

[![](http://img.youtube.com/vi/vXC6BFr3yhE/0.jpg)](http://www.youtube.com/watch?v=vXC6BFr3yhE "")

[![](http://img.youtube.com/vi/gbedcYfsKGE/0.jpg)](http://www.youtube.com/watch?v=gbedcYfsKGE "")
