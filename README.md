# PROJETOESTATISTICA
Estatística com Python: Códigos e Exemplos
***
## ESTATÍSTICA BÁSICA E UMA INTRODUÇÃO AOS SEUS PRINCIPAIS CONCEITOS COM PYTHON

`Olá, pessoal! Sejam bem-vindos ao meu repositório GIT.`
```
Neste projeto, o principal objetivo é introduzir a Estatística usando python.
Veremos exemplos práticos e divertidos para cada assunto, além de indicar as referências.
```
***
# ESTATÍSTICA BÁSICA E UMA INTRODUÇÃO AOS SEUS PRINCIPAIS CONCEITOS
1. ### [O que é a estatística?](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#o-que-%C3%A9-a-estat%C3%ADstica-1)
2. ### [O que são os conjuntos de dados?](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#o-que-s%C3%A3o-os-conjuntos-de-dados-1)
3. ### [Quais são os ramos da estatística?](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#quais-s%C3%A3o-os-ramos-da-estat%C3%ADstica-1)
4. ### [Quais são os tipos de dados](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#quais-s%C3%A3o-os-tipos-de-dados-1)
5. ### [Gráficos](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#gr%C3%A1ficos-1)
   1. #### [Passos básicos para construir um gráfico](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#passos-b%C3%A1sicos-para-construir-um-gr%C3%A1fico)
7. ### [Medidas de posição](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#medidas-de-posi%C3%A7%C3%A3o)
8. ### [Quais são as medidas de variabilidade](https://github.com/o-allanribeiro/PROJETOESTATISTICA/tree/main#--quais-s%C3%A3o-as-medidas-de-variabilidade)

## O que é a estatística
Basicamente a estatística é a arte e a ciência que se concentra em coletar, organizar, analisar e interpretar dados. Os dados são informações coletadas por meio de vários métodos como: observações, contagens, medições ou experimentos.
***
> ### Você sabia que a estatística nasceu da política
> A palavra vem do latim e significa “estado”, pois era usada para coletar e resumir dados sobre um país. Um fato
> histórico interessante é que um dos pioneiros da estatística foi John Graunt, um comerciante inglês que, em 1662,
>  publicou “Natural and Political Observations Made upon the Bills of Mortality” (Observações naturais e políticas
> feitas sobre as contas da mortalidade). Essa obra apresentou análises de informes sobre os dados de nascimentos,
> mortes e causas das mortes, e a partir disso usou o rigor da coleta dos dados para tirar conclusões. Na época, foi
> seguido por inúmeros estudos socioeconômicos, como mortalidade, taxa populacional, dentre outros.
>
> <img src="https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/billsofmortality.png?raw=true" width="480">
>
>> Pois bem, basicamente estatística é a arte e a ciência que se concentra em `coletar, organizar, analisar e interpretar dados.`
>> Os dados são informações coletadas por meio de vários métodos como: observações, contagens, medições ou experimentos.
>> Logo, entederemos como a estatística pode ser uma amiga ou uma inimiga, dependendo de como os dados são coletados e apresentados.

## O que são os conjuntos de dados

Um conjunto de dados é um grupo de dados que se referem a algum assunto ou contexto.
Existem dois tipos de conjuntos de dados: 
- **População**

  A população é o conjunto de todos os elementos que nos interessam em uma pesquisa. 
- **Amostra**

  A amostra é um subconjunto da população, selecionado de forma aleatória ou sistemática, que representa as características da população.
  
Para o exemplo, observe a imagem:

> ![Imagens/readme/samp_popu.png](https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/samp_popu.png?raw=true)

A imagem acima demonstra o conceito de população e a amostra.
- A **população** é o conjunto de todos os elementos que são objeto de estudo, e é representada pelos círculos azuis e os vermelhos.
- A **amostra** é o conjunto de elementos selecionados para obter dados, e é representada pelos cículos vermelhos.
- A imagem indica que há diferentes formas de realizar a amostragem, e que a amostra pode ser mais ou menos representativa da população.

Um *estudo de caso* sobre uso desse conceito é:

> Imagine que queremos analisar a opinião dos eleitores brasileiros sobre um certo candidato à presidência.
> A *população* é o conjunto de todos os eleitores brasileiros.
> A *amostra* é o conjunto de eleitores que participaram da pesquisa.
>> Podemos usar diferentes métodos para escolher a amostra, e que a amostra pode ter maior ou menor similaridade com a população.
>> Essa similaridade é chamada de representatividade, e depende de fatores como o tamanho da amostra, a forma de seleção dos participantes e a margem de erro da pesquisa.

## Quais são os ramos da estatística
A estatística pode ser dividida em dois ramos principais: a `estatística descritiva e a estatística inferencial`. 
> A *estatística descritiva* é uma área que se dedica a resumir e apresentar os dados de forma visual e organizada, por meio de tabelas e gráficos. 
> Sendo assim, a estatística descritiva nos ajuda a ver as características e as tendências dos dados. No entanto, a estatística descritiva não é apenas uma forma
>  de apresentação dos dados, mas também uma forma de análise dos dados, pois permite que façamos comparações, medidas de dispersão, medidas de posição, etc.
>> Uma maneira de pensar a estatística descritiva é como uma área que utiliza técnicas para descrever e explorar os dados de apresentação dos dados, buscando extrair informações relevantes e simplificar a sua interpretação.
>
> A *estatística inferencial* é uma área que se dedica a utilizar métodos de estimativa e teste de hipóteses para fazer análises sobre a população com base na
> amostra.
> Logo, a estatística inferencial se fundamenta em uma ideia e o rigor dos métodos estatísticos. Porém, a estatística inferencial não é apenas uma forma de
> iluminar o nosso entendimento da população, mas também uma forma de avaliar a confiabilidade e a validade das nossas conclusões, pois leva em conta a
> variabilidade e a incerteza dos dados.
>> Uma forma de enxergar a estatística inferencial é como uma lâmpada, no sentido de iluminar o nosso entendimento da população com base na amostra, seguindo o
>> rigor dos métodos estatísticos.
>>
>> Outra forma de enxergar a estatística inferencial é como uma balança, no sentido de pesar as evidências a favor ou contra uma hipótese, considerando o nível de
>>  significância e o poder do teste.

## Quais são os tipos de dados

Os dados podem ser classificados em dois tipos: `dados categorizados e dados quantitativos.`

Os **dados categorizados** são aqueles que expressam qualidades ou atributos dos elementos, como sexo, cor dos olhos, estado civil, etc. 

Os **dados quantitativos** são aqueles que expressam quantidades ou medidas dos elementos, como altura, peso, idade, renda, etc.

Observe a ilustração a seguir demonstrando os dados categóricos e quantitativos de forma organizada em uma tabela.

![Imagens/readme/mytabletypedata1.png](https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/mytabletypedata1.png?raw=true)

#### Como apresentar os dados estatísticos?

Existem diferentes formas para a  apresentação dos dados estatísticos, dependendo do tipo de dado e do objetivo da pesquisa.

> Algumas formas comuns são:
> **Dados brutos:** são os dados originais, sem nenhum tipo de tratamento ou ordenação.
> **Rol:** é a sequência dos dados brutos ordenados em ordem crescente ou decrescente.
> **Dados discretos:** é aquela que assume valores isolados, geralmente inteiros e finitos, como número de filhos, número de acertos em uma prova, etc.
> **Dados contínuos (numéricos):** é aquela que assume valores em um intervalo, resultam de valores infinitos possíveis, geralmente valores reais, como altura,
> peso, tempo, etc.

## Gráficos

Como construir gráficos para variáveis contínuas e discretas de forma sucinta e didática?

Os gráficos são ferramentas visuais que facilitam a análise e a comunicação dos dados, utilizando elementos geométricos como barras, setores, linhas, etc. 

> Para construir gráficos para variáveis contínuas e discretas, devemos seguir os seguintes passos:
> Escolher o tipo de gráfico mais adequado para cada tipo de variável, considerando o objetivo e o público-alvo da apresentação.

Alguns exemplos são:
- **Gráfico de barras:** usado para variáveis discretas ou categorizadas, mostrando a frequência de cada valor em barras verticais ou horizontais.

![Imagens/readme/vertbarchart.png](https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/vertbarchart.png?raw=true)
![Imagens/readme/horibarchart.png](https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/horibarchart.png?raw=true)

- **Gráfico de setores:** usado para variáveis categorizadas, mostrando a frequência de cada valor em setores de um círculo, como uma pizza ou rosca.

![Imagens/readme/sectchart.png](https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/sectchart.png?raw=true)

- **Gráfico de histograma:** usado para variáveis contínuas, mostrando a frequência de cada intervalo em barras verticais.

![Imagens/readme/histogramchart.png](https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/histogramchart.png?raw=true)

- **Gráfico de polígono de frequências:** usado para variáveis contínuas, mostrando a frequência de cada intervalo em pontos unidos por linhas.
- **Gráfico de ogiva:** usado para variáveis contínuas, mostrando a frequência acumulada de cada intervalo em pontos unidos por linhas.

![Imagens/readme/polyogive_graphics.png](https://github.com/o-allanribeiro/PROJETOESTATISTICA/blob/main/Imagens/readme/polyogive_graphics.png?raw=true)

### Passos básicos para construir um gráfico

Para construir um gráfico adequado, é preciso seguir alguns passos básicos:
- Definir o título do gráfico, indicando o assunto e a fonte dos dados.

> O título deve ser claro, conciso e informativo, sem induzir o leitor a interpretações erradas ou tendenciosas.

- Definir os eixos do gráfico, indicando as escalas e as unidades das variáveis.

> Os eixos devem ser proporcionais, consistentes e legíveis, facilitando a comparação entre os dados.

- Desenhar as figuras geométricas correspondentes aos valores das variáveis, usando cores ou padrões diferentes para facilitar a distinção.

> As figuras devem ser escolhidas de acordo com o tipo de gráfico e de variável, evitando distorções ou ambiguidades.

- Incluir legendas ou rótulos para identificar as categorias ou os intervalos das variáveis.

> As legendas devem ser breves, precisas e coerentes, sem omitir ou acrescentar informações desnecessárias.

- Incluir notas explicativas ou observações sobre o gráfico se necessário.

> As notas devem ser usadas para esclarecer aspectos relevantes ou excepcionais do gráfico, sem repetir ou contradizer o que já foi dito no título ou nas legendas.

## Medidas de posição

As medidas de posição são valores numéricos que indicam a localização dos dados em uma distribuição. 

Elas permitem comparar diferentes conjuntos de dados ou analisar a variação dos dados dentro de um mesmo conjunto. 

Algumas medidas de posição comuns são:
### Média
Média é a soma dos valores dividida pelo número de valores. Representa o valor central ou típico dos dados.

A média é representada pelo símbolo $\bar{x}$ ou μ, dependendo se os dados são de uma amostra ou de uma população.

$\bar{x} = \frac{\sum_{i=1}^n x_i}{n}   $

Representação do nosso exemplo:

$\bar{x} = \frac{(10 + 12 + 15 + 20 + 25 + 30 + 35 + 40 + 45 + 45 + 50)}{11}    $

$\bar{x} = 29.727272727272727   $

### Mediana
A mediana é uma medida de posição estatística que representa o valor que divide o conjunto de dados ordenados em duas partes iguais. 

Ela é calculada encontrando o valor central dos dados se eles tiverem um número ímpar de elementos, ou a média dos dois valores centrais se eles tiverem um número par de elementos. 

A mediana é representada pelo símbolo $M$ ou $Q_2$​, dependendo se os dados são de uma amostra ou de uma população.

> $M = x_{\frac{n+1}{2}}$, se $n$ é ímpar
>
> $M = \frac{x_{\frac{n}{2}} + x_{\frac{n}{2} + 1}}{2}$, se $n$ é par

Observando nosso exemplo:

$(10, 12, 15, 20, 25, 30, 35, 40, 45, 45, 50)$, 

logo usaremos a seguinte fórmula para elementos $n$ impar:

$M = x_{\frac{11+1}{2}}$
 
n = número de elementos no exemplo = 11

$M = x_{6}$

6 é a posição do elemento

$M = 30$

$(10, 12, 15, 20, 25, \boxed{30}, 35, 40, 45, 45, 50)$

Caso usássemos um conjunto de elementos pares, conforme a serie a seguir:

$(10, 12, 15, 20, 25, 30, 35, 40, 45, 45)$, usamos a outra fórmula:

$M = \frac{x_{\frac{n}{2}} + x_{\frac{n}{2} + 1}}{2}$

n = número de elementos = 10

$M = \frac{x_{\frac{10}{2}} + x_{\frac{10}{2} + 1}}{2}  $

$M = \frac{x_{5} + x_{6}}{2}$
 
Encontramos as posições que devemos substituir na fórmula posição 5 e posição 6
 
$M = \frac{{25} + {30}}{2}  $

$(10, 12, 15, 20, \boxed{25}, \boxed{30}, 35, 40, 45, 45)   $
 
$M = 27.5$

### Moda
A moda é uma medida de posição estatística que representa o valor mais frequente de um conjunto de dados. 

Ela é calculada contando quantas vezes cada valor aparece nos dados e escolhendo o que tem a maior frequência. 

A moda é representada pelo símbolo $M_o$​ ou $f_m$​, dependendo se os dados são de uma amostra ou de uma população.

$M_o = \text{valor de } x_i \text{ que maximiza } f_i$

No exemplo temos uma repetição, $(10, 12, 15, 20, 25, 30, 35, 40, \boxed{45}, \boxed{45}, 50)$

### Percentis
Os percentis são medidas de posição estatística que representam os valores que dividem o conjunto de dados ordenados em 100 partes iguais. 

Eles são usados para comparar a distribuição dos dados e identificar valores extremos ou atípicos. 

O método Tukey é um dos métodos para definir os percentis, baseado na seguinte fórmula:

$P_k = Q_1 + k \times (Q_3 - Q_1)$

Onde Pk​ é o percentil de ordem k, Q1​ é o primeiro quartil, Q3​ é o terceiro quartil e k é um fator que depende do valor de k. 

O método Tukey usa os seguintes valores de k:

$\text{Se k = 0.25, então Pk​=Q1​, o primeiro quartil.} $

$\text{Se k=0,5, então Pk​=Q2​, a mediana ou o segundo quartil.} $

$\text{Se k=0,75, então Pk​=Q3​, o terceiro quartil.} $

$\text{Se k=1, então Pk​ é o limite superior ou inferior do intervalo interquartílico, usado para detectar valores atípicos.}$



## Medidas de variabilidade
### Amplitude
A amplitude é a medida de variabilidade mais simples, que representa a diferença entre o maior e o menor valor de um conjunto de dados. 

Ela é calculada subtraindo o menor valor do maior valor.

$A = x_max​ − x_min​$

Onde $A$ é a amplitude, $x_max$​ é o maior valor e $x_min$​ é o menor valor dos dados.

### Desvio médio
O desvio médio é uma medida de variabilidade que representa a média dos desvios absolutos dos valores em relação à média de um conjunto de dados. 

Ele é calculado somando os valores absolutos das diferenças entre cada valor e a média dos dados, e dividindo pelo número de elementos.

$D_m = \frac{\sum_{i=1}^n |x_i - \bar{x}|}{n}$

Onde $D_m$​ é o desvio médio, $x_i$​ são os valores dos dados, $\bar{x}$ é a média dos dados e $n$ é o número de elementos dos dados.

### Variância
A variância é uma medida de variabilidade que representa o grau de dispersão dos valores em relação à média de um conjunto de dados. 

Ela é calculada somando os quadrados das diferenças entre cada valor e a média dos dados, e dividindo pelo número de elementos.

$S^2 = \frac{\sum_{i=1}^n (x_i - \bar{x})^2}{n}$

Onde $S^2$ é a variância, $x_i$​ são os valores dos dados, $bar{x} é a média dos dados e $n$ é o número de elementos dos dados.

### Desvio padrão
O desvio padrão é uma medida de variabilidade que representa o grau de dispersão dos valores em relação à média de um conjunto de dados. 

Ele é calculado tirando a raiz quadrada da variância dos dados.

$S = \sqrt{S^2} = \sqrt{\frac{\sum_{i=1}^n (x_i - \bar{x})^2}{n}}$

Onde $S$ é o desvio padrão, $S^2$ é a variância, $x_i$​ são os valores dos dados, $\bar{x}$ é a média dos dados e $n$ é o número de elementos dos dados.

>> Essas medidas podem ser calculadas para dados quantitativos, ou seja, que representam quantidades ou medidas.


Espero que vocês tenham gostado dessa postagem e que tenham aprendido um pouco mais sobre estatística. 

## Bibliografia
No caso do PDF da página atual, uma possível referência seria:

SILVA, Daiane de Oliveira; NOLL, Matias. Guia prático de fontes de informações para pesquisa1. Goiânia: Ed. das autoras, 20202. 
Disponível em: <https://phys.org/news/2023-07-korean-team-room-temperature-ambient-pressure-superconductor.html>. Acesso em: 26 ago. 2023.

TRIOLA, Mario F. Introdução à estatística. 8. ed. Rio de Janeiro: LTC, 2005.
