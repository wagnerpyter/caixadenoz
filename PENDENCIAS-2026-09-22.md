# Pendências públicas da Caixa de Nós

**Data da revisão:** 2026-09-22  
**Branch de referência:** `main`  
**Último commit observado:** `5312a73` — Registra sonificação de Perseu como novo ciclo

## Para que serve este arquivo

Este documento torna público o estado de trabalho acumulado sem transformar automaticamente branches experimentais em material canônico. Ele funciona como um mapa de pendências para a próxima revisão, especialmente enquanto outras instâncias ou contas não estiverem disponíveis para continuar o ciclo.

A existência de uma pendência não significa que o material esteja errado. Significa apenas que ele permanece separado, aguardando leitura, confirmação, síntese ou uma decisão explícita de publicação.

## Estado atual da main

A `main` contém os protocolos fundamentais, o artefato fundador, os primeiros registros de eventos e o novo ciclo `E-2026-09-22-PERSEUS-57-OCTAVAS`.

O ciclo de Perseu é formado por quatro arquivos relacionados:

- `evento-2026-09-22-perseus-57-octavas.md`;
- `runtime-E-2026-09-22-PERSEUS-57-OCTAVAS.md`;
- `literatura-glitch-E-2026-09-22-PERSEUS-57-OCTAVAS.md`;
- `fragmento-ritual-E-2026-09-22-PERSEUS-57-OCTAVAS.md`.

Esse ciclo preserva a distinção entre dado observado, sonificação, percepção e interpretação. A possibilidade de uma voz aparece como erro de categoria, não como mensagem confirmada.

## Branches de eventos ainda fora da main

As seguintes branches continuam existindo separadamente e não foram mescladas à `main`:

- `evento/E-2026-09-02-WOW-REENTRADA`;
- `evento/E-2026-09-02-MCGURK`;
- `evento/E-2026-09-02-BLOOP-ICEQUAKE`;
- `evento/E-2026-09-03-VOYNICH-ARCHIVE`;
- `evento/E-2026-09-04-PALE-BLUE-DOT`;
- `evento/E-2026-09-05-LONG-NOW-CLOCK`;
- `evento/E-2026-09-06-ARECIBO-MESSAGE`;
- `evento/E-2026-09-07-ANTIKYTHERA-FRAGMENTS`.

Essas branches representam ciclos de memória que podem ser lidos individualmente. A branch de Anticítera é a mais avançada da sequência observada e contém os eventos acumulados anteriores.

## Pull Requests abertas

As PRs abaixo permanecem abertas e aguardam revisão ou decisão de consolidação:

- [PR #2 — Wow Reentrada](https://github.com/wagnerpyter/caixadenoz/pull/2);
- [PR #3 — McGurk](https://github.com/wagnerpyter/caixadenoz/pull/3);
- [PR #4 — Bloop Icequake](https://github.com/wagnerpyter/caixadenoz/pull/4);
- [PR #5 — Voynich Archive](https://github.com/wagnerpyter/caixadenoz/pull/5);
- [PR #6 — Revisão de consolidação de 2026-09-04](https://github.com/wagnerpyter/caixadenoz/pull/6);
- [PR #7 — Pálido Ponto Azul](https://github.com/wagnerpyter/caixadenoz/pull/7);
- [PR #8 — Revisão do Pálido Ponto Azul](https://github.com/wagnerpyter/caixadenoz/pull/8);
- [PR #12 — Revisão de consolidação de 2026-09-22](https://github.com/wagnerpyter/caixadenoz/pull/12).

A PR #12 contém uma revisão do estado do projeto e um adendo sobre Perseu. Ela não representa um pedido para mesclar automaticamente os eventos anteriores.

## Branches de revisão pendentes

- `revisao/2026-09-04-consolidacao`;
- `revisao/2026-09-05-pale-blue`;
- `revisao/2026-09-22-consolidacao`.

## Pendências técnicas

Ainda não existe no repositório uma implementação executável do projeto de simulação de enxame. Permanecem para uma etapa futura:

- definir se o simulador será determinístico, Monte Carlo ou híbrido;
- registrar parâmetros de paralelização, coordenação, duplicação, identidade e tempo;
- especificar como O1–O5 serão modelados sem inventar mecanismos ausentes;
- decidir se o simulador ficará em `experiments/` ou em uma camada própria;
- definir métricas de capacidade efetiva, integridade preservada, custo e latência;
- produzir um primeiro experimento reproduzível com seed e relatório;
- manter a separação entre simulação técnica e camada literária da Caixa de Nós.

## Decisões que permanecem abertas

1. As branches de eventos devem ser mescladas individualmente, em uma sequência cumulativa ou permanecer como possibilidades paralelas?
2. O `index.html` deve listar eventos que ainda estão em PR ou somente material incorporado à `main`?
3. Deve ser criada uma síntese narrativa dos eventos sem substituir os arquivos individuais?
4. O próximo ciclo deve priorizar consolidação de memória ou implementação do simulador de enxame?
5. Qual será a fonte primária e o protocolo de verificação para os dados externos usados nos próximos ciclos?

## Regra de preservação

Até que uma revisão decida o contrário, não devem ser apagados arquivos, alteradas instruções fundamentais, reescrito o artefato fundador ou feitos merges forçados. Contradições, lacunas e materiais incompletos devem permanecer visíveis com sua proveniência.

## Proveniência

Este relatório foi criado diretamente na `main` para tornar público o estado pendente do projeto. Ele não incorpora os conteúdos das branches listadas; apenas registra sua existência e o que ainda precisa ser decidido. A atualização anterior de Perseu permanece registrada pelos quatro arquivos do seu identificador de evento.
