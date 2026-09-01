# Denisov-Egor

> **C++ developer in progress · Linux enthusiast · Arch Linux**

Изучаю **C++ и Linux**, постепенно углубляюсь в системное программирование, автоматизацию и разработку программного обеспечения.

Собираю собственное окружение на **Arch Linux**, пишу учебные и практические проекты и постепенно превращаю их в полноценные технические проекты.

---

## Сейчас

* изучаю **C++**
* изучаю **Linux / Unix**
* развиваюсь в направлении **системного программирования**
* использую **Arch Linux** как основную систему
* изучаю **C#**
* планирую изучать **C и Java**
* развиваю собственные open-source проекты
* изучаю инструменты разработки и инженерные практики

---

## Tech Stack

### Languages

`C++` `C#`

### Linux / System

`Arch Linux` `Wayland` `Hyprland` `systemd` `Bash` `Zsh`

### Development

`Git` `CMake` `GDB` `Valgrind`

### Editors & Tools

`VS Code` `Neovim` `Kitty`

---

## Projects

### `archlinux-dotfiles`

Моя конфигурация **Arch Linux** и рабочего окружения.

Репозиторий показывает, как я организую и автоматизирую собственную Linux-систему.

**Внутри:**

* Hyprland
* Waybar
* Kitty
* Neovim
* Bash / Zsh
* systemd user units
* GTK configuration
* terminal configuration
* package management
* автоматизированный installer
* резервное копирование конфигураций
* проверка Shell-скриптов через ShellCheck

Это мой основной проект, связанный с Linux и системной конфигурацией.

---

### `CPlusPlusLinux`

Практический проект для изучения **C++ и Linux через системное программирование**.

Основная идея — изучать C++ не только через синтаксис языка, но и через взаимодействие программы с операционной системой.

**Основные направления:**

* C++17 / C++20
* Linux / Unix
* POSIX API
* файловая система
* файловые дескрипторы
* процессы
* потоки
* сигналы
* IPC
* системные вызовы
* обработка ошибок
* CMake
* GDB
* Valgrind

Цель проекта — постепенно перейти от учебных программ к полноценным системным приложениям.

---

### `Cpp`

Учебный репозиторий по **C++**.

Здесь собираю:

* практические задачи
* эксперименты
* алгоритмы
* структуры данных
* небольшие программы
* изученные концепции языка
* результаты практики

Репозиторий используется как рабочая площадка для систематического изучения C++.

---

## Основное направление

```text
                    C++
                     │
          ┌──────────┼──────────┐
          │          │          │
      Algorithms    STL        OOP
          │          │          │
          └──────────┼──────────┘
                     │
             Systems Programming
                     │
                  Linux
                     │
       ┌─────────────┼─────────────┐
       │             │             │
   Processes      Filesystems    Threads
       │             │             │
       └─────────────┼─────────────┘
                     │
               POSIX / Unix
```

Моя долгосрочная цель — двигаться от изучения языка к **системному программированию и разработке реального программного обеспечения**.

---

## Linux

Моя основная операционная система — **Arch Linux**.

Рабочее окружение собираю и настраиваю самостоятельно:

```text
Arch Linux
    │
    ├── Hyprland
    ├── Wayland
    ├── Waybar
    ├── Kitty
    ├── Neovim
    ├── systemd
    └── custom dotfiles
```

Мне интересна не только настройка рабочего окружения, но и понимание того, **что происходит под ним**.

---

## C++ → Linux

Особенно интересует пересечение C++ и Linux:

```text
C++
 │
 ├── Memory
 ├── RAII
 ├── STL
 ├── Threads
 └── Error handling
       │
       ▼
     Linux
       │
 ├── Processes
 ├── File descriptors
 ├── Signals
 ├── IPC
 ├── Filesystems
 └── System calls
```

Именно поэтому `CPlusPlusLinux` является одним из основных направлений моего GitHub.

---

## Что изучаю

### C++

* базовый синтаксис
* типы данных
* функции
* указатели
* ссылки
* структуры
* классы
* ООП
* RAII
* STL
* контейнеры
* алгоритмы
* smart pointers
* move semantics
* шаблоны
* исключения
* многопоточность

### Algorithms

* массивы
* строки
* сортировки
* поиск
* бинарный поиск
* рекурсия
* структуры данных
* графы
* динамическое программирование

### Linux

* файловая система
* процессы
* файловые дескрипторы
* права доступа
* сигналы
* pipes
* IPC
* `/proc`
* системные вызовы
* процессы и потоки
* shell environment

### Development

* Git
* CMake
* GCC
* Clang
* GDB
* Valgrind
* ShellCheck
* GitHub Actions

---

## Roadmap

### C++

* [x] базовый синтаксис
* [x] переменные и типы
* [x] условия
* [x] циклы
* [x] функции
* [ ] классы и ООП
* [ ] RAII
* [ ] STL
* [ ] smart pointers
* [ ] move semantics
* [ ] templates
* [ ] multithreading

### Algorithms

* [ ] массивы
* [ ] строки
* [ ] сортировки
* [ ] бинарный поиск
* [ ] рекурсия
* [ ] структуры данных
* [ ] графы
* [ ] динамическое программирование

### Linux

* [ ] файловые дескрипторы
* [ ] системные вызовы
* [ ] процессы
* [ ] `fork()`
* [ ] `exec()`
* [ ] `wait()`
* [ ] сигналы
* [ ] pipes
* [ ] IPC
* [ ] `/proc`

### Tools

* [ ] CMake
* [ ] GDB
* [ ] Valgrind
* [ ] GoogleTest
* [ ] GitHub Actions
* [ ] clang-format
* [ ] clang-tidy

---

## Принципы

```text
Understand before abstracting.
Keep it simple.
Prefer RAII.
Avoid unnecessary dependencies.
Use the standard library when possible.
Automate repetitive work.
Write documentation.
Understand the system underneath the code.
```

Для меня важно не просто заставить программу работать, а **понять, почему она работает именно так**.

---

## Open Source

Хочу постепенно переходить от личных учебных проектов к более качественным open-source проектам.

Основные направления:

```text
C++
Linux
Systems Programming
Open Source
Automation
Developer Tools
```

---

## 2026

Основные цели на ближайший период:

* углубить знания **C++**
* изучить **C**
* продолжить изучение **Linux internals**
* разобраться глубже в системном программировании
* улучшить знания алгоритмов и структур данных
* развивать `CPlusPlusLinux`
* писать больше самостоятельных проектов
* улучшать архитектуру и качество кода
* освоить тестирование
* улучшить CMake workflow
* использовать CI/CD для проектов
* участвовать в open source

---

## GitHub Focus

```text
C++
 │
 ├── Learning
 ├── Algorithms
 ├── Systems
 └── Projects
       │
       ▼
     Linux
       │
 ├── Arch Linux
 ├── Automation
 ├── Configuration
 └── System tools
```

Мой GitHub — это прежде всего **публичный процесс обучения и развития**, где учебные проекты постепенно превращаются в реальные технические проекты.

---

## Featured Projects

| Проект               | Направление                        | Статус   |
| -------------------- | ---------------------------------- | -------- |
| `archlinux-dotfiles` | Linux / Automation / Configuration | Active   |
| `CPlusPlusLinux`     | C++ / Linux / Systems              | Active   |
| `Cpp`                | C++ / Algorithms / Practice        | Learning |

---

## Philosophy

> **Понимать систему, а не просто уметь ей пользоваться.**

И ещё один принцип, который хорошо описывает мой подход:

```text
Learn → Build → Break → Debug → Understand → Improve
```

---

## About

**Denisov-Egor**

`C++` · `Linux` · `Arch Linux` · `Systems Programming`

Изучаю разработку программного обеспечения и постепенно двигаюсь от учебных задач к самостоятельным системным проектам.

---

## GitHub

**@Denisov-Egor**

Основные направления:

`C++` `Linux` `Arch Linux` `Systems Programming` `Open Source`
