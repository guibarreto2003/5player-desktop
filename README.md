# 5player — distribuição pública

Este repositório é reservado a instaladores e metadados de atualização do 5player para Windows. Ele não recebe a árvore Git do projeto, histórico de desenvolvimento, dados de usuários ou credenciais.

## Compatibilidade dos downloads

O endereço público de compatibilidade é `guibarreto2003/5player-desktop`. Ele é reservado à distribuição, enquanto o repositório completo de desenvolvimento fica separado e privado. O nome anterior do repositório de preparação, `5player-releases`, pode redirecionar para o endereço público de compatibilidade.

As versões históricas mantêm os mesmos números, nomes de arquivos e bytes dos instaladores já distribuídos. Essa separação não lança uma versão nova nem exige que os aplicativos anteriores recebam uma atualização de transição. Consulte as Releases publicadas para obter os instaladores disponíveis.

Somente versões aprovadas para lançamento global devem aparecer em Releases. Builds de **5player dev**, seus feeds privados e suas credenciais não devem ser publicados aqui.

## Arquivos de distribuição

Uma release aprovada deve conter somente os artefatos necessários: instalador Windows `.exe`, mapa diferencial `.exe.blockmap` e manifesto `latest.yml`. O download só deve ser anunciado depois da validação dos hashes e do acesso sem autenticação.

As cópias ZIP/TAR de código-fonte geradas automaticamente pelo GitHub conterão apenas o conteúdo deste repositório de distribuição, não a árvore do projeto de desenvolvimento.

## Limite de privacidade

Um instalador Electron contém os recursos necessários para executar o aplicativo, incluindo JavaScript que pode ser extraído. Separar o repositório-fonte protege o acesso ao repositório e ao seu histórico; não torna o código distribuído no executável irrecuperável e não remove cópias públicas anteriores.

Nunca inclua tokens, senhas, cookies, arquivos `.env`, dados de salas/contas ou chaves de assinatura nos artefatos públicos.
