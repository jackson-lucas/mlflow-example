Este repositório é apenas um exemplo utilizando o mlflow tracking.

## Instalação

- Tenha as libs que estão no requirements.txt instaladas. (Instale para o python 3)

## Inicializando servidor do mlflow

- Pelo terminal nessa pasta execute `mlflow server -h 0.0.0.0`
- Acesse localhost:5000 pelo seu navegador
- Deverá ser possível ver o experimento `random_exp`

## Criando novos experimentos

- Acesse o notebook `Random Experiment` pelo seu editor favorito.
- Modifique o nome passado em `mlflow.set_experiment()`
- Divirta-se ^^