# resumo-do-lab
Alterar o idioma de exibição
Personalizar a aparência do azure
Categorias de Serviços
Dicas de como criar uma conta gratuíta

Benefícios da alta disponibilidade e da escalabilidade na nuvem.
Benefícios da confiabilidade e da previsibilidade na nuvem.
Benefícios da segurança e da governança na nuvem.
Benefícios da capacidade de gerenciamento na nuvem.
Disponibilidade
SLA
#######################################################
Os três principais modelos de serviços em nuvem são IaaS, PaaS e SaaS. Cada um oferece diferentes níveis de controle, flexibilidade e gerenciamento de infraestrutura de TI:

IaaS (Infrastructure as a Service):
O que é: Fornece infraestrutura de TI virtualizada, como servidores, armazenamento e redes.
Responsabilidade do usuário: Gerenciar sistemas operacionais, dados e aplicativos.
Exemplo: Microsoft Azure, Amazon Web Services (AWS).
Vantagem: Flexibilidade para configurar e gerenciar a infraestrutura conforme necessário12.
PaaS (Platform as a Service):
O que é: Oferece uma plataforma completa para desenvolvimento, execução e gerenciamento de aplicativos.
Responsabilidade do usuário: Focar no desenvolvimento e gerenciamento de aplicativos, enquanto o provedor cuida da infraestrutura subjacente.
Exemplo: Google App Engine, Microsoft Azure App Services.
Vantagem: Acelera o desenvolvimento de aplicativos, eliminando a necessidade de gerenciar a infraestrutura12.
SaaS (Software as a Service):
O que é: Fornece software de aplicativo pronto para uso, acessível pela internet.
Responsabilidade do usuário: Usar o software sem se preocupar com a manutenção ou gerenciamento.
Exemplo: Microsoft Office 365, Google Workspace.
Vantagem: Facilidade de uso e acesso a partir de qualquer lugar com conexão à internet.
Esses modelos permitem que as empresas escolham a melhor abordagem para suas necessidades específicas, seja para aumentar a agilidade, melhorar a segurança ou otimizar custos.

##################################################################################################
O dimensionamento de máquinas virtuais no Azure envolve ajustar a capacidade de computação para atender às necessidades específicas de sua aplicação. Aqui estão algumas opções e recursos disponíveis:

Conjuntos de Dimensionamento de Máquinas Virtuais (VMSS):
Permitem criar e gerenciar um grupo de VMs com balanceamento de carga.
O número de instâncias de VM pode aumentar ou diminuir automaticamente em resposta à demanda ou a um agendamento definido12.
Oferecem alta disponibilidade e resiliência ao distribuir VMs através de zonas de disponibilidade ou domínios de falha2.
Redimensionamento Manual:
Você pode redimensionar uma VM existente diretamente pelo portal do Azure.
No painel da máquina virtual, selecione “Tamanho” para visualizar e escolher as opções de redimensionamento3.
Dimensionamento Automático:
O Azure permite configurar o dimensionamento automático para ajustar a capacidade de VMs com base em métricas personalizáveis, como uso de CPU ou memória14.
Essas opções ajudam a garantir que suas aplicações tenham os recursos necessários para operar eficientemente, mesmo durante picos de demanda.
