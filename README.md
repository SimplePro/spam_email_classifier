spam_email_classifier
-----------------
정확도 : 약 98%
```python
>>> from spam import Spam
>>> spam = Spam("WINNING AMOUNT My name is Mark Zuckerberg, A philanthropist the founder and CEO of the social-networking website Facebook, as well as one of the world's youngest billionaries and Chairman of the Mark Zuckerberg Charitable Foundation, One of the largest private foundations in the world. I belive strongly in gving while living I had one idea that never changed in my mind - that you should use your wealth to help people and i have decided to secretly give {&1,500,000.00} to randomly selected individuals worldwide. On receipt of this email, you should count yourself as the lucky individual. Your email address was chosen online while searching at random. Kindly get back to me at your earliest convenience, so I know your email address is valid. Email me Visit the web page to know more about me")
>>> print(spam.predict())
1
