# orderBook
https://shichin-eo.github.io/orderBook/

## Tasks
- Таблица скроллится внутри (оба столбца скроллятся одновременно), шапка остается на месте. Полоса скролл-бара начинается под шапкой. При скролле значения в таблице не должны наезжать на шапку. В таблице должен быть только один скролл-бар.
- Цветные бары строятся по полю тотал, которое нужно рассчитывать на фронте, тотал суммирует все amount выше в таблице (см. скриншот). График максимального для обоих направлений тотала должен занимать 100% ширины, все остальные — меньше. В Json два массива — bids для левой колонки, asks — для правой.
- При изменении текста заголовков колонок, текст заголовков не должен наезжать на соседние колонки 
- Строки в таблице должны менять цвет фона при хавере (немного затемняться), независимо: отдельно bid-сторона, отдельно ask.
- Скролл-бар в таблице должен появляться по хаверу на таблицу. внешний вид скроллбара не принципиален.
- Браузеры: chrome, firefox, safari, edge (последние десктоп версии).
