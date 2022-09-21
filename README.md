# my_film
Сайт для просмотра кино v.1.0


На сайте написано много всего, а именно:


- Добавление категорий, жанров, кадров из кино, которые можно присваивать к фильмам, сериалам и др. 


- Добавление актёров и режиссёров, которых нужно прикреплять во время добавления фильма, для них будет создана отдельная страница, на которую можно перейти 
  нажав на ссылку в описании фильма
    name - Имя
    age - Возраст
    description - Описание актёра или режиссёра
    image - Фотография 
  
  
  
- Добавление фильма со следующими критериями:
    title - Название фильма
    
    tagline - Слоган фильма
    
    description - Описание  фильма
    
    poster - Постер, главная фотография, обложка для фильма
    
    year - Год выпуска фильма
    
    country - Страна выпуска фильма
    directors - Режиссёры, которые были добавлены
    actors - Актёры, которые были добавлены
    genres - Жанры, которые были добавлены
    world_premiere - Премьера в мире
    budget - Бюджет
    fees_in_USA - сборы в Америке
    fees_in_world - сборы в мире
    category - категории, которые были добавлены
    url - URL страницы, который хотите отображать
    draft - Хотите ли добавить фильм в черновик
    trailer - Трейлер к фильму на YouTube
    
    
    
 - Отзывы и рейтинг к фильму
На каждой страничке фильма, можно оставлять:
  Рейтинг:
       В характеристиках фильма, наводя курсором на звёзды ( Используется JavaScript ) выбираем количество звёзд, 
       которые хотите поставить и нажимаете левый клик, после этого в нашей бд , появляется запись: ip пользователя, фильм, рейтинг(update_or_create)

  Отзыв:
     Ниже трейлера можно оставлять отзыв к фильму или отзыв к отзыву(Родитель), используя форму ( Имя, Email, Комментарий ) 
     
     Отзывы храняться в формате: 
        Имя пользователя
        Email пользователя
        ID отзыва
        Родитель отзыва, если он есть


P.S.  В ближайшее время переделаю хранение данных с sqlite3 на postgresql 