Разметка страницы Студия набрана в файле index.html.
В шапке репозитория есть ссылка на живую страницу.

                          ***
Разметка страницы Портфолио набрана в файле portfolio.html.
Атрибут href навигационных ссылок Студия и Портфолио содержит относительный путь к html-файлам соответствующих страниц.
Выделена палитра цветов макета и для её хранения использованы CSS-переменные.
Оформлены эффекты (изменение цвета текста) наведения и фокусировки для интерактивных текстовых элементов.

                          ***
Вёрстка фиксированная, в пикселях, размеры блоков соответствуют макету.
Корректно заданы и использованы margin и padding.
У детей нет внешних отступов margin пробивающих родителя.
Создан div.container и использован для обёртки и центрирования блоков контента (секции, шапка, футер и т. д.).
Ширина div.container взята и макета.
Расположение элементов, позиционирование которых используя стандартный поток документа невозможно, сделано с помощью Flexbox.

                          ***
Все растровые и векторные изображения оптимизированы.
Создан один SVG-спрайт для всех иконок. Для генерации спрайта использовал Icomoon.
Размеры иконок соответствуют макету.
Большое изображение с эффектом затемнения (под шапкой) оформлено как фон. Для затемнения используется многослойный фон с градиентом.
В блоке Контактов в шапке, добавлены иконки конверта и телефона.
В секции Преимуществ добавлены иконки.
В секции Команды добавлены иконки соцсетей.
В секции Клиентов добавлены иконки компаний.
В футере добавлены иконки соцсетей.
На карточках команды есть постоянный эффект тени.
На карточках портфолио есть эффект тени при ховере по карточке.

                          ***
Для всех эффектов ховера и фокуса сделаны переходы. Время - 250ms, функция распределения времени - cubic-bezier(0.4, 0, 0.2, 1).
В главной навигации, при помощи псевдоэлемента, сделано подчёркивание текущей ссылки.
В секции Чем мы занимаемся текст спозиционирован поверх изображения.
В секции Портфолио, синий оверлей с текстом поверх изображения выезжает снизу изображения.

Есть разметка и оформление модального окна и его бекдропа (тёмного полупрозрачного фона).
Изначально модальное окно скрыто при помощи класса is-hidden (свойства visibility, opacity и pointer-events). Если класс убрать - модалка появляется.
Появление и скрытие модального окна анимированы при помощи перехода с произвольным эффектом, например scale или translate, и opacity.