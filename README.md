# Euruko 2015

Euruko 2015 was in Salzburg Austria from October 17th to 18th.

## Talks

### Saturday

1. Yukihiro Matsumoto. Keynote

    Talk about concurrency and the japanese language. Funny talk that is introducing what could become
    Ruby in the future Matz took the opportunity to explain why we are there and why we are going to
    fix it.

    * streem: a new toy language to play with streams and concurency - https://github.com/matz/streem
    * funny japanese lecon, numbers are sooooo complicated !
    * Future release migration will be less painful
    * for now, they are still playing with the different models, roadmap and models to come...
    * Not MRI but CRuby cause Ruby 1.9 switched from Matz implementation to a real VM called YARV

2. Joseph Wilk. Programming as a performance

    twitter: @listrophy

    Where music, video and ruby are merging for the show !

    * sonic-pi: a amazing editor for sound and visual - http://sonic-pi.ne
    * example sonic-pi - http://sonic-pi.net/#examples
    * CyberneticOrchestra - https://soundcloud.com/cyberneticorchestra
    * Amazing live coding demo

3. Bradley Grzesiak. Simplify Challenging Software Problems with Rocket Science

    Ruby + Space Engineering

    Amazing way of integrating ruby with rocket launching game

    * n-body problem about gravity
    * PIDC - Proportial Integral Derivative Controller

4. Satoshi Tagomori. Data Analytics Service Company and Its Ruby Usage

    * PlazmaDB - soon to be opensource
    * PerfectMonitor

5. Lydia Krupp-Hunter. Ruby Game Building Throwdown

    * Game development librairies in ruby

    Great talk about games, second part was about using websockets for gaming development

    * gosu - general game library
    * hosu - general game library
    * chipmunk - physic engine

6. Hanneli Tavante. Humanising Math and Physics on Computer Science

    Need to unify Physics and maths and our industry. it has been done but we need to work
    more in this direction.

    * Kepler wrote SF books !

7. René Föhring. One Inch at a Time - How to get people excited about inline docs

    Great tools that I definitely need to give a tool.

    Twitter: @rrrene, creator of inchCI

    * YARD -> javadocs format
    * TomDoc -> benefit of javadoc + adding visibility marker
    * "people are not Ruby parsers" v.s. "good code is its own documentation"
    * Example of tools about code: rubocop, but there's nothing great like that for documentation
    * The ideal tool would (inch)
    ** define priority of what should be documented [PRIORITY]
    ** would create a point system for every point and give a score (0..100) [SCORE]
    ** great text interface with colors, great presentation and bar chart

8. Lighting Talks

    a) Ruby Habits (Featuring bears)

        Presentation about a user group which is meeting every X times. If you have something broken
        just show up and show it to someone and they will try to help you.

    b) Elixir

        Error tracking is hard:

        * shared mutable data
        * no built-in crash recovery mechanism
        * GC is hard
        * threading is hard
        * preempting is hard
        * monitoring is hard

    c) Json api schema tools

        github.com/POSpulse/jast

    d) The dark side of Matz

        **Great small funny talk**

        "DST - The biggest work program since the invention of time itself"

        Matz commit message: "...I hate DST!"

        "I hate autoload..."

        ~"Level of hate of Matz is 0.00001 of Linus one..."

    e) @matz_translated - Automatic translation of the tweets of matz

    f) Bundler

        `ruby together` none profit in the USA !

        "improve your ruby tools"

        * @indirect @dwradcliffe are part of team that are paid to work on Bundler and Ruby Gem.
        * Work is also done on the infrastructure
        * Plan:
        ** maintain rubygem
        ** apply security gems
        ** ...
        * rubytogether.org/join

### Sunday

1. Koichi Sasada. Lightweight Method Dispatch on MRI

2. Richard Huang. Refactor ruby code based on AST

    Online tools to automate code review:

        * CodeClimate
        * PullReview

    Are based on the following packages:

        * flay: Flay analyzes code for structural similarities. [http://ruby.sadi.st/Flay.html]
        * brakeman: security scanner. [http://brakemanscanner.org/]
        * rails_best_practices. [http://rails-bestpractices.com/]

    Parsers:

        * ParseTree
        * ruby_parser
        * ripper: Ruby built-in parser
        * parser: New parser

    Interesting stuff:

        * transpec: Rewrite stuff from the old rspec syntax to the new one
        * rubocop: A Ruby static code analyzer, based on the community Ruby style guide
        * synvert: synvert is used to convert ruby code to better syntax

3. Michał Taszycki. Learn to program Commodore 64 this year!

4. Tworit Kumar Dash. RFID Technology with Internet of Things

5. Amy Wibowo. Fold, paper, scissors—an exploration of origiami's cut and fold problem

6. Simon Eskildsen. Super-Reliable Software

7. Christopher Rigor. Cryptography for Rails Developers

8. EuRuKo 2016 Voting (prepare your slides folks!)
