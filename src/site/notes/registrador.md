---
{"aliases":["registradores"],"dg-publish":true,"dg-show-local-graph":true,"dg-home":null,"permalink":"/registrador/","dgShowLocalGraph":true,"dgPassFrontmatter":true,"created":"2025-12-16T19:01:43.363-03:00","updated":"2025-12-16T19:41:58.949-03:00"}
---

Pequena quantidade de memória encontrada dentro da [[CPU\|CPU]]

Quem acessa os registradores?
	[[Unidade Lógica e Aritmética\|ULA]] ou [[Unidade de controle\|Unidade de controle]]

Seu conteúdo pode ser acessado mais rapidamente (pela unidade de controle ou ULA) do que qualquer outra forma de armazenamento disponível

# Tipos de registradores
---
- **Registradores de dados** -> usados para armazenar valores numéricos (inteiros ou ponto flutuante)
- **Registradores de endereço** -> usados para armazenar endereços ou apontadores para endereços (ex indices em um array)
- **Registradores condicionais** -> usados para armazenar valores verdadeiro ou falso, e podem ser usados pra determinar a execução de uma operação
- **Registradores de propósito geral** -> armazenam dados e/ou endereços
- **Registradores de ponto flutuante** -> armazenam valores de ponto flutuante
- **Registradores especiais** -> armazenam o estado do programa
	- e.x. contador de programa, apontador de pilha, registrador de status ou registrador de flag (indica se algo aconteceu durante uma operação) (zero, valor negativo, bit de paridade, overflow, etc)

O que é um apontador de pilha? 
	- Todo programa tem uma pilha
	- a pilha é usada quando vc faz uma chamada aos procedimentos
	- o apontador de pilha literalmente aponta pra pilha