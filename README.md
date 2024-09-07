# Configurandoumainst-nciadeBancodeDadosnaAzure

//Para configurar uma instância de banco de dados no Azure, é possível seguir os seguintes passos: 
 
1o. Fazer login no Azure; 
 
2o. Na página Visão geral, escolher + Novo banco de dados (Selecionar em HOME > SQL databases); 

3o. Na guia Básico, dar um nome para o banco de dados;

4o. Ir até a opção Detalhes do projeto, selecionar Subscrição e Grupo de recursos;

6o. Ir até a opção Detalhes do banco de dados, inserir um Nome do banco de dados e inserir um nome de Servidor(selecionar a opção criar novo);

7o. Ir na opção Computação + armazenamento > configurar banco de dados e definir a camada de serviço e computação do banco;

8o. Ir na opção Redundância de armazenamento de backup e selecionar entre as opções:
       Armazenamento de backup localmente redundante
       Armazenamento de backup com redundância de zona
        Armazenamento de backup geo-redundante
 
9o. Ir em cada aba Networking > Security > Additional settings > Tags > Review + create e configurar cada aba de acordo com as melhores práticas para BD AZURE;

Obs.: Para uma melhor prática ir na documentação oficial da Microsoft Azure e buscar como criar Instância Gerenciada de SQL do Azure, segue link abaixo:
https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal
