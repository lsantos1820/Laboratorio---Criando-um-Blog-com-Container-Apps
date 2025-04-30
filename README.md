# Laboratorio---Criando-um-Blog-com-Container-Apps


Criando um Blog com os Serviços da Azure
Recentemente, desenvolvi um projeto de blog usando os serviços da Microsoft Azure para entender na prática como funciona a hospedagem de aplicações web na nuvem. Utilizei duas abordagens: o Azure App Service e o Azure Container Apps, cada uma com suas vantagens.

Primeiro, testei o Azure App Service, que é super prático para quem quer subir uma aplicação rapidamente, sem se preocupar com infraestrutura. Fiz login no Azure pelo terminal, criei um grupo de recursos, configurei o plano de hospedagem e publiquei meu blog com apenas alguns comandos. Ele já ficou acessível por uma URL pública, o que facilita bastante em projetos rápidos ou demonstrações.

Depois, decidi explorar o Azure Container Apps, que é uma solução mais moderna e voltada para contêineres Docker. Nesse caso, construí uma imagem do meu blog localmente, enviei para o Azure Container Registry e implantei no Container Apps. Esse processo me deu mais controle sobre o ambiente da aplicação e é ideal quando precisamos de escalabilidade ou rodar aplicações com dependências específicas.

Ambas as opções funcionam muito bem, mas a escolha depende do nível de controle que você precisa. O App Service é ótimo para começar rápido. Já o Container Apps é excelente para quem já tem experiência com Docker e quer aproveitar os recursos mais avançados da nuvem.