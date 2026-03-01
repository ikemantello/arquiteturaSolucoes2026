# Trade-offs Arquiteturais

## Trade-off 1: Performance vs Custo
Decisão tomada: priorizar performance.
Justificativa: o streaming de vídeo exige baixa latência e alta qualidade.
Impacto: maior custo de infraestrutura, melhor experiência do usuário.

## Trade-off 2: Escalabilidade vs Complexidade
Decisão tomada: adoção de arquitetura em microsserviços.
Justificativa: necessidade de atender milhões de usuários simultâneos.
Impacto: sistema altamente escalável, porém mais complexo de gerenciar.

## Trade-off 3: Segurança vs Usabilidade
Decisão tomada: autenticação simples com monitoramento interno.
Justificativa: facilitar o acesso do usuário.
Impacto: melhor usabilidade, exigindo maior controle contra uso indevido.
