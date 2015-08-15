## This repository is deprecated. The network code has been merged into [`spragunr/deep_q_rl`](https://github.com/spragunr/deep_q_rl)


### Dependencies
* [Anaconda Python](https://code.google.com/p/rl-glue-ext/wiki/Python)

* OpenCV
```
conda install -c https://conda.binstar.org/menpo opencv
```

* Pylearn2
```
git clone git@github.com:lisa-lab/pylearn2.git
cd pylearn2
python setup.py develop
```

* Lasagne
```
git clone git@github.com:benanne/Lasagne.git
cd Lasagne
python setup.py install

```

* SDL
```
sudo apt-get install libsdl1.2-dev libsdl-image1.2-dev libsdl-gfx1.2-dev libopencv-dev python-opencv
```

* [RLGlue](https://code.google.com/p/rl-glue-ext/wiki/RLGlueCore)

* [RLGLue Python Codec](https://code.google.com/p/rl-glue-ext/wiki/Python)

* Arcade Learning Environment
```
git clone git@github.com:mgbellemare/Arcade-Learning-Environment.git
cd Arcade-Learning-Environment
cp makefile.unix makefile
# edit makefile to set USE_RLGLUE and USE_SDL to 1
make && make install
```
