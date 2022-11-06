# Introdução a Git/GitHub - Anotações

O Git é responsável pelo controle de códigos, suas informações e alterações, sendo um aplicativo não gráfico (ou seja, não é possível interagir com ícones, sendo necessário, apenas, a utilização da programação). Assim, é trabalhado de maneira manual e pode mostrar todas as informações e alterações tangentes ao arquivo.
O GitHub é uma plataforma remota, que funciona como uma rede social, conectando os devs e disponibilizando os códigos criados e/ou editados por estes
- Repositório: Pasta que armazena arquivos e códigos.
- SHA (Algoritmo de Hash Seguro): É um código gerado com a encriptação, sendo composto por um conuunto de caracteres identificador de 40 dígitos. O Git utiliza o SHA para identificar os arquivos de maneira rápida e segura.
- Commit: Armazena todos os metadados, é necessário atualizá-lo a cada modificação feita.

## Observações:
- Quando um arquivo/código for postado no GitHub e editado no dispositivo de origem, é necessário realizar as alterações e atualizações no git e em seu commit. 
Para checar se houve a atualização: git status
Para adicionar as alterações: git add *
Para atualizar o commit: git commit -a -m "mensagem"

- Quando for mandar o commit da máquina para o GitHub: git push

- Quando alguém atualizar seu código e houver conflitos entre o arquivo presente remotamente e o arquivo da máquina:
1. "Puxar" o arquivo da internet (git pull), checando e resolvendo o erro
2. Commitar

- Para clonar o código de alguém: git clone (link)

