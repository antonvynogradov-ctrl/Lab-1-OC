# МІНІСТЕРСТВО ОСВІТИ І НАУКИ УКРАЇНИ  
## КИЇВСЬКИЙ ФАХОВИЙ КОЛЕДЖ ЗВ’ЯЗКУ  

---

# ЗВІТ  
## про виконання лабораторної роботи №1  
### з дисципліни «Операційні системи»

---

**Тема:**  
Знайомство з робочим середовищем віртуальних машин та особливостями операційної системи Linux

---

**Виконав:**  
студент групи **БІКС-33**  
**Виноградов Антон Владиславович**

---

**Перевірила:**  
**Сушанова Вікторія Сергіївна**

---

**Київ — 2026**

---

# Лабораторна робота №1  
## Операційні системи

---

## Тема

Вивчення середовищ віртуальних машин та основних особливостей операційної системи Linux.

---

## Мета роботи

1. Ознайомитися з типами гіпервізорів та принципами віртуалізації.  
2. Дослідити основні типи сучасних операційних систем та їх можливості.

---

## Обладнання та програмне забезпечення

- Персональний комп’ютер, сумісний з IBM PC  
- ОС Windows та Oracle VirtualBox  
- Будь-який дистрибутив GNU/Linux  
- Платформа Cisco Networking Academy (netacad.com)

---

# Хід роботи

---

## Підготовка до лабораторної

### Glosssary of Basic English Terms (Virtual Environments)

**Virtual Machine** — a software-based emulation of a physical computer that runs an operating system and applications.

**Virtualization** — a technology that allows multiple operating systems to run on a single physical machine.

**Hypervisor** — software or firmware that creates and manages virtual machines.

**Type 1 Hypervisor** — a hypervisor that runs directly on the physical hardware without a host operating system.

**Type 2 Hypervisor** — a hypervisor that runs on top of a host operating system.

**Host Operating System** — the main operating system installed on the physical machine.

**Guest Operating System** — an operating system installed and running inside a virtual machine.

**Kernel** — the core component of an operating system that manages hardware resources.

---

## Типи гіпервізорів

Гіпервізор дозволяє одночасно запускати кілька ОС та розподіляти ресурси.

- **Тип 1** — використовується на серверах, висока продуктивність  
- **Тип 2** — зручний для навчання та тестування

---

## Огляд VirtualBox (варіант 16)

VirtualBox — гіпервізор другого типу.  
Дозволяє створювати віртуальні комп’ютери з різними ОС.

Основні компоненти:
- хост-ОС  
- віртуальні машини  
- віртуальне обладнання

Основні можливості:
- запуск кількох ВМ  
- встановлення різних ОС  
- розподіл ресурсів  
- збереження стану ВМ

---

# Відповіді на запитання

---

## Розгортання ОС у VirtualBox

1. Встановити VirtualBox  
2. Створити ВМ  
3. Обрати тип ОС  
4. Виділити RAM і диск  
5. Підключити ISO-образ  
6. Встановити систему

---

## Обмеження 32- та 64-бітних ОС

- 32-бітні ОС підтримують до 4 ГБ RAM  
- 64-бітні потребують 64-бітний процесор і підтримку віртуалізації

---

## Встановлення Linux у текстовому режимі

Основні кроки:
- вибір мови  
- налаштування клавіатури  
- розмітка диска  
- встановлення пакетів  
- створення користувача

---

## Встановлення GNOME і KDE

GNOME:
