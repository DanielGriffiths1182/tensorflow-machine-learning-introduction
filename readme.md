#BEGINING TENSORFLOW MACHINE LEARNING#

*Daniel Griffiths' experience*

**install TensorFlow**
1.


    `sudo pip install tensorflow --ignore-installed six`

-  `sudo` If not root user
-  `--ignore-installed six` On MacOSX due to preinstalled version of six

**easy_install**
1.


    `sudo easy_install numpy`

- `easy_install` regulates numpy versions

# start Python in Command Line
1.


    `python`

**python**
1.


    `import tensorflow as tf`
    `hello = tf.constant('Hello, TensorFlow!')``
    `sess = tf.Session()``
    `print(sess.run(hello))`

**return**
- `'Hello, TensorFlow!'`


Ya done!
