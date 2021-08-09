![](assets/images/banner.png)



<img src="assets/images/htb.png" style="margin-left: 20px; zoom: 60%;" align=left />    	<font size="10">Challenge Name</font>

​		DD<sup>th</sup> Aug 10. 2021

​		Challenge Author(s): Funkyhotspot

​		

 



### Description:
Hassu manninen likes to shop online.
Can you find out more about his online shopping habits?


### Objective

Find a review that Hassu manninen made about a book by translating stuff on Hassus Social media

### Difficulty:
Medium

### Flag:

HTB{3c0mm3rz_4R3_6r4T3!}


# Challenge

First we find the Instagram (https://www.instagram.com/manninenhassu/)




this could be done by sherlock.py for example or easily by hand


when looking at the posts we come across some comments:


when translated we find out that Hassu has a new twitter and the twitter account is @manninen1337






the first tweet on the twitter account when translatet lets us know that Hassu makes his online purchasing on Amazon.de 




The next tweet lets us know that he read the book Social engineering: the sience of Human Hacking 
and the comment on that tels us that Hassu has left a rfewiew on that book







So naturally we check out the rewiews on that book on amazon.de (https://www.amazon.de/Social-Engineering-Science-Human-Hacking/dp/111943338X/ref=sr_1_1?crid=39P4OHUVHJEIO&dchild=1&ie=UTF8&keywords=social%20engineering&language=en_GB&qid=1628430174&sprefix=social%20en%2Caps%2C254&sr=8-1)
and find Hassus reviews (third one from the top) with the flag!









