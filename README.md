# Guia Prático de comandos Batch (.bat)
Este documento fornece uma visão geral dos comandos Batch mais comuns, explicando como eles funcionam e fornecendo exemplos de uso prático. Batch é uma linguagem de script usada para automação de tarefas no Windows, sendo executada a partir do Prompt de Comando (cmd).

![Windows 11](https://purainfo.com.br/wp-content/uploads/2018/05/CMDart.png)


## 1. Criar um Diretório
Para criar um diretório (pasta), usamos o comando `mkdir`.
### Comando:
```
mkdir nome_do_diretorio
```
### Exemplo:
```
mkdir C:\Documentos\Projetos
```
Esse comando cria uma pasta chamada "Projetos" dentro do diretório "Documentos".


## 2. Remover um Diretório
Para remover um diretório (pasta) vazio, utilizamos o comando `rmdir`.
### Comando:
```
rmdir nome_do_diretorio
```
### Exemplo:
```
rmdir C:\Documentos\Projetos
```
Este comando remove o diretório "Projetos" localizado em "C:\Documentos". Lembre-se de que o diretório precisa estar vazio.

Se o diretório contiver arquivos, use o comando `rmdir /s` para remover o diretório e todos os arquivos dentro dele.
### Exemplo:
```
rmdir /s C:\Documentos\Projetos
```


## 3. Criar um Arquivo
Para criar um arquivo vazio, podemos usar o comando `echo`.
### Comando:
```
echo. > nome_do_arquivo.txt
```
### Exemplo:
```
echo. > C:\Documentos\novo_arquivo.txt
```
Esse comando cria um arquivo vazio chamado "novo_arquivo.txt" no diretório "Documentos".


##  4. Remover um Arquivo
Para remover um arquivo, utilizamos o comando `del`.
### Comando:
```
del nome_do_arquivo.txt
```
### Exemplo:
```
del C:\Documentos\novo_arquivo.txt
```
Esse comando exclui o arquivo "novo_arquivo.txt" do diretório "Documentos".


## 5. Copiar um Arquivo
Para copiar arquivos, usamos o comando `copy`.
### Comando:
```
copy caminho_do_arquivo destino
```
### Exemplo:
```
copy C:\Documentos\arquivo.txt D:\Backup\
```
Esse comando copia o arquivo "arquivo.txt" da pasta "Documentos" para a pasta "Backup" no disco D.


## 6. Mover um Arquivo
Para mover arquivos, utilizamos o comando `move`.
### Comando:
```
move caminho_do_arquivo destino
```
### Exemplo:
```
move C:\Documentos\arquivo.txt D:\Arquivos\
```
Esse comando move o arquivo "arquivo.txt" da pasta "Documentos" para a pasta "Arquivos" no disco D.


## 7. Renomear um Arquivo
Para renomear um arquivo, usamos o comando ren.
### Comando:
```
ren nome_antigo.ext nome_novo.ext
```
### Exemplo:
```
ren C:\Documentos\arquivo.txt novo_arquivo.txt
```
Esse comando renomeia o arquivo "arquivo.txt" para "novo_arquivo.txt" na pasta "Documentos".


## 8. Exibir o Conteúdo de um Arquivo
Para exibir o conteúdo de um arquivo no console, usamos o comando `type`.
### Comando:
```
type nome_do_arquivo.txt
```
### Exemplo:
```
type C:\Documentos\arquivo.txt
```
Esse comando exibe o conteúdo do arquivo "arquivo.txt" na tela.


## 9. Mudar o Diretório de Trabalho
Para mudar o diretório de trabalho (ou seja, acessar outras pastas), usamos o comando `cd`.
### Comando:
```
cd caminho_do_diretorio
```
### Exemplo:
```
cd C:\Documentos\Projetos
```
Esse comando muda o diretório de trabalho para "C:\Documentos\Projetos".


## 10. Voltar um Nível no Diretório
Para voltar um nível no diretório (ir para a pasta pai), usamos o comando `cd ..`.
### Comando:
```
cd ..
```
### Exemplo:
```
cd ..
```
Esse comando move o diretório de trabalho para o diretório pai, ou seja, para a pasta acima na estrutura de diretórios.


## 11. Limpar a Tela
Para limpar a tela do prompt de comando, usamos o comando `cls`.
```
cls
```
### Exemplo:
```
cls
```
Esse comando limpa o conteúdo exibido no console, deixando a tela limpa para novos comandos ou resultados.

---
Esses são os comandos básicos do Batch para manipulação de arquivos, pastas e navegação no sistema de arquivos. Eles podem ser usados de forma conjunta para automatizar tarefas e facilitar a administração de arquivos no Windows.
