tecs-helloworld
===============

an experimental sample with [TECS(TOPPERS Embedded Component System)](http://www.toppers.jp/tecs.html "TECS") that prints a string "Hello World!" to standard output.

how to run this sample (on Mac OS X + [HomeBrew](brew.sh/ "HomeBrew")):

1. install tecsgen using homebrew

    ```
    $ brew tap NSaitoNmiri/tecsgen
    $ brew install tecsgen
    ```

2. set environment variables

    ```
    RUBYLIB=/usr/local/opt/tecsgen/tecsgen
    TECSPATH=/usr/local/opt/tecsgen/tecs
    ```

3. clone this sample
    ```
    $ git clone https://github.com/NSaitoNmiri/tecs-helloworld.git
    ```

4. build
    ```
    $ cd tecs-helloworld
    $ make
    ```

5. run
    ```
    $ ./app.exe
    ```
