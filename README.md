<style>
  summary {
    font-size: 1.5em;
    font-weight: bold;
    background-color:rgba(59, 64, 109, 0.7);
    color: #fff;
    padding: 3px;
    border-radius: 1px;
  }
</style>

# 📚 GIT AULA

<details>
<summary>Módulo 01</summary>

## 📝 Aula 01 - Como Funciona o Git

Nesta aula, exploro o conceito de controle de versão com Git e GitHub. Destaco a importância de criar commits, branches e repositories. Comparo o Git ao Doctor Strange da Marvel, que manipula o tempo. Explico a necessidade de usar o Stage Area antes de fazer um commit. Destaco a diferença entre repositório local e remoto, enfatizando a importância de armazenar o código na nuvem, como no GitHub. Abordo a colaboração de equipes e os principais comandos do Git.

### Exemplos de Comandos

- `git init`: Inicializa um novo repositório Git.
- `git status`: Verifica o status das alterações.
- `git add <arquivo>`: Adiciona um arquivo ao stage area.
- `git commit -m "mensagem"`: Cria um commit com uma mensagem descritiva.
- `git push`: Envia alterações para um repositório remoto.

## 🛠️ Aula 02 - Comandos Básicos Para Repositório Local

Nesta aula vamos ver comandos fundamentais para trabalhar com um repositório local no Git. Comandos como git init para iniciar um repositório, git status para verificar alterações, git add para adicionar arquivos ao stage area, git commit para criar um ponto na história com uma mensagem e git log para visualizar todos os commits. Esses comandos são essenciais para gerenciar um repositório local no Git.

### Exemplos de Comandos

- `git init`
- `git status`
- `git add <arquivo>`
- `git commit -m "mensagem"`
- `git log`

## 🚀 Aula 03 - Iniciando Um Repositório Git

Nesta aula, iniciamos um repositório Git em um projeto, utilizando o comando `git init` no terminal. É importante saber navegar até a pasta do projeto usando o comando `cd` e verificar o caminho com `pwd`. Independentemente do sistema operacional, a navegação é essencial. Após executar o comando `git init`, o repositório Git é criado. O processo é simples e fundamental para gerenciar versões do projeto.

### Exemplos de Comandos

- `cd <caminho_do_projeto>`
- `pwd`
- `git init`

## 🗂️ Aula 04 - Adicionando Modificações ao Stage Area

O comando `git status` é essencial para verificar as alterações nos arquivos antes do commit. Utilize `git add` para adicionar arquivos ao StageArea e `git rm --cached` para remover. Com `git add .`, é possível adicionar todos os arquivos de uma pasta. Lembre-se de adicionar novamente os arquivos modificados ao StageArea antes de fazer o commit. Esses passos são fundamentais para o versionamento de arquivos no Git.

### Exemplos de Comandos

- `git status`
- `git add <arquivo>`
- `git rm --cached <arquivo>`
- `git add .`

## ✅ Aula 05 - Criando o Primeiro Commit

Nesta aula, aprendemos a criar o primeiro commit de um projeto no Git. Utilizamos o comando `git status` para verificar o estado do projeto e o `git restore` para restaurar um arquivo ao seu estado anterior. Ao adicionar e commitar as alterações, foi explicado o significado da mensagem gerada pelo Git. Finalizamos entendendo a importância de adicionar arquivos ao stage area antes de realizar um commit.

### Exemplos de Comandos

- `git status`
- `git add <arquivo>`
- `git commit -m "mensagem"`

## 🔄 Aula 06 - Alterando e Commitando

Nesta aula, aprendemos a fazer alterações em um arquivo, atualizar as mudanças e criar um novo commit no Git. Foi destacada a importância de entender o fluxo de trabalho, como adicionar arquivos modificados, criar commits com mensagens descritivas e gerenciar as alterações. O instrutor enfatizou que o Git rastreia automaticamente as modificações nos arquivos, facilitando o processo de versionamento. O controle de versão é essencial para gerenciar e acompanhar as alterações nos arquivos de um projeto.

### Exemplos de Comandos

- `git status`
- `git add <arquivo>`
- `git commit -m "mensagem"`

## 🔍 Aula 07 - Navegando Pelos Commits

Neste trecho, expliquei como navegar pelos commits usando o comando `git log` para visualizar a história do projeto. Demonstrei como voltar para um commit anterior usando `git checkout` e a importância de entender o identificador único de cada commit. Destaquei a possibilidade de criar uma nova branch para trazer modificações de volta ao fluxo de trabalho principal. Finalizei ressaltando a importância de revisitar versões anteriores dos arquivos para entender as mudanças e como retornar ao estado atual do projeto.

### Exemplos de Comandos

- `git log`
- `git checkout <commit_id>`

## ♻️ Aula 08 - Recuperando Um Arquivo Deletado

Neste trecho, expliquei como recuperar um arquivo deletado em um projeto usando o Git. Ao deletar um arquivo, o Git rastreia essa ação. Com o comando `git checkout`, é possível recuperar a versão anterior do arquivo. Se desejar remover o arquivo do "stage area", basta avisar ao Git. Após recuperar o arquivo, é possível criar um novo commit. O Git permite recuperar arquivos deletados com facilidade, desde que o rastreamento dos commits esteja sendo feito corretamente.

### Exemplos de Comandos

- `git rm <arquivo>`
- `git checkout -- <arquivo>`

</details>
<details>
<summary> Módulo 02 </summary>

## 🌐 Aula 01 - O Que É Github

O Github é uma plataforma online para hospedar códigos do Git, permitindo colaboração em projetos. É essencial para compartilhar e mostrar seu trabalho, além de facilitar a conexão entre desenvolvedores. Outras plataformas similares são GitLab e Bitbucket. Ao utilizar o Github, é possível trabalhar em equipe, acessar projetos de terceiros e construir um portfólio. Nas próximas aulas, aprenderemos a instalar, criar uma conta, e conectar projetos ao Github.

## 🆕 Aula 02 - Criando uma Conta no Github

Nesta aula, aprendemos a criar uma conta no GitHub. Foi demonstrado o processo de registro no site, incluindo a escolha de um e-mail, senha e nome de usuário. Também foi abordada a etapa de verificação de segurança com um quebra-cabeças. Após a confirmação por e-mail, foram feitas algumas configurações opcionais, como número de pessoas na equipe e status de estudante. Ao final, a conta foi criada com sucesso.

## ⚙️ Aula 03 - Configurando o Github

Nesta aula, aprendemos a configurar o perfil do GitHub, incluindo nome de usuário, biografia, empresa, localização, site e redes sociais. Recomenda-se adicionar uma foto de até 1MB. Organizar o perfil público é importante para que as pessoas possam conhecê-lo melhor. Essas são as configurações mínimas recomendadas para o GitHub.

## 🔗 Aula 04 - Conectando Repositório Local Com Repositório Remoto

Neste vídeo, aprendemos a conectar um repositório local com um repositório remoto no GitHub. É explicado como criar um novo repositório, a importância de deixá-lo público ou privado, a função do README, gitignore e licença, e como adicionar arquivos ao repositório remoto. São fornecidas instruções passo a passo para realizar essas ações, incluindo a criação de um README.md, o primeiro commit e o push para o repositório remoto. O processo é descrito de forma simples e direta, facilitando a conexão entre o repositório local e remoto.

### Exemplos de Comandos

- `git remote add origin <url_do_repositorio>`
- `git push -u origin master`

## 🔄 Aula 05 - Navegando Pelos Commits Através Da Interface Do Github

Neste vídeo, exploro como analisar os commits no GitHub, mostrando como verificar o histórico de commits, visualizar alterações de linhas, deletar e resgatar arquivos, e navegar entre diferentes momentos do projeto. Demonstro como usar a interface do GitHub para visualizar essas informações sem precisar digitar comandos no terminal, facilitando a navegação e compreensão do histórico do projeto. Também menciono a possibilidade de acessar diferentes branches e tags, além de mostrar como utilizar o comando `git checkout` por meio da interface do GitHub.

## ⬇️ Aula 06 - Comandos Para Atualizar e Enviar Atualizações Entre Repositórios Remoto e Local

O comando `git pull` é essencial para trazer modificações do repositório remoto para o local, evitando conflitos. O `git push` envia suas modificações locais para o repositório remoto. Gerenciar conflitos é possível com o Git. É importante puxar as modificações antes de enviar as suas. Esses comandos são fundamentais para colaboração em equipe.

### Exemplos de Comandos

- `git pull origin master`
- `git push origin master`

## 🔄 Aula 07 - Atualizando Modificações Entre Repositório Local e Remoto

Nesta aula, demonstro como atualizar e enviar alterações em um repositório compartilhado. Explico a importância do `git pull` para sincronizar as mudanças feitas por outros colaboradores antes de enviar as próprias alterações com `git push`. Destaco a necessidade de verificar possíveis erros após o `git pull` antes de realizar o `git push`. Mostrando na prática como adicionar, commitar e enviar arquivos para o repositório. É fundamental compreender a dinâmica entre `git pull` e `git push`.

### Exemplos de Comandos

- `git pull origin master`
- `git add <arquivo>`
- `git commit -m "mensagem"`
- `git push origin master`

## 📥 Aula 08 - Trazendo um Repositório Remoto para Minha Máquina

Nesta aula, aprendemos como clonar um projeto do GitHub para a nossa máquina local usando o comando `git clone`. Ao navegar até a pasta desejada no terminal e utilizar esse comando com o endereço do repositório, conseguimos trazer todos os arquivos para a nossa máquina. Mesmo que o nome da pasta local seja diferente do nome do repositório no GitHub, isso não afeta o desenvolvimento. Com isso, podemos continuar trabalhando no projeto localmente sem problemas.

### Exemplos de Comandos

- `cd <caminho_desejado>`
- `git clone <url_do_repositorio>`

## 🌟 Aula 09 - Utilizando o Github como um controle de versão completo

Nesta aula, demonstro como usar o GitHub para fazer alterações no projeto sem precisar do terminal. Acesse `github.dev`, edite arquivos, faça commits e push diretamente no navegador. Utilize o editor semelhante ao VS Code para gerenciar versões. Aprenda a deletar arquivos permanentemente e a descartar alterações. Visualize e gerencie commits feitos. A evolução da tecnologia traz soluções práticas. Estude e se especialize para acompanhar as novidades e melhorar suas habilidades de programação.

### Exemplos de Comandos

- `edit file on GitHub.dev`
- `git commit -m "mensagem"`
- `git push`

</details>
