# Классификация автоматизированного трафика по событиям cookie

## Окружение

- Python 3.12.4
- Библиотеки перечислены в `requirements.txt`: NumPy 2.5.2, pandas 3.0.5, scikit-learn 1.9.0, CatBoost 1.2.10.
- Дополнительно требуется Jupyter Notebook или JupyterLab для запуска `.ipynb` (`jupyterlab` или `notebook` устанавливается отдельно).

## Входные файлы

Разместите рядом с ноутбуком такую структуру:

```text
project/
├── solution_bot_detection.ipynb   
├── requirements.txt
├── metric.py                       
└── data/
    ├── train.csv
    ├── test.csv
    └── events.csv.gz
```

## Установка и запуск

В терминале из каталога `project` создайте виртуальное окружение и установите библиотеки:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m pip install jupyterlab
jupyter lab
```

macOS/Linux:

```bash
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m pip install jupyterlab
jupyter lab
```
