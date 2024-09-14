# Compilador X Interpretador
## Compilador
  - Traduz o código fonte inteiro antes da execução;
  - Gera um arquivo executável que pode ser executado diretamente no sistema operacional;
  - Linguagens compiladas tendem a ter melhor desempenho;
  - Geralmente exige mais memória;
  - Compila somente se o código não tiver erros;
  - Não é necessária uma nova tradução cada vez que o programa for executado, pois todos os comandos foram guardados em um novo programa completo;
      - A cada modificação é necessário traduzir novamente todo o código;
  - Possui etapas de análise e otimização;
  - A linguagem compialda precisa fazer uma tradução específica para cada platadorma destinada;
  - C, C++, Swift, Fortran, Rust;
  #### Compiladores para C:
    - GNU Compiler Collection gcc/g++;
    - Microsoft Visual C++ msvc/cl;
    - Intel C++ Compiler icpx/icx;
## Interpretador
  - Traduz o código conte linha por linha durante a execução;
  - Não é criado nenhum tipo de arquivo;
  - Quando a segunda instrução é trabalhada, a primeira é perdida, isto é, apenas uma instrução fica na memória em cada instante;
  - Detecta erros no momento em que eles passam pelo interpretador, podendo facilitar o processo de debugar;
  - São mais flexíveis e portáteis, não dependendo de um compilador específico para cada plataforma;
  - Python, Ruby, PHP, JavaScript;
  #### Interpretadores para Python:
    - CPython;
    - PyPy - implementação JIT;
    - Jython - implementação do Python na JVM;
  #### Interpretador interativo:
    - Console interativo ou shell;
    - REPL (read-evaluate-print-loop);
    - Executa comandos lidos do dispositivo de entrada padrão, sem necessidade de criação de um arquivo;
    - Usado para testar comandos, fazer cálculos rápidos ou depurar pedaços menores de código;
    - Exemplos: shell Python e shell Bash;
#### Java é uma linguagem híbrida
- Tem um compilador que converte seu código para bytecode e em sequência é lido para JVM (Java Virtual Machine), que é um interpretador, para então ser executado pelo CPU.
- *JIT (Just-in-Time)*: técnica utilizada por alguns intepretadores para melhorar o desempenho, em que partes do código são compiladas em tempo de execução e otimizadas para a arquitetura específica do computador;


### Referências
https://www.dca.fee.unicamp.br/cursos/EA876/apostila/HTML/node37.html

http://www.inf.ufsc.br/~j.barreto/cca/arquitet/arq4.htm

https://blog.geekhunter.com.br/metodos-de-traducao-compiladores-ou-interpretadores/#O_que_e_interpretador_de_codigo

https://cursos.alura.com.br/forum/topico-compilador-vs-interpretador-nas-linguagens-de-programacao-314787

https://www.oficinadanet.com.br/artigo/1527/diferencas_entre_compiladores_e_interpretadores

https://schoolcode.com.br/linguagens-compliladas-interpretadas-e-hibridas/

https://terminalroot.com.br/2023/07/lista-dos-10-melhores-compiladores-c-cpp.html

https://learn.microsoft.com/pt-br/visualstudio/python/installing-python-interpreters?view=vs-2022#review-python-interpreters

https://eduardostuart.pro.br/artigos/node-dicas-intermediarias-parte-1-repl/index.html

https://pt.wikipedia.org/wiki/REPL




