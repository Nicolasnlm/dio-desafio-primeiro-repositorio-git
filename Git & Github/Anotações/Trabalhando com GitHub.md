# Trabalhando com GitHub

  Mostrando as configurações do Git 

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Cofigs do git.jpg)

------

Para mudar as configurações do Git, como email, user, etc... Basta usar o comando:

![](C:\Users\User\Downloads\Photoshop\Algoritmos\Aulas Git\Imagens Ilustrativas Git\Modificando as configurações git 01.jpg)

**$git config --global --unset (configuração desejada)**

Fazendo o processo inverso:

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Trazendo o usuario e email novamente.jpg)

------

## Adicionando o Repositório remoto

Para linkar o Repositório Local com o Remoto, precisa-se primeiramente criar um repositório remoto no GitHub. Após criado, o GitHub irá disponibilizar uma URL na qual será usada para fazer o processo:

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Adicionando o repositório remoto.jpg)

Para adicionar, precisa-se de uma origem, na qual é este URL. Use 

**$git remote -v** para listar os repositórios remotos.

------

### Empurrando o repositório local para o remoto

Após apontar o Repositório remoto, pode-se fazer upload do repositório local:

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\Resultado de empurrar o repositório.jpg)

Veja que devido a uma atualização do Git, é preciso usar um Token de acesso para poder subir os arquivos

![](C:\workspace git\dio-desafio-primeiro-repositorio-git\Git & Github\Anotações\Imagens Ilustrativas Git\upando o arquivo no repositório.jpg)