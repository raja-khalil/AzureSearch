# Passo a Passo: Configurando a Busca Cognitiva no Azure

## Pré-requisitos
- Assinatura ativa do Microsoft Azure[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva)
- Acesso ao portal do Azure[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva)
- Familiaridade básica com conceitos de IA e Serviços Cognitivos do Azure[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva)

## Passo 1: Criar um Serviço de Busca Cognitiva
1. Acesse o Portal do Azure[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
2. No menu de serviços, procure por **Azure Cognitive Search**[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
3. Clique em **Criar** para iniciar o processo de configuração[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
4. Preencha os campos necessários, como **Nome**, **Grupo de Recursos** e **Região**[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
5. Selecione o plano de preços apropriado (uma versão gratuita está disponível)[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
6. Clique em **Revisar + Criar** e, em seguida, em **Criar** para provisionar o serviço[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).

## Passo 2: Criar um Índice
1. No serviço de Busca Cognitiva que você criou, vá para a aba **Índices**[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
2. Clique em **Adicionar Índice**[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
3. Defina um nome para o índice e crie campos que correspondam à estrutura dos dados que deseja pesquisar (por exemplo, **Título**, **Autor**, **Conteúdo**)[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
4. Defina os tipos de dados e as propriedades de pesquisa de cada campo[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
5. Clique em **Criar**[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).

## Passo 3: Carregar Documentos no Índice
1. No painel do serviço de Busca Cognitiva, vá até **Fontes de Dados**[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
2. Crie uma nova fonte de dados escolhendo o tipo de repositório de dados (por exemplo, **Blob Storage** ou **banco de dados SQL**)[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
3. Configure a conexão com a fonte de dados, garantindo que os documentos estejam no formato correto[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
4. Crie um **Indexador** para processar automaticamente os documentos e carregá-los no índice[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
5. Execute o indexador e verifique o status para garantir que os documentos foram carregados corretamente[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).

## Passo 4: Executar Consultas
1. Acesse a aba **Explorador de Pesquisa** dentro do painel do seu serviço de Busca Cognitiva[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).
2. Realize consultas simples no índice, utilizando parâmetros como **título**, **autor** ou **conteúdo**[_{{{CITATION{{{_1{Fundamentos de IA no Microsoft Azure: Busca Cognitiva - GitHub](https://github.com/mperaltarj/Fundamentos-de-IA-no-Microsoft-Azure-Busca-Cognitiva).

## Benefícios da Busca Cognitiva do Azure
- **Escalabilidade**: Pode lidar facilmente com grandes conjuntos de dados[_{{{CITATION{{{_2{Como transformar completamente a experiência de pesquisa da sua ...](https://cloudsquad.com.br/azure-cognitive-search-transforme-a-experiencia-de-pesquisa-do-seu-app/).
- **Segurança**: Inclui recursos de segurança robustos, como autenticação e autorização de usuário[_{{{CITATION{{{_2{Como transformar completamente a experiência de pesquisa da sua ...](https://cloudsquad.com.br/azure-cognitive-search-transforme-a-experiencia-de-pesquisa-do-seu-app/).
- **Flexibilidade**: Pode ser integrado a uma ampla variedade de aplicações e sites[_{{{CITATION{{{_2{Como transformar completamente a experiência de pesquisa da sua ...](https://cloudsquad.com.br/azure-cognitive-search-transforme-a-experiencia-de-pesquisa-do-seu-app/).

Espero que este guia seja útil! Se precisar de mais alguma coisa, estou aqui para ajudar. 😊
