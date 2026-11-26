# Habilidade 06: Analisar Viabilidade e Priorização

## Quando usar
Use esta habilidade quando você tiver ideias, funcionalidades, cenários de implantação ou frentes de trabalho e precisar avaliar sua viabilidade prática antes de assumir compromissos ou alocar tempo e recursos.

## Como a IA deve responder
1. Avalie a viabilidade sob dimensões objetivas relevantes ao contexto informado (ex.: viabilidade técnica, disponibilidade de tempo/rotina, recursos/infraestrutura e operação/campo).
2. Diferencie claramente o que é viável agora, o que exige condições adicionais e o que apresenta inviabilidade ou alto risco no momento.
3. Não invente custos, prazos, disponibilidade de hardware ou condições operacionais que não tenham sido informados pelo usuário. Quando faltarem informações essenciais, indique quais dados precisam ser levantados antes de concluir a avaliação.
4. Classifique as opções ou frentes avaliadas (ex.: Alta viabilidade / Priorizar agora, Viabilidade condicional / Preparar depois, Baixa viabilidade / Adiar ou descartar).
5. Apresente uma comparação estruturada (em tabela ou lista objetiva) com critérios claros e justifique cada classificação.
6. Indique o próximo passo prático (definir objetivo, ajustar plano de ação ou registrar riscos no Planner).

## Exemplo de aplicação — Caso SensoVárzea

**Entrada:**

Avaliar três frentes para o protótipo SensoVárzea: (a) estação fixa de bancada com leitura local e registro de umidade/temperatura, (b) envio automático em tempo real via rede celular em área de várzea com sinal instável e (c) modelo preditivo complexo de visão computacional e IA avançada antes mesmo de validar a coleta básica.

**Saída esperada (estrutura de análise):**
- **Priorizar agora (Alta viabilidade):** Estação de bancada com leitura de umidade/temperatura e registro de dados, pois permite validar aquisição e regras iniciais de alerta sem depender de infraestrutura externa complexa.
- **Viabilidade condicional (Preparar depois):** Envio automático em tempo real em campo, condicionado à verificação de conectividade/energia e ao uso de armazenamento local de contingência.
- **Adiar ou descartar neste ciclo (Baixa viabilidade no momento):** Modelos complexos de visão computacional/IA antes da base de dados estável, pois aumentam a complexidade e o risco sem validar primeiro o fluxo essencial.

## Resultado esperado
Uma avaliação clara e fundamentada de viabilidade e priorização, evitando sobrecarga de escopo e direcionando o foco para o que é executável no estágio atual.
