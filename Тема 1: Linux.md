# 1. LINUX

## 1.1. Основы Linux и архитектура

- Что такое Linux и Unix.
- Архитектура операционной системы.
- Ядро Linux (Kernel).
- Shell и Bash.
- Пользовательское пространство и пространство ядра.
- Системные вызовы (System Calls).
- Дистрибутивы Linux: Ubuntu, Debian, Rocky Linux.
- Различия Debian-based и RHEL-based систем.

Результат: понимать устройство Linux и назначение его основных компонентов.

## 1.2. Файловая система

- Иерархия каталогов Linux.
- Назначение /etc, /var, /home, /tmp, /usr, /opt.
- Каталог /proc и виртуальные файловые системы.
- Абсолютные и относительные пути.
- Hard Links и Symbolic Links.
- Inodes.
- Поиск файлов через find и locate.
- Архивирование: tar, gzip, zip.

Практика: создать собственную структуру директорий, настроить ссылки и научиться искать файлы.

## 1.3. Командная строка и работа с файлами

- ls, cd, pwd.
- cp, mv, rm, mkdir, touch.
- grep, awk, sed.
- Pipes и перенаправление потоков.
- stdin, stdout, stderr.
- Команды man, tldr.

Практика: анализировать системные логи и извлекать из них нужную информацию.

## 1.4. Управление пакетами

- Что такое Package Manager.
    - apt, dpkg.
    - dnf, yum, rpm.
    - Установка и удаление пакетов.
    - Обновление системы.
    - Управление репозиториями.
    - Разница между apt update и apt upgrade.
    - Проверка принадлежности файла пакету.

## 1.5. Пользователи и права доступа

- Пользователи и группы.
- /etc/passwd, /etc/shadow.
- groupadd.
-  Символьные и числовые права.
- ACL.
- sudo и /etc/sudoers.
- Практика: создать несколько пользователей с разными уровнями доступа.

## 1.6. Процессы и управление ресурсами

- PID и PPID.
- ps, top, htop.
- SIGTERM, SIGKILL, SIGHUP.
- nice, renice.
- nohup, screen, tmux.

## 1.7. Управление дисками и файловыми системами

- fdisk, parted.
- Монтирование и umount.
- LVM: PV, VG, LV.
- resize2fs, xfs_growfs.
- df, du, lsblk.
- lsof и удалённые открытые файлы.

## 1.8. Сетевые инструменты Linux

- ip r.
- ping.
- curl.
- dig.
- nc.
- traceroute.

## 1.9. SSH и удалённый доступ

- Генерация SSH-ключей.
- SSH Agent.
- Настройка SSH-сервера.
- SSH-туннели.

## 1.10. systemd и управление сервисами

- Архитектура systemd.
- Services.
- systemctl.
- Создание собственных unit-файлов.
- Restart=.
- User=.
- Зависимости между сервисами.

## 1.11. Bash Scripting

- Условия.
- Функции.
- Аргументы командной строки.
- Обработка ошибок.
- trap.
- ShellCheck.
- Идемпотентность.

## 1.12. Мониторинг и Troubleshooting

- sar.
- Load Average.
- OOM Killer.
- strace.
- iotop.

## 1.13. Безопасность Linux

- Firewall.
- iptables.
- SELinux.
- fail2ban.
- Принцип минимальных привилегий.

## 1.14. Linux для DevOps

- Cgroups.
- Network Namespace.
- OverlayFS.
- Read-only Root Filesystem.
- Oсновы взаимодействия Linux и Docker.
