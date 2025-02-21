# About project
## this is a chatbot with a graphical interface on PyQt5, which searches for the most appropriate answer in a pre-loaded database (answer.txt ) using TF-IDF and cosine similarity.
![__6](https://github.com/user-attachments/assets/eb2d08e6-2d2b-4bb0-8349-ecf55875c024)
___
# How to use
## you can change the answers in answer.txt
## You can change the response language. 

```python
# Загрузка стоп-слов и инициализация стеммера
nltk.download('stopwords')
nltk.download('punkt')
stop_words = set(stopwords.words('russian'))
ps = PorterStemmer()

```

## Also you can use UI and change it in [Qt designer](https://doc.qt.io/qt-6/qtdesigner-manual.html)
![_5](https://github.com/user-attachments/assets/f4688333-f6f1-4ce0-ba5c-6d9976e8e907)
