# Ciclo de vida dos arquivos no Git

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_1.jpg)



## Tracked e Untracked

 **Tracked** são os arquivos que o Git tem ciência dos mesmos e **Untracked** são os que o Git ainda não catalogou.

 O agrupamento dos *arquivos rastreados* se dividem em três subgrupos:

- **Unmodified**: É um arquivo que ainda não sofreu nenhuma modificação;
- **Modified**: É o arquivo "unmodified" que sofreu uma modificação;
- **Staged**: Onde ficam os arquivos que estão se preparando para fazer parte outro agrupamento que é o **Commit**.

------

 Quando foi adicionado com aquele arquivo "Pizza.md" com o comando **$git init**, o Git colocou o arquivo como *Untracked*, em seguida o usando o **$git add**, o arquivo foi passado para o *Staged*

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_2.jpg)

------



 Se o arquivo for editado, será mudado de *Unmodified* para *Modified*, o Git faz esta função comparadando o SHA do arquivo

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_3.jpg)

------

 Caso o **$git add** seja rodado novamente, este arquivo modificado será movido para *Staged*

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_4.jpg)

------

 E se for removido, será marcado como *Untracked* novamente

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_5.jpg)

------

 Quando o *commit* é realizado, o sistema pega todos esses arquivos e os salva como uma **Snapshot** e  marca como *Unmodified* novamente. Assim salvando todas as modificações e fechando o ciclo entre esses três estágios.

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_6.jpg)

------





# Repositórios

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_7.jpg)

O Ambiente de Desenvolvimento representa tudo que está na máquina local, como o Git é um sistema distribuído, as modificações dos arquivos não repercutem imediatamente no repositório remoto.

------

 Os arquivos geralmente ficam transitando entre o **Repositório de trabalho** e a **Staging Area**, quando um *Commit* é realizado, esses arquivos são passados para o **Repositório Local**.

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_8.jpg)

------

O **Repositório Local** apenas guarda os arquivos "*Commitados*", caso contrário, não será possível enviar os arquivos para o **Repositório Remoto**.

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_9.jpg)

------



# Processo



**$git status** - Mostra o status dos arquivos

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_10.jpg)

------

**$git mv ** - Move um arquivo, vamos criar e mover o arquivo  "strogonoff.md" para a  pasta "receitas" por exemplo:

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_11.jpg)

------

Veja que arquivo "strogonoff.md" foi marcado como *Untracked* e como deletado

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_12.jpg)

------

para isso basta usar o **$git add** para adicionar ao *Staged*

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_13.jpg)

Veja que o arquivo foi movido para *Staged*, então só falta apenas *Commitá-lo*

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_14.jpg)

------

Commitado :thumbsup:

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_15.jpg)

------

### Adicionando um índice

Arquivo README.md

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_17.jpg)

------

O Git mais uma vez mostra que o arquivo está *Untracked*, para resolver isso basta usar o **$git add *** , que adiciona todos os arquivos *Untracked* e *Modified* de uma vez só:

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_18.jpg)

------

Commitando:

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Screenshot_19.jpg)
