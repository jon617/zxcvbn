# zxcvbn
Command-line implementation of Dropbox's zxcvbn library

Written in Perl.  You need Perl installed.

Make sure you have CPAN installed.  On a Mac, simply type `cpan` to see a nice long paragraph about what CPAN is and how to install it.  Type "yes" and hit return.

Then, to install the Perl zxcvbn library via CPAN,
```
sudo perl -MCPAN -e 'CPAN::Shell->force( qw( install Data::Password::zxcvbn ))'
```

# How to run

1. Copy the contents of my `zxcvbn` script into your `~/bin` directory.
2. `chmod 755 ~/bin/zxcvbn` on the command-line.
3. Then just run `~/bin/zxcvbn` on the command-line.  It will wait until you type or paste your password.  Press enter to see the resulting password strength.

