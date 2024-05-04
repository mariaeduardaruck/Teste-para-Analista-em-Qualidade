# Teste para vaga - Analista de Qualidade

Teste criado pela empresa Magazord para o processo seletivo da vaga Analista de Qualidade júnior, desenvolvido pela candidata Maria Eduarda Rück.

> ## Primeiro cenário:

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
  
  Além das ferramentas citadas acima, outras como o pacote Office também podem servir para o rastreamento e registro dos dados coletados referente aos testes aplicados. Planilhas do EXCEL, arquivos WORD etc. servirão como apoio.

  Ferramentas de visualização (para a equipe interna ou stakeholders) também poderão ser utilizadas, como o Tableau, ou até mesmo esquemas feitos em Python ou no RStudio. 
  
  Como sempre, é necessário se colocar no lugar do cliente, a fim de buscar entender as suas motivações e interesses ao se tratar da utilização do software. A definição dos requisitos a serem atendidos e as perguntas certas a serem feitas (a fim de chegar nas respostas certas, também), irá guiar o analista ao resultado final que atingirá o sucesso da experiência do cliente.

  ### 5. Abrangência dos testes

  Como mencionado no enunciado, as integrações entre estoque, anúncios, faturamento, pedidos e preço deverão ser testadas. Alguns testes que poderão ser realizado entre cada integração, seriam

  - Para a integração de **estoque**, é importantíssimo conferir a sincronização e a atualização de estoque no e-commerce quando ocorrer alterações no marketplace. Será necessário conferir se a quantidade de estoque é consistente em todos os canais de venda. Realizar testes para conferir a validação desses dados será imprescindível.

  - Para a integração de **anúncios**, deve-se também conferir a sincronização e a atualização dos mesmos em cada canal de venda. Deverá ser testado, também, a listagem de novos produtos no marketplace, incluindo informações como título, descrição, imagens e categorias. Deve-se conferir se o anúncio está em perfeita condição de uso, se o usuário é levado para a página correta, como será a experiência do cliente ao decidir clicar no anúncio, se ele poderá fechá-lo, entre outros.

  - Para a integração de **faturamento**, será necessário testar o processo de faturamento para garantir que os pedidos estejam sendo corretamente faturados e processados. Verificar, também, se os dados de pagamento são processados de forma segura e precisa. Seria interessante testar todas as formas de pagamento que o marketplace acopla!

  - Para a integração de **pedidos**, realizar testes em cada produto ofertado será necessário, conferindo o processo da realização de cada pedido, para garantir que estão sendo devidamente importados e conferir a sincronização entre o estoque dos produtos e os pedidos sendo realizados.

  - Já para a integração de **preços**, deverá ser feita a conferência de preços em todos os canais de venda, além de averiguar se todos refletem as alterações feitas no marketplace. Conferir a entrada de preço dos produtos, desde o início da compra até o pagamento.
  - 
