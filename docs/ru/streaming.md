## Чтение лекций через YouTube Live 

## Вам понадобится
- Компьютер с веб камерой
- Интернет на скорости 3G или выше
- [Discord чат](https://discordapp.com/)
  * права на размещение постов в канал #announcements
- [Open Broadcast Studio (OBS)](https://obsproject.com/)
- Права на трансляцию в [YouTube канал сообщества](https://www.youtube.com/channel/UC578nebW2Mn-mNgjEArGZug)
  * выдача прав может занять до 48 часов (запросить права транслировать + 24 часа ждать)
  * [гайд как выдать права](https://support.google.com/youtube/answer/4628007?hl=en)
  * сейчас права могут выдать Rolling Scopes (Maxim Shastel, Dzmity Varabei), Anton Bely, Dzianis Sheka, Pavel Razuvalov, Sergey Shalyapin
  * для трансляции нужен только код трансляции, который может передать человек, администрующий канал
  * желательно перед трансляцией сделать тестовый прогон, можно через [YouTube канал](https://www.youtube.com/channel/UC96625SDIZVxP-MRid1w8sQ)

## Discord
Discord чат используется для анонса трансляции и общения с участниками вебинара:
- В канал #announcements необходимо разместить анонс вебинара, а перед его началом добавить ссылку на трансляцию
- Для получения прав на размешения постов в #announcements, напишите любому admin
- Для общения со студентами во время трансляции используется канал #live-streaming

[Подробнее о стуруктуре Discord](rs-school-chats.md)

## Настройка OBS
Приложение Open Broadcast Studio (OBS) необходимо для того, чтобы стримить изображение с экрана и веб камеры, звук с микрофона.

### Шаги
#### 1. Установить [Open Broadcast Studio (OBS)](https://obsproject.com/)
#### 2. Настроить параметры стрима
![установка](../images/obs_init.png)
#### 3. Настроить параметры выходного потока (чтобы сделать запись локально)
![установка](../images/obs_settings_video.png)
#### 4. Настроить сцену - добавить захват экрана, добавить веб камеру, если нужно
![добавить захват экрана](../images/obs_scene_add_display_capture.png)
#### 5. Добавить фильтр Шумоподавление в Микрофон OBSa
![добавить шумоподавление](../images/obs_setting_audio_filter.png)
#### 6. Проверить параметры видео и звука, начав запись локально

### Полная видео инструкция
[![видео инструкция](https://img.youtube.com/vi/tys-IYIcYu8/0.jpg)](https://www.youtube.com/watch?v=tys-IYIcYu8)

## Настройка параметров трансляции на YouTube
### Шаги
#### 1. Открыть дашборд live трансляции
![дашборд стрима](../images/live_dashboard.png)
#### 2. Выставить в stream options параметры задержки
![настройки стрима](../images/stream_settings.png)
#### 3. Выставить название стрима, описание и превью
![превью](../images/add_thumbnail.png)

* preview можно сделать из, например, [такого шаблона в фигме](https://www.figma.com/file/40sDhGHQgU0DmBLuu0Qim8/youtube_thumbnails?node-id=0%3A6)

#### 4. Скопировать ключ трансляции из дашборда стрима в OBS
![превью](../images/stream_key.png)
![превью](../images/obs_stream_settings.png)

### Удачного стриминга!
