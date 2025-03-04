# RetroFlux Moto

[RetroFlux Moto](https://aleks-bitkov.github.io/retroflux-moto/) — це інтернет-магазин, що спеціалізується на продажу мотоциклів різних категорій та комплектуючих до них.

## Використані технології
Проєкт реалізовано з використанням таких технологій:

[JavaScript](https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg) JavaScript
[HTML5](https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg) HTML5
[CSS3](https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg) CSS3
[SCSS (SASS)](https://upload.wikimedia.org/wikipedia/commons/9/96/Sass_Logo_Color.svg) SCSS (SASS)
[Webpack](https://upload.wikimedia.org/wikipedia/commons/9/94/Webpack.svg) Webpack
[Gulp](https://upload.wikimedia.org/wikipedia/commons/7/72/Gulp.js_Logo.svg) Gulp
[W3C](https://www.w3.org/assets/logos/w3c/w3c-bars.svg) W3C

Верстка виконана відповідно до методології БЕМ, сайт є повністю адаптивним (до розширення 320px) і містить семантичну розмітку. У проєкті використовувалися відносні одиниці вимірювання (rem, %), що забезпечує гнучкість дизайну.

## Основні сторінки

### Головна сторінка
На головній сторінці користувач одразу бачить акційні пропозиції, представлені у вигляді автоматичного слайдера. Додатково реалізовано зірковий рейтинг товарів, що були придбані, а також тематичні слайдери для акційних товарів.

### Сторінка товарів
Ця сторінка містить таби для вибору категорій товарів, а також систему фільтрації, яка дозволяє згортати та розгортати пункти. Вибрані фільтри відображаються безпосередньо під табами. 

Картки товарів мають додатковий функціонал: можливість зміни кольору транспортного засобу (за наявності опції), додавання товару до списку улюблених, а також відображення акційних пропозицій із зазначенням відсотка знижки, старої (закресленої) та нової ціни.

### Сторінка товару
Сторінка конкретного товару містить зображення з можливістю перегляду збільшеного варіанта (зум-ефект), а також додаткові фото та відео. При натисканні на будь-яке зображення відкривається модальне вікно зі слайдерами, що дозволяють переглядати всі доступні варіанти товару.

Також реалізовано систему коментарів, де користувачі можуть залишати свої відгуки. Наприкінці сторінки розміщено слайдер із відеовідгуками, що містять вбудовані відео з YouTube.

### Сторінка блогу
На сторінці розміщено всі статті та новини, пов'язані з мотоциклами. Інтерактивні елементи дозволяють переглядати короткий опис статті при наведенні, а для довгих статей передбачена кнопка «Додати до збережених». У бічному меню (aside) розміщено вбудовані відео з YouTube.

### Сторінка статті
Ця сторінка містить повний текст обраної статті.

### Сторінка "Часті питання" (ЧаП)
Сторінка складається з табів (змісту) та інтерактивного акордеону, що містить запитання та відповіді, які розгортаються при натисканні.

### Сторінка "Про нас"
Містить інформацію про компанію, її місію, філософію, історію та основні цілі.

## Головне навігаційне меню (Header)
Навігаційне меню забезпечує зручний доступ до основних сторінок сайту. Особливо цікавим є пункт "Товари", який відкриває підменю для вибору категорій і одночасно дозволяє відфільтрувати товари. Наприклад, категорія "Ретро" містить підкатегорію "Кафе-рейсери", яка, у свою чергу, розділяється на "Класичні" та "Нео-ретро".

Крім того, у хедері є:
- **Швидкий пошук**, реалізований у вигляді модального вікна.
- **Кошик**, який відкривається у вигляді компактного модального вікна.
- **Кнопка налаштувань та персональної навігації**, що надає доступ до параметрів облікового запису користувача.

Цей проєкт розроблений з акцентом на зручність користувачів, адаптивність та функціональність, забезпечуючи комфортний процес вибору та покупки товарів.
