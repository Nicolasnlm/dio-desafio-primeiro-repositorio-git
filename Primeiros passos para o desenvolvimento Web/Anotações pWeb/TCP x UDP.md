# TCP/IP

#### Transmission Control Protocol - Protocolo de Controle Transmissão 

É um protocolo que organiza os dados, para onde serão encaminhado, quem é o emissor e alguns outros recusos como cabeçalho, etc...

#### Internet Protocol

O **TCP/IP** usa um modelo de camadas, sendo assim, a comunicação precisa passar por quatro passos antes de iniciar a transmissão de dados:

**1.Camada Física**: Placas de rede, wireless, por onde a conexão irá chegar

**2.Rede:** IP, uma rede configurada para que a conexão aconteça

**3.Transporte**: TCP, UDP

**4.Aplicação**: FTP - Apenas envio de arquivos, SMTP - emails e HTTP - Requisição de sites na Internet

### TCP x UDP

- **UDP**

   Bastante rápido, porém não confiável, não se dá para saber quem está recebendo os dados. Um ponto positivo do **UDP**, são atividades como **Livestreams**, já que não é necessário avisar a plataforma de Streams que você está assistindo a Live por exemplo.

- **TCP**

Um pouco mais lento que o UDP, existe um conceito chamado *Handshake*,     onde o ponto **A** solicita o envio de pacotes ao ponto **B** e ambos fazem questão de saber de todos os pacotes foram enviados corretamente. Além de saber o que está mandando, quem está mandando, o porque disso, etc... Esse tipo de conexão permite uma maior ordenação dos dados e integridade dos mesmos, enquanto o UDP apenas atira para todo lado.

