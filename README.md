# Racket Syntax Highlighting for Sublime Text 2

## Installation
This is a Sublime package. To install it:

1. Make a home for your code and then go there, e.g.:

    ```bash
    mkdir ~/lab/SublimeText
    cd ~/lab/SublimeText
    ```

2. Clone the repo:

    ```bash
    git clone https://github.com/oubiwann/sublime-racket.git
    ```

3. Change dir to your Sublime Text 2 Packages directory. You can find that
   directory by selecting "Preferences > Browse Packages ...".

4. From the package directory, link to your checkout:

    ```bash
    ln -s ~/lab/SublimeText/sublime-racket/Racket .
    ```

5. Enable this plugin for your Racket files by doing the following:

   * Open a .rkt file in Sublime Text 2.
   * In the bottom-right of the window, click "Plain Text".
   * Select "Open all with current extension as ...".
   * Select "Racket".
   * Enjoy.
