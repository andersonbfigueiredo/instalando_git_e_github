# Instalando o Git e integrando com o Github na prática

Esse projeto tem como objetivo demonstrar, de forma prática, como instalar e configurar o Git, integrá-lo ao GitHub e realizar o upload de projetos. O passo a passo detalhado facilita o entendimento de cada etapa, desde a instalação até o envio de arquivos para o repositório remoto. Ideal para iniciantes!

## Passo 1
### Download do Git

[![Download Git](./imagens/7.PNG)](https://git-scm.com/)
<sup>Imagem Clicável</sup>

Após o processo de download, instale o Git no seu equipamento, no meu caso aqui foi utilizado no meu período o *Windows 10*. Mas o mesmo pode ser baixado em diversos sistemas operacionais como *Mac* quanto *Linux* veja qual melhor te atende para esse processo e verifique as diferenças de instalação.

![Git Bash](./imagens/12.PNG)
<sup>**IMPORTANTE:** Ao final do processo de instalação do Git selecione a opção apresentada.</sup>

Neste projeto faremos todo processo de instalação no sistema operacional *Windows 10*.

## Passo 2
### Crie um diretório

![Diretório Local](./imagens/8.PNG)
<sup>Diretório Local</sup>

Neste processo criei um diretório local chamado **"_instalando_git_e_github"** e coloquei ele em qualquer lugar no meu equipamento. Mas é muito importante saber em qual local ele se encontra.

[![Diretório Online](./imagens/4.PNG)](https://github.com/andersonbfigueiredo/instalando_git_e_github.git)
<sup>Diretório Online</sup>

Após o processo anterior fui até a [página do Github](https://github.com) crei meu usuário e depois disso crie o meu primeiro diretório o qual ficom com o seguinte nome/endereço ([andersonbfigueiredo/instalando_git_e_github](https://github.com/andersonbfigueiredo/instalando_git_e_github.git)).

<sup>Clicando nestas urls você já irá para os caminhos já apresentados nas imagens</sup>

## Passo 3
### Crie um arquivo neste diretório local

Quando você criar um **diretório online no Github** ele já te traz a orientação de qual arquivo criar com a nomenclatura devida, *mas isso é algo opicional que pode ser feito de outra forma*. Neste caso aqui como é um processo de formação oriento para que faça da mesma forma.

![README.md](./imagens/9.PNG)
<sup>README.md</sup>

> MD = **Markdown** é uma linguagem de formatação simples que converte texto em HTML, facilitando a criação de documentos bem estruturados com sintaxe fácil de ler e escrever.  
> [<sup>Saiba+</sup>](https://pt.wikipedia.org/wiki/Markdown)

## Passo 4
### Editor de texto ou código

Novamente no meu caso aqui estou usando o editor **VS Code**, mas você pode utilizar qualquer um da sua escolha.

> **VS Code** é um editor de código leve, poderoso e personalizável, com suporte a diversas linguagens e extensões para desenvolvimento eficiente.  
> [<sup>Download+</sup>](https://code.visualstudio.com/download)

![README.md](./imagens/10.PNG)
<sup>Edição do README.md, neste processo lhe sugiro escrever somente uma linha, frase ou palavra somente para ver como fica no processo final e após isso poderá fazer as atualizações necessárias.</sup>

## Passo 5
### Acessando o Git Bash

Após a instalação do Git, VS Code e criação de conta no Github + os diretórios (local/online) criados agora iremos para o **Git Bash**.

Para acessa-lo é bem simples, primeiro clique com o botão direito do mouse na área de trabalho após feito isso aparecerá algo assim:
![Git Bash](./imagens/11.PNG)
<sup>**IMPORTANTE:** Lembre-se que é sobre a área de trabalho, se clicar sobre o arquivo README.md não irá ocorrer da mesma forma.</sup>

## Passo 6
### Quais comandos utilizar e porque?

#### Comando 1

##### git --version

![Git Version](./imagens/13.PNG)
<sup>Este comando serve para verificar se a versão que baixou e instalou é a mesma que está sendo utilizada pelo Git Bash.</sup>

#### Comando 2

##### git init

![Git Init](./imagens/14.PNG)
<sup>Este comando serve para inicializar um repositório **Git**.</sup>

Observe a imagem e veja o que ocorreu nas setas:
1. Local do Git Bash que foi criado o comando *git init*.
2. Veja que um usuário *Master* apareceu no final do endereço do caminho do local do equipamento.
3. Veja que também foi criado um subdiretório no seu diretório principal chamado *.git*. Recomendo fortemente que ***NÃO*** apague/delete esse subdiretório.

#### Comando 3

##### git add

![Git Add](./imagens/15.PNG)
<sup>Este comando serve para adicionar todos os arquivos criados dentro deste diretório.</sup>

**Orientação:**
1. Pode ser feito o comando *git add README.md*
2. Pode ser feito o comando *git add .*, ou seja tudo que estiver dentro deste diretório será adicionando.

> <sup>**Observação:** É muito importante saber o local que está autenticado/logado, ou seja o diretório que está porque senão quando efetivar esse comando e se estiver por exemplo na sua raíz do diretório *c:* o comando irá compreender que tudo que estiver dentro do seu dispositivo deverá se adicionado.</sup>

