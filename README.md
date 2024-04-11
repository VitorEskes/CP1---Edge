# CP1-Edge
Vitor Alves Titus Eskes ; Gabriel Matias Simões ; Nathan Craveiro Golçalves Amin 

Este projeto demonstra o controle de LEDs e um buzzer com base na luminosidade ambiente detectada por um LDR (Light Dependent Resistor) utilizando um Arduino. O objetivo é criar um sistema que reaja à luminosidade do ambiente, acendendo diferentes LEDs e emitindo sons com o buzzer de acordo com o nível de luminosidade detectado.

Funcionamento do Sistema:

O LDR é utilizado para medir a luminosidade do ambiente, convertendo-a em um valor entre 0 e 1000 para facilitar a interpretação dos dados.
Com base nesse valor mapeado, o sistema toma decisões:
Se a luminosidade estiver abaixo de 900 (condições normais), o LED verde é aceso.
Se a luminosidade estiver entre 900 e 930 (nível moderado), o LED amarelo é aceso e o buzzer emite um som por 3 segundos.
Se a luminosidade ultrapassar 930 (condições de alta luminosidade), o LED vermelho é aceso e o buzzer emite um som contínuo.
Instruções de Uso:

Montagem do Circuito:

Siga o esquemático fornecido para montar o circuito utilizando o Arduino e os componentes necessários (LDR, LEDs, buzzer).
Carregamento do Código:

Faça o upload do código para o Arduino utilizando a IDE.
Ajuste os limiares de luminosidade conforme necessário para o seu ambiente.
Monitoramento:

Abra o monitor serial na velocidade de 9600 bps para visualizar a luminosidade mapeada em tempo real.
Observações:

Observe o comportamento dos LEDs e do buzzer conforme a luminosidade ambiente varia.
Experimente ajustar os limiares e adicionar novos comportamentos para personalizar o projeto.
Considerações Finais:

Este projeto serve como uma introdução interessante ao controle de luminosidade e sensores de luz com Arduino. Ele pode ser expandido adicionando mais LEDs, sensores ou ajustando o código para criar efeitos mais complexos.
