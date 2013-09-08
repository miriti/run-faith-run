Run, Faith, Run
======

Собственно...
-------------  

Собственно вот. Представляю вашему вниманию самый унылый раннер на свете. Хотелось сделать убийцу Mirror's Edege, но от чего-то не вышло. Получилось даже проще чем Canabalt и даже далеко не так динамично и вечело как там :) Объясняется это тем, что основной задачей на этом конкурсе я ставил перед собой практику на C++ с использованием SDL. Геймдизайну не уделено ни минуты времени на этот раз.
Схороню ка правила тут на всякий случай:

Конкурс №99 "Run to School"
---------------------------
  
Runner Как вы, наверное, догадались темой 99 конкурса становится раннер.
Общие рамки правил очертим так:
В играх этого жанра существует непреодолимый и неконтролируемый напрямую игроком процесс движения, а игрок, манипулируя другими параметрами (изменяя траекторию, прыгая, стреляя, дергая за рычаги и т.д.) пытается поддерживать этот процесс как можно дольше.
В общем бежим и преодолеваем препятствия, все просто. Ну или летим и уворачиваемся от камней. Ну или ползём и... Ну вы поняли.

Бонусы будем давать за:
Однокнопочное управление в игре(это не распространяется на выход из игры по esc и на неигровые меню, в которых управление может быть любым);
Игровые поощрения - топ игроков, медальки, рекорды, общий игровой прогресс, отмеченный на карте или другие средства мотивации и хм.. крутомерства игроков.
Бесконечный игровой процесс.

Конкурс проходит с 31.08.13 по 9.09.13 включительно.
Ограничение на размер работы - 15 Мб.

Управление
----------

Можно управлять только одной клавишей. Например *пробел* или *вверх* ну или если хочется как в Canabalt то *x* или *c*

Системные требования
--------------------

Ну вообще все это дело написано на C++, скомпилировано gcc и использует SDL что означает что особых экзотических системных требований нет. Все нужные библиотеки приложены к бинарникам. Заголовки и lib'ы SDL для компиляции можно найти тут: http://www.libsdl.org/download-2.0.php

**ВАЖНО!** По неизвестной причине игра иногда не запускается и падает на моменте загрузки звуков. На данный момент проблеме не решена. Для того, чтобы это избежать, можно запустить программу с ключом `-nosnd` который, как ни странно, запустит игру с отключенным звуком.

Вообще SDL этот у меня оставляет неоднозначные чувства. С одной стороны прослойка сделана довольно удобно, достаточно гибко и весьма переносимо. Но вот таскать за собой все эти .dll... Только для такой маленькой поделки пришлось прицепить аж 13 (!!!) библиотек!!! ТРИНАДЦАТЬ! Да, в теории можно было бы их запихать все в один exe, но это противоречит условиям лицензии, а я чувствую себя не комфортно и неуверенно когда знаю что нарушаю условия лицензии :) Так что вот. Может быть просто привык я ко всем этим Джавам и ЭкшенСкриптам где все можно запихать в один файл..

Авторы
------
* Код, "Арт": Михаил KEFIR Мирити <kefir.rwr@gmail.com>
* Музыка: Solar Fields - Boat (Mirror's Edge Original Videogame Score)
* Sfx: Выдернуто из Mirror's Edge


------
2013 (с)