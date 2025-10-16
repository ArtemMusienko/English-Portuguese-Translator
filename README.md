![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## English-Portuguese Translator

В коде представлена модель, способная переводить предложения с *английского* языка на *португальский*.  В качестве словаря для англо-португальского перевода используется набор данных из параллельных пар предложений на разных языках  [http://www.manythings.org/anki/](https://www.google.com/url?q=http%3A%2F%2Fwww.manythings.org%2Fanki%2F)  разделенных табуляцией.  Также в коде реализована **BPE-токенизация** (**Byte Pair Encoding**), которую используют в **GPT** моделях от **OpenAI**.

Для разработки переводчика использовался *рекуррентный автокодировщик*, архитектура которых представлена и описана в **Google Colab** проекте.

> Настоятельно рекомендую использовать в **Google Colab графический ускоритель T4** или
> мощнее!
