O protocolo TCP/IP é a linguagem fundamental que permite a comunicação entre dispositivos na [[Internet]]. Esse conjunto de regras define como os dados são formatados, enviados, recebidos, garantindo que diferentes sistemas possam se comunicar de forma eficiente.
A arquitetura TCP/IP é organizada em quatro camadas: Aplicação, Transporte, [[Internet]] e Acesso à Rede. Cada camada possui funções específicas, como interação com programas, comunicação entre as máquinas e a transmissão física dos dados.

## Definição

O modelo TCP/IP (Transmission Control Protocol/Internet Protocol) é a base da comunicação em redes de computadores, como a Internet. Esse conjunto de protocolos define como os dados são divididos em pacotes, enviados e remontados.
Flexível, o modelo TCP/IP permite a conexão de redes heterogêneas. Além dos protocolos principais, a arquitetura é complementada com outros protocolos de internet, como o [[HTTP]] (transferência de páginas web), [[FTP]] (transferência de arquivos) e [[SMTP]] (envio de e-mails).

## Como funciona

O protocolo TCP/IP atua para permitir a comunicação entre dispositivos na internet.
Para isso, a estrutura de rede divide a informação em pequenos pacotes com “instruções” sobre o remetente, o destinatário e a sequência em que deve ser remontado. Então, os pacotes são reorganizados ao chegar ao destino e formam a mensagem original.

### Camadas do TCP/IP

- **Camada de Aplicação:** onde os dados são preparados para serem enviados pela rede conforme os protocolos padrões (exemplo: HTTP, [[DHCP]], [[DNS]]);
- **Camada de Transporte:** o TCP divide os dados em pacotes e garante a entrega confiável ao destinatário. Em alguns modelos, o protocolo UDP também atua nessa camada, oferecendo o envio rápido de dados sem confirmação de entrega. O TCP também sincroniza a conexão entre dispositivos e realiza o controle de fluxo;
  (Exemplo: [[TCP]] e [[UDP]])
- **Camada de Internet (ou Rede):** o IP é o principal protocolo dessa camada, responsável por endereçar e rotear os pacotes pela rede;
  Exemplo ([[IP]])
- **Camada de Acesso à Rede (ou Enlace):** essa camada cuida da transmissão física dos dados através da rede, usando protocolos como [[Ethernet]] e Wi-FI

![[Pasted image 20250313120733.png]]

