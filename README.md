# Website of Armchair Conservationist

This is the source repository for the website of
[the Armchair Conservationist][home].

## Contributing contents.

To contribute contents you do not need to known any [jekyll] or ruby.
You just have to write an appropriate markdown file.


## Setup.

The website is hosted as a github page using [jekyll]. If you want to
preview the contents on your local machine, it would do good to
install [jekyll] on your local machine. We give a short setup
instruction for this (tested on Debian stable but should be easy to
replicate on any standard Unixes).

1. [Install rvm][rvm]

2. Setup appropriate version of ruby and gemset.

```
$ rvm install `cat .ruby-version`
$ rvm gemset create `cat .ruby-gemset`
```

3. Install bundler and the rest of the dependencies.

```
$ gem install bundler
$ bundle insta
```

Now you are ready to go.

## Copyright, Licenses and all that.

(C) 2016, The Armchair Conservationist.


1. Every information here is released under
   [Creative Commons Attribution-ShareAlike]

2. Every script/executable/program here is under the BSD3 license.

3. Any contribution to this repository should be through a github pull
   request. Any such pull request is treated as a transfer of copy
   right to us, i.e. [the Armchair Conservationist][home]

4. In return, we pledge that the material will continue to be released
   under the same terms and conditions.

A copy of the license is provided with this repository under the
licenses sub-directory.


### Why all this drama?

We do not have any commercial interest in the stuff available from
this site. Our goal is the wide distribution of the information
here. Contributions from people are greatly welcome. Ideally, we would
like to release every thing here under [public domain]. But the sad
fact is that we live in a less than perfect world. So to avoid crazy
litigation, we have copyrighted every material here.

[home]: <https://armchair-conservationist.github.io/> "Armchair conservationst"

[public domain]: <https://en.wikipedia.org/wiki/Public_domain>

[cc-by-sa-3]: https://creativecommons.org/licenses/by-sa/3.0/


[debian]: <http://www.debian.org> "Debian: the universal operating system"
[rvm]: <https://rvm.io/> "RVM: Ruby version manager"
[jekyll]: <https://jekyllrb.com/> "Jekyll"
[ruby]: <https://www.ruby-lang.org/> "Ruby language"
