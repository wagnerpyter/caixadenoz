# Memória

A memória da Caixa de Nós não é uma linha contínua. Cada acontecimento importante pode sobreviver em três traduções: dado, deformação e retorno.

## Identificador de evento

Todo conjunto de registros deve possuir um identificador estável, por exemplo `0001-linha-azul`. O identificador liga as formas sem obrigá-las a concordar.

```text
memoria/eventos/0001-linha-azul/
├── runtime.log.md
├── glitch.md
├── fragmento.md
└── estado.json
```

## Log runtime

Registra horário, localização, sensores, observações e confiança nos dados. Não deve transformar uma leitura em significado.

## Literatura de glitch

Registra a falha produzida quando a percepção excede as categorias disponíveis. Pode conter cortes, repetição, código, corpo, ruído e substituições de palavras.

## Fragmento ritual

Registra o retorno descontínuo do acontecimento. Pode aparecer como bloco, célula, frase recorrente, imagem, silêncio ou espera. Não resolve o que retorna.

## Proveniência

Cada camada deve indicar sua origem: sensor, observação, adaptação textual, imagem, áudio, commit ou intervenção externa conhecida. Quando a origem não puder ser determinada, essa ausência deve ser registrada sem preenchê-la com uma hipótese apresentada como fato.
