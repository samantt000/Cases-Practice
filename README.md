# Производственная практика: решения кейсов

Три кейса от индустриального партнёра. В каждой папке есть собственный `README.md` с описанием задачи, подхода, результатов и инструкцией по запуску.

| Кейс | Тема | Папка | Статус |
|---|---|---|---|
| 1 | Поиск аномалий в журнале заявок на закупку | [`case-1-anomaly-detection`](case-1-anomaly-detection/) | готов |
| 2 | Восстановление процесса по журналу событий | [`case-2-process-recovery`](case-2-process-recovery/) | готов |
| 3 | Продуктовые гипотезы для подписочного мобильного сервиса | [`case-3-product-hypotheses`](case-3-product-hypotheses/) | готов |

## Структура

```
.
├── README.md
├── case-1-anomaly-detection/
│   ├── README.md
│   ├── anomaly_analysis.ipynb   # ноутбук (Google Colab)
│   ├── anomalies.csv            # итоговый список аномалий
│   ├── data/students.csv        # исходный журнал (синтетические данные)
│   └── report/report.tex        # краткий отчёт (LaTeX)
├── case-2-process-recovery/
│   ├── README.md
│   ├── process_discovery.ipynb  # ноутбук (Google Colab)
│   ├── variants.csv             # таблица вариантов
│   ├── student_transitions.csv  # переходы между активностями
│   ├── data/students.csv        # исходный журнал
│   ├── schema/                  # схема (draw.io + png)
│   └── report/report.tex        # краткий отчёт (LaTeX)
└── case-3-product-hypotheses/
    ├── README.md
    ├── notebooks/               # 5 ноутбуков (Google Colab), запуск по порядку 00 → 04
    └── report/                  # отчёт (LaTeX + PDF) и графики fig/
```

Все данные в кейсах 1 и 2 вымышлены (учебная выгрузка). Данные кейса 3 (дамп БД и логи партнёра) в репозиторий не входят: ноутбуки скачивают их по публичной ссылке владельца.
