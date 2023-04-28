# TestingCashFlow
Cash Flow Project, the project was developed using the GT architecture, access into (https://dev.azure.com/GrantingTechnology-Community/_git/Download-Trial-Version) GT architecture studies

Este projeto teve como principal finalidade, apresentar como é fácil desenvolver usando a arquitetura GT, apresento meu projeto de aproximados 11 anos de estudos focados na arquitetura e engenharia de software.
Iniciei o projeto TestingCashFlow no dia 28/02/2023 sua primeira entrega foi no dia 02/03/2023 17:00.

# O escopo do projeto foi :

• Cadastro de operações como Débito e Crédito, simulando uma empresa e suas rotinas diárias

• Relatório com as operações cadastradas, para visualização, distinguindo entradas e saídas

# Software

• Utilização da tecnologia NetCore 6, banco de dados SQL Express e ORM Dapper

• Solução Web de multiplos projetos rodando, sendo que API e UI se comunicando 

# Instalação /Configuração

• Inicialmente a aplicação(softare) não necessitará ajustes na configurações a serem feitas, a não ser que o Murphy entre em cena!

• Necessário ter o framework instalado para NetCore 6(VIsual Studio Installer), também Sdks\Microsoft.NET.Sdk 5.0.413 / 6

• Verificar se a propriedade da solução, esta setada para multiplos projetos, simultaneos (https://github.com/PedroPriuli/TestingCashFlow/blob/main/property_soution_habil.png)

• Baixar o projeto completo (https://github.com/PedroPriuli/TestingCashFlow/blob/main/download) 

• Baixar o script database SQL (https://github.com/PedroPriuli/TestingCashFlow/blob/main/Sql), script de restauração da base

caso necessário, os scripts das 2 tabelas utilizadas estão disponiveis individualmente (https://github.com/PedroPriuli/TestingCashFlow/blob/main/SQL_create_table_single )

# Arquitetura GT

• A arquitetura consiste de multiplos projetos, que se comunicam trazendo alta coesão, oferencendo responsabilidade única e facilidade no entendimento e melhor manutenção. 

• A arquitetura oferece baixo acoplamento, trazendo independencia entre os modulos principais, deixando-os praticamente independentes para o uso de suas soluções desenvolvidas. 

• A comunicação entre dados ( banco ), tem responsabiliade única, oferecendo independencia na escolha do banco , orm ... não afetando as entidades utlizadas, caso haja necessidade de uma futura mudança de banco ou ORM.

Estarei documentando a arquitetura conforme possibilidade, mas continuo trabalhando para facilitar o desenvolvimento e velocidade na produção.

agradeço desde já
att. Pedro H Priuli
espero poder ajudar

