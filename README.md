# Duygu Analizi

Makine öğrenimi teknikleri kullanılarak duygu analizi çalışması gerçekleştirilmiştir. Çalışma kapsamında, Logistic Regression, SGDClassifier ve Naive Bayes algoritmaları kullanılmıştır.

## Veri Kümesi

Twitter üzerinde duyarlılık analizi çalışmalarında pek çok farklı teknik ve veri kümesi kullanılır. Çalışma, Twitter üzerinden elde edilen 10700 Twitter gönderisi (Tweet) ile gerçekleştirilmiştir. Gönderiler konu bağımlı olarak belirlenmiş ve "Turkcell" anahtar kelimesi kullanılarak elde edilmiştir. Belirlenen anahtar kelime ("Turkcell") ile ilgili atılan tweetler periyodik şekilde toplanmıştır. Toplanan gönderiler tek tek okunarak el ile olumlu ve olumsuz olarak etiketlenmiştir. Verileri elde etme süreci projenin içerisinde yer almamaktadır.

Veri kümesi csv dosyası olmakla birlikte, "created_at", "date", "time", "username", "tweet" ve "target" (0: Olumsuz, 4: Olumlu) kolonlarından oluşmaktadır.

## Gereksinimler
 
 `Numpy` -> 1.18.1
 `Pandas` -> 1.0.3
 `Scikit-Learn` -> 0.23.1
 `Matplotlib` -> 3.2.1
 `NLTK` -> 3.2.4
 

## Anaconda Python'u Yükleme

NumPy, Pandas, NLTK ve Matplotlib'i kurmanın en kolay yolu Anaconda Python dağıtımı ile başlamaktır.

1.  [Anaconda kurulum talimatını](https://anaconda.org/anaconda/python) izleyiniz.
2. Bu deponun tamamını etkileşimli olarak veya manuel bir şekilde GitHub'dan indiriniz. Sıkıştırılmış halini açınız.
3. Jupyter Notebook ile projeyi başlatınız.
