# Arquitetura limpa

## Sintomas de um sistema podre

Esses sintomas estão relacionados com o grau de **acoplamento** e **coesão** do seu sistema.

- Acoplamento: É o grau de dependência dos módulos do seu sistema.
- Coesão: Cada um dos módulos implementam poucas coisas. Ou seja, cada módulo é responsável somente por uma coisa.

### Rigidez

Quando toda mudança tende a demorar muito para ser feita no sistema.

As vezes achamos que a mudança vai ser rápida, mas daí quando começamos a alterar um módulo, vemos que ele depende de outro, e assim vai indo uma bola de neve. E demoramos muito pra alterar algo, tocando em muita coisa.

O gerente começa a perceber que quando ele pede uma mudança, percebe que demora muito, então ele começa a pedir menos mudança, uma política de gerência adversa.

### Fragilidade

Está relacionada com a rigidez.

É quando a gente altera um módulo do sistema e dá pau em outro. Relacionado com acoplamento. O sistema está frágil.

O gerente fica com medo de pedir alteração porque não sabe se vai dar problema no sistema. O próprio desenvolvedor fica com medo.

Uma boa arquitetura diminui as chances do sistema ser frágil.

### Imobilidade

É quando não conseguimos usar partes do sistema em outras partes do sistema ou em outros sistemas.

Não dá pra reusar, porque tem tanta bagagem no módulo que implementa aquela funcionalidade que não conseguimos extrair ela pra usar em outro lugar.

Pra não precisar ficar reinventando a roda. Retirar a funcionalidade e reutilizar em outro lugar. Deixa o desenvolvimento mais veloz.

### Viscosidade

#### Viscosidade de design

Quando a gambiarra é mais fácil de fazer do que a alteração que preserva o projeto, então seu design está viscoso.

Quando é mais fácil fazer a coisa errado do que a certa.

#### Viscosidade do ambiente

Quando o ambiente é muito lento, ineficiente. Por exemplo, demora a compilar. Então o desenvolvedor é inclinado a fazer alterações no sentido de não precisar passar por esse caminho.

Outro exemplo é na integração contínua. Digamos que os testes demoram muito pra rodar. Então a gente é tentado a não ficar fazendo muito *push*.

Se o seu pipeline demora a noite inteiro, é um sintoma de ambiente viscoso.

