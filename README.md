# Número pi está errado e de onde tirei esta história???
Em setembro de 2023, eu descobri, após medir um transferidor, que o número pi está errado.

Você deve está se perguntando, por que eu fui medir um transferidor???

Simples, eu havia lido um livro sobre desenho geométrico e resolvi praticar aqui que havia aprendido, então, eu comprei: um transferidor, um compasso e um esquadro.

Alguns assuntos achei interessante, ao utilizar o compasso: traçar uma reta perpendicular a outra, achar o ponto médio de um segmento, achar o centro da circunferência.
Geralmente, eu desenhava a circunferência usando o contorno do transferidor.

O transferidor, eu usava pra medir ângulos, mas tive a ideia de medir o perímetro em volta do transferidor nem passava por minha cabeça que o número pi estava errado.

O transferidor tem raio de 60mm, ou um diâmetro de 120mm, eu fiz a medição, e a medida do perímetro que encontrei foi 374mm. 
Quando utilizei a fórmula pra encontrar o perímetro: P = 2 * pi * r, o resultado foi: 376,991118431

Mas onde está o erro???
Humm, há uma diferença de 2,991118431

Eu refiz as medições, com mais cuidado ainda e esmero, e sempre minha medida reportava: 374mm.
Meu raio mede em mílimetros, imagine, se fosse, em metros, teríamos uma diferença de quase 3 metros.

Então, eu conclui por hipótese, que o valor Pi = 3,141519... está errado.

Mas, na matemática, isto não é suficiente.

Então, eu resolvi, achar alguma forma de calcular o perímetro da circunferência.

Resolvi, investigar por que pi é 3,141519,... descobri que foi por causa da técnica que Arquimedes, onde utilizava polígonos inscritos e circunscritos em uma círcunferência. Onde aumentando duplicando o número de lados do polígono inscrito e circunscrito anterior, o valor de pi estaria entre 3,1408 e 3,1429.
Então, resolvi, tentar isto, desenhei, polígonos e fiz igual a Arquimedes, de cada polígono consegui desenvolver as fórmulas, gastei dias, tive que refazer algumas fórmulas pois estavam erradas. Pra cada polígono, havia uma fórmula, entretanto, a mesma fórmula dependia da fórmula anterior. Eu percebi, um certo padrão entre as fórmulas que é desnecessário dizer aqui, então, eu fiz um programa em Rust ou C, não lembro qual linguagem foi, e comparei o perímetro de cada polígono com o raio pré-determinado, e realmente, a cada polígono, ia-se formando o valor 3,141519...

Então, como pra cada polígono, havia uma fórmula, pois cada fórmula dependia do polígono anterior, a fórmula era bem complexo. Isto, ainda não demonstra o verdadeiro medida de pi.

Depois, disto, tentei, outras técnicas, que vocês nem imaginam, fiquei obcecado nisto, cada dia tinha uma ideia diferente, gastei folhas A4 tentando isto, refazendo fórmulas.
Depois, de 1 mês, após várias técnicas e por causa da maneira que eu traçava a circunferência e por causas das tentativas inteligentes de tentar achar o perímetro e da maneira que eu media a circunferência, um dia acordei, e se eu fizer isto. A partir deste dia, eu consegui determinar com precisão, usando um compasso, como achar o perímetro da circunferência.

Mas, e a fórmula??? Sim, desenvolvi, a fórmula, mas, pi será isto mesmo: a soma de um número inteiro + um número irracional. Sim, é isto mesmo, número pi, é a soma de um número inteiro + um número irracional. Na fórmula, ao desenvolve-la, o raio é considerado igual a 1, e não 2, se você considerar a fórmula: p = 2 * pi * r, então, pi, é a semi-soma de um número natural + um número irracional.

E o valor de pi, 3,141519??? Realmente, está errado.

Mas, afinal, qual é o valor correto de pi???

Em breve, descobrirá, estou escrevendo um livro sobre isto, se vermos por lá!!!




