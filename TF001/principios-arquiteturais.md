# Princípios Arquiteturais

## Separação de Responsabilidades
A Netflix utiliza uma arquitetura baseada em microsserviços hospedados em nuvem.

Principais camadas identificadas:
- Camada de apresentação: aplicações web, mobile e Smart TV
- API Gateway: responsável por direcionar requisições
- Microsserviços: autenticação, catálogo, recomendação, histórico, pagamentos
- Camada de dados: bancos de dados distribuídos
- CDN: distribuição de conteúdo de vídeo

Cada componente possui responsabilidade específica, facilitando manutenção e escalabilidade.

## Coesão
A coesão do sistema é alta, pois cada microsserviço executa uma função bem definida.
Exemplos:
- Serviço de autenticação trata apenas login e segurança
- Serviço de recomendação analisa comportamento do usuário
- Serviço de streaming cuida apenas da entrega do vídeo

Isso facilita a evolução e manutenção do sistema.

## Acoplamento
O acoplamento entre os componentes é baixo, pois a comunicação ocorre por meio de APIs bem definidas.

Impactos:
- Falhas isoladas não comprometem todo o sistema
- Atualizações podem ser feitas de forma independente
- Aumenta a complexidade de monitoramento
