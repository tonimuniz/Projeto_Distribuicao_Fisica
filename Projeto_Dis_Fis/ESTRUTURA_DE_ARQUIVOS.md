# Estrutura dos arquivos

Cada instância (`C1`, `C2`, `C3` e `C4`) segue a mesma organização:

```text
C*/
├── dados/                       # CSVs, matrizes NPY e params.json
├── notebooks/                   # códigos e análises Jupyter
├── configuracao/                # licença local, quando aplicável
└── resultados/
    ├── tabelas/                 # métricas, rotas e decisões em CSV
    ├── graficos/                # figuras PNG
    ├── logs/                    # logs textuais dos solvers
    ├── resumos/                 # resumos JSON
    └── checkpoints/             # trajetórias CSV e metadados intermediários
```

Os notebooks localizam a pasta `dados` independentemente de o Jupyter iniciar
na raiz do repositório, na pasta da instância ou em `notebooks`. As pastas de
resultados são criadas automaticamente antes de qualquer exportação.

Na instância C2, o arquivo histórico `Cvar (1).npy` foi normalizado para
`dados/Cvar.npy`, igual às demais instâncias.
