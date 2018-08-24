# WordPress Development for teams with VS Code
This guide will help you get started with best practices for WordPress development using VS Code.

## Prerequisites 
### Global dependencies
- install [VS Code](https://code.visualstudio.com/download)
- install [Composer](https://getcomposer.org/download/), which is a package manager for PHP applications

Once you have Composer installed, run the following commands to install needed packages globally on your machine.

- `composer global require "squizlabs/php_codesniffer=*"`
- `composer global require "wp-coding-standards/wpcs"`

You then need to add the Composer `bin` directory to your terminal `PATH`. If you're using the default bash shell on macOS, this can be done with the following command:

- `export PATH=$PATH:~/.composer/vendor/bin`

If you are not using the default bash shell on macOS, we'll trust you're experienced enough to add the correct path inclusion to your shell's configuration file.


### Necessary VS Code Extensions
The following extensions should be searched and installed via the VS Code Extensions panel (`Command + Shift + X`).

- `EditorCongig for VS Code`
- `phpcs`

##Setup


