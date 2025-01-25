### Análise Exploratória de Dados
Neste documento tratarei dos tipos de variáveis e seus respectivos gráficos. Posteriormente pretendo tratar das correlações entre variáveis.



#### 1. Tipos de Variáveis:
A organização dos dados, quando se trata de estatística, é a parte mais crucial do trabalho, visto que a primeira parte desta empreitada sempre é a organização dos dados que se pretende analisar. Por esse motivo, é necessário atentarmos ao cerne do modelo organizacional da AED: os tipos de variáveis. 
Ao construirmos ou analisarmos um banco de dados, é importante entender que as informações devem ser guardadas de formas específicas e que estudarmos as técnicas apropriadas para resumir as informações é o passo primordial que deve ser feito na caminhada de se tornar um estatístico ou alguém que trabalha com dados.

O salário de uma pessoa, sua altura, número de filhos, grau de instrução escolar e seu estado civil são exemplos de variáveis que podemos utilizar como base de informações sobre um indivíduo. Estas variáveis seguem um modelo organizacional e são divididas em dois grandes tipos, as **Variáveis Categóricas** e as **Variáveis Numéricas**, que, por sua vez, são divididas em dois subgrupos, os quais nos aprofundaremos a seguir:


### **1.1 Variáveis Categóricas:**
As Variáveis Categóricas, que também podem ser chamadas de Qualitativas, representam atributos ou qualidades dos indivíduos pesquisados, como grau de instrução, estado civil, cor dos olhos, cabelo ou etnia. Esse tipo de variável é subdividido em dois subgrupos: **nominais** e **ordinais**, para facilitar a organização e análise dos dados. Veremos esses subtipos a seguir:

>#### **1.1.1 Variáveis Categóricas Nominais:**
As variáveis categóricas nominais expressam atributos que não possuem qualquer tipo de ordenação em suas categorias. Alguns exemplos que podemos citar são gênero, cor dos olhos, estado civil, condição de saúde. 

>| **ID** | **Gênero**     | **Estado civil**  | **Profissão**         |
|--------|-----------------|-------------------|-----------------------|
| 01     | Masculino       | Casado            | Engenheiro Metalúrgico|
| 02     | Feminino        | Solteiro          | Médico(a)             |
| 03     | Feminino        | Solteiro          | Professor(a)          |
| 04     | Não-Binário     | Casado            | Artista               |

>- Não existe uma hierarquia ou ordenação entre as categorias dessas variáveis.
>- A variável ID é considerada uma variável **categórica nominal**
---

>#### **1.1.2 Variáveis Categóricas Ordinais:**
As variáveis categóricas ordinais são aquelas que possuem uma ordem natural ou hierarquia entre suas categorias. Os exemplos deste tipo de variável incluem escolaridade, classe social, grau de satisfação e tamanho de roupa.

>| **ID** | **Escolaridade**       | **Nível de Satisfação** | **Tempo de Experiência** |
|--------|------------------------|-------------------------|---------------------------|
| 01     | Graduação              | Satisfeito             | 5-10 anos                |
| 02     | Pós-graduação          | Muito satisfeito       | Mais de 10 anos          |
| 03     | Ensino Médio           | Neutro                 | 1-5 anos                 |
| 04     | Graduação incompleta   | Insatisfeito           | Menos de 
>- É possível observar hirarquia e/ou ordenação entre as categorias dessas variáveis.
>- A variável ID **não** é uma variável **categórica ordinal**

### **1.2 Variáveis Numéricas:**
As **Variáveis Numéricas**, também chamadas de **Quantitativas**, representam os atributos mensuráveis dos indivíduos, como altura, peso, idade, temperatura, salário, entre outros. Esse tipo de variável é subdividido em dois subgrupos: **discretas** e **contínuas**, para facilitar a organização e análise dos dados. Veremos esses subtipos a seguir:

>#### **1.2.1 Variáveis Numéricas Discretas:**
As **variáveis numéricas discretas** são aquelas que assumem valores inteiros e resultam de contagens. Não é possível ter valores fracionados ou decimais para esse tipo de variável. Exemplos incluem o número de filhos, o número de carros em uma garagem, ou o número de clientes em uma loja.

>| **ID** | **Número de Filhos** | **Número de Carros**  | **Número de Clientes**   |
|--------|----------------------|-----------------------|--------------------------|
| 01     | 2                    | 1                     | 10                       |
| 02     | 3                    | 2                     | 25                       |
| 03     | 1                    | 1                     | 15                       |
| 04     | 0                    | 0                     | 5                        |

>- Não existe a possibilidade de valores fracionados ou decimais entre as categorias dessas variáveis.
>- A variável **ID** **não** é uma variável **numérica discreta**.

---

>#### **1.2.2 Variáveis Numéricas Contínuas:**
As **variáveis numéricas contínuas** são aquelas que podem assumir qualquer valor dentro de um intervalo, incluindo valores fracionados ou decimais. Exemplos incluem altura, peso, temperatura, salário e a distância percorrida.

>| **ID** | **Altura (cm)**   | **Peso (kg)**  | **Distância (km)** |
|--------|-------------------|----------------|--------------------|
| 01     | 170.5             | 70.2           | 5.6                |
| 02     | 165.3             | 60.5           | 8.2                |
| 03     | 180.0             | 85.1           | 10.3               |
| 04     | 155.8             | 55.0           | 7.5                |

>- É possível ter valores fracionados ou decimais entre as categorias dessas variáveis.
>- A variável **ID** **não** é uma variável **numérica contínua**.


### 2. A Variável ID:
A variável **ID** é categórica, mais especificamente, uma **variável categórica nominal**. Embora frequentemente representada por números, ela não tem valor quantitativo nem hierarquia. Sua principal função é **identificar de maneira única** os registros no conjunto de dados, sem ser usada em análises matemáticas ou quantitativas.

Mesmo sendo numérica, a variável **ID** é categórica, pois seus valores são apenas rótulos para distinguir registros, sem significado numérico ou ordem.

