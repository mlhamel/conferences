# Euruko 2015

Euruko 2015 was in Salzburg Austria from October 17th to 18th. It is an amazing 1 track
conference helds in Europe every year.

Last year was supposed to be held in Kiev, in Ukraine, but it was finally cancelled because
of the political situation.

## Talks

### Saturday

1. Yukihiro Matsumoto. Keynote

    Talked about concurrency and the japanese language at the same time. The talk was really funny
    and it was great to different aspect of what could become Ruby in the future. Also, Matz took the
    opportunity to explain why Ruby is like it is, why there is a GIL and `no real` concurrency there
    and how/why we are going to fix it.

    a Couple of interesting points from his talk:

        * streem: a new toy language to play with streams and concurency - https://github.com/matz/streem
        * Things about japanese: writing and prononcing long numbers seems sooooo complicated !
        * Migration from 1.8 to 1.9 was painfull, future release migration will be easier
        * Still no road has been chosen, for now, they are still playing with the different models,
          roadmap and models to come... But we can feel that matz is interested by stream programming
        * It seems that we should not ruby MRI but CRuby cause at Ruby 1.9 we've switched from Matz implementation
          to a real VM called YARV

2. Joseph Wilk. Programming as a performance

    An amazing talk about music and code. With a full demonstration what could we do we sonic-pi and ruby.

    twitter: @listrophy

    Things to note:

        * sonic-pi: a amazing editor for sound and visual - http://sonic-pi.ne
        * example sonic-pi - http://sonic-pi.net/#examples
        * CyberneticOrchestra - https://soundcloud.com/cyberneticorchestra

3. Bradley Grzesiak. Simplify Challenging Software Problems with Rocket Science

    Ruby + Space Engineering

    Amazing way of integrating ruby with rocket launching game

        * Kerbal space program is having an api !!! [http://store.steampowered.com/app/220200/]
        * Shown us how to use Ruby with the PIDC pattern
        * n-body problem about gravity
        * PIDC - Proportial Integral Derivative Controller

4. Satoshi Tagomori. Data Analytics Service Company and Its Ruby Usage

    * PlazmaDB - soon to be opensource
    * PerfectMonitor

5. Lydia Krupp-Hunter. Ruby Game Building Throwdown

    Great talk about games, second part was about using websockets for gaming development

    Great libraries to discover:

        * gosu - general game library
        * hosu - general game library
        * chipmunk - physic engine

6. Hanneli Tavante. Humanising Math and Physics on Computer Science

    Need to unify Physics and maths and our industry. it has been done but we need to work
    more in this direction.

    * Kepler wrote SF books !

7. René Föhring. One Inch at a Time - How to get people excited about inline docs

    Great talk exposing a great tools (inchci) helping developers and projects to
    document their projects, and more importanly how, where and when.

    Twitter: @rrrene, creator of inchCI

    Some interesting points:

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

    Commodore 64: The best selling computer of all times

    Interesting links:

        * C64 a visual commpendium [http://www.bitmapbooks.co.uk/]
        * vvvvvv: a game in flash that look like a C64 game but was not,
          now somebody ported it to C64
        * New release of the C64 [http://www.myretrocomputer.com/home.html]
        * 64bites community [http://64bites.com/]
        * C64 emulator [http://vice-emu.sourceforge.net/]

4. Tworit Kumar Dash. RFID Technology with Internet of Things

    Tworit kuwar Dash (@tworitdash)

5. Amy Wibowo. Fold, paper, scissors—an exploration of origiami's cut and fold problem

    Just wow

    Twitter: @sailorhg

    It is possible to create any polygon or form with folding and only 1 cut

    Interesting topics:

        * simple/straight skeleton
        * bubblesort zines
        * shoes graphical library

    Sometime the simple skeleton is now enought, you need to make it flat foldable
    by marking flat foldable lines.

6. Simon Eskildsen. Super-Reliable Software

    Amazing talk. Explaned why we are failing, why memory is failing expecially when
    reaching larger scale (but shit will happen also at smaller scale).

    The idea is that we should decouple components and systems, and more importanly
    learn how to fail gracefuly :)

    stuff look at:

        * toxyproxy
        * simian

7. Christopher Rigor. Cryptography for Rails Developers

    Great talk, update your version of rails and ruby ! forget sslv3

8. EuRuKo 2016 Voting (prepare your slides folks!)

    Next year: Sofia

9. Lighting Talks

    b) cargo, import stuff in ruby, ala python

    d) Code review: Be nice :)

## Notes:

    Interesting projects to look at:

        * Gamification of program: check.io
