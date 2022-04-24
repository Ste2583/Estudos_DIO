# Branch
### O que são branch:
Branch é uma bifurcação/ duplicação/ ramificação dos arquivos em um projeto. 

### Main/ Master: 
Nome padrão das branches.

### Head:
Referência de ramificação atual, uma espécie de ponteiro para a última confirmação que você fez ou a última confirmação registrada.

## Trabalhando com branch

- **git checkout -b:** Cria uma nova branch (exemplo: git checkout -b nova-funcionaldade)
- **git checkout:** Movmenta entre uma branch e outra (exemplo: git checkout nova-funcionalidade)
obs: Uma nova branch carrega todo histórico da outra para que consiga se fundir novamente.
- **git merge:** Junta as branches (exemplo: estou na branch MAIN digito: git merge nova-funcionalidade)
obs: Após fazer o git merge, basta fazer o git push para a branch main no repostório remoto.
- **git branch:** Mostra todas as branches existentes no repositório
- **git branch -m:** Renomea a branch quando se estar dentro dela (exemplo: estando na branch nova-funcionalidade digito: git branch -m funcionalidade) Renomear branch estando em outra ( estou na branch main digito: git branch -m nova-funcionalidade funcionalidade)
- **git branch -d:** Deleta a branch (exemplo: git branch -d nova-funcionalidade)
- **git stash save:** Pega tudo que esta sem commitar e coloca em uma "caixa" para poder trabalhar depois( exemplo: git stash save "quardar para usar no passo 4 do projeto")
- **git stash:** Salva um stash mas sem o porque diferente do anterior.
- **git stash list:** Lista todos os stash
- **git stash pop:** Volta os arquivos para o local anterior "estoura o stash" ( exemplo: git stash pop 1)
- **git stash clear:** Limpar todos os stash.

