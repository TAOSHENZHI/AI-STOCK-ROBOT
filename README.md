# AI-STOCK-ROBOT
Demo
----

![Watch the video](https://github.com/TAOSHENZHI/AI-STOCK-ROBOT/blob/master/demo video.mp4)

Configuration Instructions
----

Installation Instructions
----

We need some online packages to be installed for this Chatbot.

### **RASA-NLU**

***Prerequisites***

Make sure the Microsoft VC++ Compiler is installed, so python can compile any dependencies. You can get the compiler from: https://visualstudio.microsoft.com/visual-cpp-build-tools/ Download the installer and select VC++ Build tools in the list.

***Quick Install for RASA-NLU***

    pip install rasa_nlu
    python -m rasa_nlu.server &

**For more installation information**

Go to https://rasa.com/docs/nlu/installation/



### **iexfinance**

***Quick Install for iexfinance***

From PyPI with pip (latest stable release):

    $ pip3 install iexfinance

From development repository (dev version):

    $ git clone https://github.com/addisonlynch/iexfinance.git
    $ cd iexfinance
    $ python3 setup.py install

**For more installation information**

Go to https://github.com/addisonlynch/iexfinance



### **wxpy**

***Quick Install for wxpy***

From PyPI with pip:

    pip3 install -U wxpy

From douban IO PyPI source#(Recommend for users in China mainland):

    pip3 install -i https://pypi.doubanio.com/simple/ -U wxpy

**For more installation information**

Go to https://wxpy.readthedocs.io/zh/latest/#



Operation Instructions
----

1.Download all files in a same folder.

2.Open lty_bot.py file in any IDE, the IDE I used to run is Jupyter Notebook.

3.Change the statement below to chat with different friend.

    my_friend = bot.friends().search('游否', sex=MALE, city="深圳")[0]

4.Run it, an QR code will created automatically, use your Wechat to scan the QR code and log in.

5.Start to chat!



Contact Me
----

QQ: 529427575

Email: 529427575@qq.com


Changelog
----

2019.5.24 upload file

2019.5.24 uoload readme
