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
    <summary>Windows NT Server</summary>

</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/WinNT.png" alt="Imagem Windows NT">
</p>

    Edições:

    3.1 (Data de lançamento: 27/07/1993)
        Versões:
            Advanced Server
            Workstation

    3.5 (Data de lançamento: 21/09/1994)
        Versões:
            Workstation
            Server

    3.51 (Data de lançamento: 30/05/1995)
        Versões:
            Workstation
            Server

    4.0 (Data de lançamento: 29/07/1996)
        Versões:
            Workstation 
            Server
            Server Enterprise Edition
            Terminal Server
            Embedded

</details>

<details>
    <summary>Windows 2000 Server</summary>

    Data de lançamento: 17/02/2000
</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/Win2000.png" alt="Imagem Windows 2000">
</p>

    Funcionalidades: 

        Active Directory
        DNS Server
        DHCP Server
        Group Policy
        MMC
        Desfragmentação de disco
        Proteção de arquivos críticos do sistema

    Edições:

        Professional
        Server
        Advanced Server
        Datacenter Server

</details>

<details>
    <summary>Windows Server 2003</summary>

    Data de lançamento: 24/04/2003

</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/Win2003.png" alt="Imagem Windows 2003">
</p>

    Windows Server 2003 R2 (Data de lançamento: 06/12/2005)

    Funcionalidades:

        Nova versão do servidor IIS
        Internet Explorer 6
        Prevenção de Execução de Dados (DEP)
        Windows Media Player versão 10
        Assistente de Configuração de Segurança
        Adição de recursos de rede

    Edições:

        Datacenter Edition
        Enterprise Edition
        Standard Edition
        Web Edition


</details>

<details>
    <summary>Home Server</summary>

    Data de lançamento: 07/11/2007

    Versão do Windows Server para servidores domésticos

</details>

<details>
    <summary>HPC Server 2008</summary>

    Data de lançamento: 22/09/2008

    Desenvolvido para computação de alto desempenho e resolução de problemas complexos, como:

        Decodificação de genomas
        Animação de filmes
        Análise de riscos financeiros
        Simplificação de simulação de testes de colisão
        Modelagem de soluções de meteorologia global
        Dinâmica de fluido computacional (CFD) e outros problemas altamente complexos.

    Funcionalidades:

        Integração com o Windows Azure na qual pode-se usar recursos em execução de um Datacenter do Windows, para ampliar a capacidade de seu cluster do Windows HPC local.
    
        Com o Windows HPC pode-se usar computadores inativos com Windows 7 para estender a capacidade de computação dos clusters existentes sem precisar comprar hardware adicional.

</details>

<details>
    <summary>Windows Server 2008</summary>

    Data de lançamento: 27/02/2008

</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/Win2008.png" alt="Imagem Windows 2008">
</p>

    Versões:

        Windows Server 2008 R2 (Data de lançamento: 22/10/2009)

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
        Windows System Resource Manager (gerenciamento de recursos e pode ser usado para controlar a quantidade de recursos que um processo ou um usuário pode usar com base nas prioridades de negócios).
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

    Data de lançamento: 06/04/2011

     Sistema operacional para servidores domésticos desenvolvido pela Microsoft para suceder o Windows Home Server.

</details>

<details>
    <summary>Windows Server 2012</summary>

</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/Win2012.png" alt="Imagem Windows 2012">
</p>

    Data de lançamento: 04/09/2012

    Versões: 
    
        Windows Server 2012 R2 (Data de lançamento: 18/10/2013)

    Funcionalidades:

        Interface do Windows 8
        Opções de instalação "Server Core" e "Server com uma GUI" 
        Nova versão do Gerenciador de Servidor
        Nova versão do Gerenciador de tarefas
        Nova versão do Hyper-V
        Servidor web IIS 8.0 da própria Microsoft

    Edições:

        Datacenter
        Standard
        Essentials
        Foundation

</details>

<details>
    <summary>Windows Server 2016</summary>

</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/Win2016.png" alt="Imagem Windows 2016">
</p>

    Data de lançamento: 12/10/2016

    Funcionalidades:

        Contêineres Windows
        Nano Server
        Interface do Windows 10
        Introdução a recursos para computação em nuvem
        Sistema de ficheiros distribuídos (DFS - Distributed File System)
        Serviços de Terminal (Terminal Services)
        Sistema de logs para anormalidades 

    Edições:

        Nano Server
        Stardard
        Datacenter
        Essentials

</details>

<details>
    <summary>Windows Server 2019</summary>

</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/Win2019.jpg" alt="Imagem Windows 2019">
</p>

    Data de lançamento: 

    Funcionalidades:

        Melhorias nas tecnologias para computação em nuvem (Windows Azure)

        Windows Admin Center: Uma nova maneira de administrar remotamente a infraestrutura do servidor, melhorar a infraestrutura hiperconvergente e o suporte profundo para o subsistema Linux.   

        Melhorias no desempenho da rede para cargas de trabalho virtuais
        Contêineres do Linux no Windows
        Infraestrutura Hiper-Convergente (IHC)
        Suporte do Kubernetes

</details>

<details>
    <summary>Windows Server 2022</summary>

</br>

<p align="center">
  <img src="https://github.com/peagaaa/Win-Server/blob/main/Assets/Win2022.png" alt="Imagem Windows 2022">
</p>

    Funcionalidades:

    Mais recursos de segurança:

        TPM 2.0[8]
        Servidor de núcleo seguro
        Credential Guard 
        Hypervisor-protected Code Integrity (HVCI)
        Inicialização segura do UEFI
        Proteção de inicialização DMA
        DNS sobre HTTPS
        Criptografia AES-256 no SMB

    Mais recurso de Armazenamento:

        Serviço de Migração de Armazenamento (SMS)
        Compressão do Server Message Block (SMB)
        Segurança e desempenho do armazenamento

    Benefícios do Azure hybrid

    Edições:

        Essentials: Destinado a pequenas empresas, máximo de 25 usuários e 50 dispositivos.

        Standard: Destinado a ambientes VCC físicos ou fracos, Apenas duas máquinas virtuais e um host Hyper-V são considerados utilizáveis.

        Datacenter: Destinado a data centers altamente virtualizados e ambientes de nuvem.

        Azure Datacenter: Projetado para a plataforma Microsoft Azure.

</details>

</br>

-------

</br>

Links de referência

[ServerSpace](https://serverspace.com.br/support/help/windows-server-versions-editions-licensing/) | [Wikipedia](https://pt.wikipedia.org/wiki/Windows_Server) | [Pense em TI](https://penseemti.com.br/artigos/a-historia-do-windows-server/) | [Tio Inaldo](https://tioinaldo.com/saiba-tudo-sobre-windows-microsoft-server/)