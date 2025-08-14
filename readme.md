# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização do git e Github
## Configuração Inicial
Rode os comandos abaixo no terminal(cmd) do seu computador.
```bash
git config --global user.name "Emerson Galdino da Silva"

git config --global user.email emerson.silva138@fatec.sp.gov.br
```
## Comandos do Git
Para iniciar o GIT em uma pasta do computador utilizamos o init.
**IMPORTANTE:** Só é executado 1 vez

```bash
git init
```
Para verificar a situação do repositório (pasta) usamos o status a qualquer momento

 ```bash
 git status
 ```
Para adicionar o arquivo
 ```bash
 git add . 
 ```
Para Salvar uma mensagem
```bash
git commit -m "escrever aonde paramos" 
```