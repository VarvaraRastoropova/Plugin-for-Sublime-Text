# Converter Plugin for Sublime Text

## Описание

Плагин **converter** для Sublime Text предоставляет несколько пользовательских команд для преобразования чисел между различными системами счисления. Команды можно вызвать через главное меню, контекстное меню или сочетание клавиш.

## Функционал плагина

Плагин **converter** для Sublime Text позволяет конвертировать числа между различными системами счисления. Он поддерживает преобразование чисел из системы счисления с основанием от 2 до 10 в систему счисления с основанием от 2 до 10.

Основные возможности плагина:

- Преобразование чисел из двоичной (base 2) системы счисления в любую систему счисления от 2 до 10.
- Преобразование чисел из любой системы счисления от 2 до 10 в двоичную (base 2).
- Поддержка любых оснований числовых систем от 2 до 10, как в исходной, так и в целевой системе.
- Легкое использование команд через командную палитру, главное меню или контекстное меню.

Пример:
- Преобразование числа `1010` из двоичной системы (base 2) в десятичную (base 10) — результат `10`.
- Преобразование числа `123` из восьмеричной системы (base 8) в десятичную (base 10) — результат `83`.
- Преобразование числа `255` из десятичной системы (base 10) в восьмеричную (base 8) — результат `377`.

Плагин автоматически выполняет все преобразования, обеспечивая поддержку для систем счисления от 2 до 10.

### Описание файлов:

- **`converter.py`** — основной Python-скрипт, в котором реализованы команды для плагина. Здесь находятся все команды, доступные в Sublime Text.
- **`Main.sublime-menu`** — файл, в котором определяются команды, добавленные в главное меню Sublime Text.
- **`Context.sublime-menu`** — (опционально) файл, добавляющий команды в контекстное меню, которое появляется при правом клике.
- **`commands.json`** — (опционально) файл с командами для сочетания клавиш.

## Как использовать

1. **Через главное меню**:

   Команды, добавленные в **Main.sublime-menu**, будут доступны в меню Sublime Text. Например, если команда добавлена в раздел **Tools**, вы найдете её в меню **Tools > converter**.

2. **Через контекстное меню**:

   Команды, добавленные в **Context.sublime-menu**, будут отображаться в контекстном меню при правом клике.

3. **Через сочетание клавиш**:

   Вы также можете вызвать команды через сочетание клавиш, нажав `Ctrl + Shift + F2`.
