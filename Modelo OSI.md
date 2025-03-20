O modelo Open Systems Interconnection (OSI) descreve sete camadas que os sistemas de computador usam para se comunicar através de uma rede ([[Network]]). O modelo OSI é dividido em sete camadas distintas, cada uma com responsabilidades específicas, que vão desde conexões físicas de [[Hardware]] até interações de aplicativos de alto nível.

<hr>
##  Objetivo

O modelo OSI foi o primeiro modelo padrão para comunicações de rede, adotado por todas as principais empresas de computação e telecomunicações no início da década de 1980. Foi introduzido em 1983 por representantes das principais empresas de informática e telecomunicações, e foi adotado pela ISO como padrão internacional em 1984.
A [[Internet]] moderna não é baseada em OSI, mas no modelo [[TCP IP]] mais simples. No entanto, o modelo OSI de 7 camadas ainda é amplamente utilizado, pois ajuda a visualizar e comunicar como as redes operam.

<hr>

## Como funciona

![[Pasted image 20250316113147.png]]

### 7. Camada Aplicação

![[Pasted image 20250316113206.png]]

A Camada de Aplicação serve como a interface entre as aplicações de utilizador final e os serviços de rede subjacentes. Esta camada fornece protocolos e serviços que são utilizados diretamente por aplicativos de usuário final para se comunicar através da rede. As principais funcionalidades da Camada de Aplicação incluem compartilhamento de recursos, acesso remoto a arquivos e gerenciamento de rede.
Exemplos de protocolos que operam na Camada de Aplicação incluem Protocolo de Transferência de Hipertexto ([[HTTP]]) para navegação na [[Web]], File Transfer Protocol ([[FTP]]) para transferências de arquivos, Simple Mail Transfer Protocol (SMTP) para serviços de e-mail e Domain Name System ([[DNS]]) para resolver nomes de domínio para endereços [[IP]]. Esses protocolos garantem que os aplicativos do usuário possam se comunicar efetivamente entre si e com os servidores em uma rede.

### 6. Camada de Apresentação

![[Pasted image 20250316113304.png]]

A Camada de Apresentação, também conhecida como camada de sintaxe, é responsável por traduzir dados entre a camada de aplicação e o formato de rede. Ele garante que os dados enviados da camada de aplicação de um sistema sejam legíveis pela camada de aplicação de outro sistema. Esta camada lida com a formatação de dados criptografiae compressão, facilitando a interoperabilidade entre diferentes sistemas.

Uma das principais funções da Camada de Apresentação é a tradução de dados e conversão de código. Ele transforma os dados em um formato que a camada de aplicação pode entender. Por exemplo, ele pode converter dados de ASCII para EBCDIC. Também inclui protocolos de criptografia para garantir segurança de dados durante os protocolos de transmissão e compressão para reduzir a quantidade de dados para uma transmissão eficiente.

### 5. Camada de Sessão

![[Pasted image 20250316113341.png]]

A Camada de Sessão gerencia e controla as conexões entre computadores. Estabelece, mantém e encerra conexões, garantindo que as trocas de dados ocorram de forma eficiente e organizada. A camada é responsável pela verificação e recuperação da sessão, o que permite que as sessões sejam retomadas após interrupções.

Os protocolos que operam na Camada de Sessão incluem a Chamada de Procedimento Remoto ([[RPC]]), que permite que um programa execute um procedimento em um host remoto como se fosse local, e a fase de estabelecimento da sessão em protocolos como NetBIOS e [[SQL]]. Esses serviços permitem uma comunicação confiável, especialmente em ambientes de rede complexos.

### 4. Camada Transporte

![[Pasted image 20250316113418.png]]

A Camada de Transporte fornece serviços de comunicação de ponta a ponta para aplicativos. Ele garante a transferência completa de dados, recuperação de erros e controle de fluxo entre os hosts. Essa camada segmenta e reúne dados para uma transmissão eficiente e fornece confiabilidade com mecanismos de detecção e correção de erros.

Protocolos nesta camada incluem Protocolo Controle Transmissão ([[TCP]]) e Protocolo de Datagrama de Usuário ([[UDP]]). O TCP é orientado para conexão e garante transferência de dados confiável com verificação de erros e controle de fluxo, tornando-o adequado para aplicativos como navegação na web e e-mail. O UDP é sem conexão, oferecendo transmissão mais rápida, embora menos confiável, adequada para aplicativos como streaming de vídeo e jogos online.

### 3. Camada Rede

![[Pasted image 20250316113456.png]]

A Camada de Rede é responsável pelo roteamento, encaminhamento e endereçamento de dados. Ele determina o melhor caminho físico para que os dados cheguem ao seu destino com base nas condições da rede, na prioridade do serviço e em outros fatores. Essa camada gerencia o endereçamento lógico por meio de endereços IP e lida com o encaminhamento de pacotes.

Os principais protocolos nesta camada incluem o Protocolo de Internet (IP), que é importante para roteamento e endereçamento, Protocolo de Mensagem de Controle de Internet ([[ICMP]]) para fins de diagnóstico e relatório de erros, e protocolos de roteamento como Routing Information Protocol (RIP) que gerenciam o roteamento de dados entre redes.

### 2. Camada de Link de Dados

![[Pasted image 20250316113527.png]]

A Camada de Link de Dados é responsável pela transferência de dados de nó para nó e detecção e correção de erros. Ele garante que os dados sejam transmitidos para o dispositivo correto em um segmento de rede local. Esta camada gerencia [[MAC]] (Controle de Acesso de Mídia) endereços e é dividido em duas subcamadas: Logical Link Control (LLC) e Media Access Control (MAC).

Protocolos e tecnologias nesta camada incluem [[Ethernet]], que define as regras para a transmissão de dados através de redes de área local (LANs), e Point-to-Point Protocol (PPP) para conexões diretas entre dois nós de rede. Também inclui mecanismos para detectar e possivelmente corrigir erros que possam ocorrer na Camada Física.

### 1. Camada Física

![[Pasted image 20250316113600.png]]

A Camada Física é responsável pela conexão física entre dispositivos. Ele define os elementos de [[Hardware]] envolvidos na rede, incluindo [[Cabos de Rede]], [[Switches]] e outros componentes físicos. Essa camada também especifica as características elétricas, ópticas e de rádio da rede.

As funções da Camada Física incluem a modulação, sincronização de bits e transmissão de dados binários brutos sobre o meio físico. Tecnologias como Fibra Óptica e Wi-Fi operam nessa camada, garantindo que os dados se movam fisicamente de um dispositivo para outro na rede.