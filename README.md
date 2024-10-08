# SNDBX
Makes code sandboxes easy

## Описание
Утилита позволяет развернуть песочницу и открыть ее в VSCode с помощью одной команды.\
Поддерживаются Go и JavaScript.\
Также можно открыть документацию к выбранному языку с помощью опции для команд - docs.

* Чтобы песочница открылась в VSCode, необходимо, чтобы он был добавлен в PATH.\
Для этого в VSCode нажмите Cmd + Shift + P и выберите пункт\ `"Shell Command: Install 'code' command in PATH"`.\
В противном случае песочница откроется в finder/explorer.

## Установка
`npm i -g sndbx` - утилиту необходимо утсновить глобально

## Использование
После установки утилиту можно использовать по имени `sndbx` и передав в нее необхоимую команду, например `sndbx go`

## Список поддерживаемых команд
`sndbx go` - Разворачивает песочницу для Go\
`sndbx js` - Разворачивает песочницу для JavaScript\
`sndbx go docs` - Открывает документацию по Go (Go tour)\
`sndbx js docs` - Открывает документацию по JavaScript (MDN)\
`sndbx clear` - Удаляет все созданные песочницы\
`sndbx help` - ¯\\_(ツ)_/¯
