# DesafioPooAbstracaoCelular
Resolução do desafio lançado pelo Expert durante as aulas ministradas pela Digital One.

## Contexto
Você é responsável por modelar um sistema que trabalha com celulares. Para isso, foi solicitado que você faça uma abstração de um celular e disponibilize maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

## Proposta
Você precisa criar um sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. Você deve criar as suas classes de acordo com o diagrama abaixo:
![image](https://github.com/Lucasgyn94/DesafioPooAbstracaoCelular/assets/91031320/a121d24e-ea52-44d6-8d0c-e60a213799db)

## Regras e Validações
* A classe Smartphone deve ser abstrata, não permitindo instanciar e servindo apenas como modelo.
* A classe Nokia e Iphone devem ser classes filhas de Smartphone.
* O método InstalarAplicativo deve ser sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.
Solução

## Resolução Output da Aplicação terminada
![image](https://github.com/Lucasgyn94/DesafioPooAbstracaoCelular/assets/91031320/cb203f2b-457e-425c-bdfb-1adc8e239507)
