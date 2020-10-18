## Record the technical problem I met during my project and class

#### my machine
- Ubuntu 20.04
- intel i5-10500
- Nividia 2060 super (6G)
- 32G RAM

#### 10.17 Problem when installing pydensecrf

##### configuration 
- python 3.8
- only pip, without anaconda
- tensorflow-gpu 2.2

##### failed attempt
- 1. use pip to install pydensecrf
- 2. download the .whl file to pip install + filename
- 3. pip install git+*github repo address*
##### solution
- install anaconda
- create a environment with python version <=3.7
- then use the following command -> conda install -c conda-forge pydensecrf
