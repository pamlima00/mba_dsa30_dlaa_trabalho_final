# mba_dsa30_dlaa_trabalho_final

# Classificação de Imagens com Deep Learning (CIFAR-10)

## Objetivo
Criar um modelo de Deep Learning com acurácia mínima de 75% para classificação de imagens em 10 categorias (CIFAR-10).

## Dataset
O CIFAR-10 contém 60.000 imagens 32x32 RGB divididas em 10 classes.

## Modelo
- Rede CNN com 3 blocos convolucionais
- Otimizador: Adam
- Função de perda: Categorical Crossentropy
- Callback: EarlyStopping

## Resultados
- Acurácia de validação final: **77,24%**
- Gráficos de acurácia, perda e matriz de confusão incluídos no notebook

## Estrutura
- `trabalho_cifar10.ipynb`: código completo
- `README.md`: explicações e instruções

## Execução
Executado no Google Colab com suporte nativo a TensorFlow.
