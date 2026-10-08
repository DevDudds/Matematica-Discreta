1.3. Caso "Por absurdo":

(c) Entre três números reais, um deles sempre é maior ou igual á média 
aritmética de todos.

### 1.4. Caso "[...] se e somente se, [...]":
	p <=> q == (p => q) ^ (q => p)
	
(a) Os inteiros x e y são ímpares se, e somente se, xy é ímpar.

Dem.: ( => )

```
	xy = (2k+1) (2r+1)
	xy = 2k2r+2k+2r+1
	xy = 2(k2r+k+r) + 1
```

Pondo k2r+k+r = w:

	xy = 2w + 1

(a) ( <= ) Provando a reciproca:
Diante do já realizado na etapa anterior: xy = 2w + 1
```
	xy = 2w + 1
	xy = 2(k2r+k+r) + 1
	xy = 2k2r+2k+2r + 1
	xy = (2k + 1) (2r + 1)
```

Assim, X ou Y são um dos dois do outro membro, que estão no formato de um ímpar.

### 1.5. Caso "Demonstração de Existência e Unicidade":

Existência -> Existe um único x [] P(x)
Unicidade -> Suponha-se que existam dois possíveis e conclui-se que são o mesmo

#### Mostre que: se a, b pertence aos Reais, com a dif de 0, então existe um único r pertencente aos R tal que a*r+b = 0.

```
	ar+b = 0, ar'+b = 0 => ar+b = ar'+b
	ar = ar'
	r = r'
```

### 1.6. Caso "Demonstração de falsidade por contraexemplo":

(a) Para todo n primo, o inteiro 2^n - 1 também é primo?

Pelo método do C-E (Contraexemplo), temos: 
1 - K = 2² - 1 = 3, para todo K pertencente aos Inteiros.
2 - K = 2³ - 1 = 7,
3 - K = 2⁵ - 1 = 31
4 - K = 2⁷ - 1 = 127,
5 - K = 2¹¹ - 1   = 2047 = 23 * 89, Portando, temos um caso que resultou em um número composto. ( Contra-Exemplo )

(b) Todo inteiro positivo é a soma dos quadrados de três inteiros?

Pelo método do C-E, temos:
1 - 1 = 1² + 0² + 0²
2 - 2 = 1² + 1² + 0²
3 - 3 = 1² + 1² + 1²
4 - 4 = 2² + 0² + 0²
5 - 5 = 2² + 1² + 0²
6 - 6 = 2² + 1² + 1²
7 - 7 = 2² + 1² + x² ( Contra-Exemplo )
Portando, temos um cenário em que não existe um X pertencente aos inteiros para este caso.

(c) Se n é um inteiro e 4n é par, então n é par?

(d) O produto de dois números irracionais é um número irracional?