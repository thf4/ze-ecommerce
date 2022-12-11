# Título: Construção da API Ze-ecommerce.

**Data:** 11/10/2022

# Status 

**Aceita:**

# Contexto 

Inicio da construção dos endpoints da api ze-ecommerce. Construindo toda a api com typescript, clean architecture, orientação a objetos. 
Utilização de um api gateway para manter a segurança na exposição dos endpoints do microserviço, aonde será feita a integração privada via VPC dos recursos HTTP/HTTPS. São recursos de uma instância EC2 por trás de um Network Load Balancer por meio de um link de VPC. Será feito um VpcLink que é um recurso do API GETAWAY, que encapsula um vpc link. Ele será responsável por encaminhar as solicitações para a API e também será o responsavel pelo retorno da respostas de backend ao autor da chamada. Utilizaremos um banco não relacional para prover um menor custa na utilização de banco de dados, o DYNAMODB. A API será feita em nodejs.

# Decisão

A decisão tomada, foi relevante para aplicar as melhores praticas no desenvolvimento de software.

# Consequências

Inicio do ecosistema ze-ecommerce.