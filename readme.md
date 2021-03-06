<h1>ajnaBoard - the bulletin board engine on Yii2 Framework</h1>
<h1>ajnaBoard - двигун дошки оголошень на фреймворку Yii2</h1>

<b>ajnaBoard</b> - двигун дошки оголошень на фреймворку Yii2. Двигун в стадії розробки. Розробляється повність з нуля...

<h3>Встановлення ajnaBoard</h3>
<pre>
- встановіть через Composer базову версію шаблону Yii2 (http://www.yiiframework.com/download/)
командою:
<code>php composer create-project yiisoft/yii2-app-basic ./ 2.0.12</code>
- встановіть текстовий редактор - CKEditor (https://github.com/MihailDev/yii2-ckeditor) в каталог з базовим шаблоном Yii2, командою:
<code>php composer require --prefer-dist mihaildev/yii2-ckeditor "*"</code>
- встановіть файловий менеджер - ElFinder (https://github.com/MihailDev/yii2-elfinder) в каталог з базовим шаблоном Yii2, командою:
<code>php composer require --prefer-dist mihaildev/yii2-elfinder "*"</code>
- заватажте з GitHub архів зі всіма файлами <b>ajnaBoard</b> та розархівуйте в каталог де встановлений базовий шаблон Yii2, з заміною всіх файлів
- створити базу даних - ajna_board, імпортувати записи до БД з файлу <b>ajna_board.sql</b>
- після встановлення файл <b>ajna_board.sql</b> видалити.
</pre>

<b>Адміністратор:</b>
login: admin
password: 12345

<h3>Можливості двигунця:</h3>
<pre>
- додавання оголошень зареєстрованими користувачами
- додавання оголошень безкоштовно чи на платній основі (в розробці)
- багаторівневе дереро категорій оголошень (необмежена кількість вкладень)
- оголошення поділені по тимапам
- статичні сторінки на сайті з красивою адресою (Пр: http://ajnaboard.loc/ua/site/static/about) 
- статті на сайті
- багаторівневе дереро категорій статей (необмежена кількість вкладень)
- адміністрування баненрів (в розробці)
- повна багатомовність на сайті, швидке перемикання мови (en, ua, ru...)
- користувачі - реєстрація, авторизація
- окремі модулі для корстувача і адміністратора сайту
- персональні повідомлення між користувачами (в розробці)
- пошук по оголошеннях
- інтерактивний фільтр пошуку - по регіону, категорії, типу, ціні... (в розробці)
</pre>

<h3>Вже зробленено:</h3>
<pre>
<b>а) моделі:</b>
	1) Advert - оголошення;
	2) AdvertCategory - категорії оголошень (необмежена кількість вкладень);
	3) AdvertImage - картинки оголошень;
	4) AdvertType - тип оголошення (продам, куплю...);
	5) Article - статті;
	6) ArticleCategory - категорії оголошень (необмежена кількість вкладень);
	7) ArticleCategoryI18n - інтрернаціоналізація для категорій оголошень;
	8) ContactForm - форма зворотнього зв'язку;
	9) Language - модель для мови;
	10) LoginForm - модель для форми входу;
	11) PasswordResetRequestForm - модель для форми скидання паролю;
	12) Region - регіон оголошення;
	13) ResetPasswordForm - модель для форми скидання паролю;
	14) Setting - модель налаштувань;
	15) SignupForm - модель форми нового акаунту;
	16) StaticPage - статичні сторінки сайту;
	17) StaticPageI18n - інтрернаціоналізація для статичних сторінок сайту;
	18) User - модель для користувачів
</pre>
...

<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard1.png" />
<br />
<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard2.png" />
<br />
<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard3.png" />
<br />
<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard4.png" />
<br />
<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard5.png" />
<br />
<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard6.png" />
<br />
<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard7.png" />
<br />
<img src="https://github.com/YuriiRadio/ajnaBoard/blob/master/web/uploads/ajnaBoard8.png" />

Yurii Radio - 2017

