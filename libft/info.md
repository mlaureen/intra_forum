## General info about libft

### Author: [@ayellin](https://profile.intra.42.fr/users/ayellin)

#### Chekers:

- [BeerTest](https://github.com/Dgreat21/21libftbeertest)
 говорят что проверяет прототипы функций
- [Libftest](https://github.com/jtoty/Libftest)
тестирует в том числе норминет и makefile 
- [42FileCheker](https://github.com/jgigault/42FileChecker)
основной чекер с хорошим интерфейсом. 
- [libft-unit-test](https://github.com/alelievr/libft-unit-test)
 входит в состав 42 File Cheker. Если поставить отдельно то тестирует
 юникод у `ft_putchar` и переполнение у `ft_atoi`
- [libft_test_system](https://github.com/sitlcead/42_libft_test_system)
  Хороший чекер со множеcтвом тестов. При использовании юникода в `ft_putchar` некоторые тесты не пройдут проверку

#### F.A.Q

Внимательней прочитайте subject. На большинство вопросов там есть ответы.

1) **ВОПРОС:** Как составить правильный Makefile?

   **ОТВЕТ:** Универсального ответа на это нет. Важно чтобы он соответстоввал нормам. Некоторые пиры требуют что бы он с make дейстововал по правилу: "Нет изменений - не должен перекомпиливать. Есть изменения - должен перекомпилить". Хорошей практикой использования make считается перекомпиляция только если были изменены исходники. Это можно сделать с помощью неявныx правил и автоматических переменных в make (%.o, ... )
   
2) **ВОПРОС**:Нужно ли добавлять поддержку unicode в `ft_putchar` или переполнение в `ft_atoi`?
   
   **ОТВЕТ:** `@hgreenfe`: вопрос мировоззрения и холиваров. Зависит от пиров и тебя. Мулинет не проверяет
   
3) **ВОПРОС**: Можно ли пушить свои файлы и использовать их в своей библиотеке

   **ОТВЕТ**:- Да, это поощряется. См. ссылку про порядок функций.

4) **ВОПРОС**: Нужно ли писать свои тесты, когда есть уже готовые чекеры?

   **ОТВЕТ**: Опытные пиры и сами педагоги 42 советуют писать свои тесты чтобы лучше понять специфику функций и суметь их починить если что-то сломалось или защитить при особо строгой проверке пирами. Также в некоторых случаях можно попробовать тестировать своими тестами тесты других пиров.

5) **ВОПРОС**: Почему этот проект полезен?

   **ОТВЕТ:** На примере этого проекта можно осовоить базовые функции в С плюс опытные пиры говорят что используют библиотеку (расширенную версию конечно) во всех школьных проектах на С.

#### Useful posts:

1) Про обработку переполнения в `ft_atoi`
   - [Original](https://forum.intra.42.fr/topics/21586/)
   - [Github](https://github.com/Danilo3/intra_forum/blob/master/libft/atoi.md)
 
2) Как не завалить первую библиотеку
   - [Original](https://forum.intra.42.fr/topics/19883/)
   - [Github](https://github.com/Danilo3/intra_forum/blob/master/libft/libft-commmon_errors.md)
 
3) про `ft_strlcat`
   - [Original](https://forum.intra.42.fr/topics/20387/)
   - [Github](https://github.com/Danilo3/intra_forum/blob/master/libft/strlcat.md)

4) про порядок функций
   - [Origin](https://forum.intra.42.fr/topics/20397/messages)
   - [Github](https://github.com/Danilo3/intra_forum/blob/master/libft/libft_puzzles.md)

5) про Makefile
   - [Origin](https://forum.intra.42.fr/topics/20222/messages)
   - [Github](https://github.com/Danilo3/intra_forum/blob/master/libft/makefile.md)
6) про Memmove
   - [Toster](https://toster.ru/q/303725)
