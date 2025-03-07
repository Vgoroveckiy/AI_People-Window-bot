# Проект: "ИИ-ассистент для компании по установке окон"

## Описание проекта

Проект направлен на разработку и внедрение ИИ-ассистента, который автоматизирует взаимодействие с клиентами компании, специализирующейся на продаже и установке окон. Ассистент способен вести осмысленные диалоги, отвечать на вопросы, основываясь на базе знаний, а также записывать клиентов на встречи и добавлять эти встречи в Google Календарь. Это решение помогает оптимизировать рабочие процессы, улучшить качество обслуживания клиентов и сократить затраты времени на рутинные задачи.

---

## Функционал

### 1. **Осмысленное ведение диалога**
   - Используется современная нейросетевая технология для обеспечения естественного и логичного общения с клиентами.
   - Ассистент понимает контекст вопросов, анализирует намерения клиента и предоставляет соответствующие ответы.
   - Поддержка различных типов запросов, включая информационные, консультативные и организационные.

**Пример диалога:**
- Клиент: "Какой материал лучше выбрать для окна?"
- Ассистент: "Для выбора материала важно учитывать несколько факторов: бюджет, климатические условия и дизайн интерьера. Пластиковые окна подходят для большинства случаев благодаря своей практичности и доступной цене. Деревянные окна обеспечивают более эстетичный внешний вид, но требуют дополнительного ухода."

---

![Диалог-1](https://github.com/Vgoroveckiy/AI_People-Window-bot/blob/main/dialog-1.png?raw=true)

---

### 2. **Ответы на вопросы по базе знаний**
   - Создана структурированная база знаний, содержащая информацию о продуктах, услугах, ценах, условиях обслуживания и часто задаваемых вопросах.
   - Ассистент использует эту базу для быстрого и точного предоставления информации клиентам.

**Пример использования:**
- Клиент: "Сколько стоит замена стеклопакета?"
- Ассистент: "Цена замены стеклопакета зависит от его размера и типа. Для стандартного стеклопакета размером 100x150 см стоимость составляет 8 000 рублей. Если вам нужна более подробная информация, пожалуйста, уточните параметры."

---
 
 ![Диалог-2](https://github.com/Vgoroveckiy/AI_People-Window-bot/blob/main/dialog-2.png?raw=true)

---

### 3. **Запись клиента на встречу и интеграция с Google Календарем**
   - Ассистент может записывать клиентов на замеры, консультации или другие встречи.
   - После согласования времени и даты встреча автоматически добавляется в Google Календарь сотрудника.

**Пример сценария:**
- Клиент: "Можно записаться на замер окна?"
- Ассистент: "Конечно! Когда вам удобно провести замер? Укажите предпочтительную дату и время."
- Клиент: "Пусть это будет 10 октября, в 16:00."
- Ассистент: "Вы успешно записаны на замер окна на 10 октября, 16:00. Напоминание придет за день до встречи."

---

 ![Диалог-замер](https://github.com/Vgoroveckiy/AI_People-Window-bot/blob/main/zamer.png?raw=true)

---

**Пример записи в календаре:**

---

 ![Календарь](https://github.com/Vgoroveckiy/AI_People-Window-bot/blob/main/calendar.png?raw=true)

---

## Технологии и сервисы

### 1. **Qwen**
   - **Назначение:** Создание системного промпта и формирование базы знаний.
   - **Особенности:** Qwen предоставляет возможность генерации высококачественных текстовых ответов и позволяет эффективно структурировать информацию для использования в диалоговой системе.

### 2. **Savvy (https://suvvy.ai/)**
   - **Назначение:** Разработка и настройка ИИ-ассистента.
   - **Особенности:** Платформа Savvy предлагает интуитивно понятный интерфейс для создания диалоговых моделей. Она поддерживает интеграцию с различными API, включая Google Календарь, что делает процесс записи на встречи максимально автоматизированным.

---

## Преимущества проекта

1. **Автоматизация коммуникаций:** Снижение нагрузки на менеджеров за счет автоматического ответа на типовые вопросы.
2. **Улучшение клиентского опыта:** Быстрые и точные ответы повышают удовлетворенность клиентов.
3. **Экономия времени:** Автоматическая запись на встречи и интеграция с календарем минимизируют ручной труд.
4. **Масштабируемость:** Возможность легко расширять функционал ассистента и обновлять базу знаний под новые потребности бизнеса.

---

## Пример использования

### Сценарий работы:
1. Клиент обращается к ассистенту через чат на сайте компании.
2. Ассистент приветствует клиента и предлагает помощь.
3. Клиент задает вопрос о стоимости или желает записаться на замер.
4. Ассистент предоставляет необходимую информацию или фиксирует встречу.
5. Встреча автоматически добавляется в Google Календарь сотрудника.

---

## Заключение

Разработка ИИ-ассистента для компании по установке окон — это шаг вперед в области автоматизации клиентского сервиса. Благодаря использованию передовых технологий, таких как Qwen и Savvy, проект обеспечивает высокое качество обслуживания, экономию времени и ресурсов. Этот инструмент поможет компании выделиться на рынке, повысить уровень доверия клиентов и увеличить конверсию.

