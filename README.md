# ToDoList

Список задач выполнен на чистом JavaScript ES6. Демонстрация проекта: https://elhilarion.github.io/ToDoList/

Создаем в начале Function Declaration "createTodoItem". Функция, внутри которой с помощью Function Expression создаем элементы нашей будущей заметки. 

Нам необходимо создавать новый элемент <li> списка <ul> при добавлении новой задачи. 

`<input class="checkbox" type="checkbox">
  
<label class="title">Изучить JavaScript</label>
  
<input class="textfield" type="text">
  
<button class="edit">Изменить</button>
  
<button class="delete">Удалить</button>`

listItem.appendChild(checkbox);
<input class="checkbox" type="checkbox">

listItem.appendChild(label);
<label class="title">Изучить JavaScript</label>

listItem.appendChild(editInput);
<input class="textfield" type="text">

listItem.appendChild(editButton);
<button class="edit">Изменить</button>

listItem.appendChild(deleteButton)
<button class="delete">Удалить</button>
