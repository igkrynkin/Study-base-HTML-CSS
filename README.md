1. HTML-CSS - изменения цвета выделения и букв при выделении текста <br>
2. Псевдоклассы - first-child-last-child-nth-child <br>
3. БЭМ-1 - Блок, элемент, модификатор <br>
4. a:link - Должен быть определённый порядок псевдоклассов link-visited-hover-active, только в такой последовательности будут работать корректно стили <br>
5. Псевдоэлементы ::Before и ::After - ::Before - перед элементом, ::After - после элемента <br>
6. БЭМ-2 - Запись через блок__элемент_модификатор <br>
7. БЭМ-3 - Nested, это файловая структура, в которой каждому из созданного нами классов создаётся отдельный CSS фаил и всё это расскидывается по папкам в соответствии с иерархией <br>
8. Анимация ссылок при наведении - за стиль элемента при наведении на него курсора мыши отвечает псевдокласс :hover.
Плавный переход от одного значения к другому при наведении делается с помощью свойства transition, которое устанавливает время перехода.
:hover можно комбинировать с псевдоэлементами ::before и ::after для добавления к ссылке дополнительного декоративного оформления.
Схожего результата можно добиться, используя фон, созданный с помощью линейного градиента. Меняя параметры фона можно добиться различных эффектов при наведении курсора на ссылку.
9. Создание форм отправки HTML-CSS