# Tipos de Dados

### Estados no Hardware
- 0 = Nível Lógico Baixo
- 1 = Nível Lógico Alto
- X (Desconhecido): Ocorre quando há múltiplos drivers forçando valores diferentes <br>
   no mesmo fio, ou registradores não inicializados.
- Z (Alta Impedância) = Fio flutuando, fisicamente desconectado

---
### Logic:
⭢ Tipo de 4 estados (0, 1, X, Z). Usado para praticamente tudo no design de Hardware, <br>
O compilador é inteligente o suficiente para inferir se um logic vai virar um fio <br>
físico ou um flip-flop (memória), dependendo de como você escreve o bloco de código

• *Obs: Logic é que ele não permite múltiplos drivers (várias fontes gravando nele ao mesmo tempo).*

---
### Wire:
⭢ Tipo de 4 estados (0, 1, X, Z). Representa conexões físicas reais, os fios. <br>

• *Obs: Usa-se hoje especificadamente quando se precisa de uso de múltiplos drivers,<br>
ou seja, vários periféricos podem escrever no mesmo barramento).*
