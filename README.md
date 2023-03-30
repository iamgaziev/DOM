# DOM

##  What is DOM in JavaScript?

>The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.
>
>Объектная модель документа (DOM) — это программный интерфейс для веб-документов. Он представляет страницу, чтобы программы могли изменять структуру, стиль и содержимое документа. DOM представляет документ в виде узлов и объектов; таким образом, языки программирования могут взаимодействовать со страницей.
>
>С помощью HTML DOM JavaScript может получать доступ ко всем элементам HTML-документа и изменять их.

![](/images/1.jpg)

### methods 

>innerHTML - Это свойство предоставляет простой способ полностью заменить содержимое элемента. Например, все содержимое элемента body может быть удалено:
>
>The Element property innerHTML gets or sets the HTML or XML markup contained within the element.
>
>Свойство элемента innerHTML получает или задает разметку HTML или XML, содержащуюся в элементе.

>HTML event

>An HTML event can be something the browser does, or something a user does.
>Here are some examples of HTML events:
>•An HTML web page has finished loading
>•An HTML input field was changed
>•An HTML button was clicked

>Событием HTML может быть что-то, что делает браузер, или что-то, что делает пользователь.
>Вот несколько примеров HTML-событий:
>• Веб-страница в формате HTML завершила загрузку
>• Поле ввода HTML было изменено
>• Была нажата кнопка HTML

>CreatElement()

>The JavaScript document.createElement() method allows you to create and return a new element (an empty Element node) with the specified tag name.
>
>Метод JavaScript document.createElement() позволяет создавать и возвращать новый элемент (пустой узел элемента) с указанным именем тега.

>QuerySelector()

>The Document method querySelector() returns the first Element within the document that matches the specified selector, or group of selectors. If no matches are found, null is returned.
>
>Метод querySelector() документа возвращает первый элемент в документе, который соответствует указанному селектору или группе селекторов. Если совпадений не найдено, возвращается ноль.

>AppendChild()

>
>
>


>Classlist()

>ClassList является геттером. Возвращаемый объект имеет несколько методов:
> 1) Add(добавлять) - Добавляет указанные классы к элементу
>
> 2) Remove(удалять) - Удаляет указанные классы из элемента
>
> 3) Toggle(переключать) - Если у элемента нет класса, он добавляет его, иначе удаляет. Когда в качестве второго параметра передается false, он удаляет указанный класс, а если true, добавляет его.