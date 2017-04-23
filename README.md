# INFO7250-Final
Final Project of Engineering Big-Data Systems

Check these first:<br>
<a href="">Presentation</a><br>
<a href="">Report</a>

Prerequisites:
You need to have the following installed:<br>
python3.6<br>
Spark<br>
The following python libraries are needed:<br>
Theano, Tensorflow, Keras

To run:

1. Install Git and clone this repo

2. Download all the content of <a href="https://drive.google.com/open?id=0B-cyNEbHVKHCczZ3RlAwaFQwWlE">this</a> folder and put them in INFO7250-Final/dataset

3. Navigate to INFO7250-Final/code folder in your terminal
```sh
$ cd path/to/INFO7250-Final/code
```

4. Data preprocessing, run SmallDataProcessing.py and LargeDataProcessing.py
```sh
$ python SmallDataProcessing.py
$ python LargeDataProcessing.py
```

5. Run ANN on small dataset. Check the output in terminal.
```sh
$ python ann_s.py
```

6. Run ANN on large dataset. Check the output in terminal.
```sh
$ python ann_l.py
```
