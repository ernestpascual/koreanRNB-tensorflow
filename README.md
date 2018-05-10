# Korean RNB Chord Generator Using Tensorflow
It contains 14 test mid files generated from different Korean RNB songs by converting the songs to midi using Ableton Live 9.
Training set will be update with more files soon. 

## Dependencies
  * [Tensorflow](https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html)
  * pandas
  * numpy
  * msgpack-python
  * glob2
  * tqdm 
  * python-midi
 ```
    pip3 install pandas
    pip3 install msgpack-python
    pip3 install numpy
    pip3 install glob2
    pip3 install tqdm
    pip3 install py-midi
```

## References
Codes are heavily based from this [medium article](https://towardsdatascience.com/deep-learning-with-tensorflow-part-3-music-and-text-generation-8a3fbfdc5e9b)
You can also refer this [github repository](https://github.com/burliEnterprises/tensorflow-music-generator)

## How to use
Enter this in the commandline:
```
python3 rbm_chords.py
```

## Notes
If you encounter an error of like [this](https://github.com/vishnubob/python-midi/issues/144), make sure you have python3 and enter this on the command line:

```
pip3 install git+https://github.com/vishnubob/python-midi@feature/python3
'''

