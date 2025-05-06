# Лабораторная №8: Резервное копирование

## Как использовать:
1. Настроить пути в `config.json`
2. Запустить:
   ```bash
   python backup.py --config   # Настройка
   python backup.py           # Запуск
   ```

## Пример config.json:
```json
{
    "backup_paths": ["C:\\data"],
    "backup_dir": "D:\\backups",
    "period_days": 1
}
```
