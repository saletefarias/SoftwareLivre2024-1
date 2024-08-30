# Relatório do Trabalho Final - Daniel Rocha

* Nome completo: Daniel Rocha da Silva
* Nível: Graduação
* Matrícula: 20192SI0004
* Trabalho: Individual

## Nota
 - Conta de contribuição: [Chopper](https://github.com/choppeh), conta segudária;
 - Projeto: [Keiyoushi](https://github.com/keiyoushi). Projeto de extensões para integração entre fansubs e agregadores de HQ( EUA), Manga(Japão), Manhwa(China), artitas amadoras ou  independentes para plataforma Android e qualquer fonte aberta que disponibilize leitores de quadrinhos ou com formato semelhate.

## Adicionar grande funcionalidade
As seguintes contribuições são adições de recursos usadas pelos projetos: [Tachiyomi](https://tachiyomi.org/), [Yokai](https://github.com/null2264/yokai), [Mihon](https://mihon.app/) e variantes. Considerei como grandes funcionalidades pois são recursos que não existem no repositório e que foram desenvolvidos do zero, somente com auxilio do contrato das APIs básicas do projeto e com issues marcas com [Source Request](https://github.com/keiyoushi/extensions-source/issues/new/choose);

- Adição de fonte de dados(Extensão MangaCan) indiana. [PR #3113](https://github.com/keiyoushi/extensions-source/pull/3113);
- Adição de fonte de dados (Extensão  Manga Terra) para falantes da lingua portuguesa. [PR #2300](https://github.com/keiyoushi/extensions-source/pull/2300);
- Adição de fonte de dados (Extensão LadronCorps) para falantes de espanhol. [PR #3367](https://github.com/keiyoushi/extensions-source/pull/3367);

## Adicionar pequena funcionalidade
Considerei como pequenas funcionalidades resolução de issues marcas como [Feature Request](https://sfu-dhil.github.io/dhil-docs/github/feature_request_guidelines/) ou que vi necessidade direta de adicionar um característica importante ausente.

- Inclusão de suporte a [Deeplink Android](https://developer.android.com/training/app-links#deep-links) para tema NextJs: Funcionalidade permite que os usuários através de links ou do navegador possam ser redirecionados para os aplicativos que suportam a fonte de dados que usa o tema como base. [PR #3231](https://github.com/keiyoushi/extensions-source/pull/3231);
- Inclusão de suporte para configuração de [User-Agent](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Headers/User-Agent) para extensão japonesa MangaMate. Funcionalidade adiciona suporte para configuração individual de User-Agent, feature soluciona problemas relacionados a proteção contra robôs da Cloudflare [PR #3162](https://github.com/keiyoushi/extensions-source/pull/3162);

## Correção de bugs
- Correção para carregamento de dados: Havia problemas de autorizaçãoo no acesso de recursos. [PR #4738](https://github.com/keiyoushi/extensions-source/pull/4738);
- Correção para autenticação do usuário com a fonte de dados: Usuários logados não conseguiam acessar conteudos protegidos por login. [PR #4295](https://github.com/keiyoushi/extensions-source/pull/4295);
- Atualização de API e modelo de dados de transferencia: Fonte de dados alterou o conjunto de APIs usadas junto com o schema de dados de comunciação. [PR #4743](https://github.com/keiyoushi/extensions-source/pull/4743);
