# Inforratica
Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.
Inforratica é uma loja de assistência técnica que recentemente vem se expandindo. Com esse crescimento, criou-se uma necessidade de um software que automatize as OSs. O sistema deverá auxiliar nos orçamentos, peças, retirada dos equipamentos e relatórios.

Professores: Marco André Mendes e Alann Perini.

Equipe: 

* Guilherme Tamanini
* Felipe Rotermel
* Paulo José Zem

Links do projeto:

* Documentação: https://github.com/FelipeRotermel/Inforratica

# Ordem de Serviço (O.S.)

Loja de informatica, pois achamos o modelo o mais coerente com a demanda do mercado atual

# Situação Problema

Inforratica, é uma loja de assistência técnica centrada em computadores e notebooks. A empresa já existe ha algum tempo mas como vem crescendo ultimamente, precisaram de um sistema de orçamentos. São quatro funcionários: o dono (técnico), um(a) atendente e dois(duas) técnicos.

O cliente vai até o balcão onde está o(a) atendente, juntamente com a sua máquina e descreve o problema. O(a) atendente vai escrever os dados informados em um papel. Também será necessário um cadastro, onde o cliente falará o seus dados, que serão escritos em um papel.

Após o cadastro, realizado pelo(a) atendente, será consultado o técnico para identificar as peças do computador/notebook para que não haja nenhum desentendimento. O nome ou modelo das peças vai ser descrito no papel.

Depois que a O.S. estiver concluída, o cliente vai assiná-la(colocar na proposta), e então, vai começar o processo de reparo. Ao identificar o problema, vai repassar o orçamento para o cliente. 

Se o cliente aprovar o orçamento, sempre que houver uma alteração no andamento do reparo, o cliente vai ser notificado via “Whatsapp” ou pelo "Email". Os status são: em análise, em aprovação, aprovado, aguardando peça do fornecedor, finalizado, aguardando retirada, retirado. A garantia será de 3 meses para a troca da peça ou revisão do problema.
	
Com o término do reparo da máquina, o cliente receberá um aviso informando que ele(a) poderá retirar sua máquina na loja.

O software ajudará a automatizar e a guardar informações mais facilmente e rapidamente, sem ter a preocupação de perdê-las.

# Descrição da proposta

Uma solução para a loja de reparo de computadores que ainda usa papel para as O.S. seria implementar um sistema digital, que permita aos funcionários da loja criar, editar e gerenciar as ordens de serviço.

A aplicação poderia permitir que o(a) atendente crie uma ordem de serviço com os dados do cliente, do equipamento e do serviço a ser realizado. A aplicação poderia gerar um número de ordem de serviço único e armazenar todas as informações em um banco de dados seguro.

Os técnicos poderiam atualizar o status da ordem de serviço ao longo do processo de reparo, permitindo que o cliente acompanhe o status da reparação em tempo real.

O sistema geraria um relatório de um período determinado, que somente o dono terá acesso. Esse relatório mostraria os seguintes dados: gastos, lucro líquido, máquinas esperando peças, máquinas com reparo em andamento, máquinas esperando retirada, máquinas em garantia.

Isso tornaria o processo mais eficiente, eliminando a necessidade de papel e tornando a gestão de ordens de serviço mais organizada, rastreável e eficaz.

# Regras de negócio

* **RN01 - Início do atendimento:** Para iniciar um atendimento no balcão, o cliente deverá fornecer dados pessoais.

* **RN02 - Visita domiciliar:** Taxa de R$ 50,00 para visitas domiciliares, caso o cliente não aceite o orçamento.

* **RN03 - Inserção de dados na O.S.:** O(a) atendente deverá anotar o problema relatado pelo cliente e descrever os dados do equipamento, incluindo marca e modelo.

* **RN04 - Identificação das peças:** O técnico deverá identificar as peças do computador/notebook e descrever o nome ou modelo das peças na ordem de serviço.

* **RN05 - Assinatura do cliente:** Após a abertura da ordem de serviço, o cliente deverá assiná-lo em um papel impresso.

* **RN06 - Cancelamento do orçamento:** O cliente poderá cancelar o orçamento em até 24 horas após a emissão do mesmo e deverá buscar o seu equipamento.

* **RN07 - Status da O.S.:** Os status possiveis são: em análise, em aprovação, aprovado, aguardando peça do fornecedor, finalizado, aguardando retirada, retirada, garantia.

* **RN08 - Atualização do andamento:** O status da ordem de serviço deverá ser atualizado pelos técnicos durante todo o processo de reparo, permitindo que o cliente acompanhe o status da reparação em tempo real, recebendo as informações via “Whatsapp”, “Email” ou via site.

* **RN09 - Aprovação da execução da ordem de serviço:** 
Caso haja uma alteração no orçamento, o cliente deverá ser notificado e deverá aprovar a execução da ordem de serviço.

* **RN10 - Finalização da O.S:** O cliente deverá ser notificado quando o reparo estiver concluído e poderá retirar o equipamento na loja em um determinado prazo.

* **RN11 - Garantia:** A garantia será de 3 meses para a troca da peça ou revisão do problema.

* **RN12 - Relatórios periódicos:** Relatórios serão gerados periodicamente para o dono da loja, contendo informações como gastos, lucro líquido, máquinas esperando peças, máquinas com reparo em andamento, máquinas esperando retirada e máquinas em garantia.

# Requisitos Funcionais

## Entradas

* **RF01 - Cadastro de Cliente:** O sistema deve permitir a coleta dos dados pessoais do cliente, incluindo nome completo, telefone e endereço, a fim de criar uma ordem de serviço. **Dados necessários**: nome completo, telefone, email, CPF e endereço. **Usuários**: atendente.

* **RF02 - Inserção de Dados na O.S.:** O sistema deve permitir a inserção dos dados do problema relatado pelo cliente. **Dados necessários**: descrição do problema. **Usuários**: atendente.

* **RF03 - Identificação das Peças:** O sistema deve permitir que o técnico identifique e descreva as peças do computador/notebook na ordem de serviço. **Dados necessários**: nome ou modelo das peças. **Usuários**: técnicos e gerente

* **RF04 - Aprovação da abertura da ordem de serviço:**
Após a aprovação e assinatura do cliente, o andamento do repáro será iniciado.**Dados necessários**: número da os. **Usuários**: atendente.

<!-- * **RF05 - Assinatura do Cliente:** O sistema deve permitir que o cliente assine a ordem de serviço em papel impresso após a conclusão da O.S. **Dados necessários**: assinatura do cliente. **Usuários**: clientes. -->

## Processos

* Autenticação de usuário.

* **RF05 - Cancelamento do Orçamento:** O sistema deve permitir que o cliente cancele o orçamento em até 24 horas após a emissão, e que possa buscar o equipamento reparado na loja. **Dados necessários**: solicitação de cancelamento. **Usuários**: atendente.

* **RF06 - Visita Domiciliar:** O sistema deve permitir a cobrança de uma taxa de R$ 50,00 para visita domiciliar em caso de recusa do orçamento pelo cliente. **Dados necessários**: valor da taxa e número da O.S.. **Usuários**: técnicos.

* **RF07 - Atualização do Status:** O sistema deve permitir que os técnicos atualizem o status da ordem de serviço durante todo o processo de reparo, e que os clientes recebam as informações via WhatsApp, email ou site. **Dados necessários**: atualização do status da ordem de serviço. **Usuários**: técnicos e gerente.

* **RF08 - Finalização da O.S:** O sistema deve notificar o cliente quando o reparo estiver concluído, e informar o prazo para retirada do equipamento na loja. **Dados necessários**: notificação da finalização do reparo e prazo para retirada. **Usuários**: técnicos e gerente.

* **RF09 - Garantia:** O sistema deve estabelecer uma garantia de 3 meses para a troca da peça ou revisão do problema. **Dados necessários**: prazo da garantia. **Usuários**: técnicos e gerente.

## Saídas

* **RF10 - Relatórios:** O sistema deve gerar relatórios  para o dono da loja, contendo informações como gastos, lucro líquido, máquinas esperando peças, máquinas com reparo em andamento, máquinas esperando retirada e máquinas em garantia. **Dados necessários**: informações sobre gastos, lucro líquido, máquinas em diferentes estágios do processo e em garantia. **Usuários**: gerente.

# Requisitos Não Funcionais

* **RNF01 - Segurança:** O sistema deve ser seguro, com controle de acesso para garantir que as informações dos clientes estejam protegidas.

* **RNF02 - Escalabilidade:** O sistema deve ser escalável para permitir o aumento do número de ordens de serviço à medida que a loja cresce e mais clientes são atendidos.

* **RNF03 - Usabilidade:** O sistema deve ser fácil de usar e intuitivo, com uma interface amigável que possa ser utilizada por todos os funcionários da loja.

* **RNF04 - Confiabilidade:** O sistema deve ser confiável e ter alta disponibilidade, garantindo que não haja interrupções ou falhas que possam prejudicar a realização das ordens de serviço.

* **RNF05 - Performance:** O sistema deve ter um bom desempenho, com tempo de resposta rápido para que o atendimento aos clientes seja eficiente e ágil.

* **RNF06 - Manutenção:** O sistema deve ser fácil de manter e atualizar, permitindo a inclusão de novas funcionalidades sem impactar as já existentes.

* **RNF07 - Responsividade:** O sistema deve ser responsivo, adaptando-se a diferentes tamanhos de tela, para que os usuários possam acessá-lo de qualquer dispositivo.

* **RNF08 - Disponibilidade:** O sistema deve estar disponível 24 horas por dia, 7 dias por semana, para que os clientes possam acessá-lo a qualquer momento.

* **RNF09 - Página escura:** A página do sistema deverá ter a opção de tela clara ou escura.
