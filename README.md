# Практическая работа №2 Пронин Евгений Анатольевич ЭФМО-01-25

## Описание проекта

Минимальный Go-сервер с базовой структурой директорий соответствующей распространённым практикам (project-layout):
* `cmd/myapp/` — входная точка приложения (`main.go`).
* `internal/app/` — логика приложения (сервер, маршруты).
* `internal/app/handlers/` — отдельные обработчики (например, `/ping`).
* `utils/` — вспомогательные утилиты (логгер, функции для JSON).
* `.gitignore` — список игнорируемых файлов.
* `go.mod` — описание Go-модуля.

Доступные маршруты:
* `/` → выводит текст `Hello, Go project structure!`.
* `/ping` → возвращает JSON со статусом и временем.
* `/fail` → возвращает JSON-ошибку.
---

## Скриншоты

### Структура проекта

<img width="402" height="487" alt="image" src="https://github.com/user-attachments/assets/f7755080-7b5e-4c0c-a23f-f6db687c578b" />

### Запуск сервера и логи

Запуск выполняеться командой: ```go run ./cmd/myapp```

<img width="476" height="103" alt="image" src="https://github.com/user-attachments/assets/8bc4a289-3896-4b37-afca-93413cc20f2d" />


### Ответы

<img width="621" height="301" alt="image" src="https://github.com/user-attachments/assets/8f6f6ac2-7a86-4224-889e-2305e3cac233" />

### Ответ с заголовком

<img width="806" height="158" alt="image" src="https://github.com/user-attachments/assets/c6cd3976-d0ff-4c27-a123-d4f68585c3c9" />

### Маршрут ```/fail```

<img width="628" height="139" alt="image" src="https://github.com/user-attachments/assets/82cef38f-ef60-49df-974c-cf8f51a711b1" />


## Требования

* Go 1.25.1
* Git 2.51.0
