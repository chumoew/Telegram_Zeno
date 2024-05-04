# 🌱 「Zeno」Telegram
[![Crowdin](https://badges.crowdin.net/e/a094217ac83905ae1625526d59bba8dc/localized.svg)](https://neko.crowdin.com/nekogram)  
**「Zeno」Telegram是第三方Telegram客户端内置模块版，内有众多功能**
> "Zeno" Telegram is a built-in module version of third-party Telegram client with many functions.

- Telegram频道: [https://t.me/CMissue](https://t.me/CMissue). （暂时使用）
- 下载: https://github.com/chumoew/Telegram_Zeno/releases
- 反馈: https://github.com/chumoew/Telegram_Zeno/discussions
>- Telegram channel: https://t.me/CMissue （interim facility）
>- Downloads: https://github.com/chumoew/Telegram_Zeno/releases
>- Feedback: https://github.com/chumoew/Telegram_Zeno/discussions

## API、协议文档

Telegram API manuals: https://core.telegram.org/api

MTProto protocol manuals: https://core.telegram.org/mtproto

## Compilation Guide

1. Download the Nekogram source code ( `git clone https://github.com/Nekogram/Nekogram.git` )
1. Fill out storeFile, storePassword, keyAlias, keyPassword in local.properties to access your release.keystore
1. Go to https://console.firebase.google.com/, create two android apps with application IDs tw.nekomimi.nekogram and tw.nekomimi.nekogram.beta, turn on firebase messaging and download `google-services.json`, which should be copied into `TMessagesProj` folder.
1. Open the project in the Studio (note that it should be opened, NOT imported).
1. Fill out values in `TMessagesProj/src/main/java/tw/nekomimi/nekogram/Extra.java` – there’s a link for each of the variables showing where and which data to obtain.
1. You are ready to compile Nekogram.

## Localization

Nekogram is forked from Telegram, thus most locales follows the translations of Telegram for Android, checkout https://translations.telegram.org/en/android/.

As for the Nekogram specialized strings, we use Crowdin to translate Nekogram. Join project at https://neko.crowdin.com/nekogram. Help us bring Nekogram to the world!
