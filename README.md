# PI-school 2019


## Week 1
- Ознакомление с Android Studio и создание приложениия с ноля + первоначальные материалы для изучения
  
  - https://developer.android.com/training/basics/firstapp 
  - https://developer.android.com/guide/components/fundamentals
  - https://developer.android.com/guide/topics/resources/providing-resources
  - https://developer.android.com/guide/topics/manifest/manifest-intro 
  - https://developer.android.com/studio/intro
- Задания и CodeLabs
  - https://codelabs.developers.google.com/codelabs/android-training-hello-world/index.html?index=..%2F..android-training

  - https://codelabs.developers.google.com/codelabs/android-training-layout-editor-part-a/index.html?index=..%2F..android-training

  - https://codelabs.developers.google.com/codelabs/android-training-layout-editor-part-b/index.html?index=..%2F..android-training

- Создание приложения с разными экранами и лейаутами

  - https://developer.android.com/guide/components/activities/intro-activities
  - https://developer.android.com/guide/components/activities/activity-lifecycle
  - https://developer.android.com/training/basics/intents - вся секция
  - https://developer.android.com/guide/topics/ui/declaring-layout
  - https://developer.android.com/guide/topics/ui/layout/linear
  - https://developer.android.com/guide/topics/ui/layout/relative
  - https://developer.android.com/training/constraint-layout
  - https://guides.codepath.com/android/Constructing-View-Layouts
  - https://guides.codepath.com/android/Working-with-the-TextView

- Задания и CodeLabs
  - https://codelabs.developers.google.com/codelabs/android-training-text-and-scrolling-views/index.html?index=..%2F..android-training

  - https://codelabs.developers.google.com/codelabs/android-training-create-an-activity/index.html?index=..%2F..android-training

  - https://codelabs.developers.google.com/codelabs/android-training-activity-lifecycle-and-state/index.html?index=..%2F..android-training

  - https://codelabs.developers.google.com/codelabs/android-training-activity-with-implicit-intent/index.html?index=..%2F..android-training

- Создать простое приложение наподобии того, с которым вы встречались в кодлабе. Приложение должно состоять из нескольких экранов: 
  - Примерный макет главного экрана: https://monosnap.com/file/HszR4WuQm98kjYzIAa16AYThwL7j1l 
  - По порядку: элемент в самом верху должен быть невидимым, однако елси приложение получает текст от других приложений то полученый текст должен быть отображен именно в нем и стать видимым
  - Следующий элемент должен быть статичным
  - В третьем элементе мы должны отображать текст который мы выбререм на экране по нажатии на кнопку Choose 
  - Кнопка Choose должна открыть новый экран который будет отображать разные варианты текста (на ваш выбор, но не менее 5), нажимая на элемент возвращаемся на предыдущий экран
  - Кнопка share внизу по нажатию которой отправляем текст из третьего элемента (где мы отображаем наш выбор) в любое другое приложение
  - В то же время наше приложение тоже должно быть в состоянии принять текст и отобразить его
  - Приложение должно поддерживать украинский, русский и английский (те надписи которые статичны, например на кнопках)
  - Бонусная задача: сделать на главном экране счетчик и отображать в нем количество раз которые пользователь возвращался в приложение (именно в приложение а не на экран)
    
    
## Week 2
- Multithreading & Networking
  - https://developer.android.com/guide/background/
  - https://developer.android.com/training/multiple-threads/
  - https://developer.android.com/training/basics/network-ops/
  - https://youtu.be/yyZh3ME7Jyk 
  - https://guides.codepath.com/android/Handling-ProgressBars
  - https://guides.codepath.com/android/Consuming-APIs-with-Retrofit

 - Задания и codelabs
   - https://codelabs.developers.google.com/codelabs/android-training-create-asynctask/index.html?index=..%2F..android-training#0
   - Создать приложение которое будет контактировать с Flickr Api ( https://www.flickr.com/services/api/ ) 
     - При открытии приложения вы должны сначала демонстрировать лого приложения и названия (по сути Splash Screen)
     - После  Splash screen пользователь должен увидеть экран с полем для ввода текста и кнопкой Search
     - По нажатии на кнопку Search выполрнять поиск по Flickr (https://www.flickr.com/services/api/flickr.photos.search.html) с заданым текстом
     - Полученный результат вывести в TextView который будет расположен ниже
     - Из полученного ответа от сервера вы дорлжны сформировать прямую ссылку на каждую фотографию которая прийдет и сформировать строку где каждая ссылка будет начинаться с новой строки
     - Отобразить полученный результат в TextView ( в случае если результатов много то текст в TextView должен скроллиться)
     - Пользователь должен быть в состоянии кликнуть по каждой ссылке (подсказка см. класс Linkify)
     - При клике на линку пользователь должен перейти на другой экран в приложении где он сможет просмотреть содержимое линки (по сути отобразить в Webview)
     - Не использовать для отображения список
    
## Week 3 & 4
 - Списки, сохранение данных на диске
 
   - Списки
   - https://www.youtube.com/watch?v=G35pcPv_tEA
   - https://developer.android.com/guide/topics/ui/layout/recyclerview
   - https://developer.android.com/reference/androidx/recyclerview/widget/RecyclerView.html
   - https://developer.android.com/reference/android/support/v7/widget/helper/ItemTouchHelper
   - https://github.com/bumptech/glide
   
   - Хранение данных
   - https://developer.android.com/guide/topics/data/data-storage
   - https://developer.android.com/training/data-storage/shared-preferences 
   - https://developer.android.com/training/data-storage/sqlite.html
   - https://developer.android.com/training/data-storage/room
   - https://youtu.be/A-P6EDw5z_s
   - http://facebook.github.io/stetho/ Для работы с БД в живую на девайсе

- Задания и codelabs
  - https://codelabs.developers.google.com/codelabs/android-training-livedata-viewmodel/index.html?index=..%2F..android-training#0
  - https://codelabs.developers.google.com/codelabs/android-training-room-delete-data/index.html?index=..%2F..android-training#0
  - https://codelabs.developers.google.com/codelabs/android-training-create-recycler-view/index.html?index=..%2F..android-training#0
  - Работаем на основе приложения с прошлой недели
    - Применяем RecyclerView для отображения результатов поиска
    - Отображаем результаты в карточке (CardView)
    - На каждой карточке должна отображаться картинка и запрос по которому картинка получена
    - Пользователь должен иметь возможность свайпнуть её в сторону (удалить из списка)
    - Огранизовать локальную БД для хранения необходимых данных
    - Сделать экран входа (формальный без пароля) и сохранять все данные на каждого отдельно взятого пользователя:
    - При выходе из приложения сохраняем текст введённый в поисковую строку и восстанавливаем при запуске
    - На экране просмотра фотографии нужно выводить текст поискового запроса, по которому была найдена фотография
    - На экране просмотра фотографии нужно добавить функцию - сохранение/удаление в Избранные, реализовать одним View
    - Добавить возможность на главном экране перейти на экран Избранные. В нём отображаем избранные фотографии с группировкой по поисковым запросам: запрос по которому лайкались фотки - отдельный элемент списка после которого идут все фотографии которые ему соответствуют
    - Если на экране Избранные пользователь свайпает фотографию - её необходимо удалить из списка Избранные и в базе данных
    - На экране Избранные на каждой карточке отобразить кнопку, которая позволит убрать фотографию из списка (помимо свайпа)
    - Создать экран с историей запросов
    - Дополнительное задание: на главном экране необходимо реализовать бесконечный список (в случае наличия данных на API)

## Week 5
 - Permissions & Location 
 
   - https://developer.android.com/guide/topics/permissions/overview всю секцию
   - https://developer.android.com/training/location 
  - Задания и codelabs
    - https://codelabs.developers.google.com/codelabs/advanced-android-training-device-location/index.html?index=..%2F..advanced-android-training#0
    - https://codelabs.developers.google.com/codelabs/advanced-android-training-places-api/index.html?index=..%2F..advanced-android-training#0
    - https://codelabs.developers.google.com/codelabs/advanced-android-training-google-maps/index.html?index=..%2F..advanced-android-training#0
    - Работаем на основе приложения с прошлой недели:
     - Добавляем отдельный экран с картой Google Maps
     - По умолчанию пытаемся показать и отметить на карте текущее местоположение пользователя
     - Пользователь может тапом выбрать на карте любое место
     - Если место выбрано то по нажатии кнопки на экране он может получить фид фоточек с Flickr с заданой локации на карте и отобразить это в списке
     - Wokrflow примерно такой: попадаем на экран с картой, выбираем местоположение (или оставляем текущее определенное), жмем на кнопку "Найти фотографии" и попадаем на другой экран где будут выведены фоточки в список

## Week 6
 - Internal & external storage & camera 
 
   - https://developer.android.com/training/data-storage/files.html
   - https://developer.android.com/training/camera
   - https://github.com/Yalantis/uCrop
 - Задания и codelabs
    - https://codelabs.developers.google.com/codelabs/android-storage-permissions/#0
    - Работаем на основане приложения с прошлой недели:
      - Добавляем возможность просмотреть экран с галереей из собственных фотографий
      - Необходимо завести отдельную папку на телефоне куда ваше приложение будет сохранять фотографии сделанные пользователем
      - Когда пользователь попадет на этот экран нужно отображать фотографии в списке подобно тому как мы это делаем на остальных экранах
      - Если пользователь будет свайпать фотографию на этом экране то в таком случае мы удаляем фотографию
      - После того как пользователь сделает фотографию предлагаем ее обработать с помощью библиотеки uCrop
      - После обработки сохраняем полученный результат и отображаем как новый элемент списка
      - Так же добавляем возможность скачать фотографию на файловую систему при просмотре фулл скрин фоточки из фликера - отображать ее будеим в том же списке что и другие фотографии на файловой системе
      - Фотографии сделанные из приложения с камеры пользователя сохранять в приватное хранилище, фотографии из фликера загружать в какую то папку в общем хранилище

## Week 7
 - Resources and styling
 
   - https://developer.android.com/guide/topics/ui/look-and-feel?hl=en - всю секцию
   - https://guides.codepath.com/android/Styles-and-Themes
   - https://www.vogella.com/tutorials/AndroidStylesThemes/article.html
   - https://developer.android.com/guide/topics/resources/available-resources - вся секция
   - https://material.io/
   - https://material.io/design/color/dark-theme.html#properties
   - https://material.io/tools/build-a-material-theme/#how-to-using-android-studio
 - Задания и codelabs
    - https://material.io/collections/developer-tutorials/#android-java все в секции ява
    - https://codelabs.developers.google.com/codelabs/android-training-drawables-styles-and-themes/index.html?index=..%2F..android-training#0
    - Работаем на основане приложения с прошлой недели:
      - Стилим приложение в Material стиле. 
      - Если у нас есть вью которое переиспользуется на разных экранах то пишем единый стиль для такой вью (например для стандартной кнопки)
      - Advanced - внедряем light\dark тему и добавляем возможность переключения между ними

# Week 8
 - Fragments & System communication 
 
   - https://developer.android.com/guide/components/fragments всю секцию
   - https://guides.codepath.com/android/Fragment-Navigation-Drawer
   - https://guides.codepath.com/android/ViewPager-with-FragmentPagerAdapter
   - https://developer.android.com/guide/components/broadcasts
   - https://developer.android.com/training/basics/fragments/fragment-ui.html
 - Задания и codelabs
    - https://codelabs.developers.google.com/codelabs/android-training-broadcast-receivers/index.html?index=..%2F..android-training#0 
    - https://codelabs.developers.google.com/codelabs/advanced-android-training-fragments/index.html?index=..%2F..advanced-android-training#0
    - https://codelabs.developers.google.com/codelabs/advanced-android-training-fragment-communication/index.html?index=..%2F..advanced-android-training#0
    - Работаем на основане приложения с прошлой недели:
      - Переделываем наше приложение на master\detail flow  (пример в есть водной из кодлаб)
      - Добавляем Navigation Drawer в котором будут находится секции которые мы сделали в прошлых работах
      - Секции типа Maps, Favourites, etc. 
      - Экраны переводим на фрагменты для того что бы при выборе секции динамически менять контент на главном экране
      - Оставляем только одну главную  Activity которая будет все хостить в себе
      - Добавляем возможность запуска приложения после загрузки телефона
      - Если на телефоне меняется заряд батареи то на каком бы фрагменте мы не находились показываем  тост сообщение с текущим зарядом 
      - Лочим ориентацию приложения только на портретный режим

# Week 9
 - Тестирование 
 
   - https://developer.android.com/training/testing/fundamentals
   - https://developer.android.com/training/testing/set-up-project
   - https://developer.android.com/training/testing/unit-testing все секции
   - https://developer.android.com/training/testing/ui-testing все секции
   - https://habr.com/ru/post/352334/ краткий гайд на русском
   
 - Задания и codelabs
    - https://codelabs.developers.google.com/codelabs/android-training-unit-tests/index.html?index=..%2F..android-training#0
    - Работаем на основане приложения с прошлой недели:
      - Опрелелить код, который стоит покрыть unit-тестами
      - Определить код, который стоит покрыть UI-тестами
      - Протестировать код

# Week 10
 - Уведомления 
 
   - https://developer.android.com/training/best-background
   - https://developer.android.com/topic/libraries/architecture/workmanager
   - https://developer.android.com/guide/topics/ui/notifiers/notifications
   - https://developer.android.com/reference/android/app/Service
 - Задания и codelabs
    - https://codelabs.developers.google.com/codelabs/notification-channels-java/index.html?index=..%2F..index#0
    - https://codelabs.developers.google.com/codelabs/android-workmanager/index.html?index=..%2F..index#0
    - Работаем на основане приложения с прошлой недели:
      - Добавляем экран сеттингов
      - На этом экране добавляем возможность включать/отключать запросы приложения на обновление фоточек по какому то запросу в фоне
      - Если пользователь разрешает такие обновления разрешаем выбрать срок периодичности запросов
      - Минимальный возможный период - 15 минут, затем 30 минут, 1 час, 6 часов, сутки
      - Приложение работая в фоне должно будет с указанной периодичностью ходить на сервер и получать новые фотографии
      - После успешного обновления сохранять их в отдельную таблицу в базе, добавить возможность просмотра этих фотографий на отдельном экране (фрагменте)
      - После успешного обновления показывать уведомление
      - При желании можно сделать чт обы в увдеомлении показывалась первая картинка из загруженных
      - В уведомлении отображать количество полученных фотографий
      - При нажатии на уведомление переходить на экран просмотра скаченных фотографий
