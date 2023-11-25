<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
UML-Pizza-Express
</center></font>


**Conteúdo**

- [Autores](#autores)
- [Descrição do projeto](#descrição-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de casos de uso](#diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Diagrama de sequencia](#diagrama-de-sequencia)
- [Diagrama de classes](#diagrama-de-classes)
- [Diagrama de componentes](#diagrama-de-componentes)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-implantação)
- [Referências](#referências)


# Autores

* Enzo Ferroni - 32318014
* Gabriel Pastorelli - 32361513
* Rafael Neves - 32344317
* Rodrygo Vasconcellos - 42014492


# Descrição do projeto

A empresa Pizza-Express busca atualizar seu sistema de forma que o sistema de entrega seja capaz de realizá-las em menos de 30 minutos. É importante ressaltar que o modelo das lojas não possui espaço de varejo, ou seja, elas apenas produzem as pizzas e realizam as entregas.

Por ser uma rede de lojas, a Pizza-Express necessita de um sistema central, responsável pelo atendimento ao cliente e localizar a loja mais próxima do mesmo para a produção e entrega do pedido. Uma vez que o pedido foi realizado, a central precisa notificar a loja a respeito desse pedido e o local de entrega.

O segundo sistema envolve as operações de produção e entrega das pizzas. Além de receber informações do sistema central e realizar a produção das pizzas, o sistema deve entrar em contato com o delivery, que será realizado pela empresa patrocinadora do projeto (Papa-Léguas Delivery).


# Análise de requisitos funcionais e não-funcionais
**Requisitos Funcionais**

Sistema Central
1.	O sistema deve ser capaz de registrar o cadastro de um novo cliente
2.	O sistema deve permitir que o cliente realize um pedido, tendo como opção adicionar ou remover itens
3.	O sistema deve possibilitar que o cliente finalize o pedido exigindo que o cliente faça o pagamento
4.	Tanto o cliente quanto o atendente devem ser capazes de realizar o login
5.	O atendente deve ter a possibilidade de visualizar e validade o pedido feito pelo cliente
6.	O sistema deve permitir que o atendente busque a loja mais próxima do pedido realizado em função do endereço presente no cadastro do cliente
7.	O atendente deve ser a possibilidade de encaminhar as informações do pedido para a loja que deverá realiza-lo
   
Sistema Franquia
1.	O sistema deve informar o pedido que será preparado
2.	O funcionário deve ter a possibilidade de preparar o pedido
3.	O sistema deve ser capaz de enviar um chamado de que o pedido está pronto para a empresa de delivery 
4.	O delivery deve receber um aviso de que o pedido está pronto para entrega
   
**Requisitos Não Funcionais**
1.	O sistema precisa responder o mais rápido possível
2.	O sistema deve ser possível de acessá-lo via web e mobile
3.	A interface deve apresentar cores e contrastes que garantem acessibilidade para usuários com daltonismo
4.	O sistema deve ser seguro de maneira que um cliente não tenha acesso a informação de cadastro de outro cliente
5.	A interface deve ser intuitiva e simples para utilizar
6.	A interface deve conter elementos sofisticados e dinâmicos


# Diagrama de casos de uso

![Untitled](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/eabece67-3f02-4240-a8cd-34584231f14c)
![Untitled](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/5195fa99-d1a4-4121-a63c-70364026e642)


# Descrição dos casos de uso

**Caso de uso Central:**  

![SC01-Realizar Cadastro](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/70b152ad-fbee-42b2-8e6f-bde537728093)
![SC02-Realizar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/2b5c8ebc-1914-4fc0-a553-1ecfcdf17e43)
![SC03-Finalizar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/82b7d04e-0f85-42bc-acd6-f0bc87c98ce0)
![SC04-Realizar Pagamento](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/a16653c6-261a-455e-9402-69f92269a785)
![SC05-Adicionar Itens](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/98f215bd-f10d-432c-b801-6d3b681bcbe6)
![SC06-Remover Itens](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/2360777d-70a4-48cd-a743-200843694e4a)
![SC07-Realizar Login](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/798f917b-5e78-474c-a752-6fcae6c96548)
![SC08-Valida Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/7d4dd88b-79fd-436b-80a0-b0314c3e09e7)
![SC09-Verificar Franquia Próxima](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/54cd052a-e278-437a-bc6d-88e10d036c33)
![SC10-Encaminhar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/3dd8e6e8-d641-43f7-8694-a2a0683f8fc9)


**Caso de uso Franquia:**  

![SF01 - Receber Chamado ](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/a51ac7e4-3371-4a61-a668-f3c8b8382b0f)
![SF02 - Encaminhar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/eb4b2b90-049c-400e-a5c3-6a83c73e603c)
![SF03 - Receber Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/d55c0505-5baf-4f5b-b289-ec01a523dd29)
![SF04 - Preparar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/39461be3-3c33-495f-82d9-0528059fae16)


# Diagrama de sequencia

*Caso de uso Central:*  

![SC01-Realizar Cadastro](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/5f0c2fcb-0344-4526-8a50-8e46cdb82448)
![SC02-Realizar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/95f649ac-8d44-4ebd-addf-a100479d6b27)
![SC03-Finalizar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/06e9c2ad-16b2-43de-ab21-b0b722b66f3f)
![SC04-Realizar Pagamento](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/c364afa3-31e5-4b1a-bf3e-46053fdfa6cb)
![SC05-Adicionar Itens](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/a4c0e82e-0cb4-441a-a863-23bc10a94a5f)
![SC06-Remover Itens](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/df323f12-3158-42ee-86de-8017ef6ac371)
![SC07-Realizar Login](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/d1bb2e22-d72c-4816-8320-83d1cf30572e)
![SC08-Valida pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/a4f40f8c-2774-4b82-9296-62fe988ceec9)
![SC09-Verificar Franquia Proxima](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/c700fe82-53f9-4c8c-9b56-dee617eaea60)
![SC10-Encaminhar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/358dd96a-3219-4d79-86a6-1a410665a24b)  

*Caso de uso Franquia:*  

![SF01-Receber Chamado para Entrega](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/05247167-bda7-41e0-94fc-237823a6e8a7)
![SF02-Encaminhar Pedido para Delivery](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/1bcd5716-8955-475e-8302-526e7e49f196)
![SF03-Receber Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/7b40ed1c-1748-474d-b90f-3a8cca79d94f)
![SF04-Preparar Pedido](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/9dec89d1-e33a-4fdc-801a-f78f15c2ec28)


# Diagrama de classes

![image](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/5edf351d-2fe3-4373-8b09-dcbd6099e3f1)

# Diagrama de Componentes

![image](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/79fb6ce3-4bbe-4f27-a642-29998d2007c1)

# Decisões de arquitetura
Os servidores terão como sistema operacional Linux por conta dele ser bem adaptado para aplicações em nuvem e também projetado para ser estável e seguro. Usaremos Python que é uma linguagem de alto nível e fácil de aprender e usar oque se torna ideal para empresa onde temos desenvolvedores com diferentes níveis de experiência. O banco de dados nuvem será do tipo relacional o Amazon Relational Database Service(RDS), ele é ideal para armazenar dados estruturados, como os pedidos, informações dos clientes, estoque, etc. Nosso banco de dados físico também será do tipo relacional e guardará informções sensíveis como, cartão de crédito e o histórico de pedidos. Teremos um Firewall stateful que vai proteger todo o sistema da central de ataques externos, ele será configurado apenas para permitir o tráfego necessário para a operação do sistema. O roteador é necessário para conectar o sistema à internet, ele deverá ser configurado para permitir apenas dispsitivos autorizados terem aceso à internet. Nas estações de trabalho teremos computadores com aplicativos que serão usados para gerenciar pedidos, gerenciar estoque, para se comunicar com outras partes da empresa, como as lojas e o delivery, etc. As estações devem ser seguras tendo assim um firewall e um antivirus.

![Modelo de arquitetura](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/79a6895d-d82a-4ac1-b903-d4d0aaca17f0)

# Diagrama de implantação

![image](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/125482399/9e8f1c3b-481f-43b9-ad15-6606a11186cc)

# Referências

https://docs.google.com/document/d/1c6MQubV-Kpq2H1d02yeWLBM33FS5-o8RpMQfAHxgn1w/edit?usp=sharing 
https://docs.google.com/document/d/1UlD-0FzvBjA1x71WBz3YVZI_sw02nXXHq2GDIw3n5JE/edit?usp=sharing
