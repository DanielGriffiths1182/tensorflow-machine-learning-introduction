**BEGINING TENSORFLOW MACHINE LEARNING**

*Daniel Griffiths' experience*

**install TensorFlow**



    `sudo pip install tensorflow --ignore-installed six`

-  `sudo` If not root user
-  `--ignore-installed six` On MacOSX due to preinstalled version of six

**easy_install (only if `import tensorflow as tf` throws numpy version error)**



    `sudo easy_install numpy`

- `easy_install` regulates numpy versions

**start Python in Command Line**



    `python`

**python**



    `import tensorflow as tf`
    `hello = tf.constant('Hello, TensorFlow!')`
    `sess = tf.Session()`
    `print(sess.run(hello))`

**return**
- `'Hello, TensorFlow!'`


Ya done!
