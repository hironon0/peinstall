# Windows PE 起動環境作成ガイド

## BE Builder(PE)を起動

メニューからBE Buildeを起動します。

起動した環境にWindows PE Kitがインストールされていない場合には、MicrosoftのWebサイトからダウンロードしてインストールする必要があります。
[Windows ADK/AIKのインストール](#installPE) の手順に従ってインストールしてください。


----

## <a id='installPE'></a>Windoows ADK/AIK のインストール

ActiveImage Protectorでシステムのリカバリーを行う場合には起動環境のメディアを作成する必要がありますではWidowsPEをインストールする必要があります
WindowsPEには何種類かのToolKitがあり、各々インストール方法が違いますので注意が必要です。
 
### Windows ADK Anniversay Update 1607, 1511 

ダウンロードしたファイルを実行すると以下の画面が表示されます。

![install option](img\aip-002.png)

BE Builder で必要となるのモジュールは以下のものです。それ以外の選択は外して問題ありません。

* ToolKit
* Assesment Kit

そのままインストーラーの指示に従ってＡＤＫをインストールしてください。
インストールが完了したら、BE Builderを起動しなおすとPE Kiｔの選択が可能になります。

### Windows ADK 8.1 Update
ダウンロードしたファイルを実行すると以下の画面が表示されます。

![install option](img\aip-002.png)

BE Builder で必要となるのモジュールは、０とoなのでそれ以外の選択は外して問題ありません。
そのままインストーラーの指示に従ってＡＤＫをインストールしてください。
インストールが完了したら、BE Builderを起動しなおすとPE Kiｔの選択が可能になります。

### Windows ADK Windows 7
ダウンロードしたファイルを実行すると以下の画面が表示されます。

![install option](img\aip-002.png)

BE Builder で必要となるのモジュールは、０とoなのでそれ以外の選択は外して問題ありません。
そのままインストーラーの指示に従ってＡＤＫをインストールしてください。
インストールが完了したら、BE Builderを起動しなおすとPE Kiｔの選択が可能になります。

### Windows AIK
ダウンロードしたファイルを実行すると以下の画面が表示されます。

![install option](img\aip-002.png)

BE Builder で必要となるのモジュールは、０とoなのでそれ以外の選択は外して問題ありません。
そのままインストーラーの指示に従ってＡＤＫをインストールしてください。
インストールが完了したら、BE Builderを起動しなおすとPE Kiｔの選択が可能になります。

```
code

```
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.
![pe](img/aip-002.png)
## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.



