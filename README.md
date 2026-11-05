Sistema de Controle de Notas

Parte 1 — Cadastro de notas

1. Por que a estrutura escolhida é adequada?

Foi utilizado o for porque sabemos que serão cadastradas exatamente 5 notas. Assim, ele permite controlar a quantidade de repetições.

2. O que aconteceria se a repetição fosse executada apenas quatro vezes?

Apenas quatro notas seriam cadastradas, deixando de considerar o quinto aluno no cálculo da média.

Parte 2 — Senha de acesso

1. O que acontece se o usuário acertar a senha na primeira tentativa?

O programa não executará o while e seguirá diretamente para a mensagem “Acesso permitido!”.

2. Por que essa situação pode ser resolvida com while?

Porque não sabemos quantas tentativas serão necessárias. O while repete enquanto a senha estiver incorreta.

3. Qual erro poderia fazer o programa entrar em um laço infinito?

Não solicitar uma nova senha dentro do while, fazendo com que a senha incorreta permaneça sempre igual.

Parte 3 — Menu interativo

1. Por que do while combina com esse problema?

Porque o menu precisa aparecer pelo menos uma vez. O do while executa primeiro e verifica a condição depois.

2. O que diferencia seu funcionamento do while?

O while verifica a condição antes de executar. O do while executa pelo menos uma vez antes de verificar.

3. O que acontece se o usuário digitar 3 logo na primeira exibição?

O programa encerra imediatamente após a escolha da opção 3.

Parte 4 — Análise do código

1. Qual será a saída do programa?

1 2 3 4 5

2. Quantas vezes o laço será executado?

Cinco vezes.

3. O que aconteceria se retirássemos i++?

O valor de i permaneceria 1 e a condição continuaria verdadeira, causando um laço infinito.

4. Reescreva usando for:

for (i = 1; i <= 5; i++) {
   printf("%d ", i);
}

5. Reescreva usando do while:

i = 1;
do {
   printf("%d ", i);
   i++;
} while (i <= 5);
