# Tipos de Dados

### Estados no Hardware
- 0 = Nível Lógico Baixo
- 1 = Nível Lógico Alto
- X (Desconhecido): Ocorre quando há múltiplos drivers forçando valores diferentes <br>
   no mesmo fio, ou registradores não inicializados.
- Z (Alta Impedância) = Fio flutuando, fisicamente desconectado

---
### logic:
⭢ Tipo de 4 estados (0, 1, X, Z) e sem sinal por padrão. Usado para praticamente <br>
tudo no design de Hardware. O compilador é inteligente o suficiente para inferir <br>
se um logic vai virar um fio físico ou um flip-flop (memória), dependendo de como <br>
você escreve o bloco de código.

• *Obs: Logic é que ele não permite múltiplos drivers (várias fontes gravando nele ao mesmo tempo).*

---
### wire:
⭢ Tipo de 4 estados (0, 1, X, Z). Representa conexões físicas reais, os fios. <br>

• *Usa-se hoje especificadamente quando se precisa de uso de múltiplos drivers ou seja, <br>
vários periféricos podem escrever no mesmo barramento.*

---
### integer:
⭢ Tipo de 4 estados (0, 1, X, Z) com sinal e 32 bits. Representa conexões físicas reais, os fios. <br>

• *Usado principalmente para contadores em loops*

---
### time:
⭢ Tipo de 4 estados (0, 1, X, Z) sem sinal e 64 bits. <br>

• *Serve para calcular o tempo simulado, usado em testbenches. Usado principalmente para calcular<br>
atrasos lógicos e temporização*

---
### bit:
⭢ Tipo de 2 estados (0, 1) <br>

• *Exelente para criar sinalizadores em testsbenches*

---
### byte:
⭢ Tipo de 2 estados (0, 1) com sinal e 8 bits <br>

• *Ótimos para ler dados de arquivos ou simular memórias pequenas*

---
### shortint:
⭢ Tipo de 2 estados (0, 1) com sinal e 16 bits <br>

---
### int:
⭢ Tipo de 2 estados (0, 1) com sinal e 32 bits <br>

• *Substituto do integer em loops em testbenches, pois simula mais rápido por ter<br>
apenas dois estados.*

---
### longint:
⭢ Tipo de 2 estados (0, 1) com sinal e 64 bits <br>











