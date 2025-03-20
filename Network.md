Um "network" no ramo da tecnologia é um conjunto de computadores que podem compartilhar recursos providos pelos "nodes". Esses computadores compartilham de [[Protocolos de comunicação]] feitos pela conexão entre eles. Tal conexão é parecida, graficamente, com [[Grafos]]

![[Pasted image 20250312114053.png]]

A [[Internet]] também está completamente liga ao conceito de redes.

<hr>
## Topologia de rede

As localizações físicas ou geográficas dos nós e links da rede geralmente têm relativamente pouco efeito em uma rede, mas a topologia das interconexões de uma rede pode afetar significativamente sua taxa de transferência e confiabilidade

Topologias comuns são:

- **Rede estrela**: todos os nós estão conectados a um nó central especial. Este é o layout típico encontrado em um pequeno [[Ethernet]] Comutada LAN, onde cada cliente se conecta a um [[Switches]] de rede central, e logicamente em um LAN sem fio, onde cada cliente sem fio se associa à central ponto de acesso sem fio.

  ![[Pasted image 20250312115307.png]]
  
- **Rede anel**: cada nó está conectado ao seu nó vizinho esquerdo e direito, de modo que todos os nós estão conectados e que cada nó pode alcançar um ao outro nó atravessando os nós para a esquerda ou para a direita. Anel token redes e o Interface de Dados Distribuída por Fibra (FDDI), fez uso de tal topologia.

  ![[Pasted image 20250312115442.png]]

- **Rede malha**: cada nó é conectado a um número arbitrário de vizinhos de tal forma que há pelo menos uma travessia de qualquer nó para qualquer outro.

  ![[Pasted image 20250312115524.png]]
  
- **Rede de árvores ([[Tree]]):** os nós são organizados hierarquicamente. Esta é a topologia natural para uma rede [[Ethernet]] maior com vários [[Switches]] e sem malha redundante.

  ![[Pasted image 20250312115605.png]]

<hr>
## Principais nós de rede

Além de qualquer mídia de transmissão física, as redes são construídas a partir de blocos de construção básicos adicionais do sistema, como controladores de [[Interface de rede]], [[Repetidores]], [[Hub]] , [[Roteadores]], [[Modems]] e [[Firewall]].

### [[Interface de rede]]

Um controlador de interface de rede (NIC) é hardware do computador que conecta o computador ao mídia de rede e tem a capacidade de processar informações de rede de baixo nível.
Em redes Ethernet, cada NIC tem um único Endereço de Controle de Acesso à Mídia ([[MAC]])—normalmente armazenados na memória permanente do controlador.

![[Pasted image 20250312115955.png]]

### [[Repetidores]] e [[Hub]]

- Um repetidor é um dispositivo eletrônico que recebe uma rede sinal, limpa-o de ruído desnecessário e regenera-lo. O sinal é retransmitido em um nível de potência mais alto, ou para o outro lado da obstrução de modo que o sinal possa cobrir distâncias mais longas sem degradação.
- Um repetidor [[Ethernet]] com várias portas é conhecido como um Hub Ethernet. Além de recondicionar e distribuir sinais de rede, um hub repetidor auxilia na detecção de colisão e isolamento de falhas para a rede. Hubs e repetidores em LANs têm sido amplamente obsoletos por switches de rede modernos.

![[Pasted image 20250312120935.png]]

### [[Roteadores]]

Um roteador é um dispositivo de internetworking que encaminha pacotes entre redes processando as informações de endereçamento ou roteamento incluídas no pacote.

![[Pasted image 20250312121113.png]]

### [[Modems]]

Modems (modulador-demodulador) são usados para conectar nós de rede via fio não originalmente projetado para tráfego de rede digital, ou para wireless

![[Pasted image 20250312121135.png]]
### [[Firewall]]

Um firewall é um dispositivo de rede ou software para controlar as regras de acesso e segurança da rede. Os firewalls são inseridos em conexões entre redes internas seguras e redes externas potencialmente inseguras, como a Internet.

![[Pasted image 20250312121256.png]]


<hr>

## Comunicação

O Suíte de protocolo de internet, também chamado de [[TCP IP]], é a base de todas as redes modernas. Oferece serviços sem conexão e orientados para conexão em uma rede inerentemente não confiável atravessada pela transmissão de data grama usando o protocolo de Internet ([[IP]]). Em sua essência, o conjunto de protocolos define o endereçamento, identificação e encaminhamento especificações para Protocolo Internet Versão 4 (IPv4) e para IPv6.

### IEEE 802

IEEE 802 é uma família de padrões IEEE que lidam com redes de área local e redes de área metropolitana. O conjunto completo de protocolos IEEE 802 fornece um conjunto diversificado de recursos de rede.

## [[Ethernet]]

Ethernet é uma família de tecnologias usadas em LANs com fio. É descrito por um conjunto de padrões juntos chamados IEEE 802

### LAN sem fio

LAN sem fio baseado no IEEE 802.11 padrões, também amplamente conhecido como WLAN ou WiFi, é provavelmente o membro mais conhecido do IEEE 802 protocolo família para usuários domésticos hoje.

<hr>

## Tipos de rede

As redes podem ser caracterizadas por muitas propriedades ou recursos, como capacidade física, finalidade organizacional, autorização do usuário, direitos de acesso e outros. Outro método de classificação distinto é o da extensão física ou escala geográfica

### Rede de computadores tipos por escala

![[Pasted image 20250312121851.png]]

### Rede de área pessoal

A rede de área pessoal (PAN) é uma rede de computadores usada para comunicação entre computadores e diferentes dispositivos tecnológicos de informação perto de uma pessoa.

### Rede de área local

A rede local (LAN) é uma rede que conecta computadores e dispositivos em uma área geográfica limitada, como uma casa, escola, prédio de escritórios ou grupo de edifícios bem posicionado.

### Rede de área de residência

A rede de área residencial (HAN) é uma LAN residencial usada para comunicação entre dispositivos digitais normalmente implantados em casa, geralmente um pequeno número de computadores pessoais e acessórios, como impressoras e dispositivos de computação móvel.

### Rede de área de armazenamento

A rede de área de armazenamento (SAN) é uma rede dedicada que fornece acesso ao armazenamento de dados consolidado em nível de bloco.

### Rede de área do campus

A rede de área do campus (CAN) é constituída por uma interligação de LANs dentro de uma área geográfica limitada. O equipamento de rede ([[Switches]], [[Roteadores]]) e meios de transmissão ([[Cabos de Rede]]) 

### Rede privada virtual

A rede privada virtual ([[VPN]]) é um rede de sobreposição em que alguns dos links entre nós são transportados por conexões abertas ou circuitos virtuais em alguma rede maior (por exemplo, a Internet) em vez de fios físicos.