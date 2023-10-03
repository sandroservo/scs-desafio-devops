
# Desafio scs DEVOPS
Tarefa: Configurar e implantar um aplicativo multi-container com Docker Compose.

# Você deve criar um arquivo docker-compose.yml e usar o Docker Compose para implantar um aplicativo composto por dois contêineres:
1.	Um contêiner com um servidor web que serve ngnix uma página HTML simples.
2.	Um contêiner com um servidor de banco de dados MySQL.


# Aqui está o que é esperado no arquivo docker-compose.yml:
•	Configure 2 serviços, um para cada contêiner.
•	Certifique-se de que os contêineres estejam em uma rede de contêineres para que possam se comunicar.
•	Exponha a porta do servidor web para a máquina host para que a página possa ser acessada a partir do navegador.
•	Use volumes para persistir os dados do banco de dados MySQL.
•	Escolha imagens Docker apropriadas para os contêineres.
Após configurar o docker-compose.yml, a pessoa que realiza o teste deve executar os comandos necessários para criar e implantar o aplicativo usando Docker Compose. Eles também devem demonstrar que o aplicativo está funcionando corretamente acessando a página HTML no navegador.


# Critérios de avaliação:

1.	Criar repositório com  o arquivo docker-compose.yml funcional que atenda aos requisitos especificados README.md explicando  cada passo 
2.	Uso correto de variáveis de ambiente para configurar os contêineres.
3.	Configuração adequada da rede de contêineres.
4.	Exposição da porta do servidor web corretamente.
5.	Uso de volumes para persistência de dados.
6.	Uso de imagens Docker apropriadas.
7.	Implantação bem-sucedida do aplicativo usando Docker Compose.
8.	Demonstração de que o aplicativo está funcionando corretamente no navegador. 






