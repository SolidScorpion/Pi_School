# PI-school 2019

## Week 1
- Ознакомление с Android Studio и создание приложениия с нуля + первоначальные материалы для изучения
  
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
  - В третьем элементе мы должны отображать текст который мы выбирем на экране по нажатии на кнопку Choose 
  - Кнопка Choose должна открыть новый экран который будет отображать разные варианты текста (на ваш выбор, но не менее 5), нажимая на элемент возвращаемся на предыдущий экран
  - Кнопка share внизу по нажатию которой отправляем текст из третьего элемента (где мы отображаем наш выбор) в любое другое приложение
  - В то же время наше приложение тоже должно быть в состоянии принять текст и отобразить его
  - Приложение должно поддерживать украинский, русский и английский (те надписи которые статичны, например на кнопках)
  - Бонусная задача: сделать на главном экране счетчик и отображать в нем количество раз которые пользователь возвращался в приложение (именно в приложение а не на экран)
  - Бонусная задача: переделать все на Kotlin

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
     - Из полученного ответа от сервера вы должны сформировать прямую ссылку на каждую фотографию которая прийдет и сформировать строку где каждая ссылка будет начинаться с новой строки
     - Отобразить полученный результат в TextView ( в случае если результатов много то текст в TextView должен скроллиться)
     - Пользователь должен быть в состоянии кликнуть по каждой ссылке (подсказка см. класс Linkify)
     - При клике на линку пользователь должен перейти на другой экран в приложении где он сможет просмотреть содержимое линки (по сути отобразить в Webview)
     - Не использовать для отображения список
     - Бонусная задача - выполнить на kotlin
