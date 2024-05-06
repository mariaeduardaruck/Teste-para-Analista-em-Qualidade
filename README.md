# Teste para vaga - Analista de Qualidade

Teste criado pela empresa Magazord para o processo seletivo da vaga Analista de Qualidade júnior, desenvolvido pela candidata Maria Eduarda Rück.

> ## Primeiro cenário

Para garantir a funcionalidade de um projeto de integração de um marketplace, será necessário realizar uma série de testes acompanhado com o devido registro dos resultados referentes, além de manter um acompanhamento contínuo do sistema, a fim de mantê-lo atualizado e em perfeito estado de uso. Deverá ser testado, também, a integração de estoque, de anúncios, do faturamento, dos pedidos e dos preços. Para tal, começaremos com

### 1. Documentação e material de apoio
   
  Coletar para a análise informações, como, por exemplo, a documentação fornecida pelo próprio marketplace, incluindo suas respectivas guias de integração, a documentação de API,  e os requisitos técnicos, afim de compreender as práticas recomendadas. É importante coletar para análise, também, a arquitetura da integração entre o marketplace e o sistema de e-commerce, como por exemplo o fluxo de dados, as descrições de endpoints de API, os métodos de autenticação e segurança, entre outros.

### 2. Análise da documentação

  A análise deverá partir de perguntas como: quais são os requisitos do projeto? O que o cliente espera como resultado final? Quais as funcionalidades e objetivos a serem atingidos? Essa seria a proposta "funcional" do sistema proposto, mas e sobre os requisitos não funcionais? Como por exemplo, a escalabilidade, a segurança, a privacidade dos dados, a norma de ética (como a confiabilidade). É importante seguir, também, os acordos legais estabelecidos entre o e-commerce e o marketplace, como a política de uso de dados e as responsabilidades de privacidade. Deve ser feita a análise de todos esses (e ademais) requisitos do sistema. 

### 3. Mapeamento dos requisitos
   
  Para o mapeamento, seria importante rastrear o fluxo de integração entre o marketplace e o e-commerce. Acessar o histórico de integração do marketplace e o feedback de outros clientes também poderá servir de auxílio, como relatórios de problemas comuns e práticas recomendadas. Além disso, deve-se realizar um mapeamento constante, atualizando as informações de acordo com cada realização de teste. 

### 4. Ferramentas

  A utilização de ferramentas varia de acordo com cada empresa. Inicialmente, poderiam ser usadas ferramentas como a Confluence, com a finalidade de reunir toda a documentação do projeto (e a área teste) e compartilhar essas informações entre a equipe. Essa ferramenta trabalha bem com outras também, como por exemplo o Jira, que pode servir de auxílio para o rastreamento de problemas e o registro de resultados de testes. Algumas ferramentas de automoção de testes também podem aplicadas, como o LambdaTest (ou semelhantes), que permitirá o teste do marketplace em diversos dispositivos (e navegadores). 
  
  A ferramenta Cucumber também pode ser usada, uma vez que se relaciona bem com outras ferramentas e serve, para, testar o comportamento do software. Aqui acho importante ressaltar que metodologias como o BDD (Behavior Driven Development) poderão e muito auxiliar no teste de qualidade do produto que está sendo ofertado. Outras ferramentas de automoção como o Selenium também poderão ser utilizadas, a fim de testar a funcionalidade da interface do usuário. 

  Para teste de API, a ferramenta PostMen (ou semelhantes) poderá ser utilizada.

  Outra ferramenta muito utilizada para o registro de testes de um sistema seria o TestRail. De novo, a escolha da ferramenta depende dos costumes da equipe e da Empresa, e cada uma delas busca atender uma demanda específica. Logo, antes de escolher a ferramenta necessária, precisamos definir quais requisitos atender.
  
  Além das ferramentas citadas acima, outras como o pacote Office também podem servir para o rastreamento e registro dos dados coletados referente aos testes aplicados. Planilhas do EXCEL, arquivos WORD etc. servirão como apoio.

  Ferramentas de visualização (para a equipe interna ou stakeholders) também poderão ser utilizadas, como o Tableau, ou até mesmo esquemas feitos em Python ou no RStudio. 
  
  Como sempre, é necessário se colocar no lugar do cliente, a fim de buscar entender as suas motivações e interesses ao se tratar da utilização do software. A definição dos requisitos a serem atendidos e as perguntas certas a serem feitas (a fim de chegar nas respostas certas, também), irá guiar o analista ao resultado final que atingirá o sucesso da experiência do cliente.

  ### 5. Abrangência dos testes

  Como mencionado no enunciado, as integrações entre estoque, anúncios, faturamento, pedidos e preço deverão ser testadas. Alguns testes que poderão ser realizado entre cada integração, seriam

  - Para a integração de **estoque**, é importantíssimo conferir a sincronização e a atualização de estoque no e-commerce quando ocorrer alterações no marketplace. Será necessário conferir se a quantidade de estoque é consistente em todos os canais de venda. Realizar testes para conferir a validação desses dados será imprescindível.

  - Para a integração de **anúncios**, deve-se também conferir a sincronização e a atualização dos mesmos em cada canal de venda. Deverá ser testada a listagem de novos produtos no marketplace, incluindo informações como título, descrição, imagens e categorias. Deve-se conferir se o anúncio está em perfeita condição de uso, se o usuário é levado para a página correta, como será a experiência do cliente ao decidir clicar no anúncio, se ele poderá fechá-lo, entre outros.

  - Para a integração de **faturamento**, será necessário testar o processo de faturamento para garantir que os pedidos estejam sendo corretamente faturados e processados. Verificar, também, se os dados de pagamento são processados de forma segura e precisa. Seria interessante testar todas as formas de pagamento que o marketplace acopla!

  - Para a integração de **pedidos**, realizar testes em cada produto ofertado será necessário, conferindo o processo da realização de cada pedido, para garantir que estão sendo devidamente importados e conferir a sincronização entre o estoque dos produtos e os pedidos sendo realizados.

  - Já para a integração de **preços**, deverá ser feita a conferência de preços em todos os canais de venda, além de averiguar se todos refletem as alterações feitas no marketplace. Conferir a entrada de preço dos produtos, desde o início da compra até o pagamento, acompanhando todo o processo a fim de assegurar que o preço segue fiel.

    Além disso, é necessário realizar teste de processamento em todo o sistema, desde a capacidade de escalabilidade, testando o fluxo de usuários; funcionamento, testando cada uma das funções em diversos dispositivos e sistemas operacionais; ver a capacidade do marketplace de aguentar picos de tráfego e processar as integrações de forma eficiente.

    Assegurar que os dados coletados dos clientes estão sendo devidamente armazenados e protegidos também é uma tarefa importante, conferindo se não há vulnerabilidades na integração do sistema. Garantir, também, que as transações entre o marketplace e o e-commerce estão seguras e íntegras. Novamente, devemos seguir os requisitos impostos pelo cliente e pela norma da Empresa.

    Para todas as integrações mencionadas acima, alguns **casos de testes** poderão ser seguidos. Além de cenários de sucesso (como a sincronização bem sucedida), cenários de falha (como falha na atualização de estoque), e cenários de carga (simulando um grande volume de transações), os seguintes cenários também poderão ser arquitetados:

- Cenário de segurança: importante conferir a autenticação dos usuários, a segurança dos dados pessoais, a proteção contra ataques, etc.
- Cenário de recuperação de desastres: simular situações de falha, se o sistema comporta uma invasão de privacidade por exemplo, ou a corrupção de dados, a queda do servidor, entre outros casos.
- Cenário de escalabilidade: testar a capacidade do sistema de lidar com um aumento no número de usuários, transações ou dados. 
- Conformidade: verificar se o sistema está em conformidade com ademais regulamentações (como por exemplo no servidor de pagamento, para segurança de dados de cartão de crédito).
- Cenário de integração de terceiros: testar a integração entre os servidores de pagamento, transporte, entre outros.
- Cenário de usabilidade: avaliar a usabilidade do sistema do ponto de vista do usuário final, incluindo a navegação no site, facilidade de busca e compra de produtos, processo de checkout e feedback visual.
- Cancelamento de pedidos: importante também averigar a funcionalidade do sistema na hora de um possível cancelamento e/ou devolução do pedido, se o sistema funciona de forma integrada com as informações do estoque, se há sincronização dos dados, entre outros.
  
A **prioridade dos testes** dependerá dos acordos feitos durante o projeto, quais são as metas a serem atingidas, quais requisitos específicos deverão ser atendidos. Com base nisso, é possível realizar uma hierarquia de prioridades dependendo da criticidade do projeto. Além disso, uma tarefa grande pode ser dividida em outras tarefas pequenas, facilitando assim o processo de Teste de Qualidade. 
Ademais, manter a usabilidade em perfeito estado de funcionamento, a experiência do cliente agradável, a segurança e armazenamento dos dados, e a conformidade entre todas as integrações é de suma importância.

Já o **ambiente dos testes**, seria interessante realizá-los num ambiente de homologação dedicado, a fim de evitar impactos no ambiente de produção. Assim, evitamos também possíveis erros na experiência dos clientes. Os **dados** para a realização dos testes poderão ser fictícios ou reais, podendo retirá-los nas informações de produtos, etc.

Todos os casos de cenário acima deverão ser devidamente registrados e atualizados conforme possíveis alterações no sistema.

> ## Segundo cenário

Para validar a integração com a ferramenta Bling, a realização do seguinte passo a passo poderia ser feita:

- Acessar a documentação oficial fornecida pelo Bling sobre sua respectiva API e funcionalidades, além das especificações técnicas da integração desenvolvida pela equipe de desenvolvimento do e-commerce;
- Realizar o mapeamento dos requisitos da integração, conferindo se a mesma atende-os com sucesso;
- Efetuar testes para conferir a funcionalidade da ferramenta, registrá-los e atualizá-los conforme possíveis alterações;
- Conferir possíveis relatórios gerados (como de vendas, estoque, pedidos);
- Repassar os resultados para a equipe, mantendo contato frequente, entre outros.

Alguns testes imprescíndiveis a serem aplicados: 

- Conferir a sincronização de produtos entre o e-commerce e a ferramenta Bling;
- Acompanhar a transmissão de dados, averiguar se as atualizações de estoque refletem corretamente entre o e-commerce e a ferramenta;
- Alterar e validar em tempo real a inserção de novos dados;
- Testar o fluxo de processamento de pedidos, desde a criação no e-commerce até a sua integração e registro no Bling;
- Verificar o desempenho da resposta do sistema;
- Monitorar em tempo real a funcionalidade do Bling;
- Avaliar a segurança da conexão, incluindo a autenticação dos usuários, o controle de acesso e o armazenamento de dados;
- Testar a capacidade de recuperação da integração diante de falhas, como interrupções de rede ou indisponibilidade temporária do Bling;
- Conferir, também, a experiência do usuário, como por exemplo mensagens de erro, se a navegação é intuitiva, se o layout é agradável, etc.;
- Certificar que as notas fiscais são geradas corretamente no Bling para os pedidos realizados no e-commerce, entre outros.

Os testes serão priorizados com base no critério dos requisitos para o funcionamento do e-commerce e para o cumprimento das obrigações legais relacionadas à gestão de estoque. Algumas ferramentas que poderão servir de auxílio, seriam

1. Testar a interface, utilizando o Selenium por exemplo;
2. O PostMan poderá ser usado a fim de testar a API;
3. A ferramenta TestRail poderá ser utilizada para gerenciamento dos testes;
4. Ferramentas de análise de texto também poderão ser úteis, como por exemplo a NLP;
5. Para registro dos resultados obtidos, a ferramenta Confluence poderá ser útil;
6. Até mesmo o pacote OFICCE poderá ser utilizado, devido a sua capacidade de compartilhamento e sincronização de informações;

Poderão ser utilizados dados fictícios para a comprovação da eficácia do sistema e/ou dados reais, retirados anteriormente com base na pesquisa feita durante a realização do projeto.

Manter a privacidade e a segurança dos dados também é imprescindível, logo, deve ser feita uma varredura constantemente na integração a fim de encontrar possíveis vulnerabilides e evitar problemas maiores. Seria interessante também testar a integração do Bling com os outros sistemas correlacionados. 

A prioridade dos testes varia de acordo com os requisitos pré-estabelecidos, devendo então selecionar uma base a ser atendida, assim poderá ser feita uma hierarquia de prioridades. Realizar os testes levando em consideração diversos contextos também será importante, prevendo falhas e eventuais problemas (como queda de servidor, redução do ping, múltiplos acessos, entre outros).

Já o ambiente dos testes, de preferência realizá-los no ambiente de homologação a fim de evitar maiores desastres. 

Como sempre, a prioridade é a satisfação do cliente e o perfeito funcionamento do sistema, logo, deve-se olhar através da lente do cliente a fim de buscar possíveis melhorias. Manter uma janela aberta para feedback do cliente, como críticas e sugestões, também seria interessante.

> ## Terceiro cenário

Há algumas hipóteses a serem levantadas no caso de interferência entre a integração de estoque e os pedidos disponíveis referente ao cliente mencionado do Mercado Livre. Primeiramente, seria necessário realizar uma investigação aprofundada a fim de analisar a situação e encontrar a raiz do problema, como por exemplo:

- Reunir dados acerca da documentação do próprio Mercado Livre;
- Procurar por registros de chamadas de API, respostas do servidor, mensagens de erro ou qualquer outra informação relevante que possa trazer clareza acerca do problema em questão;
- Analisar o comportamento que era esperado e onde que o sistema está falhando em atender esse requisito;
- Conferir o restante do catálogo do cliente, a fim de identificar se há semelhanças/diferenças entre os produtos que estão apresentando determinada anomalia;
- Acessar o log dos pedidos, conferir versões passadas, histórico de alterações e atualizações, possíveis falhas e/ou vulnerabilidades que acabaram culminando o erro relatado pelo cliente;
- Conferir se há possíveis limitações na API do próprio Mercado Livre que podem estar gerando atrasos ou falhas na atualização de estoque;
- Confirmar se, realmente, não houve alterações feitas pelo cliente (ou envolvidos) nas configurações de seus pedidos, entre outros.
  
Após analisar cuidadosamente os detalhes mencionados acima, nota-se a importância de realizar novos testes a fim de encontrar possíveis padrões de erro e melhorias, como:

  - Averiguar a sincronização automática de estoque entre o Magazord e o Mercado Livre;
  - Conferir a comunicação entre o ERP Magazord e o Mercado livre;
  - Simular uma compra, acompanhar todo o processo da venda;
  - Alterar os dados do estoque no ERP e validar em tempo real se a transmissão de informações fluiu corretamente;
  - Identificar se os dados estão sendo formatados corretamente antes de serem enviados para o Mercado Livre;
  - Testar os parâmetros de autenticação e as endpoints do API;
  - Realizar manualmente a atualização do estoque do Mercado Livre, entre outros.

Enfim, a solução do problema vem após a identificação da fonte do erro mencionado. Após a localização do mesmo, poderão ser feitas alterações como ajustes nas configurações de integração, correções de bugs, atualizações de software ou outras ações corretivas específicas que irão variar de acordo com a necessidade da situação. Pode-se também entrar em contato com os desenvolvedores, a fim de investigar o próprio código, em busca de possíveis falhas.

> ## Quarto cenário

Após serem feitas alterações no sistema de gerenciamento de cadastros mencionado acima, é necessário realizar uma série de testes para verificar se o sistema está em funcionamento pleno. Sendo assim, é importante validar cada campo inserindo dados em formatos diversos, seguindo situações hipotéticas, a fim de confirmar o sucesso do cadastramento.
  Alguns testes que poderiam ser realizados, por exemplo, seriam
- No campo do nome, é possível inserir caracteres especiais como acentuação? E quanto à pontuação? Há um campo mínimo de caracter a ser preenchido? E se, por exemplo, o usuário digitar somente o seu primeiro nome, esquecendo, assim, de inserir seu último nome? Será aceito o cadastro dessa pessoa? E se o usuário introduzir números? Como evitar tais possíveis erros? 
- No e-mail, além de ser necessário realizar a formatação do texto a ser inserido pelo usuário (como o uso do caracter especial '@' e a finalização '.com', por exemplo) seria interessante realizar testes com e-mails existentes e não existentes e, também, inserir um e-mail já cadastrado anteriormente. O sistema irá permitir um e-mail duplicado? Como evitar essa situação?
- A mesma lógica deve ser aplicada em todos os campos do cadastro. Na seção do número de telefone, seria interessante inserir um número válido e, claro, um número inválido, além de verificar também se o sistema está aceitando os dados dentro da formatação correta do país. Nesse caso, pode ser exigido um número de espaçamento mínimo e/ou máximo na hora de inserir os dados. Sabemos que o prefixo no Brasil seria +55, mais o código do DDD referente ao Estado do usuário e, por fim, seu número de telefone. Essas informações devem ser levadas em consideração na fase de desenvolvimento do sistema a fim de evitar a coleta de dados incompletos ou inválidos.
- No campo da data de nascimento, qual vai ser o formato aceito? Há alguma idade mínima? E se, por um acaso, o usuário errar o ano, excedendo a sua idade para além dos 100 anos de vida? Esses dados deverão ser validados em tempo real durante o preenchimento do cadastro.
- O mesmo valeria para o campo do CEP. E se, por exemplo, não for inserido um CEP completo ou existente? O sistema irá verificar e retornar um feedback ao usuário em tempo real? Seria importante realizar esses testes.
- Já no campo do CPF, onde obrigatoriamente devem ser inseridos 11 dígitos, seria necessário realizar testes nesse campo inserindo CPFs válidos e inválidos, verificando se o sistema os aceita ou não, além de conferir se o mesmo aceita números inferiores a 11 dígitos.

  A **obrigatoriedade do preenchimento** e o **feedback** ao usuário seria uma regra geral que se encaixa em todos os campos a serem preenchidos durante o cadastro do usuário, além de, claro, a validação em tempo real dos dados inseridos.
  
  É importante, também, visualizar o layout do _site_ através da lente do usuário e realizar alguns questionamentos. Os campos obrigatórios mencionados acima estão destacados de forma clara? Está evidente que estes campos precisam ser preenchidos? Os elementos visuais servem de auxílio para o usuário, ou o distraem? Os botões estão localizados de forma correta? O espaçamento, as cores do layout e o tamanho das letras podem ser mudados para aprimorar a experiência do usuário? Quais possíveis erros essas alterações evitariam? O _site_ foi projetado de forma tal onde o "passo a passo" a ser seguido pelo cliente seja, de fato, intuitivo?
  
  Esses questionamentos devem ser levados para à equipe de front-end, a fim de buscar melhorias e evitar possíveis erros na hora do preenchimento do cadastro. Por exemplo, caso o usuário esquecer de preencher um campo corretamente, pode ser feita uma validação dos dados pelo lado do cliente (em sua tela de computador ou celular, como por exemplo pela aparição de um aviso) para garantir que esses dados sejam preenchidos conforme os critérios do sistema, antes mesmo do cadastro ser enviado para o servidor.
  
  Ainda, essa mesma validação deve ser feita pelo lado de quem desenvolveu o código do sistema. Podem ser usadas expressões regulares para que o usuário insira os dados dentro do formato exigido, como, por exemplo, o número de telefone (que não deve aceitar strings como letras), e a data de nascimento (que pode ser codificada para aceitar somente números). O mesmo se aplica para o campo do CPF, o código foi desenvolvido de forma tal pra aceitar a inserção de pontuação? E o campo do e-mail? O usuário está ciente dessa configuração? Como transmitir de forma clara o que está sendo solicitado para o usuário? 
  
  Erros na hora do preenchimento do cadastro (como inserir letras onde deveria haver números, ou a inserção de um endereço incorreto, e-mail, e por aí vai) podem ser evitados antes mesmo do envio desse cadastro. Há diversas validações que podem ser feitas enquanto o usuário preenche o seu cadastro. Esses eventuais erros de digitação podem e devem ser considerados durante o desenvolvimento do sistema pela equipe do back-end, ao introduzir na construção do código bibliotecas e condicionais, como as estruturas if e else, ou for e while,  onde é criado condições necessárias para o preenchimento dos campos presentes no cadastro. Além disso, podem ser colocadas linhas de código que irão automaticamente verificar o formato do campo inserido, desde o tipo (int, string, float etc.) até o tamanho (quantidade de caracteres), e ainda, é possível fazer uma conversão automática, além de desconsiderar os caracteres especiais que o usuário digitar, desconsiderar strings específicas como letras ou números nos campos inadequados para tal, entre outros.
  
  É muito mais difícil e custoso contornar dados nulos, incorretos ou enviesados após a coleta dos mesmos. Para evitar que seja feito esse tipo de tratamento de dados (eliminação de dados nulos, repetidos ou incoerentes) e, também, para evitar a perda deles, é importante realizar uma série de procedimentos para garantir o sucesso da coleta desses dados (na hora de realizar o cadastro do usuário) e, claro, testá-los. Raramente o analista conseguirá resgatar um dado que não foi entregue da forma correta, logo, a importância de realizar testes do serviço que está sendo prestado (e esperado) é essencial.

  Em resumo, os testes a serem realizados seriam:
1. Avaliar a experiência do usuário durante a usabilidade do sistema, certificando que o mesmo seja de fácil compreensão, intuitivo e informativo;
2. Tornar ciente ao usuário a obrigatoriedade do preenchimento dos campos mencionados, dando feedback para ele em cada interação;
3. Considerar, durante a construção do código, possíveis erros de digitação e/ou desatenção pela parte do usuário, colocando limitações e conversões (através de condicionais, expressões, bibliotecas, loops etc.) que evitarão a inserção de dados corrompidos/inconsistentes e o fracasso do cadastramento;
4. Validar em tempo real os dados inseridos antes dos mesmos serem entregues ao servidor (confirmar o CEP, o CPF, etc.);
5. Testar a compatibilidade em diversos desktops, navegadores, mobiles etc.;
6. Certificar que o sistema esteja em perfeito estado de funcionamento, validando os dados inseridos e armazenando-os com segurança, tendo em vista a política de privacidade e a ética do usuário; 
7. Testar a exibição dos dados inseridos;
8. Conferir a performance do sistema, certificando que o mesmo funcione com diversos acessos simultâneos;
   
  Nesse sentido, é importante também averiguar a medição da velocidade, da capacidade de processamento, a estabilidade do serviço (do sistema em questão), da segurança dos dados que estão sendo coletados (se estão sendo armazenados de forma correta e ética), e da capacidade do sistema (levando em consideração um número grande de acessos/demanda).

  E, claro, **testar a usabilidade** do sistema ao longo de todo o percurso percorrido. Manter um monitoramento constante, aceitar críticas e sugestões dos usuários, visando sempre a qualidade do serviço que está sendo prestado e a experiência do cliente que está usufruindo do mesmo.
