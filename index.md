# Структура проекта: AI Dashboard с интеграцией данных

## **ГЛАВНАЯ ЦЕЛЬ**
**Создать рабочий дашборд с интегрированным AI, который сам себя "рассказывает" и предлагает решения**

## **ТЕКУЩАЯ СИТУАЦИЯ**

### Имеющиеся ресурсы
- **Технологии готовы** (графики, AI)
- *Планируемая архитектура: Streamlit + Plotly + AI интерпретация*
- *Возможная альтернатива: Vegalite + Altair*

### **КЛЮЧЕВАЯ ПРОБЛЕМА: Отсутствие бизнес-требований**

![](https://i.imgur.com/2jp71pc.png)

#### Низкая культура работы с данными
- **Отчеты используются только для отчетности**, а не для принятия решений
- **Отсутствует data-driven подход** ("мерий то чем управляешь")
- *Спекуляция общепринятыми показателями*
- *Стремление показать только высокие показатели и приросты*

#### Сопротивление линейных менеджеров
- **Не могут ответить на вопросы о метриках** и управлении продуктом
- *Причины сопротивления:*
 - *Никогда не искали эти ответы*
 - *Боятся конкуренции*

## **СТРАТЕГИЯ РЕШЕНИЯ**

### **Следующий шаг: Работа с руководителем управления**
*Поскольку линейные менеджеры "ходят на поклон" к руководителю управления*

#### Цель встречи с руководителем
- **Выяснить какие данные он хочет видеть**
- **Понять как планирует их использовать**
- *Определить роль AI в интерпретации данных*

### **ТРЕБУЕТСЯ: План вопросов для максимизации пользы от встречи**

## **ТЕХНИЧЕСКАЯ КОНЦЕПЦИЯ**

### Архитектура приложения
- **3-4 логические секции на Streamlit**
- *Частичная интерактивность через фильтры в сайдбаре*
- *Графики Plotly без взаимодействия между собой*

### **Революция в потреблении информации**

#### Традиционный подход (устаревший)
*Многоуровневая передача информации:*
- *Получение данных снизу*
- *Группировка и передача наверх*
- *"Рассказ слайдов" на каждом уровне*
- *Менеджер как оператор презентации*

#### **Проблемы существующих BI систем**
- *Чтение данных требует навыков*
- *Интерпретация в знание и решения - искусство менеджмента*

### **Инновационное решение с AI**
**LLM модели (развиваются 2,5 года) превосходят людей в интерпретации данных**

#### Функционал AI Dashboard
- **Красивая визуализация данных** (Plotly)
- **AI интерпретирует видимую часть графика**
- **Констатирует данные и предлагает идеи/решения**
- *Может успокаивать при необходимости*

## **БУДУЩЕЕ РАЗВИТИЕ**
*Следующая версия: интеграция с задачником для автоматического создания и отправки задач на исполнение*

---

## **КРИТИЧЕСКИЕ ВОПРОСЫ ДЛЯ ДАЛЬНЕЙШЕЙ РАБОТЫ**
1. **Какие конкретные данные нужны руководителю управления?**
2. **Как он планирует использовать эти данные для принятия решений?**
3. *Какой дополнительной информации не хватает для формирования вопросов?*
