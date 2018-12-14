Overview
============
This is the Generative Adversarial Network Demo written in Python using the Theano ML library. This is the code for the Generative Adversarial Network Episode of Fresh Machine Learning on [Youtube](https://youtu.be/deyOX6Mt_As). There is a default static gaussian distribution curve that the generator curve continously tries to mimic. Each timestep it gets better and better as it slowly gets better at fooling the disciminator network. Here's a cool live [demo](http://cs.stanford.edu/people/karpathy/gan/)

![http://i.imgur.com/5qzjtgd.png](http://i.imgur.com/5qzjtgd.png)

Dependencies
============

* Python 2.7+ - (https://www.python.org/downloads/)
* matplotlib - `pip install matplotlib`
* theano - `pip install theano`
* scipy - `pip install scipy`
* foxhound (included)

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies

Basic Usage
===========
If your dependencies are installed you can just run the code! A pyplot GUI should pop up and it will get better and better as it trains. 

```shell
python demo.py
```

*Pull Requests are encouraged!!! This pyplot stuff can get wonky, so definitely make a PR if you see something that needs fixing.*

Credits
===========
Credit for this demo code Alec Radford and can be found [here](https://gist.github.com/Newmu/4ee0a712454480df5ee3). I've merely moved some functions around and added a lot more documentation. 

### Support:

If you want the good work to continue please support us on

* [PAYPAL](https://www.paypal.me/ishandutta2007)
* [BITCOIN ADDRESS: 3LZazKXG18Hxa3LLNAeKYZNtLzCxpv1LyD](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)
