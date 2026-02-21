# LLM-driven-report-filler

## Текущее состояние

Сейчас репозиторий практически пустой (только `.gitkeep`), поэтому рабочую структуру проекта нужно создать с нуля.

## Предложенная базовая структура

```text
LLM-driven-report-filler/
├── src/
│   ├── app/
│   │   ├── api/
│   │   ├── core/
│   │   ├── services/
│   │   └── models/
│   ├── prompts/
│   └── main.py
├── tests/
│   ├── unit/
│   ├── integration/
│   └── e2e/
├── config/
│   ├── settings.example.yaml
│   └── prompts.yaml
├── scripts/
│   ├── dev.sh
│   └── test.sh
├── docs/
│   └── project-structure-proposal.md
├── .env.example
├── .gitignore
└── pyproject.toml
```

Подробнее по слоям и шагам внедрения — в `docs/project-structure-proposal.md`.
