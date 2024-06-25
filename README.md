![MIT](https://img.shields.io/badge/license-MIT-green)
[![Crowdin](https://img.shields.io/badge/Localization-Crowdin-blueviolet?logo=Crowdin)](https://crowdin.com/project/tts-server)

[![CI](https://github.com/jing332/tts-server-android/actions/workflows/release.yml/badge.svg)](https://github.com/jing332/tts-server-android/actions/workflows/release.yml)
[![CI](https://github.com/jing332/tts-server-android/actions/workflows/test.yml/badge.svg)](https://github.com/jing332/tts-server-android/actions/workflows/test.yml)

![GitHub release](https://img.shields.io/github/downloads/jing332/tts-server-android/total)
![GitHub release (latest by date)](https://img.shields.io/github/downloads/jing332/tts-server-android/latest/total)

# TTS Server [![](https://img.shields.io/badge/Q%E7%BE%A4-124841768-blue)](https://jq.qq.com/?_wv=1027&k=y7WCDjEA)

This APP was originally used for online reading of reading APP. On the basis of the original, it now supports:

* Built-in Microsoft interface (Edge Read Aloud, ~~Azure Demo API~~(already released)), customizable HTTP requests, imports of other local TTSengines, simple narration/dialogue recognition & reading based on Chinese double quotes, auto retry, alternate configuration, text replacement & more.

<details>
  <summary>Click to expand & view screenshots</summary>

  <img src="./images/1.jpg" height="150px">
  <img src="./images/2.jpg" height="150px">
  <img src="./images/3.jpg" height="150px">
  <img src="./images/4.jpg" height="150px">

</details>

# Download

* [Stable ver. - (Releases)](https://github.com/jing332/tts-server-android/releases)

* .[Dev.Ver. - (require logging into Github account)])](https://github.com/jing332/tts-server-android/actions)

## Actions mirror

app: https://jing332.lanzn.com/b09jpjd2d

dev: https://jing332.lanzn.com/b09ig9qla

Password: 1234


# JS

#### Read the rules

The program has built-in narration dialogue rules, which can be added through Reading Rules Management -> Plus Sign.

User-created reading rules：

1. Rules for character-name-aware voiceover dialogue：
   Open [this link](https://www.gitlink.org.cn/geek/src/tree/master/ttsrv-speechRules-multiVoice.json),
   Copy all the content to the clipboard, and then import it in the rule management interface

2. 5 languages ​​detected: Copy [this link](https://jt12.de/SYV2_1/2023/04/16/10/08/08/1681610888643b588876c09.json),
   In the rule management interface, select Network link import.

#### TTS Plugins

The program has built-in TTS plug-in for Azure official interface: Plug-in management -> Add in the upper right corner -> Save -> Set variables -> Fill in Key and Region

iFlytek WebAPI plugin: Copy [this link](https://jt12.de/SYV2_1/2023/04/16/10/25/17/1681611917643b5c8d61313.json),
In the plugin management interface, select network link import, and then set the variable AppId, ApiKey, ApiSecret。

# Grateful

<details>
  <summary>Open Source Projects</summary>

| Application                                                                     | Microsoft TTS                                                         |
|---------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| [gedoor/legado](https://github.com/gedoor/legado)                               | [wxxxcxx/ms-ra-forwarder](https://github.com/wxxxcxx/ms-ra-forwarder) |
| [ag2s20150909/TTS](https://github.com/ag2s20150909/TTS)                         | [litcc/tts-server](https://github.com/litcc/tts-server)               |
| [benjaminwan/ChineseTtsTflite](https://github.com/benjaminwan/ChineseTtsTflite) | [asters1/tts](https://github.com/asters1/tts)                         |
| [yellowgreatsun/MXTtsEngine](https://github.com/yellowgreatsun/MXTtsEngine)     |
| [2dust/v2rayNG](https://github.com/2dust/v2rayNG)                               |

| Library                                                                                                         | Description                                                                                                                                                   |
|-----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [dromara/hutool](https://github.com/dromara/hutool/)                                                            | 🍬A set of tools that keep Java sweet.                                                                                                                        |
| [LouisCAD/Splitties](https://github.com/LouisCAD/Splitties)                                                     | A collection of hand-crafted extensions for your Kotlin projects.                                                                                             |
| [getactivity/logcat](https://github.com/getactivity/logcat)                                                     | Android log printing framework, you can directly see the Logcat log on your phone                                                                                                                      |
| [rosuH/AndroidFilePicker](https://github.com/rosuH/AndroidFilePicker)                                           | FilePicker is a small and fast file selector library that is constantly evolving with the goal of rapid integration, high customization, and configurability~ |
| [androidbroadcast/ViewBindingPropertyDelegate](https://github.com/androidbroadcast/ViewBindingPropertyDelegate) | Make work with Android View Binding simpler                                                                                                                   |
| [zhanghai/AndroidFastScroll](https://github.com/zhanghai/AndroidFastScroll)                                     | Fast scroll for Android RecyclerView and more                                                                                                                 |
| [Rosemoe/sora-editor](https://github.com/Rosemoe/sora-editor)                                                   | sora-editor is a cool and optimized code editor on Android platform                                                                                           |
| [gedoor/rhino-android](https://github.com/gedoor/rhino-android)                                                 | Give access to RhinoScriptEngine from the JSR223 interfaces on Android JRE.                                                                                   |
| [liangjingkanji/BRV](https://github.com/liangjingkanji/BRV)                                                     | The best RecyclerView framework on Android, simpler and more powerful than BRVAH                                                                                                                   |
| [liangjingkanji/Net](https://github.com/liangjingkanji/Net)                                                     | The best network request tool for Android, easier to use than Retrofit/OkGo                                                                                                                       |
| [chibatching/kotpref](https://github.com/chibatching/kotpref)                                                   | Android SharedPreferences delegation library for Kotlin                                                                                                       |
| [google/ExoPlayer](https://github.com/google/ExoPlayer)                                                         | An extensible media player for Android                                                                                                                        |
| [material-components-android](https://github.com/material-components/material-components-android)               | Modular and customizable Material Design UI components for Android                                                                                            |
| [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization/)                                       | Kotlin multiplatform / multi-format serialization                                                                                                             |
| [kotlinx.coroutine](https://github.com/Kotlin/kotlinx.coroutines)                                               | Library support for Kotlin coroutines                                                                                                                         |

</details>

Additional Resources：

* [Alibaba IconFont](https://www.iconfont.cn/)

* [Cool An@Silence_9520](http://www.coolapk.com/u/25956307) The author of this APP icon

# Build

### Android Studio:
Create a new file `local.properties` in the project root directory and write the following content:
```
KEY_PATH=E\:\\Android\\key\\sign.jks (Signature File)
KEY_PASSWORD= password 密码
ALIAS_NAME= aliases 别名
ALIAS_PASSWORD= Alias ​​Password 别名密码
```



### Github Actions:
> See https://www.cnblogs.com/jing332/p/17452492.html

Use Git Bash to Base64 encode the signature file without line breaks: `openssl base64 < key.jks | tr -d '\r\n' | tee key.jks.base64.txt`

Add the following four security variables respectively (Repository secrets):
> Go to the following link：https://github.com/你的用户名/tts-server-android/settings/secrets/actions
* `ALIAS_NAME` aliases 别名
* `ALIAS_PASSWORD` aliases password 别名密码
* `KEY_PASSWORD` password 密码
* `KEY_STORE` Previously generated 前面生成的 sign.jks.base64.txt content 内容
