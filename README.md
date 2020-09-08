# Bengali.AI_Handwritten_Grapheme_Classification    ![](https://img.shields.io/badge/python-3.7+-pink.svg) ![](https://img.shields.io/badge/tensorflow-2.x-important.svg) 


***Group Member: [Guansu Niu](https://github.com/francesniu), [Shiqi Lei](https://github.com/beckyleii), [Tongxin Wang](https://github.com/tongxinw)***


*[Project Posts] (https://tongxinw.github.io/bengali.ai/)*


### Project Motivation & Goal
Bengali (bāṅlā / বাংলা or bāṅālī / বাঙালী) is the official language of Bangladesh and the second most spoken language in India. Considering the number of its users, there are significant benefits in developing models that can optically recognize images of the handwritten graphemes. Bengali has 49 letters (to be more specific 11 vowels and 38 consonants) in its alphabet, there are also 18 potential diacritics, or accents. This means that there are many more graphemes that added complexity results in ~13,000 different grapheme variations (compared to English’s 250 graphemic units).

This Kaggle project hopes to improve on approaches to Bengali recognition and to classify the components of handwritten Bengali. We obtained the dataset from Kaggle Research Code Competition (https://www.kaggle.com/c/bengaliai-cv19) and we are given the images of a Bengali handwritten grapheme. We separately classified three elements in the image: grapheme root, vowel diacritics, and consonant diacritics. This blog post serves as a documentation of our learning experience. All secourses we used are listed in the reference list.



