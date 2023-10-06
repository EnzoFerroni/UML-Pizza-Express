<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
UML-Pizza-Express
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

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

A Pizza-Express é uma cadeia de 40 lojas de fast-food e entrega em casa.

Pizza-Express tem perdido recentemente 30% do rendimento de vendas devido a um problema em seu negócio da entrega. Atribuem este problema a seu concorrente principal que promoveu um programa que garante o serviço de entrega em 30 minutos, desde a entrada da ordem de serviço até a entrega na casa do cliente (delivery).

Pizza-Express anuncia a entrega em uma hora.

Pizza-Express usa atualmente computadores para armazenar as operações e as funções usuais do negócio, mas não auxiliam nas funções para processar a entrega dos pedidos dos seus clientes.

Elonn Muske, o gerente de sistemas de informação é o encarregado para desenvolver uma aplicação do software para identificar a localização de lojas de pizza Pizza-Express mais próxima do cliente e para criar o sistema de software necessário para operá-las.

O patrocinador deste projeto, a empresa Papa-Léguas Delivery, disse que o futuro da Pizza-Express depende deste projeto.

A equipe deverá investigar uma opção para entregar a pizza em menos de 30 minutos.

A sua idéia é montar lojas de pizza Pizza-Express que não teriam nenhum espaço de varejo, pois a sua função é somente receber ordens, preparar e entregar as pizzas.

A loja deverá ser localizada o mais próximo do cliente receberá a ordem através de uma central, processará, e entregará a ordem dentro de 10 ou 15 minutos da entrada do pedido.

Há dois projetos do desenvolvimento do software identificados aqui:

• primeiro é um sistema de software para o atendimento do pedido e para encontrar localização da fábrica da pizza mais próxima do cliente para fazer a entrega.

• segundo é um sistema de software para suportar operações da fábrica de pizzas.


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

![SC01-Realizar Cadastro](https://github.com/EnzoFerroni/UML-Pizza-Express/assets/143665284/abaef047-6486-45fe-a7dc-02d51bd606f4)
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

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
