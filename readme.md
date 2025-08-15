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

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no Github e seguir a segunda opção da lista de comandos que aparece no site.<br>
**IMPORTANTE** Depois do remote deve ser executado os outros 2 comandos da página.
```bash
git remote add origin <url_repositorio_github >
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

Para baixar as alterações que estão apenas no Github utilizamos o pull<br>
**IMPORTANTE** Sempre deve baixar a ultima versão da nuvem antes de enviar o atual do computador.
```bash
git pull
```

Para enviar os commits do pc para o Github utilizamos o **push**.<br>
```bash
git push
```

Para baixar o repositório do Github em um novo computador utilizamos o git clone
```bash
git clone < url_do_repositorio_github >
```
