-------------- Aula #05 --------------------
-- Identificadores
	* Podem começar com letra, $ ou _
	* Não podem começar com números
	* É possível usar letras ou números
	* É possível usar acentos e símbolos
	* Não podem conter espaços
	* Não podem ser palavras reservadas

-- Dicas
	* Maiúsculas e minúsculas fazem diferença
	* Tente escolher nomes coerentes para as variáveis
	* Evite se tornar um 'programador alfabeto'  ou um 'programador contador'

-- Data types
	* number
		* Infinity
		* NaN
	* string
	* boolean
	* null
	* undefined
	* object
		* Array
	* function

Comandos:
  typeof
Descrição: Diz o tipo de variável

-------------- Aula #06 --------------------
Comando para trocar o ponto por vírgula:
  variável.toFixed(2).replace('.', ',')

Comando para mudar a moeda:
  variável.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})


-------------- Aula #07 --------------------
-- Operadores:
	-- Aritméticos
		* 5 + 2 -> 7         Adição
		* 5 - 2 -> 3         Subtração
		* 5 * 2 -> 10         Multiplicação
		* 5 / 2 ->   2.5      Divisão Real
		* 5 % 2 ->  1       Divisão Inteira
		* 5 ** 2 ->   25      Potência   -> Nova no JS
		* Ordem de precedência:
		*  ( )
		* **
		* *  /  %
		* +  -
  -- Atribuição
		-- Atribuição Simples:
			* var a = 5 + 3       -> 8
			* var b = a - 5       -> 3
			* var c = 5 * b ** 2       -> 45
			* var d = 10 - a / 2       -> 6
			* var e = 6 * 2 / d       -> 2
			* var f = b % e + 4 / e       ->3
		-- Auto Atribuições:
			-- Completa:
				* var n = 3
				* n  = n + 4
				* n = n - 5
				* n = n * 4
				* n = n / 2
				* n = n ** 2
				* n = n % 5         -> 1
			-- Simplificada:
				* var n = 3
				* n  += 4
				* n -= 5
				* n *=4
				* n /= 2
				* n **= 2
				* n %= 5         -> 1
			-- Incremento:
				* var n = 5
				* n ++      -> 6
				* n --      -> 5
	-- Relacionais
		* >
    * <
    * >=
    * <=
    * ==
    * !=
      -- Identidade
        * ===
  -- Lógicos
    * !     --- negação
    * &&     --- conjunção
    * ||     --- disjunção

    -- Ordem de precedência dos OPERADORES LÓGICOS --
      * !
      * &&
      * ||
	-- Ternário
    * ?
    * :
      - Exemplo:  media >= 7 ? "Aprovado" : "Reprovado"

Ordem de precedência de TODOS OS OPERADORES:
  * Aritméticos
  * Relacionais
  * Lógicos
  * Ternário

-------------- Aula #09 --------------------

Árvore DOM:
	src("../_prints/Arvore-DOM")
Selecionando:
	src("../_prints/Arvore-DOM/Arvore-DOM-selecionando/")

-------------- Aula #09 --------------------

Alguns Eventos DOM:
	src("../_prints/Arvore-DOM")

a.addEventListener('click', clicar) 	<!-- Ouvidores de Eventos -->