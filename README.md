![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## English-Portuguese Translator

В коде представлена модель, способная переводить предложения с *английского* языка на *португальский*.  В качестве словаря для англо-португальского перевода используется набор данных из параллельных пар предложений на разных языках  [http://www.manythings.org/anki/](https://www.google.com/url?q=http%3A%2F%2Fwww.manythings.org%2Fanki%2F) разделенных табуляцией. Также в коде реализована **BPE-токенизация** (**Byte Pair Encoding**), которую используют в **GPT** моделях от **OpenAI**. 

**BPE-токенизация** (**Byte Pair Encoding** )— это алгоритм субсловной токенизации, который находит оптимальный баланс между токенами-словами и токенами-символами, итеративно объединяя наиболее частые пары символов или токенов в корпусе текста до достижения заданного размера словаря. В результате он создает компактный и эффективный словарь, где частые слова остаются целыми, а редкие или неизвестные слова разбиваются на осмысленные подслова или символы, что позволяет языковым моделям обрабатывать любой текст без проблем с незнакомой лексикой.

Для разработки переводчика использовался рекуррентный автокодировщик. **Рекуррентный автокодировщик** — это архитектура нейронной сети, в которой рекуррентные нейронные сети (RNN) используются в качестве энкодера и декодера. Его архитектура представлена и описана в **Google Colab** проекте.

> Настоятельно рекомендую использовать в **графический ускоритель T4** или
> мощнее!
