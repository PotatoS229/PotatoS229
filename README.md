# PotatoS229 · Low-level сетевой разработчик

[![GitHub followers](https://img.shields.io/github/followers/PotatoS229?style=social)](https://github.com/PotatoS229)

**Системный программист, специализирующийся на низкоуровневых сетях, обходе цензуры и разработке ядра.**

---

## 🚀 О себе

Попал в IT в **18 лет в компанию Бифорком тек (Biforcom Tech)**, где начинал как младший fullstack-разработчик и участвовал в одном из ключевых проектов компании.

Сейчас я — **начинающий системный программист**, специализируюсь на **сетевых технологиях низкого уровня**, пишу на C/C++, JS/TS, Electron и работаю с ядром (Linux/Windows). Разрабатываю инструменты для обхода DPI и сетевой цензуры.

*   **Путь в IT:** fullstack → системный программист
*   **Основной фокус:** kernel / network dev

---

## 🛠 Инструменты и стек

**Основные технологии:**
`JavaScript/TS` · `React` · `Electron` · `C / C++` · `Node.js` · `Bash` · `Docker`

**Системное программирование:**
`Kernel Modules` · `Raw Sockets` · `eBPF` · `Netfilter / XDP` (Linux) · `Windows Filtering Platform` (WFP)

**Машинное обучение:**
`TensorFlowJS`

### 🎯 В фокусе сейчас:

- Обход DPI на уровне ядра (Windows / Linux)
- Низкоуровневая работа с сетевыми пакетами
- Интеграция ML-моделей (TensorFlowJS) в Electron для анализа трафика
- Асинхронный I/O и оптимизация memory footprint

---

## ⚛️ OS Dev · Долгосрочная цель

Разрабатываю собственную **Linux-подобную ОС** с фокусом на сетевую производительность и минимализм. В процессе изучения:

- Загрузчики (GRUB / Limine)
- Управление памятью и страничная организация
- Планировщик задач
- Сетевой стек с нуля (драйверы, DMA, прерывания)

> «От обхода DPI до собственного микроядра — системный подход»

---

## 🌟 Ключевой проект: UDPilot

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=PotatoS229&repo=UDPilot&theme=dark)](https://github.com/PotatoS229/UDPilot)

**UDPilot** — инструмент на базе **Electron, TensorFlowJS и C/C++** для обхода систем глубокого анализа пакетов (DPI) и цензуры.

**Архитектура:**
- **Фронтенд:** React + ML-модель для детекции DPI-признаков
- **Бэкенд:** Node.js с нативными модулями на C/C++
- **Ядро:** Работа с сетевым стеком через raw-сокеты и kernel-хуки
- **ML:** Активное использование TensorFlowJS для классификации паттернов трафика в рантайме

**Платформы:** `Windows` (WFP) · `Linux` (Netfilter/XDP)

**Техники обхода:** Фрагментация, обфускация, ML-классификация для маскировки потоков.

---

## 🐞 Low-level инженерия сетей

Изучаю структуру Ethernet/IP/TCP/UDP до битов, пишу kernel модули для перехвата и модификации пакетов. Экспериментирую с XDP и eBPF на Linux, Reverse Engineering сетевых драйверов.

- `zero-copy`
- `packet interception`
- `memory safety`

---

## 📫 Контакты

- **GitHub:** [@PotatoS229](https://github.com/PotatoS229)
- **Telegram:** low-level network dev
- **Стек:** `C++23` · `Electron` · `Kernel space`

---

**Biforcom Tech** · fullstack → core systems
**UDPilot:** обход DPI с ML + ядро
**Цель:** собственная ОС с продвинутым сетевым стеком