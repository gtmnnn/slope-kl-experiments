# Slope Entropy for Change Point Detection

Репозиторий содержит экспериментальные расчеты для обнаружения разладок на основе Slope Entropy и KL-дивергенции.

## Структура
1. `01_SlopeEntropy_CPD_Algorithm.ipynb` — моделирование временного ряда, калибровка порога и оценка задержки, визуализация статистики $D_n$.
2. `02_Statistic_Distribution_Analysis.ipynb` — проверка гипотезы о распределении $2nD_n \sim \chi^2_{k-1}$.

## Как запустить
Для работы требуются Python 3.8+ и библиотеки:
`pip install numpy matplotlib scipy jupyter`

Запустите Jupyter Lab или Notebook:
```bash
jupyter lab
