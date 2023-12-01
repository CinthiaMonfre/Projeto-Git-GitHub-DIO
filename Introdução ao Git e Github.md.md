# Introdução ao Git e Github

**Comandos básicos para um bom desempenho no terminal no windows**

Para abrir o terminal no sistema operacional → windows + cmd

Listar local (pastas) → dir

Descer nível de diretório ao principal → cd /

Subir nível de diretório → cd nome da pasta

Descer nível de diretório → cd ..

Limpar terminal → cls

Autocompletar → TAB

Criar pasta → mkdir nome da pasta

Criar arquivo → echo nomequequerincluir > nomearquivo.txt

Deletar todos os arquivos na pasta → del nomedapasta

Deletar pasta e todo conteúdo dentro dela → rmdir nome da pasta /S /Q

****Tópicos fundamentais para entender o funcionamento do Git****

SHA1 - Secure Hash Alforithm, é um conjunto de funções hash criptográgicas projetadas pela NSA Agência de Segurança Nacional dos EUA. A encriptação gera um conjunto de caracteres identificador de 40 dígitos.

Verificar chave SHA → openssl shal nomedoarquivo.txt

**Objetos internos do Git**

Blobs (bolha) - arquivos ficam guardados dentro desse objeto blob, guarda o sha1, o tamanho do arquivo e o conteúdo

echo

Tree (árvore) - armazena e aponta blobs, guarda também um sha1 e o nome do arquivo (estrutura de onde está localizado os arquivos)

Commit - Objeto que vai juntar junto, aponta para uma árvore, aponta para um blob, aponta para último commit, autor, data/hora e mensagem. É uma alteração dentro dos arquivos e pastas.

****Iniciando o Git e criando um commit****

Listar diretórios → ls

Entrar em pasta → cd nome da pasta

Criar pasta nova → mkdir nome da pasta

Voltar para diretorio anterior → cd ..

Criar arquivo → echo > nome do arquivo

Iniciar o git → git init

Ver pasta oculta → ls -a

Limpar terminal → clear

Configurar e-mail → git config -- global [user.email](http://user.email) “email aqui”

Configurar usuário→ git config -- global [user.](http://user.email)name “usuário aqui”

Adicionar arquivo → git add * → git commit -m “texto do commit” (git add nome do arquivo, git add * ou git add .)

Verificar status de arquivos → git status

Mover arquivo para outra pasta → mv nome do arquivo ./ nome da nova pasta

Adicionar modificações para o diretório web → git remote add origin link do repositório

Listar diretórios web → git remote -v

Empurrar modificações para o diretório web → git push origin main

****Como os conflitos acontecem no GitHub e como resolvê-los****

Puxar alterações do diretório web → git pull origin main

Baixar repositório no diretório local → git clone cola url do repositório