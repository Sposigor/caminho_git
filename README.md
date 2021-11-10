# O Caminho do GIT

>Git é um sistema de controle de versão distribuído open source que facilita ações com o GitHub em seu notebook ou desktop.

## Primeiros passo em GIT: instale o git e crie uma conta GitHub

As duas primeiras coisas que você deseja fazer são instalar o git e criar uma conta GitHub gratuita.

Siga as instruções [aqui](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git) para instalar o git (se ainda não estiver instalado). Observe que usaremos git apenas na linha de comando. Embora existam ótimas GUIs (interfaces gráficas de usuário) do git, acho que é mais fácil aprender o git usando comandos específicos do git primeiro e depois experimentar uma GUI do git quando você estiver mais confortável com o comando. Recomendo que durante a instalação integre o git Shell ao seu terminal, se não o fizer basta usar o git shell que é instalado junto com o git.

Depois de fazer isso, crie uma conta GitHub [aqui](https://github.com/).

    Git e GitHub

    Um adendo: Git e GitHub não são a mesma coisa. Git é uma ferramenta de controle de versão de código aberto criada em 2005 por desenvolvedores que trabalham no sistema operacional Linux; GitHub é uma empresa fundada em 2008 que fabrica ferramentas que se integram ao git. Você não precisa do GitHub para usar o git, mas não pode usar o GitHub sem usar o git. Existem muitas outras alternativas ao GitHub, como GitLab, BitBucket e soluções "hospede seu próprio", como gogs e gittea. Todos esses são referidos no git-speak como “remotes” e todos são completamente opcionais. Você não precisa usar um controlador remoto para usar o git, mas tornará mais fácil compartilhar seu código com outras pessoas.

Aqui o link do [Linus Torvalds](https://www.youtube.com/watch?v=o8NPllzkFhE) de um TED que ele explica um pouco sobre o inicio do linux e do GIT.

Site para download e documentação do GIT:
<https://git-scm.com/>

Configuração inicial, após a instalação:
<https://git-scm.com/docs/git-config/pt_BR> e <https://git-scm.com/book/pt-br/v2/Customizing-Git-Git-Configuration>

No terminal:
> 1 - Configurar seu nome: **git config --global user.name *"Seu nome"*.**\
> 2 - Configurar email: **git config --global user.email *seuemail@email.com*.**\
> 3 - Configurar seu editor: **git config --global core.editor *editor*.**

São algumas das configurações iniciais após a instalação, para verificar basta digitar: **git config --list**


## Segundo passo em GIT: Repositorio local

Crie uma pasta em algum lugar do computador e vamos começar a trabalhar, abra a pasta e inicialize o terminal dentro dela, 

Após inicializar o git, vamos criar nosso primeiro projeto/repositorio local(Seu computador).

> Na linha de comando digitar: **git init**

Para inicializar o git na pasta local e em seguida vamos adicionar os arquivos para o git monitorar as mudanças/alterações.

> Na linha de comando digitar: **git add *nome do arquivo* ou *-A*.**

Para adicionar um arquivo em especifico ou todos eles. Apos as alterações vamos agora realizar nosso primeiro commit.

> Na linha de comando digitar: **git commit -a *"descrição do commit"***

Após a realização dessa 
