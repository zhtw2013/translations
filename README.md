# [Snipaste](https://snipaste.com) Translations

# How to contribute
* Translate (see below for instructions).
* Send a pull request.
   * If you don't know how to send a pull request:
     * [Create an issue](https://github.com/Snipaste/translations/issues) and tell us where we can download your translation.
     * Or, you may just email the language files to snipaste.app@gmail.com.
* Tell us your name (or id) and link as a translator.
* Your translation will be included in the next version of Snipaste.

# How to translate

Though you may open the .ts files with a text editor and start translating,
we strongly recommend you translate them using [Qt Linguist](http://doc.qt.io/qt-5/qtlinguist-index.html).

For your convenience, we have prepared the portable packages of Qt Linguist:
* [Windows x64](https://bitbucket.org/liule/snipaste/downloads/VC2015_dll_x64.zip) | [Windows x86](https://bitbucket.org/liule/snipaste/downloads/VC2015_dll_x86.zip)

Basic steps to translate using Qt Linguist:
<details>
<img src="https://cloud.githubusercontent.com/assets/2010459/25688906/911ad78a-30b5-11e7-8dc2-c8bcd2955615.png" alt="linguist_basic"/>

Tip: You may open multiple .ts files of different languages (such as `zh_cn.ts` and `zh_tw.ts`) in the same window, used for reference.
</details>

# How to add a new language

1. Suppose you language code is **xyz**.
1. Download and rename `qt_new.ts` to `qt_xyz.ts`.
1. Open `qt_xyz.ts` with your favorite text editor, replace the 3rd line with `<TS version="2.1" language="xyz">`, save and quit.
1. Translate `qt_xyz.ts` using Qt Linguist.
1. Download and rename `new.ts` to `xyz.ts`.
1. Repeat Step 3 and 4 for `xyz.ts`.
1. Translation done!

# Contact

If you need any help, feel free to [create an issue](https://github.com/Snipaste/translations/issues). We will help you.
