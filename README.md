MxDevTool(Beta) : Financial Library
==========================

![image](https://img.shields.io/badge/Platform-Windows-Green.svg)
![image](https://img.shields.io/badge/python-3.6|3.7|3.8-blue)


MxDevTool is a Integrated Developing Tools for financial analysis. 
Now is Beta Release version. The Engine is developed by C++. 

Feature Support
---------------

Functionalty :

-   Economic Scenario Generator
-   Asset Liability Mangement
-   Random Number Generator (MersenneTwister, Sobol)
-   Moment-Matching Process
-   InterestRateSwap Pricing
-   Option Pricing


Requests officially supports Python 3.6–3.8

Quick start
-----------

To install MxDevTool, simply use pip :

``` {.sourceCode .bash}
$ pip install mxdevtool
```

Import MxDevTool Library :
```python
import mxdevtool as mx
```

MxDevTool Core Engine Version :
```python
>> mx.__version__
```

For more examples, check this repository.


Npzee Viewer
-----------

All scenario results are generated by npz file format. you can read directly using numpy library or Npzee Viewer.

You can download Npzee Viewer in [WindowStore](https://www.microsoft.com/store/apps/9N19KHP7G2P4) or [WebPage](https://npzee.montrix.co.kr).


License
-------

This mxdevtool-python project is licensed under MIT. But MxDevTool is following.

MxDevTool(non-commercial version) is free for non-commercial purposes. 
This is licensed under the terms of the Montrix Non-Commercial License(see the file LICENSE).

Please contact us for the commercial purpose. <master@montrix.co.kr>

If you're interested in other financial application, visit [Montrix](http://www.montrix.co.kr)