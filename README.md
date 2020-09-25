# zxcvbn
Command-line implementation of Dropbox's zxcvbn library

Written in Perl.  You need Perl installed.

Have CPAN installed on your computer, which is Perl's module installer.  On a Mac or Ubuntu, simply type `cpan` to see a nice long paragraph about what CPAN is and how to install it.  Type "yes" and hit return.  If you see a `cpan>` prompt, then CPAN is installed and CTRL-C out of it.

Then, to install the Perl zxcvbn library via CPAN,
```
sudo perl -MCPAN -e 'CPAN::Shell->force( qw( install Data::Password::zxcvbn ))'
```

## How to run command-line zxcvbn

1. Copy the contents of my `zxcvbn` script into your `~/bin` directory.
2. `chmod 755 ~/bin/zxcvbn` on the command-line to make it executable.
3. Then just run `~/bin/zxcvbn` on the command-line.  It will wait until you type or paste your password.  Press enter to see the resulting password strength.
4. Add ~/bin to your path, so you can just type `zxcvbn` at any time.
