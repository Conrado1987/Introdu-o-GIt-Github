# Introdução Git Github

Curso de Introdução ao Git e ao Github

### Para que serve Git

O Git foi criado em 2005 pelo Linus Torvalds

A função dele é criar um sistema distribuído e seguro.

### Github:

- Controle de Versão
- Armazenamento em nuvem
- Trabalho em equipe
- melhorar seu código
- Reconhecimento

### Git Funções basicas.

- Mudar de pastas
- Listar as Pastas
- Criar pastas/arquivos
- Deletar pastas/arquivos

#### Códigos:

Windows  x  Unix

cd-----------------cd--------------->mudar de diretório

dir----------------ls----------------->listar pastas

mkdir-----------mkdir------------>fazer arquivo/pasta

del/rmdir------rm-rf-------------->remover arquivo/pasta

cd ..  -------------cd ..   ------------->Voltar pasta

cls-----------------clear ou ctrlL---------->limpar tela

del : ...

rmdir...   ------->remove pasta vazia

rmdir.../S/Q  --------> remove pasta com conteúdo

### Como o Git funciona

- SHA1

- Objetos fundamentais

- Sistema distribuído

- Segurança

  #### Sha1

  #### A sigla SHA significa Secure Hash Algorithm, é um conjunto de funções hash criptográficas projetadas pela NSA(Agência de Segurança dos EUA).

  A encriptação gera um conjunto de caracteres identificador de 40 dígitos.

  É uma forma curta de representar um arquivo.

  Openssl sha1"..."

  Openssl sha1 texto.txt

### Chave SSH e Tokens

##### Comando

ssh-keygen -t ed25519 -C ...(e-mail)

Enter  coloca senha

Depois :

eval $(ssh-agent-s)

aparece o agente pid...

ssh-add id_ed25519

### Primeiros comandos Git

### Git init

- Iniciar o Git
- Iniciar o versionamento
- Cria um commit.

git init----------->iniciar o repositório

git add---------->mover arquivos dar inicio ao versionamento

git commit---------->commitar

### Criando um repositório

#### **Mostrar arquivos ocultos: ls -a **

### Configurar usuario e e-mail

git config --global user.email "..."

git config --global user.name "..."

#### Remover usuario e e-mail:

git config --list--------------------->para ver o que esta lá

git config --global --uset user.name

git config --global --uset user.email

git config --list--------------------->para ver se removel

### Criar arquivo

git add *

git commit -m "o que quiser escrever"

git status----------------->mostra o status 

colocar arquivo dentro da pasta para ser commitada:

mv stroggonoff.md ./receitas/      

git commit -m "Receita de stroggonoff"   

### Empurar:

git push origin main (ou master)

### Resolvendo conflitos

git pull origin master--------------------->puxar o arquivo do github

git add *--------------------------------------->para adicionar na área de staged

git commit -m "resolve conflitos"

### Criando seu primeiro Repositório

git add .      ------------------------------> adicionar

git commit -m "..........."       --------->commitar

git push origin main     --------------->mandar os arquivos para github