# DesafioJava

Crie uma classe chamada Pessoa com os atributos nome, sobrenome e data de nascimento. Também deve ser criada uma classe AtividadeFisica contendo o tipo de exercício (aeróbico, caminhada, corrida ou bicicleta), o tempo da atividade, a distância percorrida durante a atividade em metros (exceto para atividades aeróbicas), a data que o exercício foi realizado e a frequencia cardíaca mínima e máxima medida durante o exercício.

Escreva um aplicativo Java que permita cadastrar (criar, editar e excluir) Pessoas e AtividadeFisica, solicitando as informações necessárias para criar o objeto (não precisa ter tela, pode ser feito tudo via texto). Deve ser possível visualizar as informações de uma Pessoa cadastrada no sistema (nome, sobrenome, data de nascimento no formato dia/mês/ano - x anos, seu intervalo de frequência cardíaca máxima e sua frequência cardíaca alvo). Também deve ser possível visualizar um resumo e um relatório completo das AtividadeFisica de uma Pessoa. O resumo irá mostrar apenas o dia, tempo total e frequência cardiaca média das atividades realizadas no dia, enquanto que o relatório completo irá detalhar cada atividade realizada durante o dia, informando também se a Pessoa permaneceu dentro de sua frequência cardiaca alvo ou não. O resumo e o relatório devem permitir filtrar dados pela data e pelo tipo de atividade física, sendo possível combinar os dois filtros.

# Dicas
- Para facilitar o desenvolvimento, as datas podem ser divididas em 3 atributos independentes: dia, mes e ano
- Tente usar o máximo da orientação a objetos do Java para desenvolver o exercício
- Podem ser adicionados mais atributos para as classes informadas, mas os atributos citados são obrigatórios
- Pense numa forma simples de ligar uma Pessoa a uma AtividadeFisica, lembrando que uma pessoa pode fazer várias atividades mas uma atividade está relacionada a apenas uma pessoa
- Tente criar métodos dentro da classe Pessoa e AtividadeFisica com alguma lógica comum (por exemplo para calcular a idade da Pessoa)
- A frequência cardíaca máxima é 220 - a idade atual de quem será medido.
- A frequência cardíaca alvo é um intervalo entre 50-85% da sua frequência cardíaca máxima.
