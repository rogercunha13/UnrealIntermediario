# Unreal Intermediario

# Utilizando Delta Seconds para controle de movimento.

1. Delta Time;
1. Delta Seconds;

## Delta Time

O que é Delta Time?

É o tempo entre cada frame.
Frame: Um quadro ou imagem apresentada, uma animação é composta por vários frames.

## Delta Seconds

Delta Seconds é a quantidade de tempo decorrido desde o último evento Tick. Ao multiplicar seu deslocamento por Delta Seconds, seu movimento será independente da taxa de quadros.
Por exemplo, seu peão tem uma velocidade máxima de 100. Se um segundo tivesse se passado desde o último tique de evento, seu peão moveria todas as 100 unidades. Se meio segundo tivesse passado, ele moveria 50 unidades.

## Utilizando o Delta Seconds
