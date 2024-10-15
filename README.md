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

#######################################################################################################

O Azure oferece vários tipos de armazenamento para atender diferentes necessidades. Aqui estão os principais:

1. **Armazenamento de Blobs**: Ideal para armazenar grandes quantidades de dados não estruturados, como texto ou dados binários. É dividido em quatro camadas: Premium, Hot, Cool e Archive, dependendo da frequência de acesso aos dados.

2. **Armazenamento de Arquivos**: Fornece compartilhamentos de arquivos gerenciados na nuvem que podem ser acessados via SMB e NFS. É útil para migração de aplicativos legados que dependem de compartilhamentos de arquivos.

3. **Armazenamento de Filas**: Permite a comunicação entre componentes de aplicativos distribuídos, armazenando grandes volumes de mensagens que podem ser acessadas de forma assíncrona.

4. **Armazenamento de Tabelas**: Oferece armazenamento NoSQL para dados estruturados, permitindo acesso rápido e eficiente a grandes volumes de dados.

5. **Discos Gerenciados**: Fornece armazenamento de discos persistentes para máquinas virtuais, com opções de desempenho e redundância.

Fontes: 
Armazenamento de Blobs do Azure. https://azure.microsoft.com/pt-br/products/storage/blobs/.
Armazenamento de Arquivos do Azure. https://azure.microsoft.com/pt-br/products/storage/.
Introdução ao Armazenamento do Microsoft Azure. https://learn.microsoft.com/pt-br/azure/storage/common/storage-introduction.
Introdução aos tipos de Armazenamento do Microsoft Azure – Armazenamento em nuvem .... https://bing.com/search?q=Tipos+de+armazenamento+no+azure.
Entenda os modelos de armazenamento de dados - Azure Application .... https://learn.microsoft.com/pt-br/azure/architecture/guide/technology-choices/data-store-overview.

#######################################################################################################

Entendendo sobre Segurança e Identidade na Azure

Entender sobre segurança e identidade no Azure é fundamental para proteger recursos e dados na nuvem. O Azure oferece uma variedade de ferramentas e práticas recomendadas para garantir que suas identidades e acessos estejam seguros. Aqui estão alguns pontos-chave:

1. **Identidade como Perímetro de Segurança**: Tratar a identidade como o perímetro de segurança primário é crucial. Isso significa centralizar o gerenciamento de identidade e habilitar logon único (SSO) para facilitar o acesso seguro.

2. **Autenticação Multifator (MFA)**: Implementar MFA adiciona uma camada extra de segurança, exigindo que os usuários forneçam mais de uma forma de verificação para acessar recursos.

3. **Controle de Acesso Baseado em Função (RBAC)**: Usar RBAC permite que você controle quem tem acesso a quais recursos, minimizando a exposição de contas privilegiadas.

4. **Gerenciamento de Identidade Híbrida**: Integrar identidades locais com o Azure Active Directory (AAD) para uma gestão unificada e segura.

5. **Monitoramento e Alertas**: Utilizar relatórios baseados em aprendizado de máquina, alertas e monitoramento de segurança para detectar atividades suspeitas e responder rapidamente a possíveis ameaças.

###########################################################################################################



