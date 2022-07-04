# ToDoList

Список задач выполнен на чистом JavaScript ES6. Демонстрация проекта: https://elhilarion.github.io/ToDoList/

Создаем в начале Function Declaration "createTodoItem". Функция, внутри которой с помощью Function Expression создаем элементы нашей будущей заметки. 

Каждый раз мы должны создавать новый элемент <li> списка <ul> при добавлении новой задачи. Для чего применяем метод document.createElement(tag), где вместо (tag), прописываем тег каждого под-элемента, который мы добовляем в элемент списка.

Соответственно необходимо создать следующие под-элементы списка: 
  
- checkbox, который будет зачеркивать задачу, если она выполнена;
  
- title, который будет принимать текст задачи и показывать его;
  
- textfield, само поля ввода задачи;
  
- edit, кнопка редактирования задачи;
  
- delete, кнопка удаления задачи;
  

  



<--! listItem.appendChild(checkbox);
<input class="checkbox" type="checkbox">

listItem.appendChild(label);
<label class="title">Изучить JavaScript</label>

listItem.appendChild(editInput);
<input class="textfield" type="text">

listItem.appendChild(editButton);
<button class="edit">Изменить</button>

listItem.appendChild(deleteButton)
<button class="delete">Удалить</button> -->
