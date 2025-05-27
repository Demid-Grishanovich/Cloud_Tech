# CI/CD Pipeline with Azure DevOps

В проекте настроен CI/CD pipeline через Azure Pipelines. Файл конфигурации: `azure-pipelines.yml`.

Pipeline запускается автоматически при каждом push в ветку `main`.

Он состоит из трёх стадий:

- 🏗 **Build**: выполняет сборку Java Spring Boot проекта через Maven
- ✅ **Test**: запускает unit-тесты
- 🚀 **Deploy**: выполняет имитацию деплоя (на данном этапе просто `echo`)

## Структура

