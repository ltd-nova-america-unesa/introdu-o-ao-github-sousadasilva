# :wave: Fundamentos do GitHub 

## 🤓 Visão geral do curso e objetivos de aprendizado 

O objetivo deste curso é oferecer uma breve introdução ao GitHub. Também vamos fornecer materiais para aprendizado adicional e algumas ideias para começar na nossa plataforma. 🚀

## :octocat: Git e GitHub

Git é um **Sistema de Controle de Versão Distribuído (VCS)**, o que significa que é uma ferramenta útil para acompanhar facilmente as alterações no seu código, colaborar e compartilhar. Com o Git, você pode rastrear as alterações que faz no seu projeto para sempre ter um registro do que trabalhou e pode facilmente voltar a uma versão anterior, se necessário. Também facilita o trabalho com outras pessoas – grupos de pessoas podem trabalhar juntas no mesmo projeto e mesclar suas alterações em uma fonte final!

GitHub é uma forma de usar o mesmo poder do Git online, com uma interface fácil de usar. É usado em todo o mundo do software e além para colaborar e manter o histórico de projetos.

GitHub é lar de algumas das tecnologias mais avançadas do mundo. Se você está visualizando dados ou construindo um novo jogo, há toda uma comunidade e conjunto de ferramentas no GitHub que podem levá-lo para o próximo passo. Este curso começa com o básico do GitHub, mas vamos aprofundar o assunto mais tarde.

## :octocat: Compreendendo o fluxo do GitHub 

O fluxo do GitHub é um fluxo de trabalho leve que permite que você experimente e colabore em seus projetos facilmente, sem o risco de perder seu trabalho anterior.

### Repositórios

Um repositório é onde acontece o trabalho do seu projeto – pense nele como sua pasta de projeto. Ele contém todos os arquivos do seu projeto e o histórico de revisões. Você pode trabalhar dentro de um repositório sozinho ou convidar outras pessoas para colaborar com você nesses arquivos.

### Clonagem 

Quando um repositório é criado com o GitHub, ele é armazenado remotamente na ☁️. Você pode clonar um repositório para criar uma cópia local no seu computador e, em seguida, usar o Git para sincronizar os dois. Isso facilita a correção de problemas, adição ou remoção de arquivos e envio de commits maiores. Você também pode usar a ferramenta de edição de sua escolha em vez da interface do GitHub. A clonagem de um repositório também baixa todos os dados do repositório que o GitHub possui naquele momento, incluindo todas as versões de cada arquivo e pasta do projeto! Isso pode ser útil se você experimentar com o projeto e, em seguida, perceber que gostou mais de uma versão anterior. 
Para saber mais sobre clonagem, leia ["Clonando um Repositório"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Confirmação e envio
**Confirmação** e **envio** são como você pode adicionar as alterações que fez em sua máquina local ao repositório remoto no GitHub. Dessa forma, seu instrutor e/ou colegas de equipe podem ver seu trabalho mais recente quando estiver pronto para compartilhá-lo. Você pode fazer uma confirmação quando fizer alterações em seu projeto que deseja "checkpoint". Você também pode adicionar uma **mensagem de confirmação** útil para lembrar a si mesmo ou aos seus colegas de equipe sobre o trabalho que realizou (por exemplo, "Adicionado um README com informações sobre nosso projeto").

Depois de ter uma confirmação ou várias confirmações prontas para adicionar ao seu repositório, você pode usar o comando de envio para adicionar essas alterações ao seu repositório remoto. Fazer confirmações e envios pode parecer novo no início, mas prometemos que você se acostumará com isso 🙂

## 💻 Termos do GitHub para conhecer 

### Repositórios 
Já mencionamos repositórios, é onde acontece o trabalho do seu projeto, mas vamos falar um pouco mais sobre os detalhes deles! À medida que você trabalha mais no GitHub, terá muitos repositórios, o que pode parecer confuso no início. Felizmente, seu ["painel do GitHub"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ajuda a navegar facilmente pelos seus repositórios e ver informações úteis sobre eles. Certifique-se de estar logado para vê-lo!

Os repositórios também contêm **README**s. Você pode adicionar um arquivo README ao seu repositório para informar às outras pessoas por que seu projeto é útil, o que podem fazer com seu projeto e como podem usá-lo. Estamos usando este README para comunicar como aprender Git e GitHub com você. 😄 
Para saber mais sobre repositórios, leia ["Criando, Clonando e Arquivando Repositórios](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) e ["Sobre README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Branches
Você pode usar branches no GitHub para isolar o trabalho que não deseja mesclar em seu projeto final ainda. Branches permitem que você desenvolva recursos, corrija bugs ou experimente com segurança novas ideias em uma área contida do seu repositório. Tipicamente, você pode criar um novo branch a partir do branch padrão do seu repositório — main. Isso cria uma nova cópia de trabalho do seu repositório para você experimentar. Depois que suas novas alterações forem revisadas por um colega de equipe ou se estiver satisfeito com elas, você pode mesclar suas alterações no branch padrão do seu repositório.
Para saber mais sobre branches, leia ["Sobre Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
Um fork é outra maneira de copiar um repositório, mas geralmente é usado quando você deseja contribuir para o projeto de outra pessoa. Fazer um fork de um repositório permite que você experimente livremente com alterações sem afetar o projeto original e é muito popular ao contribuir para projetos de software de código aberto!
Para saber mais sobre forks, leia ["Fazer um fork de um repositório"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Solicitações de pull
Ao trabalhar com branches, você pode usar uma solicitação de pull para informar aos outros sobre as alterações que deseja fazer e solicitar feedback. Uma vez que uma solicitação de pull é aberta, você pode discutir e revisar as possíveis alterações com colaboradores e adicionar mais alterações, se necessário. Você pode adicionar pessoas específicas como revisores da sua solicitação de pull, o que mostra que você quer o feedback delas sobre suas alterações! Uma vez que uma solicitação de pull está pronta para ser concluída, ela pode ser mesclada no seu branch principal.
Para saber mais sobre solicitações de pull, leia ["Sobre Solicitações de Pull"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 


### Problemas
Problemas são uma maneira de rastrear aprimoramentos, tarefas ou bugs para o seu trabalho no GitHub. Problemas são uma ótima maneira de manter o controle de todas as tarefas que você deseja realizar para o seu projeto e informar aos outros sobre o que você planeja trabalhar. Você também pode usar problemas para informar a um projeto de código aberto favorito sobre um bug que encontrou ou um recurso que acha que seria ótimo adicionar!

Para projetos maiores, você pode acompanhar muitos problemas em um quadro de projeto. Os Projetos do GitHub ajudam você a organizar e priorizar seu trabalho e você pode ler mais sobre eles [neste documento "Sobre quadros de projeto](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). Provavelmente, você não precisará de um quadro de projeto para suas atribuições, mas uma vez que avance para projetos ainda maiores, eles são uma ótima maneira de organizar o trabalho da sua equipe! Você também pode vincular solicitações de pull e problemas para mostrar que uma correção está em andamento e fechar automaticamente o problema quando alguém mesclar a solicitação de pull.
Para saber mais sobre problemas e como vinculá-los às suas solicitações de pull, leia ["Sobre Problemas"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 

### Seu perfil de usuário

Sua página de perfil conta a história do seu trabalho por meio dos repositórios em que você está interessado, das contribuições que fez e das conversas que teve. Você também pode dar ao mundo uma visão única sobre quem você é com o README do seu perfil. Você pode usar seu perfil para informar aos futuros empregadores tudo sobre você! 
Para saber mais sobre seu perfil de usuário e adicionar e atualizar o README do seu perfil, leia ["Gerenciando o README do seu perfil"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Usando markdown no GitHub 

Você pode ter notado, mas você pode adicionar algum estilo divertido aos seus problemas, solicitações de pull e arquivos. ["Markdown"](https://guides.github.com/features/mastering-markdown/) é uma maneira fácil de estilizar seus problemas, solicitações de pull e arquivos com alguma sintaxe simples. Isso pode ser útil para organizar suas informações e facilitar a leitura para os outros. Você também pode adicionar gifs e imagens para ajudar a transmitir seu ponto de vista!
Para saber mais sobre o uso do markdown do GitHub, leia ["Sintaxe Básica de Escrita e Formatação"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

### Engajando-se com a comunidade do GitHub

A comunidade do GitHub é vasta. Existem muitos tipos de pessoas que usam o GitHub em seu dia a dia – estudantes como você, desenvolvedores profissionais, entusiastas trabalhando em projetos de código aberto e exploradores que estão apenas começando no mundo do desenvolvimento de software por conta própria. Existem muitas maneiras de interagir com a comunidade do GitHub, mas aqui estão três lugares onde você pode começar. 

#### Favoritar repositórios 

Se você achar um repositório interessante ou quiser acompanhar, favorite-o! Quando você favorita um repositório, ele também é usado como um sinal para apresentar melhores recomendações em github.com/explore. Se você quiser voltar aos seus repositórios favoritos, pode fazer isso por meio do seu perfil de usuário. 
Para saber mais sobre favoritar repositórios, leia ["Salvando Repositórios com Estrelas"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 

#### Seguir usuários 

Você pode seguir pessoas no GitHub para receber notificações sobre sua atividade e descobrir projetos em suas comunidades. Quando você segue um usuário, a atividade pública do GitHub deles aparecerá no seu painel para que você possa ver todas as coisas legais em que estão trabalhando. 
Para saber mais sobre seguir usuários, leia ["Seguindo Pessoas"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### Explorar o GitHub Explore 

O GitHub Explore é um ótimo lugar para fazer exatamente isso... explorar :smile: Você pode encontrar novos projetos, eventos e desenvolvedores para interagir.

Você pode conferir o site GitHub Explore [em github.com/explore](https://github.com/explore). Quanto mais você interage com o GitHub, mais personalizada será sua visualização do Explore. 

## 📝 Próximos passos opcionais 

* Abrir uma solicitação de pull e informar ao seu professor que você concluiu este curso.  
* Criar um novo arquivo markdown neste repositório. Informe o que você aprendeu e o que ainda está confuso! Experimente estilos diferentes!
* Criar o README do seu perfil. Deixe o mundo saber um pouco mais sobre você! O que você está interessado em aprender? No que você está trabalhando? Qual é o seu hobby favorito? Saiba mais sobre como criar o README do seu perfil no documento, ["Gerenciando o README do seu perfil"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Acesse o painel do seu usuário e crie um novo repositório. Experimente os recursos dentro desse repositório para se familiarizar com eles. 
* [Nos informe o que você gostou ou não gostou sobre o conteúdo deste curso](https://support.github.com/contact/education). O que você gostaria de ver mais? O que seria interessante ou útil para
