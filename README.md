<h1 align="center">
    🀄 <a href="https://mahtools.github.io/riichi-centrepiece/">Riichi Centrepiece</a> 🀄
</h1>

<p align="center">- A round/honba tracker to aid during play -</p>

## 📝 About 📝
A centrepiece in Riichi is a tool that helps track the current round and seat winds, they are found on a lot of online websites and real-life tables:

<div align="center">
    <img src="./example.png" alt="Example of what a centrepiece looks like">
    <p>Example of a centrepiece on the <a href="https://tenhou.net/">Tenhou</a> client.</p>
</div>

Riichi Centrepiece is a web app that tracks:
- The round wind
- The seat winds
- The [honba](https://riichi.wiki/Honba)

Intended to be placed in the middle of the table during a game of Riichi Mahjong. 

It is written as a single-page and single-file web app with no external dependencies. Just a browser and JavaScript!

## 🌐 Use online 🌐
You can head over to the [Github Pages](https://mahtools.github.io/riichi-centrepiece/) site and start using the app. 

Once opened it has no dependency on a stable internet connection to keep working.

## 🚫🌐 Use offline 🌐🚫
The app is contained within a single html file. Download the file from the [master branch](https://github.com/mahtools/riichi-centrepiece/blob/master/index.html) or from the [releases tab](https://github.com/mahtools/riichi-centrepiece/releases) and run it inside your preferred web browser.

## 🕹️ Controls 🕹️
The primary controls are simple. In the middle of the screen you will see the wind, round number and honba count.

In Japanese this will look something like 

```
東1局
0本場
```

In English it will look something like

```
E1
0H
```

Click on the text at the top to increment the round. Click on the text at the bottom to increment the honba/repeat count. 

Extra options are given below:

---

### ☀☼ - Setting Dark Mode
Click the `☼` icon to set dark mode. Click on the `☀` icon to set light mode. These will always be in the top left.

---

### 34 - Setting/unsetting Sanma (3-player)
Click on the `34` icon to toggle whether you are playing Sanma (3-player Mahjong) or regular Mahjong (4-player). 

The selected option should be highlighted in <span style="color: #55dd55"><b>green</b></span>.

---

### 東半一 / THI - Setting game length (Tonppusen, Hanchan, Iichan)
Click on the `東半一` icon (or, if you are using English, `THI`) to set the game length. You can pick **T**onpuusen (1 wind), **H**anchan (2 winds) or **I**ichan (4 winds).

For beginners, the most common way to play Mahjong is **H**anchan. **I**ichan is rarely played, but included for completeness.

The selected option should be highlighted in <span style="color: #55dd55"><b>green</b></span>.

---

### Aあ - Setting language
The `Aあ` icon toggles the language between Japanese and English. 

English is currently fully supported, but is **not** the default when you boot up the app.

**Some environments may not be able to render Japanese fonts.** 

The order of font priority is: `"Hiragino Mincho", "AoyagiKouzanFont2OTF", "EPSON >太行書体Ｂ", "Times New Roman", serif`. If your fallback serif font doesn't display Japanese, then you will need to install one that does.

---

## 👷 Supports 👷
### Game types
| Supported | Match type | Winds | Rounds/Wind | 
| --- | --- | --- | --- | 
| ✅ | Iichan (Full-length) | 4 | 4 |
| ✅ | Iichan (Full-length) sanma | 3 | 3 |
| ✅ | Hanchan | 2 | 4 |
| ✅ | Hanchan sanma | 2 | 3 |
| ✅ | Tonpuusen | 1 | 4 |
| ✅ | Tonpuusen sanma | 2 | 3 |

### Languages
| Language | Support |
| --- | --- |
| Japanese | Full ✅ | 
| English | Full ✅ | 
