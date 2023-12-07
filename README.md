# Streamlit RecSys

## Demo
[Streamlit Cloud]()

## Backlog

**Далее**

- [ ] Добавить `selectbox()` для выбора типа модели и подключить к коду приложения
- [ ] Составить выборку с оценками фильмов пользователями
- [ ] GitHub репозиторий проекта, с последующим merge request от каждого студента
- [ ] Добавить идентификацию пользователей (своя реализация или `streamlit credentials`)
- [ ] Сохранять выбор пользователя (`user_login`, `user_password`, `added_movies`)
- [ ] Сохранять рейтинг выбранных пользователем фильмов (`st.slider` или `st.number_input`)
- [ ] Модель на основе предпочтений пользователей (по списку фильмов, после и по рейтингу)
- [ ] Деплой приложения в облачный сервис (streamlit-hub, hf spaces, heroku)

---
**Если успеем**
- [ ] Добавить метрики качества рекомендаций для модели по пользователям
- [ ] ФидБек рекомендаций от пользователей
- [ ] A/B тестирование на пользователях (сами сделаем или попросим студентов)

---
**Реализовано**
- [x] Исправить проблему со ссылками на постеры
- [x] Базовая модель коллаборативной фильтрации с простой сортировкой, ранкингом, по `cos_sim score`
- [x] Исправить проблему с выводом выбранных фильмов в рекомендациях модели
- [x] Добавить альтернатиную сортировку, ранкинг, по популярности фильма (`popularity`)

## Prerequisite

- Python 3.8+

## Installation

```
pip install -r requirements.txt
```

## How to Run App locally

```
streamlit run main.py
```
