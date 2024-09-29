# CloudAzureFundamentals
Um repositório com lista do conhecimentos iniciais a respeito do serviços de cloud na Azure
Relacionado ao bootcamp Microsoft Azure Essentials oferecido pela DIO https://web.dio.me/

### Computação em Nuvem (Cloud Computing)
> Definição: É a entrega de serviços de computação (servidores, armazenamento, bancos de dados, redes, software e análises) pela internet, oferecendo escalabilidade, flexibilidade e redução de custos.
> Tipos de Nuvem:
> Nuvem Pública: Serviços oferecidos pela internet para qualquer pessoa (ex: Azure).
> Nuvem Privada: Infraestrutura dedicada a uma única organização (On-premises).
> Nuvem Híbrida: Combinação de nuvem pública e privada, permitindo que dados e aplicativos sejam compartilhados entre elas.
> Nuvem Multipla (Multi cloud) Combinação de vários serviços de nuvem para se utilizar vantagens diversas entre eles

### Principais Modelos de Serviço da Nuvem
> IaaS (Infrastructure as a Service):
> Serviço de infraestrutura de TI, incluindo máquinas virtuais, redes e armazenamento. Ex: Azure Virtual Machines (VMs).
> PaaS (Platform as a Service):
> Fornece plataformas para desenvolvimento, gerenciamento e entrega de aplicativos sem precisar gerenciar a infraestrutura. Ex: Azure App Service, Azure Functions.
> SaaS (Software as a Service):
> Software entregue e gerenciado pela internet. Ex: Microsoft 365.

### Regiões e Zonas de Disponibilidade
> Regiões: Localizações físicas onde os data centers do Azure estão situados.
> Zonas de Disponibilidade: Infraestruturas dentro de uma região que garantem alta disponibilidade e recuperação de desastres, com data centers isolados entre si.

### Responsabilidade compartilhada
> O provedor garante a segurança da nuvem (infraestrutura física)
> O cliente é responsável pela segurança na nuvem

## Beneficios da nuvem

### Alta disponibilidade
> O contrato do serviço de nuvem fornece um SLA, sem contar a possibilidade de replicação de serviços.

### Escalabilidade
> A nuvem permite ajustar o uso de recursos de acordo com a demanda, uma vez que o pagamento está relacionado ao uso é um excelente modelo para economizar, já que podemos reduzir o uso de acordo com a demanda e > > assim reduzir custos.

### Elasticidade
> A possibilidade de aumentar e reduzir automaticamente os recursos de nuvem oferecidos.

### Confiabilidade
> O design descentralizado permite uma estrutura mais resiliente, fornecendo acesso a recursos em diversas regiões do mundo, mesmo que ocorra uma catastrofe em uma região, as outras se mantem.

### Previsibilidade
> O custo ou desenpenho do ambiente são previsivelmente confiáveis definidos em uma arquitetura bem definida.

### Segurança
> A nuvem oferece diversas ferramentas que permitem segurança em arquiteturas implementadas, contudo todas as configurações devem ser realizadas pelo cliente, por exemplo patches atualizações e policies.

### Governança
> Os padrões corporativos definem uma conformidade a seguir, uma auditoria pode informar que uma estratégia de mitigação pode ser aplicada.

### Gerenciabilidade
> Um dos principais benefícios da computação em nuvem são as diversas formas de gerenciamento, por exemplo usando api ou usando powershell e não apenas o console.

### SLA
> O serviçe level agreement, apresenta um quantidade calculada de provável indisponibilidade de serviços, condição que pode ser mitigada com replicação de dados e serviços, contudo aumentando o custo da solução.
