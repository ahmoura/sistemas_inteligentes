# Aprendizado de máquina
-   Busca automatizar o processo de aquisição de conhecimento.
-   Algumas tarefas são melhor definidas e/ou executadas a partir de exemplos (como reconhecimento facial).
-   O ser humano não é capaz de explicar nem programar sua habilidade para executar algumas tarefas (como dirigir ou andar de bicicleta).
-   A quantidade de conhecimento disponível pode ser muito grande para ser descrito por humanos (Era do big data).
-   Algumas tarefas exigem cálculos complexos, possíveis apenas com computador (busca por correlação).

## O que é aprendizado de máquina?
O ramo do aprendizado de máquina busca encontrar um reconhecimento de padrões dado uma entrada de dados.
É importante levar em conta alguns tópicos nos campos dos estudos de filosofia, neurociência e psicologia para uma compreensão melhor do todo.

A definição fornecida por Mitchell diz que:
>   “Um programa aprende a partir da experiência **E**, em uma relação a uma classe de tarefas **T**, com medida de desempenho **P**, se seu desempenho em **T**, medido por **P**, melhora com **E**.”

**Exemplo:** Filtrar mensagens de e-mail:
-   **Tarefa T:** Categorizar mensagens de e-mail como spam ou legítima.
-   **Medida de desempenho P:** Porcentagem de mensagens de spam e legítimas corretamente identificadas
-   **Experiência E:** Conjunto de e-mails apontados pelo usuário como spams.


### Inteligência
Algumas literaturas definem inteligência como a capacidade de alguém/algo para compreender e resolver novos problemas, sejam eles:
-   Lógica;
-   Abstração;
-   Memorização;
-   Compreensão;
-   Comunicação;
-   Aprendizado;		
-   Resolução de problemas.

### Percepção
```diff
- ESCREVER SOBRE
```

### Cognição
```diff
- ESCREVER SOBRE
```

### Experiência
```diff
- ESCREVER SOBRE
```
### Aprendizado
Aprendizado é o processo pelo qual as competências, habilidades ou conhecimentos são adquiridos ou modificados, como resultado de estudo, experiência, raciocínio e observação.

### Treino
Treino  é a  tentativa de melhorar o desempenho em certas habilidades.

### Experiência
```diff
- ESCREVER SOBRE
```
### Inteligência artificial
Abordagens do estudo de inteligência artificial se dividem em 4 categorias:

-   Sistemas que pensam como humanos;
-   Sistemas que pensam racionalmente;
-   Sistemas que agem como humanos;
-   Sistemas que agem racionalmente.

O foco da inteligência artificial é ensinar a máquina na execução de tomada de decisões. Um framework nada científico (que compila alguns científicos e uma tentativa de deixar mais claro os pontos mas que deixa mais complexo).

```diff
- COLOCAR O FRAMEWORK AQUI
```

1. Busca
2. Conhecimento
3. Experiência

-   Busca + Estudo = Conhecimento
-   Conhecimento + Aprendizagem = Experiência
-   Experiência + Treino = Busca

### Inferência indutiva
Raciocínio para obter conclusões sobre todos os membros de uma classe pelo exame de alguns membros da classe. Exemplo:
>   1 + 3 + 5 + 7 + 9 + +	…	+ (2k-1) + (2k+1) = (k + 1)²

Os passos necessários para uma boa indução são:
-   Testar o Passo Base;
-   Assumir uma hipótese de indução;
-   Testar o Passo indutivo;

|| K ||
|-|-|-|
|**PB** |0   |1 = 1
|**HI** |n   |1 + 3 + …. + (2n+1) = (n + 1)²
|**PI** |n+1 |1 + 3 + …. + (2(n+1)+1) = ((n+1) + 1)²

### Conjunto de dados

O conjunto de dados é um arquivo de qualquer tipo (texto, áudio, vídeo, planilhas, etc) que possuem dados e esses, após uma certa adequação, levantamento de hipóteses, fornecem de alguma maneira uma informação relevante para alcançar um fato.
Todos algoritmos de aprendizado de máquina possuem uma entrada de dados específicas, e por vezes um conjunto de dados precisa ser ajustado para se tornarem dados que podem ser consumidos pelo mesmo.
A maneira mais comum é tornar esses dados em tabulares (que nada mais é que os transformar em tabelas). 
**Exemplo:** Um conjunto de dados de um hospital.
**Meta:** Induzir hipóteses para fazer diagnósticos corretos para novos pacientes

|Id. 	|Nome 	|Idade 		|Sexo		|Peso 		|Manchas 		|Temp. 	|# Int. 	|Est.	|Diagnóstico
|-|-|-|-|-|-|-|-|-|-|
|4201 	|Igor		|28 		|M 		|79 		|Concentradas 	|38.0 		|2 	|SP 	|Doente
|3217 	|Moutinha	|18 		|F 		|67 		|Inexistentes 	|39.5 		|4	|MG 	|Doente
|4039 	|Perot		|49 		|M 		|92 		|Espalhadas 	|38.0 		|2 	|RS 	|Saudável
|1920 	|Tonin		|18 		|M 		|43 		|Inexistentes 	|38.5		|8 	|MG 	|Doente
|4340 	|Tuzinha	|21 		|F 		|52 		|Uniformes 		|37.6 		|1 	|PE 	|Saudável
|2301 	|Icara		|22		    |F 		|? 		    |Inexistentes 	|38.0 		|3 	|RJ 	|Doente
|1322	|Vitinha	|19 		|F 		|87 		|Espalhadas 	|39.0 		|6	|AM 	|Doente
|3027 	|Gabriel	|34	        |M 		|67 		|Uniformes 		|38.4 		|2 	|GO 	|Saudável

**Colunas:** Cada coluna é uma tupla com as características (também chamados de atributos, campos, variáveis, etc) que descrevem seus objetos.

|Id. 	|Nome 	|`Idade` 		|Sexo		|Peso 		|Manchas 		|Temp. 	|# Int. 	|Est.	|Diagnóstico
|-|-|-|-|-|-|-|-|-|-|
|4201 	|Igor		|`28` 		|M 		|79 		|Concentradas 	|38.0 		|2 	|SP 	|Doente
|3217 	|Moutinha	|`18` 		|F 		|67 		|Inexistentes 	|39.5 		|4	|MG 	|Doente
|4039 	|Perot		|`49` 		|M 		|92 		|Espalhadas 	|38.0 		|2 	|RS 	|Saudável
|1920 	|Tonin		|`18` 		|M 		|43 		|Inexistentes 	|38.5		|8 	|MG 	|Doente
|4340 	|Tuzinha	|`21` 		|F 		|52 		|Uniformes 		|37.6 		|1 	|PE 	|Saudável
|2301 	|Icara		|`22`		    |F 		|? 		    |Inexistentes 	|38.0 		|3 	|RJ 	|Doente
|1322	|Vitinha	|`19` 		|F 		|87 		|Espalhadas 	|39.0 		|6	|AM 	|Doente
|3027 	|Gabriel	|`34`	        |M 		|67 		|Uniformes 		|38.4 		|2 	|GO 	|Saudável

**Linhas:** Cada linha é refere a um dado (também chamado de objeto, exemplo, registro, padrão, etc).

|Id. 	|Nome 	|Idade 		|Sexo		|Peso 		|Manchas 		|Temp. 	|# Int. 	|Est.	|Diagnóstico
|-|-|-|-|-|-|-|-|-|-|
|4201 	|Igor		|28 		|M 		|79 		|Concentradas 	|38.0 		|2 	|SP 	|Doente
|3217 	|Moutinha	|18 		|F 		|67 		|Inexistentes 	|39.5 		|4	|MG 	|Doente
|`4039` 	|`Perot`		|`49` 		|`M` 		|`92` 		|`Espalhadas` 	|`38.0` 		|`2` 	|`RS` 	|`Saudável`
|1920 	|Tonin		|18 		|M 		|43 		|Inexistentes 	|38.5		|8 	|MG 	|Doente
|4340 	|Tuzinha	|21 		|F 		|52 		|Uniformes 		|37.6 		|1 	|PE 	|Saudável
|2301 	|Icara		|22		    |F 		|? 		    |Inexistentes 	|38.0 		|3 	|RJ 	|Doente
|1322	|Vitinha	|19 		|F 		|87 		|Espalhadas 	|39.0 		|6	|AM 	|Doente
|3027 	|Gabriel	|34	        |M 		|67 		|Uniformes 		|38.4 		|2 	|GO 	|Saudável

Aqui, vemos que cada registro é um paciente, composto por diversas caracteristicas que o definem.

**Atributo de saída:** Presente em algumas tarefas (aprendizado supervisionado), seus valores devem ser estimados usando outros atributos (predizê-los através das caracteristicas de todo conjunto que foi utilizado para treinar a máquina). Também pode ser chamado de meta ou alvo, e cada valor que pode ser atribuído nessa característica recebe o nome de **rótulo** (rótulos do exemplo: saudável ou doente).

|Id. 	|Nome 	|Idade 		|Sexo		|Peso 		|Manchas 		|Temp. 	|# Int. 	|Est.	|`Diagnóstico`
|-|-|-|-|-|-|-|-|-|-|
|4201 	|Igor		|28 		|M 		|79 		|Concentradas 	|38.0 		|2 	|SP 	|`Doente`
|3217 	|Moutinha	|18 		|F 		|67 		|Inexistentes 	|39.5 		|4	|MG 	|`Doente`
|4039 	|Perot		|49 		|M 		|92 		|Espalhadas 	|38.0 		|2 	|RS 	|` Saudável`
|1920 	|Tonin		|18 		|M 		|43 		|Inexistentes 	|38.5		|8 	|MG 	|`Doente`
|4340 	|Tuzinha	|21 		|F 		|52 		|Uniformes 		|37.6 		|1 	|PE 	|`Saudável`
|2301 	|Icara		|22		    |F 		|? 		    |Inexistentes 	|38.0 		|3 	|RJ 	|`Doente`
|1322	|Vitinha	|19 		|F 		|87 		|Espalhadas 	|39.0 		|6	|AM 	|`Doente`
|3027 	|Gabriel	|34	        |M 		|67 		|Uniformes 		|38.4 		|2 	|GO 	|`Saudável`

### Pré-processamento

O pré-processamento é um tópico que necessita de ser aprofundado à parte. Mesmo assim, é importante discutir o valor dele no início desse trabalho com o conjunto de dados. Nesse exemplo, temos uma quantidade pequena de registros para uma apresentação, Porém, nem sempre é assim que os cojuntos estão. Muitas vezes é possível ter milhões ou milhares de registros.
Com uma quantidade tão imensa de dados, é preciso ter inteligência quando os mesmos forem passados para o treino. Exemplo: O nome e o id de cada paciente de nada influencia o resultado do seu diagnóstico. Assim, os mesmos podem ser ignorados tanto pelo motivo de economizar espaço e ganhar velocidade quanto para não gerar correlações erradas (como descobrir que 90% dos Joãos podem estar doentes, mesmo sabendo que adoecer não tem uma influência direta do nome do paciente).
Outros fatores importantes para o pré-processamento.

```diff
- COLOCAR DADOS DO SEGUNDO SLIDE 
 dados faltantes
```

|`Id.` 	|`Nome` 	|Idade 		|Sexo		|Peso 		|Manchas 		|Temp. 	|# Int. 	|Est.	|Diagnóstico
|-|-|-|-|-|-|-|-|-|-|
|`4201` 	|`Igor`		|28 		|M 		|79 		|Concentradas 	|38.0 		|2 	|SP 	|Doente
|`3217` 	|`Moutinha`	|18 		|F 		|67 		|Inexistentes 	|39.5 		|4	|MG 	|Doente
|`4039` 	|`Perot`		|49 		|M 		|92 		|Espalhadas 	|38.0 		|2 	|RS 	|Saudável
|`1920` 	|`Tonin`		|18 		|M 		|43 		|Inexistentes 	|38.5		|8 	|MG 	|Doente
|`4340` 	|`Tuzinha`	|21 		|F 		|52 		|Uniformes 		|37.6 		|1 	|PE 	|Saudável
|`2301` 	|`Icara`		|22		    |F 		|`?`		    |Inexistentes 	|38.0 		|3 	|RJ 	|`Doente
|`1322`	|`Vitinha`	|19 		|F 		|87 		|Espalhadas 	|39.0 		|6	|AM 	|Doente
|`3027` 	|`Gabriel`	|34	        |M 		|67 		|Uniformes 		|38.4 		|2 	|GO 	|Saudável


## Variáveis numéricas

## Variáveis categóricas

## Aprendizado supervisionado

## Aprendizado não supervisionado

## Conceitos, entradas e atributos

## Dados de treino e teste

## Classificadores

## Predição

## Lift

## Overfitting e underfitting

## Viés & Variância

## Árvores & Classificação

## Avaliação de classificadores

## Árvores de decisão

## Boosting

## Classificador Naïve Bayes

## K-Vizinhos mais próximos

## Regressão logistica

## Ranqueamento

## Regressão linear

## Perceptron

## Clusterização hierárquico

## Clusterização K-means

## Redes neurais

## Análise de sentimentos

## Collaborative Filtering

## Tagging


