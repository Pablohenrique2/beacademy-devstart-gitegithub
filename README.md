# Beacademy-devstart-gitgithub
Esse repositório foi criado com a finalidade de fazer a entrega dos exercícios propostos pelos professores da beacademy/devstart..👨‍💻

## Configuração inicial do git: ⚙️

Configurando o nome do usuário e email:

```bash
  git config --global user.name '*nome do seu usuario*'
  git config --global user.email '*digite seu email*'
```

## Comandos git Apresentados nas aulas: 🎓
Comandos basico para desde a inicialização da criação de um projeto até subir para o repositório.

Iniciar o repositório git:

```bash
  git init
```
Verificar o status do arquivo:

```bash
  git status
```
Adicionar todos os arquivos e salvar :

```bash
  git add .
```
ou
Adicionar o arquivo que você deseja:
```bash
  git add nome-do-arquivo
```
Adicionar o commit :

```bash
  git commit -m "mensagem explicativa"
```
selecionar qual branch deseja:

```bash
  git branch -M Master ou main
```
Selecionar qual o repositório que sera enviado:

```bash
  git remote add origin *e digitar o endereço do repositório*
```
Enviar o arquivo para o repositório:

```bash
  git push -u origin main ou Master
```
#### Remover arquivo/diretório 😵

Remover arquivo:

```bash
  git rm meu_arquivo.txt
```
Remover diretório:

```bash
  git rm -r diretorio
```
#### Visualizar histórico 🧐

Exibir histórico:

```bash
  git log
```

### Comando de Ramificação 🌲

Criar uma branch:
```bash
 git branch "nome da nova branch"
```
  ou
Criar uma branch e entrar nela:
```bash
 git checkout -b "nome da nova branch"
```
Acessar branch:
```bash
 git checkout "nome da branch"
```
Para ver qual branch você possui:
```bash
 git branch
```
Para unificar as branch:
```bash
 git merge "nome da  branch"
```
Para apagar a branch:
```bash
 git branch -d "nome da  branch"
```

### Comando para clonar repositorio: 👨‍🏫

```bash
 git clone url_do_projeto
```

### Comando para usar stash: 🧠
Quando precisar guarda rapidamente aquele arquivo para ter que resolver algum outro poblema sem precisar ter que fazer commit no arquivo sendo que ele não esta nem perto do esperado:

```bash
 git stash
```
lista os arquivo guardado no stash:
```bash
 git stash list
```
volta o stash mais recente:
```bash
 git stash pop
```
aplica o stash mais recente:
```bash
 git stash apply
```
ou escolher qual stash você que voltar:

```bash
 git stash apply@{ *aqui botar o numero da stash*}
```
fazer a limpeza do stash:
```bash
 git stash drop
```
