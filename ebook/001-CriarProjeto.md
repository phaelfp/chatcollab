# Onde tudo começa

## Exercício 00 - Inicie projeto

### Tarefas
1. Pelo terminal, crie um template de react com o nome **chatcollab** no Desktop (área de trabalho) do seu SO ou em outro lugar que você preferir;
2. Entre na pasta do seu projeto usando o terminal e inicie o Git dentro dela;


### Passo a passo
#### 1. Crie pasta do projeto

Abra o terminal do seu SO, se estiver no Windows use o Power Shell, Git BASH ou similares para que o comando do Linux funcione. Se estiver no Linux ou Mac, ambos têm comandos muitos similares. Agora que você já está com o seu terminal aberto vamos executar os seguintes passos:

Entre no Desktop com o comando a seguir:
```bash
cd ~/Desktop
```

Criar um template de projeto react **chatcollab** dentro do Desktop:
```bash
yarn create vite chatcollab --template react
```
> Caso você queira criar um projeto React com TypeScript o comando é `yarn create vite chatcollab --template react-ts`

Acessar a pasta **chatcollab**:
```bash
cd chatcollab
```

> Caso você tenha criado uma pasta com o nome errado você pode usar o comando `rm -r nomeDaPasta` para excluir a pasta e aí só precisa criá-la novamente ou ainda o comando `mv nomeDaPastaErrado nomeDaPastaCerto` para renomear.

#### 2. Iniciar Git

No terminal e dentro da pasta **chatcollab** execute o comando a seguir, esse comando criará uma pasta oculta no seu projeto chamada **.git** (toda pasta e arquivos que começam com um ponto são ocultas). Dentro desta pasta ficará tudo sobre o Git que é o sistema de versionamento de arquivos que vamos utilizar durante todo o projeto. Tenha calma se você não sabe o que é Git, teremos um dia para entrar mais a fundo no conhecimento sobre ele.
```bash
git init
```

Se tudo deu certo você receberá uma saída similar no seu terminal:
```bash
Initialized empty Git repository in /home/marcobruno/Desktop/chatcollab/.git/
```

Está na dúvida se a pasta **.git** foi criada? Digite o comando a seguir que ele listará todos os arquivos e pasta que tem lá dentro:
```bash
ls -la
```

Terá uma resposta similar a esta no terminal:
```bash
total 32
drwxr-xr-x 4 marcobuno marcobuno 4096 Feb 23 16:34 ./
drwxr-xr-x 3 marcobuno marcobuno 4096 Feb 23 16:33 ../
drwxr-xr-x 7 marcobuno marcobuno 4096 Feb 23 16:34 .git/
-rw-r--r-- 1 marcobuno marcobuno  253 Feb 23 15:58 .gitignore
-rw-r--r-- 1 marcobuno marcobuno  364 Feb 23 15:58 index.html
-rw-r--r-- 1 marcobuno marcobuno  327 Feb 23 15:58 package.json
drwxr-xr-x 2 marcobuno marcobuno 4096 Feb 23 15:58 src/
-rw-r--r-- 1 marcobuno marcobuno  162 Feb 23 15:58 vite.config.js
```