<h1 align="center">Introdução a Sistemas operacionais: Servidores</h1>

## O que é um servidor ?

Um servidor pode ser definido como um software e/ou computador que fornece serviços específicos para clientes. Quando você escuta alguém falar de um servidor, ele está se referindo a uma máquina dedicada para executar um sistema ou aplicação que fornecem dados e serviços para os clientes em uma rede ou internet. Basicamente um servidor é uma máquina conectada a uma rede ou à internet que recebe e responde solicitações (requisições).

## O que é o Windows Server ?

É uma versão do Windows projetada para ser utilizada em servidores. Ele oferece recursos e funcionalidades otimizados para ambientes de rede, gerenciamento de usuários, armazenamento de dados, execução de aplicativos e outros serviços como suporte a funções de hospedagem de websites, gerenciamento de banco de dados, controle de domínio, gerenciamento de impressão, serviços de e-mail, entre outros. É especialmente adequado para ambientes corporativos que necessitam de estabilidade, segurança e suporte a muitos usuários simultâneos.

### Porque utilizar esse SO ao inves de um sistema convencional?

1. Capacidade de Gerenciamento de Rede:
    - Active Directory
	- DNS (Domain Name System)
	- DHCP (Dynamic Host Configuration Protocol)
	- políticas de grupo
	- System Center.

2. Suporte a Serviços de Servidor:
    - hospedagem de websites
	- gerenciamento de banco de dados
	- serviços de e-mail
	- virtualização (Hyper-V)
	- backup

3. Estabilidade e Confiabilidade:

    - O Windows Server é otimizado para oferecer alta disponibilidade e confiabilidade. 

4. Segurança Avançada:

5. Suporte Técnico Especializado:

    - A Microsoft oferece suporte técnico dedicado para o Windows Server, incluindo atualizações de software e patches de segurança que são essenciais para manter a integridade e a segurança do seu servidor.

6. Licenciamento e Direitos de Uso: 

<h2 align="center">Evolução Windows Server:</h1>

### Versões:

<details>
    <summary>Windows NT Server (Data de lançamento: 27/07/1993)</summary>

    Versões:

    3.1 Advanced Server
    3.5 Server 
    3.51 Server 
    4.0 Server   

    Edições:

    Advanced Server e Workstation	
    Workstation e Server	
    Workstation e Server	
    Workstation, Server, Server Enterprise Edition, Terminal Server, Embedded	

    Funcionalidades:



</details>

<details>
    <summary>Windows 2000 Server</summary>

    Funcionalidades: 

    * Active Directory
    * DNS Server
    * DHCP Server
    * Group Policy
    * MMC
    * Desfragmentação de disco
    * Proteção de arquivos críticos do sistema

    Edições:

    Professional, Server, Advanced Server e Datacenter Server.


</details>

<details>
    <summary>Windows Server 2003</summary>

    Windows Server 2003 R2

</details>

<details>
    <summary>Home Server</summary>

    Versão do Windows Server para servidores domésticos

</details>

<details>
    <summary>HPC Server 2008</summary>

    Desenvolvido para computação de alto desempenho e resolução de problemas complexos, como:

    Decodificação de genomas
    Animação de filmes
    Análise de riscos financeiros
    Simplificação de simulação de testes de colisão
    Modelagem de soluções de meteorologia global
    Dinâmica de fluido computacional (CFD) e outros problemas altamente complexos.

    Funcionalidades:

    * Integração com o Windows Azure na qual pode-se usar recursos em execução de um Datacenter do Windows, para ampliar a capacidade de seu cluster do Windows HPC local.
    
    * Com o Windows HPC pode-se usar computadores inativos com Windows 7 para estender a capacidade de computação dos clusters existentes sem precisar comprar hardware adicional.

</details>

<details>
    <summary>Windows Server 2008</summary>

    Versões:

    Windows Server 2008 R2

    Funcionalidades:

     Virtualização Hyper-V 
     Server Core (Configuração e manutenção é feita inteiramente através de janelas de interface de linha de comando ou conectando-se à máquina remotamente)
     BitLocker
     IPv6 nativo
     Rede sem fio nativa
     Recuperação baseadas em imagem
     ASLR (randomização de layout de espaço de endereço)
     Firewall do Windows melhorado com configuração padrão segura
     Clustering de failover
     Windows System Resource Manager (gerenciamento de recursos e pode ser usado para controlar a quantidade de recursos que um processo ou um usuário pode usar com base nas prioridades de negócios)
     Melhorias no núcleo do SO
     Melhorias no Active Directory
     Melhorias relacionadas a políticas
     Aperfeiçoamentos de protocolo e criptografia

    Edições:

    Standard
    Enterprise 
    Datacenter 
    Web Server 

     

</details>

<details>
    <summary>Home Server 2011</summary>

     Sistema operacional para servidores domésticos desenvolvido pela Microsoft para suceder o Windows Home Server.

</details>

<details>
    <summary>Windows Server 2012</summary>

    Versões: 
    
    Windows Server 2012 R2

    Funcionalidades:

    * Opções de instalação "Server Core" e "Server com uma GUI" 
    * Nova versão do Gerenciador de Servidor
    * Nova versão do Gerenciador de tarefas
    * nova versão do Hyper-V
    * servidor web IIS 8.0 da própria Microsoft

    Edições:

    Datacenter
Edição destinado a ambientes de nuvem privada ou híbrida. Está é a versão mais completa da edição 2012.

Standard
Possui funcionalidade completa, assim como a edição Datacenter porém, é destinados a ambientes não-virtualizados.

Essentials
Destinado a pequenos negócios, esta edição está limitada a apenas 25 contas de usuários.

Foundation
Para uso geral, está disponível apenas na versão OEM. Limitado com 15 contas de usuários.


</details>

<details>
    <summary>Windows Server 2016</summary>

    Versões:

    1806

    Funcionalidades:

    Contêineres Windows
    Nano Server
    Interface do Windows 10
    “sistema operacional pronto para a nuvem”, e apresenta tecnologias para facilitar a transição para a nuvem do Windows Azure
    Sistema de ficheiros distribuídos (DFS - Distributed File System):
    Serviços de Terminal (Terminal Services): 
    Sistema de logs para anormalidades 

    Edições:

    Nano Server
    Stardard
    Datacenter
    Essentials

</details>

<details>
    <summary>Windows Server 2019</summary>

    sistema operacional pronto para a nuvem”, e apresenta tecnologias para facilitar a transição para a nuvem do Windows Azure.

    Windows Admin Center: Uma nova maneira de administrar remotamente a infraestrutura do servidor , melhorar a infraestrutura hiperconvergente e o suporte profundo para o subsistema Linux.   

    Melhorias no desempenho da rede para cargas de trabalho virtuais
    Contêineres do Linux no Windows
    Infraestrutura Hiper-Convergente (IHC)
    Suporte do Kubernetes

</details>

<details>
    <summary>Windows Server 2022</summary>

    Funcionalidades:

    Segurança
TPM 2.0[8]
Servidor de núcleo seguro; Credential Guard e Hypervisor-protected Code Integrity (HVCI)[9]
Inicialização segura do UEFI[10]
Proteção de inicialização DMA. [11]
DNS sobre HTTPS[10]
Criptografia AES-256 no SMB[10]
Armazenamento
Serviço de Migração de Armazenamento (SMS)
Compressão do Server Message Block (SMB)
Segurança e desempenho do armazenamento
Nuvem
Benefícios do Azure hybrid

    Edições:

    Essentials
Disponível somente por meio de parceiros OEM da Microsoft.[12]

Destinado a pequenas empresas
Suporta um máximo de 25 usuários e 50 dispositivos
Não são necessárias licenças de acesso de cliente (CALs)[13]
Standard
Destinado a ambientes VCC físicos ou fracos
Apenas duas máquinas virtuais e um host Hyper-V são considerados utilizáveis[5][14][15]
Datacenter
Destinado a data centers altamente virtualizados e ambientes de nuvem
Azure Datacenter
Projetado para a plataforma Microsoft Azure[5]

</details>

</br>

-------

</br>

Links de referência

[ServerSpace](https://serverspace.com.br/support/help/windows-server-versions-editions-licensing/) | [Wikipedia](https://pt.wikipedia.org/wiki/Windows_Server) | [Pense em TI](https://penseemti.com.br/artigos/a-historia-do-windows-server/)

