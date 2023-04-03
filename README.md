# Modelos de Sistemas

Loja de informatica, pois achamos o modelo o mais coerente com a demanda do mercado atual

## 3- Ordem de Serviço (O.S.)

Inforratica é uma loja de assistência técnica que recentemente vem se expandindo. Com esse crescimento, criou-se uma necessidade de um software que automatize as O.S. O sistema deverá auxiliar nos orçamentos, peças, retirada dos equipamentos e relatórios.

# Situação Problema

Inforratica, é uma loja de assistência técnica centrada em computadores e notebooks. A empresa já existe ha algum tempo mas como vem crescendo ultimamente, precisaram de um sistema de orçamentos. São quatro funcionários: o dono (técnico), um(a) atendente e dois(duas) técnicas.

O cliente vai até o balcão onde está o(a) atendente, juntamente com a sua máquina, descreve o problema, o(a) atendente vai escrever os dados informados em um papel, também será necessário um cadastro, onde o cliente falará o seus dados, que será escrito em um papel.

Após o cadastro realizado pelo(a) atendente, será consultado o técnico para identificar as peças do computador/notebook para que não haja nenhum desentendimento. O nome ou modelo das peças vai ser descrito no papel.

Depois que a O.S. estiver concluído, o cliente vai assina-lá(colocar na proposta), e então, vai começar o processo de reparo, ao identificar o problema vai repassar o orçamento para o cliente. 

Se o cliente aprovar o orçamento sempre que houver uma alteração no andamento do reparo, o cliente vai ser notificado via “Whatsapp” ou pelo "Email". Os status são: em análise, em aprovação , aprovado, aguardando peça fornecedor, finalizado, aguardando retirada, retirada. A garantia será de 3 meses para a troca da peça ou revisão do problema.
	
Com o término do reparo da máquina, o cliente receberá um aviso que ele(a) poderá retirar sua máquina na loja.

O software ajudará a automatizar e a guardar informações mais facilmente e rapidamente, sem ter a preocupação de perdê-las.

# Descrição da proposta

Uma solução para a loja de reparo de computadores que ainda usa papel para as O.S. seria implementar um sistema digital, que permita aos funcionários da loja criar, editar e gerenciar as ordens de serviço.

A aplicação poderia permitir que o(a) atendente crie uma ordem de serviço com os dados do cliente, do equipamento e do serviço a ser realizado. A aplicação poderia gerar um número de ordem de serviço único e armazenar todas as informações em um banco de dados seguro.

Os técnicos poderiam atualizar o status da ordem de serviço ao longo do processo de reparo, permitindo que o cliente acompanhe o status da reparação em tempo real.

O sistema ira gerar um relatório toda semana, que somente o dono terá acesso. Esse relatório vai mostrar os seguintes dados: gastos, lucro líquido, máquinas esperando peças, máquinas com reparo em andamento, máquinas esperando retirada, máquinas em garantia.

Isso tornaria o processo mais eficiente, eliminando a necessidade de papel e tornando a gestão de ordens de serviço mais organizada, rastreável e eficaz.

# Regras de negócio

* **RN01 - Início do atendimento:** Para iniciar um atendimento no balcão, o cliente deverá fornecer dados pessoais.

RN01 - Visita domiciliar: taxa de R$ 50,00 para visitas domiciliares.

* RN02 - Inserção de dados na O.S.: O(a) atendente deverá anotar o problema relatado pelo cliente e descrever os dados do equipamento, incluindo marca e modelo.

* RN03 - Identificação das peças: O técnico deverá identificar as peças do computador/notebook e descrever o nome ou modelo das peças na ordem de serviço.

* RN04 - Assinatura do cliente: Após a conclusão da ordem de serviço, o cliente deverá assiná-lo em um papel impresso.

* RN05 - Atualização do andamento: O status da ordem de serviço deverá ser atualizado pelos técnicos durante todo o processo de reparo, permitindo que o cliente acompanhe o status da reparação em tempo real, recebendo as informações via “Whatsapp”, “Email” ou via site.

RN - Finalização da O.S.

* RN06 - Garantia: A garantia será de 3 meses para a troca da peça ou revisão do problema.

* RN07 - Relatório semanal: Um relatório semanal será gerado para o dono da loja, contendo informações como gastos, lucro líquido, máquinas esperando peças, máquinas com reparo em andamento, máquinas esperando retirada e máquinas em garantia.