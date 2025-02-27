# PortScanner
Repositório para desenvolvimento do Roteiro 1 de Tecnologias Hacker

### Premissas feitas:

- Ser em linguagem Python;
- Deverá possuir uma interface amigável e de fácil utilização (user-friendly interface); (1 ponto)
- Permitir o escaneamento de um host ou uma rede; (1 ponto)
- Permitir inserir o range (intervalo) de portas a serem escaneadas; (1 ponto)
- Além da função de escaneamento, espera-se que seu código relacione as portas Well-Know Ports e seus serviços, e apresente em sua saída (imprimir) o número da porta e o nome do serviço associado. (2 pontos)

Requisitos adicionais para o escaneamento de portas:
1. Detecção do estado das portas (1 ponto)
O código deve indicar se uma porta está aberta, fechada ou filtrada (usando respostas como RST, TIMEOUT, etc.).
2. Opção de escaneamento UDP (2 pontos)
Implementar escaneamento de portas UDP além de TCP.
3. Detecção do sistema operacional via banner grabbing (2 pontos)
Permitir que a ferramenta tente identificar o sistema operacional pelo banner de resposta.