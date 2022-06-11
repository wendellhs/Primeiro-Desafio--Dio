# Primeiro-Desafio--Dio:page_with_curl:

Desafio  de Projeto sobre Git/Github da Dio:

## O que é Git?

O Git é um sistema de controle de versão distribuído e amplamente adotado. O Git nasceu e foi tomando espaço dos outros sistemas de controle. Seu criador principal é o mesmo que o do Linux: Linus Torvalds.

O Github tem sim muita relação com o Git. GitHub é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle.

##Repositório Local##
Criar novo repositório
-git init
Verificar estado dos arquivos/diretórios
git status
Adicionar arquivo/diretório (staged area)
Adicionar um arquivo em específico
git add meu_arquivo.txt
Adicionar um diretório em específico
git add meu_diretorio
Adicionar todos os arquivos/diretórios
git add .	
Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)
git add -f arquivo_no_gitignore.txt
Comitar arquivo/diretório
Comitar um arquivo
git commit meu_arquivo.txt
Comitar vários arquivos
git commit meu_arquivo.txt meu_outro_arquivo.txt
Comitar informando mensagem
git commit meuarquivo.txt -m "minha mensagem de commit"
Remover arquivo/diretório
Remover arquivo
git rm meu_arquivo.txt
Remover diretório
git rm -r diretorio
