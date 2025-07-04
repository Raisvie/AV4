# AV4
Programa em Python para calcular as frequências naturais de vibração e os modos normais (deslocamentos relativos) de uma cadeia atômica finita com 2, 3 e 4 átomos, incluindo interações com vizinhos mais distantes (segunda vizinhança) no último caso.

🔹 Efeito da variação das massas
Nos testes com 2 massas, quando se aumenta uma das massas provoca redução das frequências naturais associadas aos modos de vibração. Isso ocorre porque a massa maior aumenta a inércia, dificultando o movimento coletivo da cadeia. Além disso, os modos mostram que as massas mais leves se deslocam com maior amplitude relativa, enquanto as mais pesadas permanecem quase paradas em certos modos.

Nos testes com 3 massas, o mesmo padrão foi notado quando as frequências diminuem, as massas centrais ou terminais aumentam e os modos normais apresentaram padrões em que as massas leves vibram mais fortemente em determinados modos.

🔹 Impacto da inclusão de segundos vizinhos
No caso de 4 massas, a inclusão da segunda vizinhança com k’ = 3*k alterou significativamente as frequências naturais em relação ao caso sem segunda vizinhança. As frequências se tornaram mais elevadas para os modos que apresentam variações mais rápidas no padrão de deslocamento. Os modos normais mostraram um comportamento mais acoplado: os deslocamentos das massas passaram a ser mais distribuídos, com menos "isolamento" de movimento nas extremidades.

🔹 Interpretação física
Fisicamente, as massas maiores reduzem a agilidade do sistema, concentrando o movimento nas massas mais leves. A segunda vizinhança cria um reforço estrutural, limitando vibrações locais e promovendo um comportamento coletivo nas oscilações, o que se assemelha mais a materiais reais, onde átomos interagem além do primeiro vizinho.
