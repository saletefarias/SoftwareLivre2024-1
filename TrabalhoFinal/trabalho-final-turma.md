# Trabalho Final - Turma Software Livre 2024-1

Esse arquivo compila **todas as colaborações** realizadas pela turma durante a realização do trabalho final.
O propósito deste arquivo é permitir uma visão global de tudo o que foi desenvolvido, de maneira simples e rápida.

As colaborações estão divididas por tipos, conforme estabelecido na [especificação do trabalho final](TrabalhoFinal.md), e devem seguir o seguinte padrão:

* frase descrevendo o que foi feito ([link para a colaboração]() - [@usuario]())

* OBS: Caso esteja utilizando conta secundária ou pseudônimos e nicknames no nome de usuário, adicionar o @usuario + (seu_nome) no escopo da contribuição*

Por exemplo:

```Permite que o OpenDSSDirect busque o caminho para o GCC independente da distribuição ([OpenDSSDirect#24](https://github.com/Muxelmann/OpenDSSDirect.make/pull/24) - [@filipesaraiva](https://github.com/filipesaraiva))```

```Tradução do README do projeto scancode-toolkit ([PR](https://github.com/nexB/scancode-toolkit/pull/1640) - [@danielXYZ](https://github.com/danielxyz))```

Segue abaixo todas as colaborações realizadas pela turma durante a disciplina.

## Reportar bug (0)


## Melhorar documentação (0)


## Realizar tradução (4)

* Foi feito uma tradução para PT-BR do Godot Editor - ([contribuição](https://hosted.weblate.org/translate/godot-engine/godot/pt/?checksum=658e910cac54b47a) - [@davidAly(david-alysson)](https://github.com/DavidAly));
* Foi feito uma tradução para PT-BR do Godot Editor - ([contribuição](https://hosted.weblate.org/translate/godot-engine/godot/pt/?checksum=4098574c0e119176) - [@davidAly(david-alysson)](https://github.com/DavidAly));

* EXEMPLO Tradução do README do projeto scancode-toolkit ([PR](https://github.com/nexB/scancode-toolkit/pull/1640) - [@danielXYZ](https://github.com/danielxyz))
  
* Foi feito a [tradução](https://docs.google.com/presentation/d/1jslBpZlaSi5D8dGLpMDhHx7__1fY_LmqgXw7haiOgTo/edit?usp=sharing) de funcionalidades da biblioteca calendario da documentação do Python - [@DanielMoura](https://github.com/DanielLieblen/SoftwareLivre2024-1/blob/main/TrabalhoFinal/DanielMoura.md).

## Corrigir bug (5)


* Correção para carregamento de dados: Havia problemas de autorização no acesso de recursos. ([PR #4738](https://github.com/keiyoushi/extensions-source/pull/4738) - [Chopper(daniel-rocha)](https://github.com/choppeh));
* Correção para autenticação do usuário com a fonte de dados: Usuários logados não conseguiam acessar conteudos protegidos por login. ([PR #4295](https://github.com/keiyoushi/extensions-source/pull/4295) - [Chopper(daniel-rocha)](https://github.com/choppeh));
* Atualização de API e modelo de dados de transferencia: Fonte de dados alterou o conjunto de APIs usadas junto com o schema de dados de comunciação. ([PR #4743](https://github.com/keiyoushi/extensions-source/pull/4743) - [Chopper(daniel-rocha)](https://github.com/choppeh));
*  Correção de bug para ferramenta de save automático que estava salvando os documentos sem a existência de qualquer alteração. ([PR #18](https://github.com/Slacky300/REAL_TIME_EDIFY/pull/18) - [a-mais(paulo-pinheiro)](https://github.com/a-mais));
* Foi realizado um commit para o `Projeto Pessoal - Listador Online` [[Link do Projeto](https://github.com/PetsuTHEPRO/ListadorOnline)] para corrigir o bug de falha ao carregar as imagens do sistema. [[Commit](https://github.com/PetsuTHEPRO/ListadorOnline/commit/8953a0dead04672c8053a38c3c90a8f60ea036a6)] inclui a adição de uma lógica de prevenção de erros caso a imagem não exista, além da correção dos caminhos das imagens que estavam incorretos;

## Adicionar pequena funcionalidade (5)

* Inclusão de suporte a [Deeplink Android](https://developer.android.com/training/app-links#deep-links) para tema NextJs: Funcionalidade permite que os usuários através de links ou do navegador possam ser redirecionados para os aplicativos que suportam a fonte de dados que usa o tema como base. ([PR #3231](https://github.com/keiyoushi/extensions-source/pull/3231) - [Chopper(daniel-rocha)](https://github.com/choppeh));

* Inclusão de suporte para configuração de [User-Agent](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Headers/User-Agent) para extensão japonesa MangaMate. Funcionalidade adiciona suporte para configuração individual de User-Agent, feature soluciona problemas relacionados a proteção contra robôs da Cloudflare ([PR #3162](https://github.com/keiyoushi/extensions-source/pull/3162) - [Chopper(daniel-rocha)](https://github.com/choppeh));

* Adição de funcionalidade de alteração de useragent ([PR #4877](https://github.com/keiyoushi/extensions-source/pull/4877) - [@davidAly(david-alysson)](https://github.com/DavidAly));

* Implementação para habilitar funcionalidade de abas recentes ([PR #4878](https://github.com/keiyoushi/extensions-source/pull/4878) - [@davidAly(david-alysson)](https://github.com/DavidAly));

* Foi feito o [pull request](https://github.com/cardo-podcast/cardo/pull/5/commits/8baef31b292edcd359a0a9a75919561d9abe8bcb) Essa solicitação de pull adiciona um componente VolumeControl ao arquivo AudioPlayer.tsx, permitindo que os usuários ajustem o volume e alternem entre os estados mudo e som. O componente inclui ícones para estados de volume e mudo e atualiza o volume de áudio e o estado mudo conforme necessário - [@DanielMoura](https://github.com/DanielLieblen/SoftwareLivre2024-1/blob/main/TrabalhoFinal/DanielMoura.md).



## Adicionar grande funcionalidade (5)


*  Adição de fonte de dados(Extensão MangaCan) indiana. ([PR #3113](https://github.com/keiyoushi/extensions-source/pull/3113) - [Chopper(daniel-rocha)](https://github.com/choppeh));

* Adição de fonte de dados (Extensão  Manga Terra) para falantes da lingua portuguesa. ([PR #2300](https://github.com/keiyoushi/extensions-source/pull/2300) - [Chopper(daniel-rocha)](https://github.com/choppeh));

* Adição de fonte de dados (Extensão LadronCorps) para falantes de espanhol. ([PR #3367](https://github.com/keiyoushi/extensions-source/pull/3367) - [Chopper(daniel-rocha)](https://github.com/choppeh));

* Adicionado funcionalidade de tema escuro e claro e botão alternador de modo escuro e modo claro para todo o software com persistência da escolha do modo em sessão  ([PR #17](https://github.com/Slacky300/REAL_TIME_EDIFY/pull/17) - [a-mais(paulo-pinheiro)](https://github.com/a-mais));

* Foi realizado commit's para o `Projeto Pessoal - Listador Online` [[Link do Projeto](https://github.com/PetsuTHEPRO/ListadorOnline)].
    - Primeiro [[Commit](https://github.com/PetsuTHEPRO/ListadorOnline/commit/c00386bd65671eabfa2836bf5741300dbe476da6)] feito por [Pedro Vitor](https://github.com/PedroVitorLNP) para realizar o desenvolvimento da tela de principal. 
    - Segundo [[Commit](https://github.com/PetsuTHEPRO/ListadorOnline/commit/d14c5ec8a2ff226aa661fcccad65e7fe62875ed5)] feito por [Akilan Henderson](https://github.com/AkilanHenderson) Foi feita a configuração da lógica de conexão ao banco de dados e o processo de cadastro do usuário.
    - Terceiro [[Commit](https://github.com/PetsuTHEPRO/ListadorOnline/commit/7e8479c14db930df81d829e10c8b596495565c8c)] feito por [Ramon](https://github.com/Ramon-ms) Implementação de busca de usuários cadastrados e edição de seus dados.
    - Quarto [[Commit](https://github.com/PetsuTHEPRO/ListadorOnline/commit/c1f115b33bfeb655c6585f39c1c6c453c28c7806)] feito por [José Peterson](https://github.com/PetsuTHEPRO) Implementação da exclusão de usuários, listagem e botão para abrir o link do perfil do instagram.

## Desenvolver estudo original com artigo sobre software livre (1)

* Foi feito estudo original com artigo sobre software livre como alternativa ao monopólio tecnológico [@DanielMoura](https://github.com/DanielLieblen/SoftwareLivre2024-1/blob/main/TrabalhoFinal/DanielMoura.md).

