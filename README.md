# ai-900-lab1
 arquivos para entrega do primeiro lab da ceritifação AI-900 da Microsoft.

# Passo a Passo
    Prezei por uma entrega simples porém completa.
    1. Reaproveitei o mesmo workspace da aula
    2. Criei um novo job de auto-ml porém com um dataset da keggle (subi no meu blob)
    3. Escalonei o job no Azure ML com o setup básico de regressão linear.
        - setei o mínimo possível de iterações pois o intuito aqui foi aprender a dar schedule no job, e não treinar um modelo assertivo.
        - test-split e k-fold cross validation também com o mínimo possível de iterações
        - escolhi uma máquina standart um pouco mais barata como servidor (Standard_D4s_v3 (4 core(s), 16GB RAM, 32GB storage, $0.19/hr))
    5. Rodei o modelo e copiei o JSON do endpoint pra dentro deste repositório GIT.