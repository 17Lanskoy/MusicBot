<img align="right" src="https://i.imgur.com/zrE80HY.png" height="200" width="200">

# JMusicBot

[![Downloads](https://img.shields.io/github/downloads/jagrosh/MusicBot/total.svg)](https://github.com/jagrosh/MusicBot/releases/latest)
[![Stars](https://img.shields.io/github/stars/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/stargazers)
[![Release](https://img.shields.io/github/release/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/releases/latest)
[![License](https://img.shields.io/github/license/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/blob/master/LICENSE)
[![Discord](https://discordapp.com/api/guilds/147698382092238848/widget.png)](https://discord.gg/0p9LSGoRLu6Pet0k)<br>
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/jagrosh/MusicBot/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/jagrosh/MusicBot/tree/master)
[![Build and Test](https://github.com/jagrosh/MusicBot/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/jagrosh/MusicBot/actions/workflows/build-and-test.yml)
[![CodeFactor](https://www.codefactor.io/repository/github/jagrosh/musicbot/badge)](https://www.codefactor.io/repository/github/jagrosh/musicbot)

Кроссплатформенный музыкальный бот Discord с понятным интерфейсом, который легко настроить и запустить самостоятельно!

[![Setup](http://i.imgur.com/VvXYp5j.png)](https://jmusicbot.com/setup)

## Особенности
 * Простота запуска (просто убедитесь, что установлена Java, и запускайте!)
 * Быстрая загрузка песен
 * Не требуется никаких внешних ключей (кроме токена Discord-бота)
 * Плавное воспроизведение
 * Настройка для конкретного сервера роли "DJ", который может модерировать музыку
 * Понятные и красивые меню
 * Поддерживает множество сайтов, включая Youtube, Soundcloud и другие
 * Поддерживает множество онлайн-радио / трансляций
 * Поддерживает локальные файлы
 * Поддерживает плейлист (как веб / youtube, так и локальный)

## Поддерживаемые источники и форматы
JMusicBot поддерживает все источники и форматы, поддерживаемые [lavaplayer](https://github.com/sedmelluq/lavaplayer#supported-formats):
### Источники
  * YouTube
  * SoundCloud
  * Bandcamp
  * Vimeo
  * Twitch streams
  * Local files
  * HTTP URLs
### Форматы
  * MP3
  * FLAC
  * WAV
  * Matroska/WebM (AAC, Opus or Vorbis codecs)
  * MP4/M4A (AAC codec)
  * OGG streams (Opus, Vorbis and FLAC codecs)
  * AAC streams
  * Stream playlists (M3U and PLS)

## Пример
![Loading Example...](https://i.imgur.com/kVtTKvS.gif)

## Настройка
Пожалуйста, ознакомьтесь с [Setup Page](https://jmusicbot.com/setup) чтобы запустить этого бота самостоятельно!

## Вопросы /Предложения /Сообщения об ошибках
**Пожалуйста, прочтите [Issues List](https://github.com/jagrosh/MusicBot/issues) прежде чем предлагать какую-либо функцию **. Если у вас есть вопросы, вам нужна помощь в устранении неполадок или вы хотите провести мозговой штурм новой функции, пожалуйста, запустите [Discussion](https://github.com/jagrosh/MusicBot/discussions). Если вы хотите предложить какую-либо функцию или сообщить о воспроизводимой ошибке, пожалуйста, откройте [Issue](https://github.com/jagrosh/MusicBot/issues) в этом репозитории. Если вам нравится этот бот, не забудьте отметить звездочкой библиотеки, которые делают это возможным: [**JDA**](https://github.com/DV8FromTheWorld/JDA) и [**lavaplayer**](https://github.com/sedmelluq/lavaplayer)!

## Редактирование
Возможно, неопытным программистам будет нелегко отредактировать этого бота (и приведенный здесь исходный код). Основная цель публикации исходного кода - продемонстрировать возможности библиотек, дать возможность другим пользователям понять, как работает бот, и дать возможность тем, кто разбирается в разработке ботов на java, JDA и Discord, внести свой вклад. Для его редактирования и компиляции требуется множество требований и зависимостей, и людям, которые хотят внести изменения самостоятельно, поддержка предоставлена не будет. Вместо этого рассмотрите возможность запроса новой функции (см. раздел выше). Если вы решите внести изменения, пожалуйста, делайте это в соответствии с лицензией Apache 2.0.
