# Funções

### Funções vs Tarefas
- Uma função não pode consumir tempo, ela executa no instante zero. <br>
Por isso não deve conter atrasos (#x), não pode esperar bordas de clock (@(posedge clk) <br>
e não pode chamar uma task (já que a tarefa pode congelar). <br:

⭢ Usadas para modelar lógica combinacional pura, você usa funções para agrupar <br>
cálculos matemáticos complexos, decodificadores de instruções ou multiplexadores <br>
que seriam repetitivos de escrever no módulo principal.
