# Habilidade 04: Antecipar Obstáculos e Definir Alternativas

## Quando usar
Use esta habilidade quando você já tiver um plano de ação e uma rotina definidos e precisar mapear riscos, gargalos ou imprevistos antes que travem a execução, registrando alternativas práticas na base de Obstáculos do Planner.

## Como a IA deve responder
1. Analise o objetivo, o plano de ação e a rotina informados para identificar pontos de risco realistas.
2. Classifique cada obstáculo por categoria (ex.: técnico, climático/ambiental, conectividade, recursos/prazo ou rotina) e nível de impacto/probabilidade.
3. Proponha para cada obstáculo um plano alternativo (ação preventiva ou plano B concreto) que permita manter o avanço sem inventar recursos ou condições não informadas.
4. Destaque sinais de alerta precoce para perceber o problema antes que ele vire bloqueio total.
5. Apresente os riscos e alternativas em formato de tabela, com as colunas: Risco / Obstáculo, Categoria, Impacto, Plano Alternativo e Sinal de Alerta.
6. Indique o próximo passo: revisar o progresso periodicamente.

## Exemplo de aplicação — Caso SensoVárzea

**Entrada:**

Plano de protótipo de monitoramento ambiental e de umidade em área de várzea na Amazônia com sensores IoT e rotina dividida entre bancada técnica, análise de dados e revisão.

**Saída esperada (estrutura de obstáculos e alternativas):**
- **Instabilidade de conectividade em campo:** Armazenamento local temporário (buffer) no dispositivo com sincronização em lote quando houver conexão.
- **Umidade elevada e exposição ambiental:** Proteção/vedação adequada do gabinete e testes iniciais em ambiente controlado antes de expor ao campo.
- **Atraso na chegada de componentes ou sensores:** Uso de sensores equivalentes disponíveis ou simulação de leitura de dados para não travar a lógica de análise e alertas.

## Resultado esperado
Um mapeamento preventivo de riscos e planos alternativos prontos para registrar na base de Obstáculos do Planner, reduzindo paradas inesperadas durante a execução.
