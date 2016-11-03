## Design e Arquitectura de Software
### 2016/2017
# Aula Laboratorial 1

1. Considere um sistema que visa permitir aos seus utilizadores comunicarem entre si, através de um sistema de pergunta/resposta público. Qualquer utilizador pode criar uma pergunta, que se torna visível para os outros utilizadores. Estes podem optar por responder a essa pergunta (SIM/NÃO). O criador original pode observar as respostas e, em qualquer momento, pode cancelar a pergunta, após o qual a mesma mantém-se
visível apenas para o ele. Por exemplo:

  - O Luis entra no sistema, cria a pergunta “Viram o jogo da selecção?” e sai.

  - Outros utilizadores entram no sistema e vêm a nova pergunta disponibilizada. Podem optar por dar um resposta (sim/não), ou então ignorá-la. Enquanto a pergunta não for cancelada pelo seu criador, qualquer utilizador pode optar por dar ou alterar a sua resposta em qualquer momento. Alguns utilizadores podem querer responder de forma anónima.

  - Quando o Luis entra de novo no sistema, recebe a indicação que recebeu novas respostas à sua pergunta. O sistema apresenta o total agregado de respostas sim/não. O Luis pode também ver mais detalhes, consultando o nome do utilizadores que responderam e a sua resposta (as respostas anónimas aparecem agregadas p.ex: Anónimos 10 sim / 20 não). O Luis está satisfeito com as respostas que obteve e decide cancelar a pergunta. Deixa de ser possível alterar ou criar uma nova resposta a partir deste momento, e só o criador e os utilizadores que responderam é que podem ainda consultá-la.

  - Qualquer utilizador pode optar por apagar uma pergunta. Isto fará com que ela deixe de estar visível (para ele).

1.1.Identifique e escreva uma versão sucinta dos casos de uso, bem como os respectivos diagramas de sequência de sistema.

1.2.Projecte uma arquitectura de camadas adequada ao problema.

1.3.Construa o sistema, criando um interface de texto e/ou gráfico adequado.
