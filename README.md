# Projeto Elo Cash

### Union Squad! – Juliana Lima, Daniel Rocha, Letícia Fiorito e Everton Arruda

#### **Descrição**

Criamos um aplicativo que permite o usuário navegar e pesquisar estabelecimentos ao seu redor que estejam oferecendo cashback (e que aceitem a bandeira Elo).

#### **Solução**

No modelo de negócio que idealizamos, inicialmente haveria um crescimento inorgânico, com a Elo reduzindo as tarifas de cartão para incentivar com que os estabelecimentos aderissem à política de cashback. Após este período de adesão dos comerciantes, a contrapartida seria o direcionamento de novos clientes (incentivados pelo cashback) ao estabelecimento, de modo que o restaurante teria que arcar com os custos de manter o cashback (ou optar por cessá-lo).

#### **Tecnologias**

Além de mais de uma tecnologia de georreferenciamento, utilizamos criptografias das chaves de acesso, conexão com o mecanismo de transferências (para pagamento e cashback) da Elo, além da tecnologia de cashless para reduzir a fricção na hora da compra, com o pagamento por meio de QR Code.

#### **APIs utilizadas**

1. Geocodign and Search - **Here**: utilizada para procurar a localização do usuário, bem como estabelecimentos ao redor
2. Isoline Routing - **Here**: utilizada para restringir a procura de parceiros a um determinado perímetro (considerando o tempo de deslocamento)
3. Hub QR Code Elo Canal Originador - **Elo**: utilizada para o pagamento de por meio de escaneamento do QR Code no celular
4. Peer-to-Peer (P2P) - **Elo**: utilizada para fazer o pagamento do produto/serviço e para efetuar as transferências de cashback entre o estabelecimento e o cliente

#### **Execução**

Como desenvolvemos o aplicativo em HTML e CSS, para executá-lo é preciso abrir o navegador do celular para visualizar a versão mobile.

#### **Informações adicionais**

Um dos elementos centrais para popularizar meios de pagamentos digitais é oferecer facilidades para pequenos e médios negócios, como MEIs, bem como dar incentivos para que os consumidores explorem as possibilidades das novas tecnologias. Por meio da nossa estratégia de cashback, é criado um efeito de rede onde os comerciantes passam a ter mais clientes, e os consumidores passam a enxergar mais vantagens na cultura cashless. Esse ciclo virtuoso é reforçado cada vez mais conforme aumenta-se o número de estabelecimentos e usuários da nossa solução, gerando um impulso para a popularização da plataforma digital da Elo.

----------
