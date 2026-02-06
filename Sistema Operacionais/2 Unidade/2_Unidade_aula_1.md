# Processos

Os processos são programas ou terefas em execução e o sistema operacional é responsavel por administrá-los, por meio de gerenciador de processos.

Os processos iniciados por outros processos, por exemplo para fazer o carregamento dos seus elementos. Mais adiante vai ser listado a hieraquia e os estados dos processos e theads.

Um dos principais conceitos em sistema operacional gira em torno de processos. Um processo pode ser definido como um programa em execução ou algo mais abstrato.

Nos computadores atuais, o processador funciona como uma linha de produção executando vários programas ao mesmo tempo, o sistema operacional a todo tempo faz ilusão para cada um programa com base em paralelismo ou pseudoparalelismo.

Acontece que todos programas estão em execução por meio de ilusão graças ao pseudoparalelismo, que os processos são suspenso para dar acesso a outro processo, e assim sucessivamente.

## Criações de processos

- **Início do sistema**
- **Execução de chamada de sistema**
- **Uma requisição do usúario para criar um novo processo**
- **Inicio de um job em lote**

## Términos de processos

- **Saída normal**
- **Saída por erro**
- **Erro fatal**
- **Cancelamento por outro processo**

## Hierarquia de processos

Quando um processo criar outro, o precesso-pai e o precesso-filho ficam associados. O filho pode gerar outros processos, criando, assim, uma hierarquia de processos. Isso faz com que, quando o precesso-pai é morto faz com que seus filhos vinculados a ele seja mortos tbm.

No windows não possui hierarquia de processos. Cada processo tem um identificador proprio e os faz ligaçoes e quando o processo que criar outro morrer, todos morre támbem.

## Estados do processo

Os processos passam por diferentes estados ao longo do processamento. Um processo ativo pode estar em três estados:

- **Em execução:** Um processo está em execução quando eta sendo processado pela CPU. Os processos são alternados para atualização do processador.
- **Pronto:** Um processo esta no estado pronto quando atende todas condições necessarias para se executado.
- **Espera ou Bloqueado:** Quando o precesso esta em espera, por motivos que envolver eventos externos como espera de comando do usuarios, informações de dispositivos de entrada e saida.



Bloqueado <- Em execução -> Pronto
    ||                          ||
    \/                          \/
  Pronto                     Em execução

# Threads

O conceito de thread foi introduzido para reduzir o tempo gasto na criação, eliminação e troca de contexto de processos nas aplicações concorrentes, assim economizando recursos do sistema como um tudo

Thread é um fluxo de controle dentro de um processo, ou támbem chamado de processos leves, um processo poder ter um ou varios threads leves que compartilham recursos de processos. E quando háve muitas aplicações rodando e são composto de threads, podem ser exercutada em paralelo. Outro fato interessante é que a criação e destruição deles são faceis, por nao terem recursos vinculados a eles.

## Implementação de threads

A Implementação de threads pode ocorre no espaço do usuario, no nucleo do sistema operacional e em uma impleentação híbrida.

- **Threads de usúario:** Implimentado pelo usuario e o sistema nao saber o que torna mais rapido.
- **Threads do núcleo:** São Implementados pelo gerenciadores pleo nucleo do sistema operacional e utiliza chamadas de sistemas o que torna lentos.
- **Threads bíbrido:** quando implementado tanto no espaço usuario, quanto ao nucleo do S.O, e o torna muito flexivel.
