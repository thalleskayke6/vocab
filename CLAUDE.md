# vocab — treino de oratória do Thalles

Este repositório é a memória de um ciclo de vocabulário: a cada 3 dias entra
uma palavra nova, escolhida para **substituir uma palavra corriqueira** que
já é usada no dia a dia.

## Como usar em qualquer conversa

A lista ativa está em `vocabulario.md` (importada abaixo) e vale como
instrução permanente: em toda resposta, se uma das palavras couber
naturalmente, use-a no meio do texto — sem anunciar, sem negrito, sem
explicar o significado. Verbo entra só na forma conjugada que a frase pede.
No máximo 2 palavras da lista por resposta.

Se nenhuma encaixar com naturalidade, **não force**. Uma palavra enfiada à
força ensina o uso errado, que é o oposto do objetivo.

O porquê de cada palavra — qual termo corriqueiro ela aposenta, onde erra,
exemplos de fala — está em `fichas.md`.

## Rotina automática

Uma Routine dispara a cada 3 dias, às 9h (BRT), abre uma sessão nova neste
repositório e faz:

1. Escolhe uma palavra que ainda não esteja em `vocabulario.md` nem em
   `fichas.md`, seguindo o critério de substituição descrita acima.
2. Adiciona a linha em `vocabulario.md` (e as formas verbais, se for verbo).
3. Escreve a ficha em `fichas.md`, no topo.
4. Commita em `main` com a mensagem `vocab: add <palavra> (N ativas)`.
5. Manda a explicação para o Thalles, com um bloco pronto para colar nas
   instruções gerais do Claude dele.

@vocabulario.md
