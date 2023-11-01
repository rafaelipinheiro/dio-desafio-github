# GIT/GITHUB

## Verificar a instalação
`git --version`

## Sua identidade
`git config --global user.name “Seu nome”`
`git config --global user.email seu@email`

## Visualizar configurações
`cat .gitconfig`

## Criar um repositório
`git init`

## Ajuda
`git help`

## Visualizar configurações
`cat .gitconfig`

## Adicionar ou modificar arquivos no repositório

### Para adicionar todos os arquivos novos ao repositório digitar o comando:
`git add .`

### Para adicionar um arquivo através do nome dele:
`git add filename`

### Para adicionar todos os arquivos de determinado tipo
`git add *.extension`

### Em seguida será necessário digitar o comando para confirmar a operação:
`git commit -m “Descrição da operação”`

### Para realizar um commit sem adicionar ter a necessidade de primeiro colocá-lo no staged area com o git add, utilizar o seguinte comando: (só funciona para arquivos já rastreados, ou seja, que já foram incluídos por um git add uma vez)
`git commit -am “Descrição para operação”`