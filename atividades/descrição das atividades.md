# Atividades Git e GitHub

## 1. Faça um fork do repositório
- Fork do repositório: [oficina-git-pet-si-ufsm](https://github.com/ldnora/oficina-git-pet-si-ufsm).
- Siga [esse tutorial](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository) para criar um fork do repositório. 

## 2. Clone o repositório em sua máquina
- Siga [esse tutorial](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository) para clonar o repositório "forkado" em sua máquina.

## 3. Crie uma pasta com o seu nome
- Dentro do repositório clonado, crie uma pasta com o seu nome. 
- Dentro dessa pasta, crie um arquivo chamado `atividade-seu_nome.md` e insira dados sobre você, tais como: 
  - Matérias favoritas;
  - Hobbiens que mais gosta;
  - E outras informações. Seja criativo 😉.

### 3.1 Verifique o que foi mudado
- Use o comando `git status` para verificar quais foram os arquivos alterados em seu repositório;
- Use o comando `git diff` para verificar quais foram as alterações feitas em da cada um dos arquivos modificados em seu repositório.

### 3.2 Boas práticas 
- Para cada dado do item anterior que você inserir, faça um `commit` seguindo essas [boas práticas](https://github.com/sampaiodias/git-boas-praticas?tab=readme-ov-file#commit). 
Ou seja, quando adicionar as "Matérias favoritas", faça um `commit` (que envolve fazer o `add` antes). Isso também serve para os demais intens.


## 4. Envie as alterações para o seu repositório no GitHub
- Use os comandos apredidos ao longo da oficina para enviar as alterações para o seu repositório no GitHub.
- Use `git log` para ver os históricos de commits. 

## 5. Crie uma nova branch
- Crie uma nova branch, com o nome `nova_branch`, acesse ela e modifique o conteúdo do seu arquivo `atividade-seu_nome.md`. Você pode adicionar outras informações como:
  - Ano que ingressou no curso;
  - Quais são suas primeiras impressões sobre a universidade.
- Por fim, envie as alterações para o seu repositório no GitHub (geralmente falamos "fazer um commit")

### 5.1 Observação
Siga as mesmas boas práticas para fazer os commits. 

### 5.2 Desafio
- Faça outras branches e commits para simular um real ambiente de desenvolvimento de software.  

## 6. Edite a branch main
- Volte a brach main e adicione os seguintes dados:
  - Quais são seus objetivos profissionais. 
- Faça um commit dessas alterações.

## 7. Faça o merge
- Faça o merge das informações alteradas nas outras branches `nova_branch` para a branch `main` e resolva os conflitos que surgirem. 


# Desafio final - pull request

## Dê seu feedback
- Crie uma nova branch para fazer dar um feedback da oficina.
- Crie um arquivo com o seu nome dentro da pasta `feedbacks` e escreva o seu feedback sobre a oficina. 
  - Você pode destacar os pontos que gostou e aqueles que melhoraria. 
- "Commite" e faça um `push` as alterações.
- Por fim, crie um [`pull request`](https://www.freecodecamp.org/portuguese/news/como-fazer-o-seu-primeiro-pull-request-no-github/) (siga a partir do passo 6).


