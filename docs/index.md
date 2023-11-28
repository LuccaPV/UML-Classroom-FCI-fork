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
Nicolai Jeroshenko Ziminiani

# Descrição do projeto

O projeto consiste em nossa equipe de profissionais da área de Sistema de Informação, desenvolvermos um Sistema de Gerenciamento das pizzarias da marca "Pizza-Express", com foco em diminuir o tempo geral de entrega de 1 hora(tempo atual) para 30 minutos(tempo ideal ou menos). A ideia seria montar lojas sem varejo, apenas designadas a montar e entregar as pizzas, e as lojas já existentes serviriam como uma central de pedidos.
  Distribuição do tempo: 10-15 min dedicados a central processando os dados do pedido e encontrando a pizzaria mais próxima, e o restante do tempo seria dedicado a confeccionar e entregar as pizzas.
O sistema seria dividido em 2 partes, sendo elas:
  O perfil do cliente e o cálculo de distância utilizando os dados do cliente. O perfil do consumidor seria composto com informações pessoais do próprio, a informação que será importante extrair do perfil é o endereço, o sistema criaria um reta transversal ligando o endereço do cliente com as unidades da pizzaria para medir as distâncias, as retas transversais que possuírem as menores distâncias entre 2 unidades, serão as escolhidas para realizar a entrega, o fator decisivo será o mapeamento de ambos os caminho, retirando o tempo médio considerando trânsito, velocidade média das vias e a quantidade de pedidos designados às 2 pizzarias(como por exemplo: se uma unidade for 2 minutos mais próxima que a outra, porém ela possui uma quantidade maior de pedidos ativo, o sistema escolheria a pizzaria com menos pedidos ativos no momento da checagem, pois a diferença de tempo na entrega pode ser compensada na montagem mais rápida das pizzas).


# Análise de requisitos funcionais e não-funcionais
### Requisitos funcionais do Projeto<br><br>
1-Cadastro de Clientes:
O sistema deve permitir que os clientes se cadastrem, fornecendo informações pessoais, incluindo nome, endereço, número de telefone, e-mail, etc.

2-Pedido de Pizza:
Os clientes devem ser capazes de fazer pedidos de pizza através do sistema, especificando os sabores, quantidades e quaisquer instruções especiais.

3-Cálculo de Distância:
O sistema deve calcular a distância entre o endereço do cliente e as unidades da pizzaria para determinar a mais próxima.

4-Seleção de Pizzaria:
Com base no cálculo de distância, o sistema deve selecionar a pizzaria mais próxima para atender o pedido do cliente.

5-Rastreamento de Pedidos:
Os clientes devem ser capazes de rastrear o status de seus pedidos, desde o momento do pedido até a entrega.

6-Gestão de Pizzarias:
O sistema deve permitir o cadastro e gerenciamento das unidades de pizzarias, incluindo informações sobre a capacidade de produção de pizzas e pedidos ativos.

7-Processamento de Pedidos:
A central de pedidos deve processar os pedidos recebidos, considerando a proximidade das pizzarias, a capacidade de produção, e outros fatores para determinar a melhor pizzaria para atender o pedido.

8-Tempo Estimado de Entrega:
O sistema deve calcular e informar aos clientes o tempo estimado de entrega com base na pizzaria selecionada e nas condições de trânsito.

9-Gestão de Estoque:
O sistema deve monitorar o estoque de ingredientes nas pizzarias e informar quando os níveis estiverem baixos, para que seja possível fazer pedidos de reposição.
### Requisitos não-funcionais do Projeto<br><br>
1-Desempenho:
O sistema deve ser capaz de lidar com um grande volume de pedidos simultaneamente, garantindo tempos de resposta rápidos e eficiência na entrega.

2-Segurança:
O sistema deve proteger as informações pessoais dos clientes e os dados da empresa, garantindo a confidencialidade e integridade dos dados.

3-Usabilidade:
O sistema deve ser de fácil utilização para clientes e funcionários da empresa, com uma interface intuitiva e amigável.

4-Disponibilidade:
O sistema deve estar disponível 24 horas por dia, 7 dias por semana, para atender pedidos a qualquer momento.

5-Escalabilidade:
O sistema deve ser escalável para permitir a adição de mais unidades de pizzarias ou clientes sem impactar significativamente o desempenho.

6-Integração com Mapas e Tráfego:
O sistema deve ser capaz de integrar-se com serviços de mapeamento e tráfego em tempo real para calcular as estimativas de tempo de entrega com precisão.

7-Monitoramento de Pedidos em Tempo Real:
Deve haver um sistema de monitoramento em tempo real para rastrear a localização dos entregadores e atualizar os clientes sobre o status de seus pedidos.

8-Backup e Recuperação de Dados:
O sistema deve realizar backups regulares dos dados e ter um plano de recuperação de desastres em caso de falhas no sistema.

9-Eficiência de Produção:
O sistema deve otimizar a produção de pizzas nas unidades de pizzarias, considerando a carga de pedidos e a disponibilidade de ingredientes.

10-Adaptabilidade ao Tráfego:
O sistema deve ser capaz de ajustar as estimativas de tempo de entrega com base nas condições de tráfego em tempo real.



# Diagrama de casos de uso

![Imagem do WhatsApp de 2023-10-06 à(s) 19 02 28_683bea2b](https://github.com/LuccaPV/UML-Classroom-FCI-fork/assets/142755990/cc23c515-c72e-45bf-8f48-e5cc88c4c023)

# Descrição dos casos de uso

![Imagem do WhatsApp de 2023-10-06 à(s) 00 11 59](https://github.com/LuccaPV/UML-Classroom-FCI-fork/assets/124841314/779ae32f-3d39-452c-b861-314c317635e3)

# Diagrama de sequencia

![WhatsApp Image 2023-10-05 at 20 42 03](https://github.com/LuccaPV/UML-Classroom-FCI-fork/assets/146880715/475a7165-a79f-4b46-8d2a-99ab46fffbef)

# Diagrama de classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*[Uploading diagramaClasse.drawio…]()


# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

### Hardware<br>
#### 1.Servidores:
Servidores para hospedar a aplicação web e o banco de dados.
Servidores dedicados para processamento de pedidos e cálculos de distância em tempo real.
#### 2.Dispositivos de Entrada:
Terminais de pedidos para as lojas de montagem.
Dispositivos para entrada de dados do perfil do cliente nas unidades de pedidos.

### Software<br>
#### 1.Aplicação Web:

Desenvolvida utilizando tecnologias como HTML, CSS, JavaScript.
Módulos distintos para o perfil do cliente e cálculos de distância.
Interface intuitiva para facilitar a entrada de dados e o gerenciamento de pedidos.
Backend:

#### 2.Desenvolvido em uma linguagem de programação como Python, Java, ou outra adequada.
Responsável por processar os dados do cliente, calcular distâncias, e gerenciar pedidos.
Algoritmos eficientes para encontrar a pizzaria mais próxima considerando trânsito, velocidade média e carga de pedidos.
Banco de Dados:

#### 3.Armazenamento dos perfis dos clientes, informações de pedidos, e dados das pizzarias.
Utilização de um banco de dados relacional para garantir integridade e consistência dos dados.
Sistema de Geolocalização:

#### 4.Integração com serviços de mapas para cálculos precisos de distâncias.
Algoritmos para mapeamento de caminhos considerando variáveis como trânsito e carga de pedidos.

### Comunicação<br>
#### 1.APIs:
Estabelecer APIs para comunicação entre o módulo de perfil do cliente e o cálculo de distância.
Integração com serviços de geolocalização através de APIs.
#### 2.Comunicação Interpessoal:
Ferramentas de comunicação interna para a equipe de desenvolvimento.
Canais de feedback entre lojas de montagem e central de pedidos.

### Arquitetura Geral<br>
#### Arquitetura em Camadas:

#### Separação clara entre a interface do usuário, a lógica de negócios e o banco de dados.
Facilita a manutenção e escalabilidade do sistema.
Escalabilidade:

#### Previsão para o aumento do número de lojas e clientes.
Possibilidade de distribuir cargas de trabalho para garantir um desempenho consistente.
#### Segurança:
Implementação de medidas de segurança para proteger dados sensíveis dos clientes e informações da empresa.

## Equipe de Desenvolvimento<br>
### Papéis e Responsabilidades:

#### Identificação clara das funções de cada integrante na equipe.
Designação de líder de projeto, desenvolvedores, e especialistas em banco de dados.
Colaboração:

#### Utilização de ferramentas de controle de versão (Git, por exemplo) para colaboração eficiente.
Reuniões regulares para discussão de progresso, desafios e próximos passos.

# Diagrama de implantação

![image](https://github.com/LuccaPV/UML-Classroom-FCI-fork/assets/124841314/a7650ed5-5f50-4f6c-aa50-3ee5cdc56101)
