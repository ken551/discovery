# Windows

## `arm-none-eabi-gdb`

<!-- ARM provides `.exe` installers for Windows. Grab one from [here][gcc], and follow the instructions.
Just before the installation process finishes tick/select the "Add path to environment variable"
option. Then verify that the tools are in your `%PATH%`: -->

ARMによって、Windows向けの`.exe`形式のインストーラが提供されています。
[ここ][gcc]からダウンロードし、説明に従ってインストールをしてください。
インストール完了直前に表示される「Add path to environment variable」項目には、チェックを入れるようにしてください。
ここまで終わったら、ツールに正しくパスが通っていることを確認してください。

``` console
$ arm-none-eabi-gcc -v
(..)
gcc version 5.4.1 20160919 (release) (..)
```

[gcc]: https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads

## PuTTY

<!-- Download the latest `putty.exe` from [this site] and place it somewhere in your `%PATH%`. -->
最新版の`putty.exe`を[このサイト][this site]からダウンロードして、`%PATH%`環境変数に登録されるディレクトリのどこかに配置してください。

[this site]: http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html

[next section]: verify.md
