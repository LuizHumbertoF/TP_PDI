# Trabalho de PDI - Few-Shot Learning

Trabalho de Processamento Digital de Imagens sobre aprendizado few-shot aplicado ao dataset HAM10000.

## Estrutura do Projeto

```
.
├── notebooks/
│   ├── 00_download_dataset.ipynb
│   └── 01_dataset_preparation.ipynb
└── src/
    ├── few_shot_episodic_eval.ipynb    # Avaliação episódica
    └── helpers.ipynb                    # Funções auxiliares
```

## Dataset

O projeto utiliza o HAM10000 (Human Against Machine with 10000 training images), um dataset de imagens dermatoscópicas de lesões de pele pigmentadas.

## Notebooks

### Preparação
- `00_download_dataset.ipynb` - Download do dataset
- `01_dataset_preparation.ipynb` - Preparação e organização dos dados

### Experimentos
- `few_shot_episodic_eval.ipynb` - Avaliação few-shot com episódios aleatórios
- `helpers.ipynb` - Funções para salvar e visualizar resultados

## Como Usar

1. Execute os notebooks na pasta `notebooks/` para preparar o dataset
2. Execute os notebooks em `src/` para rodar os experimentos
3. Os resultados são salvos automaticamente em formato JSON, TXT e PNG

## Requisitos

- PyTorch
- torchvision
- timm
- scikit-learn
- matplotlib
- seaborn
- numpy

## Observações

Os notebooks foram desenvolvidos para rodar no Google Colab com os dados no Google Drive.
