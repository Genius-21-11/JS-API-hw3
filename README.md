# JavaScript про API браузеров (семинары) 
## Урок 3. Сетевые запросы 
### Цель: Разработать веб-приложение, которое каждый день будет отображать новое случайное изображение из коллекции Unsplash, давая пользователю возможность узнать больше о фотографе и сделать "лайк" изображению. 
### Регистрация на Unsplash: 
• Перейдите на веб-сайт Unsplash (https://unsplash.com/).

• Зарегистрируйтесь или войдите в свой аккаунт. (если у вас не было регистрации до этого, новый аккаунт создавать не нужно).

### Создание приложения: 
• Перейдите на страницу разработчика Unsplash (https://unsplash.com/developers).

• Нажмите "New Application". 

• Заполните необходимую информацию о приложении (можете использовать http://localhost для тестирования). 

• Получите свой API-ключ после создания приложения.

### Разработка веб-приложения: 
• Создайте HTML-страницу с элементами: изображение, имя фотографа, кнопка "лайк" и счетчик лайков. 

• Используя JavaScript и ваш API-ключ, получите случайное изображение из Unsplash каждый раз, когда пользователь загружает страницу. 

• Отобразите информацию о фотографе под изображением.

• Реализуйте функционал "лайка". Каждый раз, когда пользователь нажимает кнопку "лайк", счетчик должен увеличиваться на единицу.

### * Дополнительные задачи (по желанию):

 • Добавьте функцию сохранения количества лайков в локальное хранилище, чтобы при новой загрузке страницы счетчик не сбрасывался.
 
 • Реализуйте возможность просмотра предыдущих "фото дня" с сохранением их в истории просмотров.
