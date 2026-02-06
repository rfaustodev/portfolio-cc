# Sistema Operacionais Monoprogramaveis e Multiprogramaveis

Os computadores estão classificados de como geral em 2 categorias de maneira que exercutam os programas.

- Sistema Monoprogramaveis: Os sistema operacionais monoprogramaveis se referem aos primeiros computadores pessoais criados em 1960. Eles exercutam único programa por vez e os recursos da máquina é totalmente distribuido para esse programa, exemplo de sistema monotarefa é o MS-DOS.

- Sistema Multiprogramaveis: Os Sistema operacionais multiprogramaveis é aquele que distribui recursos da máquina para mais de um programa, afim de que podemos exercuta mais de um programa por vez, e outro ponto importante é que o S.O não precisa alocra todo recurso em um único programa. Temos os  **Monousúarios:** onde somente um usuario tem acesso a máquina, **Multiusúarios:** pode ter mais de um usuario com acesso ao sistema.

# Sistema com Multiplos Processadores

Os sistemas com multiplos processadores, ou seja, multiplos cores.

# Sistema fortemente acoplados

## Possuem doi ou mais processaodres, compartilham a mesma memória e os depositivos de entrada/saida, e gerenciar os recursos da máquina para um controler de distribuição de recursos, e os sistemas acoplados sao classificado em:

- Simétricos: Os processadores compartilha uma única memória e utilizam o mesmo S.O. Utilizam tecnicas de paralelismo em programas, e mesmo que apareça um erro o sistema nao parar de funcionar, e 

o linux e windows suportam os sistemas simétricos.

# Sistema fracamente acoplados

## Eles funcionam de forma independente, possuindo seu sistema operacional e gerenciando seus próprios recursos como memória, CPU e dispositivos de entrada e saida. É depedente a uma rede para distribuir as atividades de processamento. E são classificados em:

- Operacionais de rede: Os Sistema Operacionais de rede são indepedente e então conectado por meio de uma rede. Dela, cada estação de trabalho ou nó possui um sistema operacional próprio e tem capacidade de processamento das suas aplicações. Eles támbem compartilha recuros como diretórios, copia de arquivos e etc.

- Operacionais distribuidos: Permitem que um programa seja dividido em partes e que cada um programa seja dividido em pates e que cada parte seja executada em nós diferente da rede.

# Drivers

É o componente responsavel para fazer as conversões de dados de diferentes tipos de dispositivos, como mouse, display, audio e etc.
