# azure-criar-configurar-vm
Esse repositório tem como objetivo praticar o processo de criação e configuração de uma máquina virtual na plataforma Microsoft Azure. Nesse repositório conterá resumos, anotações e dicas sobre o uso da Azure, servindo como material de apoio para estudos e futuras implementações.

Doucumentação oficial do site da Microsoft sobre criar uma máquina virtual do Windows o Portal da Azure.
https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal

Existem diversos SLAs disponíveis pela Microsoft. Caso a Microsoft não atinja o SLA contrato, ela vai ressarcir sobre o que não foi cumprido. 
Em toda requisição de serviço recebida, é muito importante qual é o SLA aceitável para aquela demanda, para que seja contratado o SLA adequado. 
No link abaixo é possível realizar o download do contrato de SLA:
https://www.microsoft.com/licensing/docs/view/Service-Level-Agreements-SLA-for-Online-Services?lang=24 

Na criação de máquinas virtuais na Azure, temos as seguintes opções:
a) Regiões: é o agrupamento de datacenters em regiões geográficas ao redor do mundo. No Brasil, temos a região "(South America) Brazil South".
b) Opções de disponibilidade: expandem o nível de controle de que você precisa para manter a disponibilidade dos aplicativos e dos dados em suas VMs. Uma Zona de Disponibilidade é uma zona fisicamente separada em uma região do Azure. Há três Zonas de Disponibilidade por região do Azure com suporte.
c) Zonas de disponibilidade: opção na qual a vm e o ip publico (caso tenha) é implantado adicionalmente nas zonas de disponbilidade selecionadas.

Na parte de contas de armazenamento, ao criar um conta de armazenamento é possível configurar uma redundância.

Foi abordado também sobre o Azure Bastion, é um serviço de PaaS totalmente gerenciado que você provisiona para se conectar com segurança às máquinas virtuais por meio de um endereço IP privado. 
