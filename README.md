# CardioIA – Diagnóstico Automatizado (Fase 2)

> Módulo inteligente de análise de dados clínicos com NLP e Machine Learning aplicados à cardiologia.

## Objetivo

Simular a automatização do diagnóstico com IA, utilizando:

- Extração de sintomas a partir de frases de pacientes (NLP básico)
- Classificação de risco clínico com Machine Learning (TF-IDF + Scikit-learn)

## Estrutura do Projeto

```
cardioia-diagnostico-automatizado/
│
├── dados/
│   ├── frases_sintomas.txt          # 10 frases simulando relatos de pacientes
│   ├── mapa_sintomas_doencas.csv    # Mapa de conhecimento: sintomas → doenças
│   └── dataset_risco.csv            # Dataset rotulado para classificação de risco
│
├── codigo/
│   ├── extracao_sintomas.ipynb      # Parte 1: NLP – extração de sintomas e diagnóstico
│   └── classificador_risco.ipynb    # Parte 2: ML – classificador de risco (TF-IDF)
│
└── README.md
```

## Como Rodar

### Pré-requisitos

```bash
pip install pandas scikit-learn jupyter
```

### Parte 1 – Extração de Sintomas

```bash
jupyter notebook codigo/extracao_sintomas.ipynb
```

### Parte 2 – Classificador de Risco

```bash
jupyter notebook codigo/classificador_risco.ipynb
```

## Integrantes do Grupo

| Nome   | RM       |
| ------ | -------- |
| João   | RM565999 |
| Endrew | RM563646 |
| Tayna  | RM562491 |
| Carlos | RM566487 |

## Tecnologias Utilizadas

- Python 3.x
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Jupyter Notebook

## Divisão de Funções

| Pessoa   | Função           | Responsabilidade                                     |
| -------- | ---------------- | ---------------------------------------------------- |
| Pessoa 1 | Data Designer    | Criação dos arquivos de dados                        |
| Pessoa 2 | NLP              | Extração de sintomas (`extracao_sintomas.ipynb`)     |
| Pessoa 3 | Machine Learning | Classificador de risco (`classificador_risco.ipynb`) |
| Pessoa 4 | Documentação     | GitHub, README e vídeo                               |

---

_Projeto desenvolvido para a Fase 2 do PBL – CardioIA: A Nova Era da Cardiologia Inteligente._
