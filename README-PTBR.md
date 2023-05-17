# Andreys_QA

só umas dicas minhas de testes que você deve fazer no seu código.

## INDEX

- [1.CONHEÇA SEU CÓDIGO](https://github.com/andreyvdl/Andreys_QA/blob/main/README-PTBR.md#1conheça-seu-código)   
- [2.TESTES LÓGICOS](https://github.com/andreyvdl/Andreys_QA/blob/main/README-PTBR.md#2testes-lógicos)   
    - [2.1.BÁSICO](https://github.com/andreyvdl/Andreys_QA/blob/main/README-PTBR.md#21básico)   
    - [2.2.AVANÇADO](https://github.com/andreyvdl/Andreys_QA/blob/main/README-PTBR.md#22avançado)
    - [2.3.ACABE COM ISSO](https://github.com/andreyvdl/Andreys_QA/blob/main/README-PTBR.md#23acabe-com-isso)   
- [3.AMIGOS DE PROGRAMADOR](https://github.com/andreyvdl/Andreys_QA/blob/main/README-PTBR.md#3amigos-de-programador)   

### 1.CONHEÇA SEU CÓDIGO   

A primeira vista isso pode parecer/sooar _estúpido_, mas é bem comum para um programador **não** saber o que seu programa faz depois de um tempo, então pare para ler e fazer notas sobre as funções/métodos que seu programa chama, isso vai ser importante no futuro (Uma coisa que pode ajudar é manter a **ÚNICA** parte boa do código limpo).   

> "Um nome deve dizer a você porquê existe, o que faz, e como é usado. Se um nome precisa de um comentário, então o nome não revela sua intenção."   

OK, então agora que você sabe o que seu programa faz, vamos para a parte mais importante desse texto.   

### 2.TESTES LÓGICOS   

> "Eu não sei como testar meu código."   

É uma frase que eu ouço bastante, o que me surpreende, é muito simples de testar qualquer código, se você sabe o que ele deveria fazer.   

Se você seguiu a parte um ([me clique]()) você sabe como seu programa funciona, mas se você está testando um programa que não é seu, pergunte a pessoa como deveria funcionar.   

Lembre de fazer anotações dos testes: por que falhou? Que testes similares quebraram? É um problema na chamada de função/método? É um problema de memória? etc.

#### 2.1.BÁSICO   

Comece com testes básicos, se o programa functiona com números tente números comuns como: `1`, `2`, `3`, `5`, `7`, `10`, `50`, `100` e etc.   

Se o programa funciona com strings tente strings comuns como: `"foo"`, `"bar"`, `"abc"`, `"xyz"`, `"hello"` e `"world"`.   

#### 2.2.AVANÇADO   

Se o programa passou os testes básicos a gente pode tentar coisas avançadas, para números vamos de negativos: `-1`, `-2`, `-3`, `-5`, `-7`, `-10`, `-50`, `-100` e etc.   

Se o programa funciona com strings a gente pode passar strings invalidas ou strings granders como: `NULL`, `""`, `"Ola Mundo! Hoje eh um belo dia! Eu estou curioso sobre o quao grande a string pode ser ateh o programa quebrar... Bem eu vou apertar enter............. AGORA!"` e etc.   

#### 2.3.ACABE COM ISSO   

OK... agora a gente vai **BEM** longe com strings vamos tentar algo **GRANDE**:   
```
"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam dui quam, laoreet ac augue nec, sagittis                           laoreet est. Aliquam dictum, lacus a congue blandit, mauris mi pharetra nulla, non fringilla lorem neque a mi. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae;                                        Etiam lacinia ullamcorper ligula, sit amet condimentum lectus tincidunt eu. Sed non neque eu nibh consectetur varius nec et tellus. Fusce lobortis dignissim enim, ut eleifend libero vestibulum ut. Aliquam fermentum pretium blandit. Sed luctus tempus purus, quis pharetra diam fermentum vel. Nunc facilisis nunc id nulla volutpat condimentum. Donec quis erat aliquam urna viverra tristique in tincidunt purus. Ut et hendrerit ante. Pellentesque non vestibulum justo. Quisque sit amet felis nec mi faucibus ullamcorper quis a arcu. Mauris volutpat, dolor vitae luctus scelerisque, ligula justo dignissim metus, sit amet laoreet quam sem vitae lectus. Vivamus pellentesque leo vel dui iaculis, in mollis dolor sagittis. Sed faucibus dignissim ipsum lobortis semper."   
```
... SIM, isso é **UMA** string... se você quiser ir ainda mais pode tentar uma maior [lorem ipsum](https://lipsum.com).   

A gente também tem uma string como:   
```
"     Eu posso s      er simp      les mas     voce pode                    ver qu      a n to          s                 white                                                                                                  spaces                                             eu t     e nh     o   ~'@#$&\*()\_-+=789456123,,,,,??|/\\;:><..!                                          "   
```
Agora números... bem a gente não vai muito longe, só: `-0`, `-2147483648`, `2147483647`, `2147483648`, `-2147483649`, `000000000123456789`, `-000000000123456789`, `-9999999999999999999999`, `99999999999999999999999999` e etc.   

Se seu programa falhou em qualquer um dos testes era esperado, a ideia dos testes, é tentar casos simples que você pode ter pensado então ir para os casos difíceis que podem causar dor de cabeça, caso contrário vá beber um café, chá, Monster™️ ou o que você quiser, o importante é ter tempo para relaxar.   

### 3.AMIGOS DE PROGRAMADOR   

Eu chamo eles de amigos... mas para algumas pessaos eles podem ser inimigos.   

Primeiro nós temos nosso detector de vazamentos de memória, [Valgrind](https://valgrind.org) ([um bom vídeo para ver um básico do valgrind](https://www.youtube.com/watch?v=DyqstSE470s)).   

Seguido do amigo debugador [GDB](https://sourceware.org/gdb) ([outro vídeo para aprender um básico](https://www.youtube.com/watch?v=gFCQ37jVN3g)).   

<p align="center">
    Feito com 🧠 por @<a href="https://github.com/andreyvdl">andreyvdl</a>
</p>
