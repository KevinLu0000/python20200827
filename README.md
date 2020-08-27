# Python基礎及應用課程講義

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/victorgau/python20200827/master)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/victorgau/python20200827/)

在本課程中，我們主要會使用[Google Colab](http://colab.research.google.com/)來授課。使用colab的好處是，如果使用者有gmail帳號，就可以直接透過瀏覽器(Browser)來使用Google提供的Python環境，省掉初學者一開始不知道怎麼在自己的電腦上安裝Python環境的困擾。

當初學者在colab上熟悉了Python的基本資料結構跟語法之後，我們會建議進一步嘗試在自己的電腦上安裝Python的環境來寫程式。

對於初學者，我們建議安裝Anaconda。Anaconda是Python的懶人包，裡面除了有Python的直譯器(Interpreter)外，還打包了很多常用的套件，安裝了Anaconda之後，大致上初學者就不太需要再另外裝一些缺少的套件。

如果您安裝的是[官網](https://www.python.org/)上的Python直譯器，您有很大的可能會常需要使用pip或conda等套件安裝工具來安裝您缺少的套件。

### 建議初學者安裝的Python直譯器及編輯器：

* [Anaconda 下載網址](https://www.anaconda.com/download/)
* [Visual Studio Code 下載網址](https://code.visualstudio.com/)

### 名詞解釋：

* python
* ipython

python跟ipython的主要差別在於ipython多了許多互動(interactive)功能，譬如說TAB自動補齊程式碼、使用?查詢函式說明、使用!呼叫命令列指令、使用%呼叫魔術指令等。

* ipython notebook
* jupyter notebook

ipython notebook跟jupyter notebook對我們(Python開發者)來說是一樣的東西。notebook的含義是可以讓使用者邊寫程式邊作筆記。因為ipython notebook好用，所以R跟Julia族群的開發者也跟著想使用notebook類型的介面來開發程式，所以原本的ipython notebook再加入了Julia跟R的kernel後，改名叫做jupyter notebook，jupyter開頭的ju指的就是Julia語言，結尾的r指的就是R語言。

* jupyter lab

jupyter lab跟jupyter notebook很類似，算是jupyter notebook的絢麗版。

* colab

colab是Google提供的雲端notebook服務，使用的方式類似jupyter notebook。雲端的notebook並非只有Google一家提供，Microsoft也有雲端notebook服務叫做Azure notebook。

* git / github

git是版本管理工具。github是程式碼託管的服務，open source的專案可以在github上面免費託管，使用git可以很容易的使用指令跟github互動。

### Python的副檔名：

Python的程式碼通常有兩種副檔名：

* .py
* .ipynb

使用一般文字編輯器編輯的Python程式檔，我們通常會以.py做檔案的結尾。使用Jupyter Notebook/Lab編輯的Python筆記，通常會以.ipynb做為檔案的結尾。

### 內容說明：

本課程著重的是動手做。課程內的練習題，分為使用Colab / Jupyter Notebook跟Visual Studio Code(或自選的IDE)兩部分，說明如下：

### colab / Jupyter Notebook：

* 基本運算及條件判斷練習
* 迴圈練習
* 基本資料結構使用練習
* 函式練習
* 爬蟲練習
* 影像處理
* 文字雲

### Visual Studio Code (或自選的IDE):

* 使用 turtle 來練習函式跟模組的概念。
* 使用 flask 練習做網頁。

turtle 會使用 tkinter 來產生 GUI 視窗，而 Jupyter Notebook 只能內嵌 HTML 或圖形檔，所以沒有辦法在 Jupyter Notebook 上面使用 Python 原生的 turtle。

## 相關連結：

* Markdown

  * [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
  * [Markdown Cells](https://goo.gl/opufZk)