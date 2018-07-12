# Zalgo in TypeScript

There once was a perfect answer to a often asked StackOverflow question: RegEx match open tags except XHTML self-contained tags (briefly, how to use a Regex to parse HTML or HTML). The answer got...[weird](https://stackoverflow.com/questions/1732348/regex-match-open-tags-except-xhtml-self-contained-tags).

I liked the effect, and looked to see if anyone had listed how to do it. Someone did one better, and created a site that would do it on demand in 2009: [Zalgo text generator by tchouky](http://www.eeemo.net/).

Then someone stole that script, and stuck it on a GitHub gist. Then I stole it from them (well, forked it).

In this project I have refined the gist down to a simple typescript file that will 'Zalgo-ise' any text you give it, with configurable options. Also in the repo is the same script as JS compiled with TSC, and a sample file. Feel free to use as you wish (or steal it in turn - woo unilicense). 