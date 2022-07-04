# ToDoList

Список задач выполнен на чистом JavaScript ES6. Демонстрация проекта: https://elhilarion.github.io/ToDoList/

Создаем в начале Function Declaration "createTodoItem". Функция, внутри которой с помощью Function Expression создаем элементы нашей будущей заметки. 

## Формирование нового элемента списка "createTodoItem"

Каждый раз мы должны создавать новый элемент списка при добавлении новой задачи. Для чего применяем метод document.createElement(tag), где вместо "tag", прописываем тег каждого под-элемента, который мы добовляем в элемент списка.

![createElement](https://github.com/ElHilarion/ToDoList/blob/main/createElement.png)

Под-элементы списка: 

![Под-элементы](https://github.com/ElHilarion/ToDoList/blob/main/items.png)
  
- checkbox, который будет зачеркивать задачу, если она выполнена;
  
- title, который будет принимать текст задачи и показывать его;
  
- textfield, само поля ввода задачи;
  
- edit, кнопка редактирования задачи;
  
- delete, кнопка удаления задачи.

![listItem](https://github.com/ElHilarion/ToDoList/blob/main/listItem.png)

listItem с классом todo-item, наш конечный родительский элемент, в который мы будем добавлять все под-элементы. Используем метод appendChild(function). Где вместо "function" мы вставляем название каждой функции под-элемента.

![appendChild](https://github.com/ElHilarion/ToDoList/blob/main/appendChild.png)

## Привязка событий "bindEvents"

Действия, осуществляемые пользователем: 

- checkbox, изменение уже существующей заметки;

- editButton, активация и сохранение изменения;

- deleteButton, удаление задачи.

## Наши функции-действия:

- addTodoItem, добавление задачи;

- editTodoItem, редактирование задачи;

- deleteTodoItem, удаление задачи.

## Доступ к DOM-элементам (html-разметка страницы)

С помощью "getElementById" и "querySelectorAll" получаем доступ соответственно по id и class элемента.   

![Доступ к DOM-элементам](https://github.com/ElHilarion/ToDoList/blob/main/id-class.png)
