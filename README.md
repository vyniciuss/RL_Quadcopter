# Ensinando um quadricoptero a voar

O projeto faz parte do curso Engenheiro de Machine Learning

![alt text](https://github.com/vyniciuss/RL_Quadcopter/blob/master/drone.jpg)

## Visão Geral do Projeto

O quadricóptero ou helicóptero quadrirotor está se tornando um tipo de aeronave cada vez mais popular tanto para uso pessoal quando profissional. Sua facilidade para manobras mostra-se útil para várias aplicações, de entregas em curtas distâncias a cinematografia, de acrobacias a busca e resgate.

A maioria dos quadricópteros têm 4 motores para fornecer impulso, embora alguns outros modelos com 6 ou 8 motores também sejam incluídos informalmente nesta categoria. Múltiplos pontos de impulso com um centro de gravidade no centro aumentam a estabilidade e possibilitam uma variedade de comportamentos de voo.

Mas existe um preço para tudo isso–a alta complexidade do controle de uma aeronave desse tipo faz com que seja quase impossível controlar o impulso de cada motor manualmente. Assim, a maioria dos quadricópteros comerciais tentam simplificar os controle de voo ao aceitar uma única magnitude de impulso e controles de arfagem/rolagem/guinada, tornando seu controle muito mais intuitivo e divertido.

O próximo passo nesta evolução é possibilitar que quadricópteros assumam comportamentos de controle desejados, tais como decolagem e pouso, de forma autônoma. Você poderia projetar estes controles usando uma abordagem clássica (digamos, implementando controladores PID). Ou ainda você poderia usar aprendizado por reforço para criar agentes que possam aprender estes comportamentos por conta própria. E é exatamente isso que você irá fazer neste projeto!





