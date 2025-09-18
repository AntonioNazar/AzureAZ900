# AzureAZ900

# Computação em nuvem: domínio do objetivo

## O que é?

A computação em nuvem é fornecimento de serviços pela Internet.

## Por que utilizar?

A computação em nuvem permite uma flexibilização do trabalho muito grande, porém é necessário ter uma estrutura para guiar os custos, pois por ser um serviço on-premisse, o custo pode ser maior que os benefícios.

## Modelos 

### Nuvem privada

Ambiente on-premisse, mas somente para minha empresa. Ou seja, a organização cria um ambiente em nuvem em seu datacenter e são responsáveis por operar o serviços que fornecem. E não fornece acesso aos usuários de fora da organização.

A organização têm controle total sobre os recursos e segurança. E sendo assim, são responsáveis também pela manutenção do hardware.

### Nuvem pública

Ambiente pertencente a um hosting ou provedor. Fornece recursos e serviços a várias organizações e usuários, acessada via conexão de rede segura! Pela internet.

Os recursos podem variar o preço do serviço por região, uso etc.

Os aplicativos podem ser provisionados e desprovisionados rapidamente. Ou seja, podemos modificar alguns serviços de forma natural.

A organização paga apenas pelo o que utiliza.

### Nuvem híbrida

Ambiente que combina aspectos da nuvem pública e aspectos da nuvem privada para executar serviços em locais mais apropriados.

As organizações determinam onde executar seus aplicativos.

 A organização controla a segurança.
 
 ## CapEx e OpEx
 
 ### CapEx 
 
 O gasto inicial de dinheiro em infraestrutura física.
 
 As despesas do CapEx têm um valor que se reduz com o tempo.
 
 
 ### OpEx 
 
Gastar com produtos e serviços conforme necessário, o tempo conforme o uso.
 
Cobrado imediatamente.

 
# Benefícios: domínio de objetivo

## Benefícios

### Alta disponibilidade
Alta disponibilidade se concentra em garantir a disponibilidade máxima, independetemente de interrupções ou eventos que possam ocorrer.


### Escalabilidade

A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda.

A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento de demanda.

### Elasticidade

Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos.

### Confiabilidade

Mesmo que algo muito problemático aconteça em uma região, as outras regiões ainda estarão funcionando, ou seja, podemos confiar que a rede não irá parar de funcionar.

### Previsibilidade

A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo microsoft azure well-architected framework.

### Segurança

A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.

### Governança

A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação.


### Gerenciabilidade

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.

Diz respeito a gerenciar seus recursos de nuvem da forma como você desejar, automaticamente ou não etc.

![image](https://hackmd.io/_uploads/B1gnTQRDjxl.png)

## Tipos de serviço de nuvem

### IaaS

Infraestrutura como serviço

Cria uma infraestrutura de TI de pagamento conforme o uso alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.

Você configura e gerencia o hardware para o seu aplicativo

### PaaS

Plataforma como serviço

Fornece um ambiente para a criação, o teste e a implementação de aplicativos de software, sem focar no gerenciamento da infraestrutura.

O gerenciamento de plataforma é realizado pelo provedor de nuvem.

### SaaS

Software como serviço

Os usuários se conectam e usam aplicativos com base em nuvem pela internet, como emails, calendários e microsoft office.

O usuários pagam pelo software que utilizam em um modelo de assinatura.

![image](https://hackmd.io/_uploads/S1OK91Yoge.png)
    
    
### Modelo de responsabilidade compartilhada

![image](https://hackmd.io/_uploads/S1cE2ytseg.png)

### Regiões 

Nem todos os recursos estão para todas as regiões e cada região tem um valor determinado, ou seja, o preço varia.

As regiões são compostas de um ou mais datacenters próximos que são conectados entre si.

Eles fornecem flexibilidade e escala para reduzir a latência do cliente.

As regiões preservam a residência dos dados com uma oferta abrangente de conformidade. 

![image](https://hackmd.io/_uploads/SyEekgFseg.png)

#### Pares de região

Cada região tem uma região par, que são separadas por no mínimo 300 milhas.
Possui replicação automática para alguns serviços.
É usada para recuperação da região priorizada em caso de interrupções.
As atualizações são distribuidas sequenciamente para minimizar tempo de inatividade.

![image](https://hackmd.io/_uploads/rJwgzetoll.png)


#### Região soberana

São regiões exclusivas para clientes especiais. Ou seja, apenas para questões militares ou de segurança. Geralmente atende serviços de segurança dos EUA, China e . É acessível apenas para o pessoal autorizada.

Na China os serviços de nuvem da Azure são operados pela 21Vianet.


### Assinaturas do Azure

Uma assinatura do Azure fornece a você acesso autenticado e autorizado às contas do Azure.

#### Limite de cobrança

Gerencia relatórios de cobrança e faturas separadas para cada assinatura

#### Limite de controle de acesso

Gerencia e controla o acesso aos recursos que os usuários podem provisionar com assinaturas específicas.

![image](https://hackmd.io/_uploads/B1EameFiel.png)

### Alguns recursos do Azure

- Máquinas virtuais
- Conjunto de dimensionamento de VMs
- Área de Trabalho Virtual do Azure
- Instâncias de Contêiner do Azure
- Aplicativos de Contêiner do Azure (é diferente de instâncias pois tem balanceamento de carga e colocação em escala)
- Serviço de Kubernet do Azure (Orquestração de grande volumes de quantidades e ciclos de vida)
- Azure functions
- Serviço de aplicativos
Consistem em criar uma plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs
- Rede virtual do Azure (Vnet)
- Gateway de VPN
- ExpressRoute


# Armazenamento: domínio de objetivos

## Contas de Armazenamento

Deve ter um nome exclusivo globalmente.
Fornecer acesso à internet em todo mundo.
Precisa determinar os serviços de armazenamento e as opções de redundância.

![image](https://hackmd.io/_uploads/SJOBjptogx.png)

### Blob do Azure
Otimizado para armazenamento de quantidades massivas de dados não estruturados, como texto e dados binários.

### Disco do Azure
Fornece discos para máquinas virtuais, aplicativos e outros serviços acessarem e utilizarem.

### Fila do Azure

Serviço de armazenamento de mensagens que fornece armazenamento e recuperação para grandes quantidades de mensagens, cada um com até 64Kb.

### Arquivos do Azure

Configura um compartilhamento de arquivos de rede altamente disponível que pode ser utilizado usando o protocolo Bloco de Mensagem do Servidor.

### Tabela do Azure

Fornece uma opção de chave/atributo para o armazenamento de dados estruturados não relacionais com um design sem esquema.

### Camadas de acesso de armazenamento do Azure

![image](https://hackmd.io/_uploads/SyWZ0atigg.png)

## Migração de Dados para Azure

### Azure Data Box

Armazena até 80Tb de dados.

Utilizado para migrar dados para o Azure de locais geralmente remotos, com conectividade limitada ou sem conectividade.

Proteja seus dados em uma caixa robusta durante o trânsito.

### AzCopy

Utilitário de linha de comando.

Copiar blobs ou arquivos de um local para sua conta de armazenamento.

Sincronização em uma direção.

### Gerenciador de Armazenamento do Azure

Interface gráfica do usuário.

Compatível com o Windows, MacOS e Linux.

De baixo dos panos, ele utiliza o AzCopy.

### Sincronização de Arquivos do Azure

Sincronização dos arquivos do Azure e locais de forma **bidirecional**

A camada de nuvem mantém os arquivos acessados com frequência no local, enquanto libera espaço.

# Identidade, acesso e segurança: domínio de objetivo

## Microsoft Entra ID

Autenticação

Logon único (SSO)

Gerenciamento de aplicativos

Negócios para negócios (B2B)

Gerenciamento de dispositivo

## Microsoft Entra Domain Service

Obtenha os benefícios dos serviços de domínio baseados em nuvem sem gerenciar os controladores de domínio.

Execute aplicativos herdados (que não podem utilizar os padrões de autenticação modernos) na nuvem.

### Autenticação

Identifica a pessoa ou serviço buscando acesso a um recurso.

Solicita credenciais de acesso legítimo.

Base para criar princípios de identidade e controle de acesso seguros.

### Autorização

Determina o nível de acesso de uma pessoa ou serviço autenticado.

Define quais dados eles podem acessar e o que podem fazer com eles.

### Acesso condicionais

- Associação de usuário ou grupo
- Local do IP
- Dispositivo
- Aplicativo
- Detecção de risco

### Controle de acesso baseado em função (RBAC)

Gerenciamento de acesso de granularidade fina.

Divida as tarefas dentro da equipe e conceda a somente a uma quantidade de acesso de que o os usuários precisam  para trabalhar.

Habilite o acesso ao portal do Azure e o controle de acesso aos recursos.

## Microsoft Defender para Nuvem

É um serviço de monitoramento que fornece proteção contra ameaças nos datacenters do Azure e locais.

# Gerenciamento e Governança

