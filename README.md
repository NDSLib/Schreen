# Schreen1.1.1
This application is easy to screen sharing.
<br>
かんたんにローカル内で画面共有ができるアプリケーションでｔｈ。

test NDSL commit

# DEMO
![schreenDEMO](https://user-images.githubusercontent.com/50548952/77206946-8a8d9b00-6b3b-11ea-9e69-25570f4c82ff.gif)
# Requirement

read `requiments.txt`.

# Installation
**OpenCVのバージョンは、3を使用してください。4だとPyinsatllerでパッケージ化したときにエラー吐きます**
## パッケージ化されたものをインストールしたいですか？

** Windows coming soon. sorry. **

https://github.com/hirossan4049/Schreen/releases

## いや、改良、コードを見たい、修正したいですか？
  `python3.7.7`&`python3.6.5`で検証済み
```bash
pip install -r requirements.txt
```



# Usage

```bash
python app/main.py
```

# ChangeLog
**1.1.1** : flask import 場所変更。起動速度上昇。

# Note
`pyinstaller`で`.app`化するときは、`app/DEBUG.py`の`DEBUG=True`を`DEBUG=False`にしてください。
# Packaging
## MacOS
coming soon.
## Windows
coming soon.
## Linux(debian)
coming soon.
# Author

* hirossan4049


# License
"Schreen" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
