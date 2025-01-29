

# Uma breve reflexão
 Existimos em um universo de grandeza infinita quando o contemplamos através dos olhos humanos. Na história da construção da ciência e da matemática, muitos de nós nos preocupamos em estudar as maiores partes do cosmo, enquanto outros buscaram entender as minúsculas coisas que se espalham por aí. Contudo, a maior parte daqueles que se dedicaram a entender os mistérios da existência aplicaram continuamente seu tempo de vida quantificando ou encontrando meios de quantificar essas parcelas do universo, a fim de tentar entender melhor a realidade em que estamos inseridos.

 Organizar o universo em dados quantificáveis é provavelmente a tarefa mais antiga e intelectualmente desafiadora à qual a humanidade se propôs. Desde o início de nossa existência, somos compelidos a tentar entender o lugar onde nascemos e passamos a existir. A organização das parcelas da existência em dados pode parecer uma tarefa hercúlea e impossível, mas neste artigo gostaria de compartilhar alguns dos métodos e técnicas que a humanidade encontrou para facilitar esse processo.

> "There is a single light of science, and to brighten it anywhere is to brighten it everywhere."
> — Isaac Asimov
> 
---

## 1. Tipos de Variáveis:
 Quando se trata de estatística, a organização dos dados é a parte mais crucial do trabalho, visto que a primeira etapa dessa empreitada é organizar os dados a serem analisados. Por esse motivo, é essencial atentarmos ao cerne do modelo organizacional da AED: os tipos de variáveis. Ao construirmos ou analisarmos um banco de dados, é fundamental entender que as informações devem ser armazenadas de maneiras específicas. Estudar as técnicas apropriadas para resumir essas informações é o passo primordial para se tornar um estatístico ou alguém que trabalha com dados. O salário de uma pessoa, sua altura, número de filhos, grau de instrução escolar e seu estado civil são exemplos de variáveis que podemos utilizar como base de informações sobre um indivíduo. Estas variáveis seguem um modelo organizacional e são divididas em dois grandes tipos, as Variáveis Categóricas e as Variáveis Numéricas, que, por sua vez, são divididas em dois subgrupos, os quais nos aprofundaremos a seguir:

## 1.1 Variáveis Categóricas:

 As Variáveis Categóricas, que também podem ser chamadas de Qualitativas, representam atributos ou qualidades dos indivíduos pesquisados, como grau de instrução, estado civil, cor dos olhos, cabelo ou etnia. Esse tipo de variável é subdividido em dois subgrupos: nominais e ordinais, para facilitar a organização e análise dos dados. Veremos esses subtipos a seguir:

### 1.1.1 Variáveis Categóricas Nominais:

 As variáveis categóricas nominais expressam atributos que não possuem qualquer tipo de ordenação em suas categorias. Alguns exemplos que podemos citar são gênero, cor dos olhos, estado civil, condição de saúde.

| ID  | Gênero      | Estado civil | Profissão              |
| --- | ----------- | ------------ | ---------------------- |
| 01  | Masculino   | Casado       | Engenheiro Metalúrgico |
| 02  | Feminino    | Solteiro     | Médico(a)              |
| 03  | Feminino    | Solteiro     | Professor(a)           |
| 04  | Não-Binário | Casado       | Artista                |

 Não existe uma hierarquia ou ordenação entre as categorias dessas variáveis.  
 A variável ID é considerada uma variável categórica nominal.

### 1.1.2 Variáveis Categóricas Ordinais:

 As variáveis categóricas ordinais são aquelas que possuem uma ordem natural ou hierarquia entre suas categorias. Os exemplos deste tipo de variável incluem escolaridade, classe social, grau de satisfação e tamanho de roupa.

| ID  | Escolaridade        | Nível de Satisfação | Tempo de Experiência |
| --- | ------------------- | ------------------- | -------------------- |
| 01  | Graduação           | Satisfeito          | 5-10 anos            |
| 02  | Pós-graduação       | Muito satisfeito    | Mais de 10 anos      |
| 03  | Ensino Médio        | Neutro              | 1-5 anos             |
| 04  | Graduação incompleta| Insatisfeito        | Menos de 1 ano       |

 É possível observar hierarquia e/ou ordenação entre as categorias dessas variáveis.  
 A variável ID não é uma variável categórica ordinal.

## 1.2 Variáveis Numéricas:

 As variáveis numéricas, também chamadas de quantitativas, representam os atributos mensuráveis dos indivíduos, como altura, peso, idade, temperatura, salário, entre outros. Esse tipo de variável é subdividido em dois subgrupos: discretas e contínuas, para facilitar a organização e análise dos dados. Veremos esses subtipos a seguir:

### 1.2.1 Variáveis Numéricas Discretas:

 As variáveis numéricas discretas são aquelas que assumem valores inteiros e resultam de contagens. Não é possível ter valores fracionados ou decimais para esse tipo de variável. Exemplos incluem o número de filhos, o número de carros em uma garagem, ou o número de clientes em uma loja.

| ID  | Número de Filhos | Número de Carros | Número de Clientes |
| --- | ---------------- | ---------------- | ------------------ |
| 01  | 2                | 1                | 10                 |
| 02  | 3                | 2                | 25                 |
| 03  | 1                | 1                | 15                 |
| 04  | 0                | 0                | 5                  |

 Não existe a possibilidade de valores fracionados ou decimais entre as categorias dessas variáveis.  
 A variável ID não é uma variável numérica discreta.

### 1.2.2 Variáveis Numéricas Contínuas:

 As variáveis numéricas contínuas são aquelas que podem assumir qualquer valor dentro de um intervalo, incluindo valores fracionados ou decimais. Exemplos incluem altura, peso, temperatura, salário e a distância percorrida.

| ID  | Altura (cm) | Peso (kg) | Distância (km) |
| --- | ----------- | --------- | -------------- |
| 01  | 170.5       | 70.2      | 5.6            |
| 02  | 165.3       | 60.5      | 8.2            |
| 03  | 180.0       | 85.1      | 10.3           |
| 04  | 155.8       | 55.0      | 7.5            |

 É possível ter valores fracionados ou decimais entre as categorias dessas variáveis.  
 A variável ID não é uma variável numérica contínua.

## 2. Tipos especiais de variáveis
### 2.1 A variável ID
 A variável ID é categórica, mais especificamente, uma variável categórica nominal. Embora frequentemente representada por números, ela não tem valor quantitativo nem hierarquia. Sua principal função é identificar de maneira única os registros no conjunto de dados, sem ser usada em análises matemáticas ou quantitativas. Mesmo sendo numérica, a variável ID é categórica, pois seus valores são apenas rótulos para distinguir registros, sem significado numérico ou ordem.
 
 
 
**Subgrupo:** **Nominais**.
 
---

### 2.2 Variáveis Dicotômicas

 Dentro do escopo das variáveis categóricas nominais, existe um subtipo de variável cujo valor de suas possíveis realizações podem assumir apenas **duas categorias**. As chamamos de variáveis dicotômicas e o seu exemplo mais simples incluem perguntas que só podem ser respondidas com "sim" ou "não". Normalmente, os valores assumidos em suas possíveis realizações são mútuamente exclusivos.

### Exemplo:

| ID  | Aprovado | Completou o curso |
| --- | -------- | ----------------- |
| 01  | Sim      | Não               |
| 02  | Não      | Sim               |
| 03  | Não      | Não               |
| 04  | Sim      | Sim               |
| 05  | Sim      | Não               |


**Subgrupo:** **Nominais**.

---

---
## 3. Escalas de medidas:
 No universo em que vivemos, cada uma das coisas que existem podem ser mensuradas seguindo os princípios de sua natureza, a imensa capacidade humana de observar o universo e encontrar padrões é provavelmente a melhor ferramenta conhecida para se analisar e entender a natureza física em que estamos inseridos. Podemos tomar como exemplo a temperatura de um paciente, a distância até uma estrela, o tempo de vida médio de um ser humano, o número de grãos de areia em uma praia, a cor favorita de um indivíduo ou até mesmo **o grau de felicidade de alguém por ter vindo ao mundo**. Existem diversas formas de mensurar as variáveis, chamamos estes níveis de **Escalas de Medida**. As técnicas estatísticas usadas para analisar uma variável e forma como os dados são representados dependem da forma como a variável é medida. Veremos a seguir os quatro níveis de mensuração das variáveis.

---
### 3.1 Escala Nominal
 É qualitativa é a mais básica das escalas de medidas. As realizações representam diferentes categorias, não há hierarquia ou relação entre estes valores. Não é possível fazer cálculos ou comparações quantitativas.  
**Exemplos:** Cores favoritas, gênero, estado civil.

| ID  | Cor Favorita | Gênero     | Estado Civil |
| --- | ------------ | ---------- | ------------ |
| 01  | Vermelho     | Masculino  | Solteiro     |
| 02  | Azul         | Feminino   | Casado       |
| 03  | Verde        | Não-binário| Divorciado   |
| 04  | Amarelo      | Masculino  | Solteiro     |

---

**Gráficos recomendados:**
- Gráfico de barras
- Gráfico de pizza

---

### 3.2 Escala Ordinal
 Os dados nesta escala possuem uma ordem natural entre as categorias, mas a diferença entre os níveis não pode ser medida de forma exata. Embora as categorias possam ser classificadas seguindo uma sequência, a distância entre elas não tem um valor numérico específico.  
**Exemplos:** Nível de satisfação, escolaridade, classes sociais.

| ID  | Nível de Satisfação | Escolaridade | Classe Social |
| --- | ------------------- | ------------ | ------------- |
| 01  | Satisfeito          | Superior     | Alta          |
| 02  | Neutro              | Médio        | Média         |
| 03  | Insatisfeito        | Fundamental  | Baixa         |
| 04  | Satisfeito          | Superior     | Alta          |

---

**Gráficos recomendados:**
- Gráfico de barras
- Gráfico de barras horizontais
- Box plot (para distribuições de dados ordinais)

---

### 3.3 Escala Intervalar
 Nesta escala, os valores numéricos possuem intervalos consistentes entre si, mas não existe um ponto zero absoluto. Isso significa que, embora seja possível medir as diferenças entre os valores, não se pode fazer cálculos de proporções.  
**Exemplos:** Temperatura (em Celsius ou Fahrenheit), anos em um calendário.

| ID  | Temperatura (°C) | Ano         | Hora do Dia |
| --- | ---------------- | ----------- | ----------- |
| 01  | 25.3             | 2023        | 14:00       |
| 02  | 30.1             | 2024        | 08:30       |
| 03  | 15.8             | 2022        | 21:15       |
| 04  | 22.5             | 2025        | 10:45       |

---

**Gráficos recomendados:**
- Gráfico de linhas
- Gráfico de barras
- Histograma

---

### 3.4 Escala de Razão
 A escala de razão é a mais completa, pois os valores numéricos têm um ponto zero verdadeiro, permitindo a realização de todas as operações matemáticas. Com ela, é possível calcular proporções entre os dados.  
**Exemplos:** Peso, altura, distância, salário.

| ID  | Altura (cm) | Peso (kg) | Distância (km) |
| --- | ----------- | --------- | -------------- |
| 01  | 170.5       | 70.2      | 5.6            |
| 02  | 165.3       | 60.5      | 8.2            |
| 03  | 180.0       | 85.1      | 10.3           |
| 04  | 155.8       | 55.0      | 7.5            |


**Gráficos recomendados:**
- Gráfico de barras
- Gráfico de linhas
- Histograma
- Box plot

---

### 3.5 Comparação Resumida:

| Escala     | Ordem | Diferença Quantificável | Zero Verdadeiro | Exemplos                           | Gráficos Recomendados                                |
|------------|-------|-------------------------|-----------------|-----------------------------------|-----------------------------------------------------|
| Nominal    | Não   | Não                     | Não             | Cores, gênero, estado civil       | Gráfico de barras, gráfico de pizza                 |
| Ordinal    | Sim   | Não                     | Não             | Satisfação, escolaridade          | Gráfico de barras, gráfico de barras horizontais, box plot |
| Intervalar | Sim   | Sim                     | Não             | Temperatura (°C, °F), anos        | Gráfico de linhas, gráfico de barras, histograma    |
| Razão      | Sim   | Sim                     | Sim             | Peso, altura, idade               | Gráfico de barras, gráfico de linhas, histograma, box plot |

---

### 3.6 Escalas Likert

 A escala Likert é uma ferramenta extremamente útil para capturar, mensurar e analisar opiniões, sentimentos, níveis de satisfação ou atitudes de um grupo de indivíduos. Esta abordagem é necessária porque sentimentos e atitudes são difíceis de quantificar de forma objetiva. Normalmente, o questionário apresenta respostas que indicam o nível de concordância do participante com a afirmativa proposta. As escalas Likert são ordinais, com respostas geralmente organizadas em 5 pontos, embora também possam ser usadas com 4, 7 ou mais pontos, dependendo da necessidade da pesquisa. Este tipo de escala é muito útil para medir aspectos subjetivos, como sentimentos, que não podem ser facilmente expressos em números, mas que podem ser analisados de forma eficaz usando essa abordagem.

Vamos comparar:
Questionário de Satisfação no Trabalho  

 1. De 0 a 10, o quanto você está satisfeito com o seu trabalho?
>**( ) 0  ( ) 1  ( ) 2  ( ) 3  ( ) 4  ( ) 5  ( ) 6  ( ) 7  ( ) 8  ( ) 9  ( ) 10**  

 2. "Estou satisfeito com o meu trabalho."  
- ( ) Discordo totalmente  
- ( ) Discordo parcialmente 
- ( ) Neutro  
- ( ) Concordo  parcialmente
- ( ) Concordo totalmente

Levando em consideração que a diferença entre números não é tão clara neste contexto, é possível afirmar que se tratando do exemplo 01 um indivíduo ao responder este questionário terá dificuldade em quantificar seus sentimentos. No entando, quando utilizamos a escala Likert(exemplo 02) que utiliza respostas em níveis de satisfação torna-se possível captar de forma mais específica o que se deseja saber de um indvíduo.

### Exemplo:

| ID  | Afirmação                           | Resposta                    |
| --- | ------------------------------------ | --------------------------- |
| 01  | "Estou satisfeito com meu trabalho"  | Concordo totalmente         |
| 02  | "A qualidade do atendimento é boa"   | Concordo parcialmente       |
| 03  | "O ambiente de trabalho é acolhedor" | Neutro                      |
| 04  | "A carga de trabalho é excessiva"    | Discordo parcialmente       |
| 05  | "Eu recomendaria a empresa"          | Discordo totalmente         |

**Subgrupo:** Escala **Ordinal**.

---
### 3.7 Conversão entre Escalas

Converter uma variável de uma escala para outra pode necessita de bastante cautela, pois a conversão de **escala ordinal** para **intervalar** pode levar a distorções, já que as distâncias entre os valores não são precisas e os valores muitas vezes são atribuídos de forma indiscriminada.

### Exemplo:

| ID  | Grau de Satisfação (Ordinal) | Valor Numérico (Intervalar) |
| --- | ---------------------------- | --------------------------- |
| 01  | Muito Satisfeito             | 5                           |
| 02  | Neutro                       | 3                           |
| 03  | Insatisfeito                 | 2                           |
| 04  | Satisfeito                   | 4                           |
| 05  | Extremamente insatisfeito    | 1                           |

**Subgrupo:** **Ordinal para Intervalar**.


