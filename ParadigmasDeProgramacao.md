# Paradigmas de programação

A ordem em que eles foram descobertos, é diferente da ordem em que eles foram adotados. Inverso na verdade.

## Breve resumo

### Programação Estruturada

Qual seria a limitação? Seria a disciplina de não utilizar os comandos goto.

Ou seja, impomos disciplina no desvio de controle, por meio de estruturas de controle. IF, WHILE, FOR, etc.

Os pulos com esses comandos são disciplinados, e quando utiliza-se goto é indisciplinado, pula para qualquer parte do programa.

### Programação Orientada a Objetos

A disciplina sobre desvio de controle indireto.

Quando a gente tem polimorfismo, a gente tem um desvio de controle indireto.

Em determinado ponto, em que a chamada a um método, a gente não sabe qual método vai ser chamado, porque depende do tipo do objeto, há um desvio de controle indireto.

No caso da programação orientada a objetos, esse desvio indireto ficou disciplinado, por que ele é com base no nome e no tipo do objeto.

### Programação funcional

Derivada do cálculo lambda 1936, mas como linguagem mesmo veio a partir do LISP 1958.

Os valores dos símbolos não mudam. Disciplina sobre o uso de atribuição.

### Conclusão

Cada um dos paradigmas retira uma liberdade do programador. Esses paradigmas apareceram entre 1950 e 1970, depois disso nada mais foi descoberto, Robert Martin afirma que não tem mais nada a descobrir a respeito disso.

Ou seja, a gente retirou goto, atribuição e ponteiros para função. Então estamos trabalhando da maneira mais disciplinada possível.

### O que tem a ver

A programação orientada a objetos, por meio do polimorfismo, oferece um meio para cruzarmos os limites arquiteturais. (SEPARAÇÃO DE INTERESSES)

A programação funcional impõe disciplina na localização e acesso a dados. (GERENCIAMENTO DE DADOS)

E a programação estruturada é utilizado como fundamento algorítmos para nossos módulos. (FUNCIONALIDADE)

## Programação estruturada

