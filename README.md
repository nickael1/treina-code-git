# Code & Git

Repositório de problemas de programação com o objetivo de ser aplicado durante as formações sobre programação e controle de versão com git. A ideia é fornecer um local para treinamentos de programação, forks e pull requests (mas poderá ser utilizado para outros fins).


## Como Participar

1. Realize o fork do repositório;
2. Faça o clone do repositório em sua máquina;
3. Crie uma pasta dentro do diretório do problema que pretende resolver, nomenado-a com o nome da linguagem que irá utilizar (usar lowercase). Depois dentro desta, crie uma outra pasta com o seu username. É dentro desta última que irá conter a sua solução. Formato do caminho de diretórios completo: *problemas/id-problema/linguagem/username*. **Exemplo**: problemas/1-calculo-produto/php/fabiosperotto;
4. Resolva o problema;
5. Copia a ficha-modelo.md para dentro da pasta que possui a sua implementação e preencha o template de acordo (reonomeie para ficha.md);
6. Crie uma branch com a sua solução no formato: git checkout -b problemas/id-problema/linguagem/username. Para o desafio 1, realizado em php, o nome da branch ficaria: problemas/1-calculo-produto/php/fabiosperotto
7. Adicione os seus arquivos para esta brach: git add .
8. Realize o commit (mensagem pode ser de sua escolha): git commit -m "feat: resolvendo o desafio"
9. Realize o push no branch respectivo: git push origin problemas/id-problema/linguagem/username. Ou seja, conforme exemplo no item 6: git push origin problemas/1-calculo-produto/php/fabiosperotto
10. Abra um pull request para este projeto aqui;
11. Agora é esperar pela revisão da sua contribuição.


Passo a passo de uma organização para a contribuição, não copie e cole os comandos sem pensar, utilize os mesmos alterando onde for necessário:
```sh
#1: realizar o fork no github
#2: depois realizar o clone do projeto
#3:
$ cd problemas/1-calculo-produto/
$ mkdir php/seu-username
#4: implemente a solucao
#5: depois, copie a ficha-modelo.md para o diretorio php/seu-username, renomear para ficha.md
#6:
$ git checkout -b problemas/1-calculo-produto/php/seu-username
#7: 
$ git add .
#8:
$ git commit -m "resolvendo o problema ..."
#9:
$ git push origin problemas/1-calculo-produto/php/seu-username
#10: verifique as atualizacoes no seu github e faca o pull request 
```



## Revisão de código

Verifique por legibilidade de código, cuide da estrutura e dos nomes das variáveis. Inserir comentários em partes complexas do código também se somam a uma maior compreensão sobre a implementação. Verifique também se falta alguma explicação sobre como utilizar o seu programa. Respeite a formatação de entrada e saída conforme enunciado dos problemas. Todos estes itens serão verificados para a aceitação da solução.


## Contribuindo com o projeto

Melhorias na estrutura, correções nos desafios (ou adições de novos), também pode ser enviados para este repositório.


## Premiação

Todos os estudantes, ex-estudantes e colegas do Prof. Fábio que, colaborarem de alguma forma com este repositório (ter um pull request aceito), vão receber a badge [Git Dev](https://www.holopin.io/personalsticker/clflrnr5y33880fl2aj4aro0n).


## Referências

- Inspirado pelas contribuições da comunidade [He4rt Developers](https://github.com/he4rt).
- Como o [git funciona](https://www.youtube.com/watch?v=w3jLJU7DT5E).
- Documentação de [sintaxe do markdown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
- Convenção para [descrição de commits](https://www.conventionalcommits.org).