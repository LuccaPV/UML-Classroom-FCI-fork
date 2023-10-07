<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*Engenharia_FCI*
</center></font>

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

Lucca Pivoto De Brito Padilha<br>
Matheus Vaghetti Gomes<br>
Iago Leite Chain Intacli<br>
Carlos Gabriel Alves Bertunes<br>
Rafael Riki Nascimento de Oliveira<br>

# Descrição do projeto

O projeto consiste em nossa equipe de profissionais da área de Sistema de Informação, desenvolvermos um Sistema de Gerenciamento das pizzarias da marca "Pizza-Express", com foco em diminuir o tempo geral de entrega de 1 hora(tempo atual) para 30 minutos(tempo ideal ou menos). A ideia seria montar lojas sem varejo, apenas designadas a montar e entregar as pizzas, e as lojas já existentes serviriam como uma central de pedidos.
  Distribuição do tempo: 10-15 min dedicados a central processando os dados do pedido e encontrando a pizzaria mais próxima, e o restante do tempo seria dedicado a confeccionar e entregar as pizzas.
O sistema seria dividido em 2 partes, sendo elas:
  O perfil do cliente e o cálculo de distância utilizando os dados do cliente. O perfil do consumidor seria composto com informações pessoais do próprio, a informação que será importante extrair do perfil é o endereço, o sistema criaria um reta transversal ligando o endereço do cliente com as unidades da pizzaria para medir as distâncias, as retas transversais que possuírem as menores distâncias entre 2 unidades, serão as escolhidas para realizar a entrega, o fator decisivo será o mapeamento de ambos os caminho, retirando o tempo médio considerando trânsito, velocidade média das vias e a quantidade de pedidos designados às 2 pizzarias(como por exemplo: se uma unidade for 2 minutos mais próxima que a outra, porém ela possui uma quantidade maior de pedidos ativo, o sistema escolheria a pizzaria com menos pedidos ativos no momento da checagem, pois a diferença de tempo na entrega pode ser compensada na montagem mais rápida das pizzas).


# Análise de requisitos funcionais e não-funcionais
Requisitos Funcionais<br><br>
Cadastro de Clientes:
O sistema deve permitir que os clientes se cadastrem, fornecendo informações pessoais, incluindo nome, endereço, número de telefone, e-mail, etc.

1-Pedido de Pizza:
Os clientes devem ser capazes de fazer pedidos de pizza através do sistema, especificando os sabores, quantidades e quaisquer instruções especiais.

2-Cálculo de Distância:
O sistema deve calcular a distância entre o endereço do cliente e as unidades da pizzaria para determinar a mais próxima.

3-Seleção de Pizzaria:
Com base no cálculo de distância, o sistema deve selecionar a pizzaria mais próxima para atender o pedido do cliente.

4-Rastreamento de Pedidos:
Os clientes devem ser capazes de rastrear o status de seus pedidos, desde o momento do pedido até a entrega.

5-Gestão de Pizzarias:
O sistema deve permitir o cadastro e gerenciamento das unidades de pizzarias, incluindo informações sobre a capacidade de produção de pizzas e pedidos ativos.

6-Processamento de Pedidos:
A central de pedidos deve processar os pedidos recebidos, considerando a proximidade das pizzarias, a capacidade de produção, e outros fatores para determinar a melhor pizzaria para atender o pedido.

7-Tempo Estimado de Entrega:
O sistema deve calcular e informar aos clientes o tempo estimado de entrega com base na pizzaria selecionada e nas condições de trânsito.

8-Gestão de Estoque:
O sistema deve monitorar o estoque de ingredientes nas pizzarias e informar quando os níveis estiverem baixos, para que seja possível fazer pedidos de reposição.


# Diagrama de casos de uso

![Imagem do WhatsApp de 2023-10-06 à(s) 19 02 28_683bea2b](https://github.com/LuccaPV/UML-Classroom-FCI-fork/assets/142755990/cc23c515-c72e-45bf-8f48-e5cc88c4c023)

# Descrição dos casos de uso

![Imagem do WhatsApp de 2023-10-06 à(s) 00 11 59](https://github.com/LuccaPV/UML-Classroom-FCI-fork/assets/124841314/779ae32f-3d39-452c-b861-314c317635e3)

# Diagrama de sequencia

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

