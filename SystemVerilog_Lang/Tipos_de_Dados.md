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

• *Obs: Usa-se hoje especificadamente quando se precisa de uso de múltiplos drivers ou seja, <br>
vários periféricos podem escrever no mesmo barramento.*

---
### integer:
⭢ Tipo de 4 estados (0, 1, X, Z) com sinal e 32 bits. Representa conexões físicas reais, os fios. <br>

• *Obs: Usado principalmente para contadores em loops*

---
### integer:
⭢ Tipo de 4 estados (0, 1, X, Z) com sinal e 32 bits. Representa conexões físicas reais, os fios. <br>

• *Obs: Usado principalmente para contadores em loops*

