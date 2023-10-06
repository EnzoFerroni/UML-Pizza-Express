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
*&lt;Descrição dos requisitos&gt;*


# Diagrama de casos de uso

![Untitled](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/eabece67-3f02-4240-a8cd-34584231f14c)
![Untitled](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/5195fa99-d1a4-4121-a63c-70364026e642)


# Descrição dos casos de uso

Caso de uso Central:  
https://docs.google.com/document/d/1c6MQubV-Kpq2H1d02yeWLBM33FS5-o8RpMQfAHxgn1w/edit?usp=sharing  

Caso de uso Franquia:  
https://docs.google.com/document/d/1UlD-0FzvBjA1x71WBz3YVZI_sw02nXXHq2GDIw3n5JE/edit?usp=sharing


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

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software&gt;*

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
