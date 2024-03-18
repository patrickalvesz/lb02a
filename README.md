# Lab02a - Processos - 04N12
  Laboratório lab02a com os exercicios em c, feitos em AWS, e as duas perguntas respondidas nesse readme.txt.

# Grupo:
  Nome: Patrick Alves Gonçalves – 42214440

  Nome: Nicholas dos Santos Leal – 42210771

  Nome: Gustavo Ibara - 42210720

# 1) Rode o programa anterior para valores grandes de n. As mensagens sempre estarão ordenadas pelo valor de i?
  Quando executamos o programa com valores grandes de n, a ordem das mensagens não vai ser ordenada pelo valor de i. Porque os processos filhos são executados juntos e podem imprimir as mensagens em qualquer ordem. Então, a saída provávelmente não será ordenada.

# 2) O que acontece se o programa anterior escrever as mensagens para sys.stdout, usando print, ao invés de para sys.stderr?
  Se o programa escrever as mensagens para sys.stdout usando print, as mensagens serão direcionadas para a saída padrão.

  Com isso, a saída será mais ordenada. Os processos filhos imprimirão as mensagens na ordem em que foram criadas, resultando em uma saída ordenada.

  Ou seja, sys.stdout será mais ordenado que sys.stderr.
