# projeto para entender como as branches funcionam

## Branche master ou main

É a branch principal do repositório, é a partir dela que nosso sistema será entregue aos clientes.

O 'git' usa o nome da branch como master o 'github' como main.


Para converter use 'git branch -M main' depois que fizer o primeiro commit a partir do repositório criado com o 'git init'.

# manipulação de branch
para listar use
```
$ git branch --list
``` 

 Para excluir uma branch
 ```
 $ git branch -d nome_da_branch

 Para alterar o nome de uma branch 
 ```
 $ git branch -m nome_da_branch