# Bootstrap-классы HobbyFest


CSS в таблице немного упрощён: настоящий Bootstrap также использует `!important`, CSS-переменные и дополнительные служебные правила.

| Bootstrap-класс | Расшифровка названия | Примерный обычный CSS | Краткое описание |
|---|---|---|---|
| `.container` | `container` — контейнер | `width: 100%; max-width: зависит от breakpoint; margin-inline: auto;` | Центрирует содержимое и ограничивает его максимальную ширину. |
| `.h-100` | `h` = `height`; `100` = 100% | `height: 100%;` | Растягивает элемент на всю высоту родителя. |
| `.min-vh-100` | `min` — минимальный; `vh` = viewport height | `min-height: 100vh;` | Задаёт минимальную высоту, равную высоте окна браузера. |
| `.object-fit-cover` | `object-fit: cover` — заполнить область объектом | `object-fit: cover;` | Заполняет область изображением без искажения, при необходимости обрезая края. |
| `.opacity-25` | `opacity` — прозрачность; `25` = 25% | `opacity: .25;` | Устанавливает непрозрачность элемента на 25%. |
| `.d-flex` | `d` = `display`; `flex` — Flexbox | `display: flex;` | Делает элемент flex-контейнером. |
| `.flex-row` | `flex`; `row` — строка | `flex-direction: row;` | Располагает flex-элементы горизонтально. |
| `.flex-column` | `flex`; `column` — колонка | `flex-direction: column;` | Располагает flex-элементы вертикально. |
| `.flex-sm-row` | `flex`; `sm` — ≥576px; `row` — строка | `@media (min-width: 576px) { flex-direction: row; }` | Начиная с SM располагает элементы горизонтально. |
| `.flex-sm-column` | `flex`; `sm` — ≥576px; `column` — колонка | `@media (min-width: 576px) { flex-direction: column; }` | Начиная с SM располагает элементы вертикально. |
| `.flex-grow-1` | `grow` — расширение; `1` — включено | `flex-grow: 1;` | Позволяет flex-элементу занять оставшееся место. |
| `.align-items-center` | `align-items`; `center` — центр | `align-items: center;` | Центрирует элементы по поперечной оси flex-контейнера. |
| `.justify-content-between` | `justify-content`; `between` — между | `justify-content: space-between;` | Размещает свободное пространство между элементами. |
| `.gap-2` | `gap` — промежуток; `2` — размер | `gap: .5rem;` | Добавляет промежуток `.5rem` между элементами. |
| `.gap-3` | `gap` — промежуток; `3` — размер | `gap: 1rem;` | Добавляет промежуток `1rem` между элементами. |
| `.overflow-hidden` | `overflow` — переполнение; `hidden` — скрыто | `overflow: hidden;` | Скрывает содержимое, выходящее за границы элемента. |
| `.position-relative` | `position`; `relative` — относительное | `position: relative;` | Создаёт точку отсчёта для абсолютно позиционированных потомков. |
| `.position-absolute` | `position`; `absolute` — абсолютное | `position: absolute;` | Позволяет разместить элемент по координатам поверх других элементов. |
| `.top-0` | `top` — сверху; `0` — ноль | `top: 0;` | Прижимает позиционированный элемент к верхнему краю. |
| `.top-50` | `top` — сверху; `50` = 50% | `top: 50%;` | Размещает верхний край элемента на середине родителя. |
| `.start-0` | `start` — начало строки; `0` — ноль | `left: 0;` | Прижимает элемент к началу строки. В LTR — влево. |
| `.start-50` | `start` — начало строки; `50` = 50% | `left: 50%;` | Размещает начало элемента на середине родителя. |
| `.translate-middle` | `translate` — сдвиг; `middle` — середина | `transform: translate(-50%, -50%);` | Сдвигает элемент для точного центрирования. |
| `.z-1` | `z` = `z-index`; `1` — уровень | `z-index: 1;` | Поднимает элемент над слоями с меньшим `z-index`. |
| `.col-12` | `col` = `column`; `12` из 12 | `width: 100%;` | Занимает всю строку. |
| `.col-sm-6` | `col`; `sm` — ≥576px; `6` из 12 | `@media (min-width: 576px) { width: 50%; }` | Начиная с SM занимает половину строки. |
| `.col-sm-12` | `col`; `sm` — ≥576px; `12` из 12 | `@media (min-width: 576px) { width: 100%; }` | Начиная с SM занимает всю строку. |
| `.col-md-4` | `col`; `md` — ≥768px; `4` из 12 | `@media (min-width: 768px) { width: 33.333333%; }` | Начиная с MD занимает треть строки. |
| `.col-md-6` | `col`; `md` — ≥768px; `6` из 12 | `@media (min-width: 768px) { width: 50%; }` | Начиная с MD занимает половину строки. |
| `.col-xl` | `col`; `xl` — ≥1200px | `@media (min-width: 1200px) { flex: 1 0 0%; }` | Начиная с XL делит строку поровну с соседними колонками. |
| `.g-3` | `g` = `gutter`; `3` — размер | `--bs-gutter-x: 1rem; --bs-gutter-y: 1rem;` | Добавляет промежутки между строками и колонками. |
| `.px-4` | `p` = `padding`; `x` — горизонталь; `4` — размер | `padding-inline: 1.5rem;` | Добавляет горизонтальные внутренние отступы. |
| `.py-4` | `p` = `padding`; `y` — вертикаль; `4` — размер | `padding-block: 1.5rem;` | Добавляет вертикальные внутренние отступы. |
| `.py-md-5` | `p`; `y`; `md` — ≥768px; `5` — размер | `@media (min-width: 768px) { padding-block: 3rem; }` | Начиная с MD увеличивает вертикальные отступы. |
| `.m-0` | `m` = `margin`; `0` — ноль | `margin: 0;` | Убирает все внешние отступы. |
| `.ms-auto` | `m` = `margin`; `s` = `start`; `auto` | `margin-left: auto;` | Сдвигает элемент к концу строки в LTR. |
| `.mt-auto` | `m` = `margin`; `t` = `top`; `auto` | `margin-top: auto;` | Прижимает элемент вниз внутри flex-контейнера. |
| `.mb-4` | `m` = `margin`; `b` = `bottom`; `4` — размер | `margin-bottom: 1.5rem;` | Добавляет нижний внешний отступ. |
| `.text-white` | `text`; `white` — белый | `color: white;` | Делает текст белым. |
| `.text-start` | `text`; `start` — начало строки | `text-align: left;` | Выравнивает текст по началу строки. |
| `.text-center` | `text`; `center` — центр | `text-align: center;` | Центрирует текст. |
| `.text-sm-center` | `text`; `sm` — ≥576px; `center` | `@media (min-width: 576px) { text-align: center; }` | Начиная с SM центрирует текст. |
| `.fw-bold` | `fw` = `font-weight`; `bold` — жирный | `font-weight: 700;` | Делает текст жирным. |
| `.fs-4` | `fs` = `font-size`; `4` — размер | `font-size: 1.5rem;` | Устанавливает четвёртый размер шрифта Bootstrap. |
| `.h5` | заголовок пятого уровня | `font-size: 1.25rem; font-weight: 500;` | Оформляет элемент визуально как `<h5>`. |
| `.bg-dark` | `bg` = `background`; `dark` — тёмный | `background-color: var(--bs-dark);` | Задаёт стандартный тёмный фон Bootstrap. |
| `.btn` | `button` — кнопка | `display: inline-block; padding: .375rem .75rem; border: 1px solid;` | Включает базовое оформление кнопки. |
| `.btn-primary` | `button`; `primary` — основной | `background-color: var(--bs-primary); color: white;` | Применяет основной цвет Bootstrap к кнопке. |
| `.navbar` | `navigation bar` — навигационная панель | `display: flex; flex-wrap: wrap; align-items: center;` | Создаёт основу адаптивной навигационной панели. |
| `.navbar-expand-sm` | `navbar`; `expand` — раскрывать; `sm` — ≥576px | `@media (min-width: 576px) { flex-wrap: nowrap; }` | Показывает полную навигацию начиная с SM. |
| `.navbar-dark` | `navbar`; `dark` — тёмная тема | `--bs-navbar-color: rgba(255,255,255,.55);` | Настраивает Navbar для тёмного фона. |
| `.navbar-brand` | `navbar`; `brand` — название бренда | `font-size: 1.25rem; text-decoration: none;` | Оформляет логотип или название сайта. |
| `.navbar-toggler` | `navbar`; `toggler` — переключатель | `padding: .25rem .75rem; border: 1px solid;` | Оформляет кнопку мобильного меню. |
| `.navbar-toggler-icon` | `navbar`; `toggler`; `icon` — значок | `width: 1.5em; height: 1.5em;` | Отображает стандартный значок hamburger. |
| `.navbar-collapse` | `navbar`; `collapse` — сворачивание | `flex-basis: 100%; flex-grow: 1;` | Подготавливает навигацию к сворачиванию. |
| `.navbar-nav` | `navbar`; `nav` = navigation | `display: flex; flex-direction: column; list-style: none;` | Оформляет список ссылок внутри Navbar. |
| `.nav-item` | `navigation item` — элемент навигации | `/* служебный класс */` | Обозначает элемент списка навигации. |
| `.nav-link` | `navigation link` — навигационная ссылка | `display: block; padding: .5rem 1rem;` | Оформляет ссылку внутри навигации. |
| `.collapse` | `collapse` — сворачивать | `display: none;` | Скрывает блок до его раскрытия Bootstrap JavaScript. |
| `.card` | `card` — карточка | `display: flex; flex-direction: column; border: 1px solid;` | Создаёт контейнер Bootstrap Card. |
| `.card-img-top` | `card`; `image`; `top` — сверху | `width: 100%; border-radius: верхние углы;` | Оформляет изображение карточки. |
| `.card-body` | `card`; `body` — содержимое | `flex: 1 1 auto; padding: 1rem;` | Создаёт внутреннюю область карточки. |
| `.card-title` | `card`; `title` — заголовок | `margin-bottom: .5rem;` | Оформляет заголовок карточки. |
| `.card-text` | `card`; `text` — текст | `/* служебные правила текста */` | Обозначает основной текст карточки. |
| `.shadow-sm` | `shadow` — тень; `sm` = small | `box-shadow: 0 .125rem .25rem rgba(0,0,0,.075);` | Добавляет небольшую тень. |
| `.bi` | `Bootstrap Icons` | `font-family: "bootstrap-icons";` | Включает базовое оформление значка. |
| `.bi-facebook` | `Bootstrap Icon: Facebook` | `::before { content: код значка; }` | Показывает значок Facebook. |
| `.bi-instagram` | `Bootstrap Icon: Instagram` | `::before { content: код значка; }` | Показывает значок Instagram. |
| `.bi-twitter-x` | `Bootstrap Icon: Twitter/X` | `::before { content: код значка; }` | Показывает значок X (Twitter). |

## Сокращения в названиях

| Сокращение | Значение |
|---|---|
| `m` | `margin` — внешний отступ |
| `p` | `padding` — внутренний отступ |
| `t` | `top` — сверху |
| `b` | `bottom` — снизу |
| `s` | `start` — начало строки |
| `x` | горизонтальная ось: слева и справа |
| `y` | вертикальная ось: сверху и снизу |
| `h` | `height` — высота |
| `d` | `display` — способ отображения |
| `g` | `gutter` или `gap` — промежуток |
| `col` | `column` — колонка |
| `bg` | `background` — фон |
| `fw` | `font-weight` — насыщенность шрифта |
| `fs` | `font-size` — размер шрифта |
| `bi` | `Bootstrap Icons` — библиотека значков |
| `sm` | `small` — breakpoint от 576px |
| `md` | `medium` — breakpoint от 768px |
| `xl` | `extra large` — breakpoint от 1200px |

Шкала размеров Bootstrap:

```text
0 = 0
1 = 0.25rem
2 = 0.5rem
3 = 1rem
4 = 1.5rem
5 = 3rem
```
