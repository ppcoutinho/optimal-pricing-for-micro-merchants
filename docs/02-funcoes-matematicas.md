# Funções matemáticas escolhidas

Esta seção apresenta, de forma geral, as funções matemáticas utilizadas no projeto e o motivo de cada escolha. A aplicação delas ao problema será detalhada na modelagem matemática.

## Função exponencial

Uma função exponencial tem a forma dada por:

$$f(x) = a \cdot e^{kx}$$

onde:

- $e \approx 2{,}718$ é a base natural, uma constante matemática;
- $x$ é a variável independente (pode ser o preço, por exemplo);
- $a$ é o valor inicial da função, isto é, seu valor quando $x = 0$, pois $f(0) = a \cdot e^{0} = a$;
- $k$ é a constante de crescimento ou decaimento: se $k > 0$, a função cresce; se $k < 0$, a função decresce e se aproxima de zero, sem nunca atingi-lo. Quanto maior $|k|$, maior a velocidade com que a função varia. Além disso, a cada unidade que $x$ aumenta, o valor da função é multiplicado pelo fator $e^{k}$, isto é, varia sempre na mesma proporção.

*Por que utilizaremos a função exponencial:* a quantidade vendida diminui à medida que o preço aumenta, e essa queda é proporcional: cada real a mais afasta sempre a mesma porcentagem de clientes. Além disso, a demanda nunca pode ser negativa. O decaimento exponencial atende às duas exigências.

## Função logarítmica

A função logarítmica natural é dada por:

$$g(y) = \ln(y), \quad y > 0$$

Ela é a **função inversa da exponencial** de base $e$, ou seja:

$$y = e^{x} \iff x = \ln(y)$$

Em outras palavras, $\ln(y)$ responde à pergunta: *"a que expoente devo elevar $e$ para obter $y$?"*

onde:

- $y$ é a variável independente, que precisa ser positiva ($y > 0$), já que $e^{x}$ nunca resulta em zero ou em valores negativos;
- $\ln$ indica o logaritmo natural, isto é, o logaritmo na base $e \approx 2{,}718$.

*Por que utilizaremos a função logarítmica:* no modelo de demanda, o preço aparece no expoente da função exponencial. Sempre que precisarmos descobrir um valor que está nesse expoente, o logaritmo será a ferramenta necessária. Ele será usado em dois momentos: na **calibração do modelo**, para estimar a sensibilidade dos clientes ao preço a partir de vendas reais observadas, e no **cálculo de metas**, para determinar quanto o preço deve variar para atingir um aumento desejado nas vendas.