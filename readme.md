ИСПРАВИТЬ

соответствие макету - 7\10
- дропдауны друг друга перекрывают  - исправил
- при уменьшении разрешения элементы вылазят на другие - исправил 

используемые технологии - 3\10
+ есть сборка через галп
- бутстреп (можно обойтись без него с CSS3 flex или grid) - использовал flex
- нет лайвсервера с удобным рефрешем проекта при изменении - добавил flex, удалил бутстрап библиотеку
- нет препроцессоров, .css файлы структурированы очень плохо - использовал препроцесор sass, структурировал файлы, использовал переменные, добавил миксины

семантичность - 3\10
- большинство списков\секций это просто div 
исправил по возможности

анимации - 5\10
+ кнопки в основном все имеют фокус анимацию
- дропдауны\инфобоксы без анимации (fadein\fadeout)
исправил

Start project
npm install 
npm install gulp --save-dev

запускеаем все с помощью команды
gulp