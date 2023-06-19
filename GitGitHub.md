GIT e GITHUB

Beneficios
# Controle de Versão
# Armazamento em nuvem
# Trabalho em equipe
# Melhor Seu Código
# Reconhecimento

Comandos basico terminais (GUI x CLI)

O que Vamos aprender?
- Mudar de pastas
- Listar as Pastas
- Criar pastas/arquivos
- Delete pastas/arquivos

Windows		Unix
- cd		- cd
- dir		- ls
- mkdir		- mkdir
- del / rmdir	- rm - rf
	/S /Q
- cls		- clear
		- pwd
		- mv exemplo.txt ./pasta

Tópicos fundamentais.
- SHA1
- Objetos Fundamentais
- Sistema Didtribuido
- Segurança

# SHA1
A sigla SHA significa Segure Hash Algotithm(Algoritmo de hash Seguro), é um conjuto de funções
hash criptográficas projetadas pela NSA(Agência de segurança Nacional dos EUA).

A encriptação gera conjunto de characteres identificador de 40 digitos.

Exemplo comando: echo "ola mundo" | openssl sha1

# Objetos Internos do GIT

- Blobs
As bolhas são os elementos basicos.
Armazena o SHA1 do arquivo.
Tem metadados do objeto.
Exemplo comendo: echo 'conteudo' | git hash-object --stdin

- Trees
A arvore armazena os blobs.
Aponta para cada bolha ou outras arvores.
Armazena o nome do arquivo.
Mota a estrutura de onde estão os arquivos.
Armazena o SHA1 das arvores.
Tem metadados.

- Commits
Junta toda essa estrutura.
Aponta para uma arvore.
Aponta para um parente(ultimo commit antes dele).
Aponta para um autor. "Jeff"
Aponta para uma mensagem "1º commit"
Tem metadados.
Armazena o SHA1 


Chave SSH

Comandos no CLI.
- ssh-keygen -t ed25519 -c jefferson.santossilva22@gmail.com

comando dentro da pasta .ssh
- cat id_ed25519.pub

chave gerada: ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAICgrwuVgw8I3GJzqpjmHPy+CConDQpkfFdG5jJNFIg7M jefferson.santossilva22@gmail.com


eval $(ssh-agent -s)

ssh-add id_ed25519


Comandos GIT
- git init
git init
ls -a

- confg inicial
git config --global user.email "jefferson.santossilva22@gmail.com
git config --global user.name Jefferson

- git add
git add*

- git commit
git commit -m "commit inicial"

- git status

- git clone
git clone git@github.com:JeffersonSnjolly/clone-netflix.git



















