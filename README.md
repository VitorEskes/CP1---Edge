# CP1-Edge
Vitor Alves Titus Eskes ; Gabriel Matias Simões ; Nathan Craveiro Golçalves Amin 

<Controle de Luminosidade com Arduino>
  Este projeto utiliza um Arduino para controlar LEDs e um buzzer com base na luminosidade ambiente detectada por um LDR (Light Dependent Resistor). O objetivo é criar um sistema que reaja à luminosidade do ambiente, acendendo diferentes LEDs e emitindo sons com o buzzer   dependendo do nível de luminosidade.

<Funcionamento>
  O LDR é utilizado para medir a luminosidade do ambiente. Essa medida é então mapeada para um valor entre 0 e 1000, permitindo uma interpretação mais fácil dos dados. Com base nesse valor mapeado, o sistema toma decisões:
    Se a luminosidade estiver abaixo de um limite pré-definido (900 no exemplo), o LED verde é aceso, indicando condições normais.
    Se a luminosidade estiver entre o limite de alerta (900) e um segundo limite (930), o LED amarelo é aceso e um som é emitido pelo buzzer por 3 segundos, indicando um nível de luminosidade moderado.
    Se a luminosidade ultrapassar o segundo limite (930), o LED vermelho é aceso e o buzzer emite um som contínuo, indicando condições de luminosidade alta.

<Instruções de Uso>
  Montagem do Circuito: Monte o circuito conforme o esquemático fornecido, utilizando um Arduino e os componentes necessários (LDR, LEDs, buzzer).
  Código: Faça o upload do código para o Arduino utilizando a IDE. Certifique-se de ajustar os limiares de luminosidade conforme necessário para o seu ambiente.
  Monitoramento: Abra o monitor serial na velocidade de 9600 bps para visualizar a luminosidade mapeada em tempo real.
  Observação: Observe o comportamento dos LEDs e do buzzer conforme a luminosidade ambiente varia. Experimente ajustar os limiares e adicionar novos comportamentos para personalizar o projeto.

<Considerações Finais>
  Este projeto é uma introdução interessante ao controle de luminosidade e sensores de luz com Arduino. Ele pode ser expandido adicionando mais LEDs, sensores ou ajustando o código para criar efeitos mais complexos. Divirta-se explorando as possibilidades e aprendendo     
 mais sobre eletrônica e programação com Arduino!
