## 1. Выбранный вариант

**Oracle VirtualBox + Ubuntu**

## 2. Проверка Linux-окружения

В терминале были выполнены команды:

```bash
whoami
pwd
cat /etc/os-release
```

Команда `whoami` показала пользователя `sergei`.

Команда `pwd` показала домашнюю директорию:

```text
/home/sergei
```

Команда `cat /etc/os-release` подтвердила использование Ubuntu.

## 3. Обновление списка пакетов

Была выполнена команда:

```bash
sudo apt update
```

Команда выполнилась успешно, список пакетов был обновлён.

## 4. Создание рабочей папки

Была создана папка `linux-course`:

```bash
mkdir linux-course
cd linux-course
pwd
```

Результат:

```text
/home/sergei/linux-course
```

## 5. Результат

Ubuntu успешно запущено в VirtualBox. Терминал работает, базовые команды выполняются, список пакетов обновлён, рабочая папка `linux-course` создана.
