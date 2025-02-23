# perlres

List of resources about Perl :dromedary_camel:

![Perl 5 raptor](https://camo.githubusercontent.com/039c0b770fdaff0f1418c5afa4296dfaba5f2875/68747470733a2f2f7261772e6769746875622e636f6d2f6b726169682f7065726c2d726170746f722f6d61737465722f6578616d706c652e706e67)  

Perl 5 raptor from [kraih](https://github.com/kraih/perl-raptor), licence [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## :clipboard: Summary 

Derivated from [LinuxFR](https://linuxfr.org/) french article [Pour tout savoir du Perl post-moderne](https://linuxfr.org/news/pour-tout-savoir-du-perl-post-moderne) 

As a reminder, [Perl](https://www.perl.org/) is a general-purpose progamming langage created in 1987 by [Larry Wall](https://fr.wikipedia.org/wiki/Larry_Wall). 

> "Perl continues to flourish into its fourth decade thanks to a vibrant community of users and developers" (dixit [perldelta](https://metacpan.org/pod/distribution/perl/pod/perldelta.pod#Acknowledgements))

Perl is distributed under a dual licence : [Artistic Licence](https://opensource.org/licenses/Artistic-2.0) and [GPL v1+](https://www.gnu.org/licenses/gpl-3.0.html). Most of CPAN modules [follow the same rule](https://www.cpan.org/misc/cpan-faq.html#How_is_Perl_licensed).

------

## :construction_worker: Perl core development
- :octocat: [Perl git](https://perl5.git.perl.org/perl.git) - Where is located the **Perl interpreter source code** (as of today) and its [github mirror](https://github.com/Perl/perl5)
- :bug: [Perl bug tracker](https://rt.perl.org/Public/Search/Results.html?Query=Queue%20=%20%27perl5%27%20AND%20(Status%20=%20%27new%27%20OR%20Status%20=%20%27open%27%20OR%20Status%20=%20%27stalled%27)) - Uses Perl software [Request Tracker](https://bestpractical.com/request-tracker) the ticketing system
- :mailbox: [Perl porters mailing list](https://lists.gt.net/perl/porters/) - Mailing list of the Perl core developers
- :hammer: [Compile and install Perl](https://metacpan.org/pod/distribution/perl/INSTALL) - If you want to compile it by hand (if you don't want Perl vendor)
- :small_red_triangle_down: [Perl Delta](https://perldoc.pl/perldelta) - The latest changelog
- :small_red_triangle: [All changelogs]( https://perldoc.pl/perl#Miscellaneous) - All changelogs
- :scroll: [Very detailed history of Perl versions](https://perldoc.pl/perlhist.html) - Date and major changes from Perl creation to today
- :older_woman: [Depreciations](https://metacpan.org/pod/distribution/perl/pod/perldeprecation.pod) - The latest list of deprecated symbols
- :penguin: [Portability](https://perldoc.pl/perlport.html) - Perl supports [more than 100 platforms](https://www.cpan.org/ports/index.html)

## :necktie: Official
- :house: [perl.org](https://www.perl.org/) - The Perl's "home"
- :european_castle: [Perl Fundation](https://www.perlfoundation.org/) - The Perl fundation
- :mortar_board: [White Camel Awards](https://www.perl.org/advocacy/white_camel/) - Yearly awards for important contribution to Perl (not only with code)

## :hammer_and_pick: Modules and installers
- :pill: [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm) - Modern CPAN modules installer by [Tatsuhiko Miyagawa](https://github.com/miyagawa) ([CPAN profile](https://metacpan.org/author/MIYAGAWA))
- :hammer: [Perlbrew](https://perlbrew.pl/) - Perl binaries installer
- :wrench: [plenv](https://github.com/tokuhirom/plenv) - Another Perl binaries handler. [Differences between perlbrew and plenv](https://weblog.bulknews.net/plenv-alternative-for-perlbrew-7b5bf00a419e)
- :gift: [Perl carton](https://github.com/perl-carton/carton) - A bundler for Perl (uses [cpanfile](https://github.com/miyagawa/cpanfile))
- :book: [Task::Kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho) - List of important modules
- :moneybag: [Corelist](http://corelist.rpee.be/) - A web interface of the tool **Corelist** used to know _core modules_ shipped in a specific version of Perl.
- :older_man: [CPAN.pm](https://metacpan.org/pod/CPAN) - Venerable CPAN modules installer, part of core distribution, fully configurable ([github](https://github.com/andk/cpanpm))
- :frog: [CPAN Plus](https://github.com/jib/cpanplus-devel) - API to access CPAN mirrors (+ CPAN modules installer)

## :dromedary_camel: General
- :man_with_turban: [Perl Monks](https://www.perlmonks.org/) - The Perl _Stack Overflow_
- :man_with_turban: [Perl Monks… **again**](https://www.perlmonks.org/) - Because it's so cool, even if it looks like a cave :speak_no_evil:
- :book: [Perldoc from perl.org](https://perldoc.perl.org/) and [perldoc from grinnz](https://perldoc.pl) :new:
- :moneybag: [Core modules list](https://perldoc.pl/modules) - Web interface to the tool `corelist`
- :book: [Perl Maven](https://fr.perlmaven.com/) - A huge website about Perl
- :books: [Perl Meme](http://perlmeme.org/) - A website about Perl (tutorials, FAQ and more)
- :school: [Enlightened Perl](https://ww2.enlightenedperl.org/) - An organization supporting Perl

## :fuelpump: Around the CPAN
- :ocean: [CPAN Deps](http://deps.cpantesters.org/) - List dependencies from a CPAN module
- :new: [CPAN Doc](https://cpandoc.grinnz.com/) - Documentation of some important modules
- :heavy_check_mark: [CPAN Testers](http://cpantesters.org/) - Build and test reports of CPAN modules
- :scroll: [BackPAN](http://backpan.cpantesters.org/) - The CPAN with all history
- :speech_balloon: [PrePAN](http://prepan.org/) - Discuss modules before CPAN upload
- :earth_africa: [CPAN Map](http://mapofcpan.org) - Namespaces map of CPAN modules
- :heavy_check_mark: [CPAN Cover](http://cpancover.com) - Test coverage of CPAN modules
- :heavy_check_mark: [CPAN TS](https://cpants.cpanauthors.org/) - Kwalitee metrics
- :mortar_board: [CPAN IO](http://cpan.io/) - CPAN authors rankings according to their activity
- :octocat: [CPAN PRC](http://cpan-prc.org/) - CPAN Pull Request Challenge
- :floppy_disk: [CPAN Mirrors](http://mirrors.cpan.org/) - The CPAN mirrors around the world
- :cloud: [StratoPAN](https://stratopan.com) - Private CPAN repositories in the cloud
- :underage: [CPAN Audit](https://github.com/vti/cpan-audit) - Audit CPAN modules for security vulnerabilities
- :mag_right: [CPANMeta](https://cpanmeta.grinnz.com) - Browse CPAN metadata ([github](https://github.com/Grinnz/cpan-meta-browser))

## :beers: Social
### Community
- :speech_balloon: [Perl Reddit](https://www.reddit.com/r/perl/) - Subreddit for Perl
- :neckbeard: [Perl Mongers](https://www.pm.org/) - Perl Mongers
- :neckbeard: [French Perl Mongers](http://www.mongueurs.net/) - French Perl Mongers group
- :jp: [Perl Entrance](http://www.perl-entrance.org) - Sort of Perl Mongers group in Japan
- :speech_balloon: [IRC channels](https://perldoc.pl/perlcommunity.html#IRC) - IRC channels for the french mongers, mojolicious, dancer, catalyst, etc...
- :thought_balloon: [Perl Weekly Challenge](https://perlweeklychallenge.org) - Friendly coding competition
- :newspaper: [The Perl Journal](http://www.foo.be/docs/tpj/) - E-Zine about Perl
- :santa: [Perl Advent Calendar](http://www.perladvent.org) - Avent Calendar about Perl
- :christmas_tree: [Mojolicious Advent Calendar](https://mojolicious.io) - Advent calendar about Mojolicious web framework
- :christmas_tree: [Dancer Advent Calendar](http://advent.perldancer.org) - Advent calendar about Dancer web framework
- :octocat: [Pull Request Club](https://pullrequest.club/hello) - Linking maintainers with contributors

### Newsfeeds
- :clipboard: [Perl Sphere](http://perlsphere.net/) - Newsfeed
- :newspaper: [Medium Perl tag](https://medium.com/tag/perl/latest) - Newsfeed
- :newspaper: [Perl Buzz](https://perlbuzz.com/) - Newsfeed
- :memo: [Perl.com](https://www.perl.com/) - Recent domain (despite its name....), a newsfeed
- :clipboard: [Weekly Newsletter](http://perlweekly.com/) - Newsletter gathering Perl news and links

### Blogs
- :couple: [Blogs about Perl](http://blogs.perl.org/) - Blog service for Perl folks
- :family: [Nice Perl blog](http://niceperl.blogspot.com/) - An important blog 
- :speech_balloon: [Cultured Perl](https://culturedperl.com) - A Blog about Perl
- :couple: [Perl Hacks](https://perlhacks.com/) - Just another Perl Hacker's blog

### Conferences
- :heavy_dollar_sign: [YAPC](https://www.yapc.org/) - Major Perl events ([wikipedia](https://fr.wikipedia.org/wiki/Yet_Another_Perl_Conference))
- :walking: [YAPC::NA](http://www.yapcna.org/) - North American flavor of YAPC. Since 2017 it is renamed as [TPC](https://perlconference.us)
- :couple: [YAPC::Europe](http://www.yapceurope.org/) - European flavor of YAPC. 2019 edition is known as [PerlCon](https://perlcon.eu) 
- :family: [YAPC::Asia](http://yapcasia.org) / [YAPC::Japan](https://yapcjapan.org) - Asian/Japanese flavor of YAPC (supported by [Japan Perl Association](https://japan.perlassociation.org/))
- :two_men_holding_hands: **YAPC::SA** - Sud American flavor of YAPC
- :runner: **YAPC::RUSSIA** - Russian flavor of YAPC
- :two_women_holding_hands: **YAPC::AUSTRALIA** - Australian flavor of YAPC
- :heavy_check_mark: **Perl QA Hackathon** 
- :dromedary_camel: **Perl Toolchain Summit**
- :kissing_cat: [OSDC](https://fr.wikipedia.org/wiki/Open_Source_Developers%27_Conference) - Various events like [Israel OSDC](http://osdc.org.il), [French OSDC](http://www.osdc.fr/), **Taiwan OSDC**, **Australia OSDC** or **Malaysia OSDC** 
- :fr: [French Perl Workshop](https://journeesperl.fr/jp2019/) 
- :fr: [Perl Fun Again](http://boivin.eu/download/Perl_Fun_Again/) 
- :fr: [Patch.pm -pn](http://patch.pm) 
- :dromedary_camel: [Several others](https://www.yapc.org/old-events.html) - Several Perl workshops or events

## :book: Official documentations
- :question: [Perl FAQ](https://perldoc.pl/perlfaq.html) - Perl FAQ table of content (several FAQ pages)
- :symbols: [Perlre](https://perldoc.pl/perlre.html) - Regular expression documentation and [tuto](https://perldoc.pl/perlretut.html) and  [quick start](https://perldoc.pl/perlrequick.html) 

![Perl regex](http://imgs.xkcd.com/comics/perl_problems.png)

- :symbols: [Operators list](https://perldoc.pl/perlop.html) and [built‑in functions](https://perldoc.pl/perlfunc.html)
- :pill: [How to write modules/packages](https://perldoc.pl/perlmod.html) or [here](https://perldoc.pl/perlmodlib.html) - or [write a new module](https://perldoc.pl/perlnewmod.html). Some advices to [respect the style](https://perldoc.pl/perlmodstyle.html) in modules
- :symbols: [Perl syntax](https://perldoc.pl/perlsyn.html) - Doc about Perl syntax
- :book: [References](https://perldoc.pl/perlref.html) and [tutorial](https://perldoc.pl/perlreftut.html)
- :book: [Documentation about IPC](https://perldoc.pl/perlipc.html)
- :underage: [Perl security](https://perldoc.pl/perlsec.html) - About _taint checking_ (or « _data flow analysis_ »), _setuid_, _clean PATH_ or _algorithm complexity attacks_
- :straight_ruler: [Reports generation thanks to formats](https://perldoc.pl/perlform.html) - Documentation about formats. *Formats* are a reason of the initial creation of Perl, but they are limited and less and less used
- :wrench: [Degugger documentation](https://perldoc.pl/perldebug.html) - The Perl debugger is itself written in Perl :muscle: 
- :alien: [perlobj](https://perldoc.pl/perlobj.html) and [tuto oo](https://perldoc.pl/perlootut.html) -  Object Oriented Programming in Perl

## :us: Tutorials 
- :closed_book: [Perl Maven](https://perlmaven.com/perl-tutorial)
- :clock230: [Learn Perl in about 2 hours and 30 minutes](https://qntm.org/files/perl/perl.html)
- :green_book: [Minimum Viable Perl (MVP)](http://mvp.kablamo.org)
- :blue_book: [Perl Begin](http://perl-begin.org)
- :100: [Perl101](https://perl101.org)
- :orange_book: [Perl Tutorial Points](https://www.tutorialspoint.com/perl)
- :notebook: [Perl Tutorial](https://www.perltutorial.org)
- :ledger: [Perl in 1 day guru99](https://www.guru99.com/perl-tutorials.html)
- :construction: [Perl Newbie](https://newbie.perlzemi.com)
- :point_up: [Exercism.io](https://exercism.io/my/tracks/perl5) - Learn Perl with code practice and mentorship

## :fr: French tutorials
- :scroll: [Guide Perl](http://formation-perl.fr/guide-perl.html)
- :triangular_ruler: [Formation-Perl](http://formation-perl.fr/)
- :straight_ruler: [Guide de programmation pour apprendre Perl](https://lhullier.developpez.com/tutoriels/perl/intro/)
- :racehorse: [Site du zero](http://sdz.tdct.org/sdz/apprenez-a-programmer-en-perl.html)
- :school: [Cours de l'Université de Rennes](https://perso.univ-rennes1.fr/francois.dagorn/perl/)

## :vibration_mode: Interactive tutorials
- :pizza:[Perltuts](http://perltuts.com/tutorials/quick-start/hello-world) - Learn modern Perl any time and from everywhere :purple_heart: 
- :fries: [Learn Perl](https://www.learn-perl.org/) - Free interactive Perl tutorial :blue_heart:
- :chocolate_bar: [TryPerl](http://tryperl.pl) - TryRuby clone for Perl :heart: ([github](https://github.com/thibaultduponchelle/tryperl))

## :school: Tutorials meta-site
- :books: [Perl tutorials](http://perl-tutorial.org/) - Perl tutorials meta site

## :squirrel: Perl folklore
- :bomb: "**Perl**" vs "**perl**" - **Perl** is the langage, **perl** is the interpreter, **PERL** is how you catch newbies :baby:
- :neckbeard: [JAPH](https://en.wikipedia.org/wiki/Just_another_Perl_hacker) - Just Another Perl Hacker
- :stars: [PerlSecret](https://metacpan.org/pod/distribution/perlsecret/lib/perlsecret.pod) - Secrets operators and their nice nicknames
- :heavy_plus_sign: [$A++](http://paris.mongueurs.net/aplusplus.html) - More than three hundred ways to increment `$A`, by the [Paris Perl Mongers](http://paris.mongueurs.net/)

![](https://imgs.xkcd.com/comics/regular_expressions.png)

- :heavy_dollar_sign: [Magic variables](https://perldoc.pl/perlvar.html) - Why some hate or love Perl (among other reasons)
- :100: [TIMTOWTDI](https://en.wikipedia.org/wiki/There%27s_more_than_one_way_to_do_it) - There's more than one way to do it
- :recycle: [Only perl can parse Perl](https://www.perlmonks.org/?node_id=663393) or [PPI](https://metacpan.org/pod/PPI#Background)
- :notes: The Perl poetry and for instance the poem [Black Perl](https://fr.wikipedia.org/wiki/Black_Perl) from Larry Wall
- :golf: [Perl Golf](http://perlgolf.sourceforge.net/) - Code Golf
- :golf: [Anarchy Golf](http://golf.shinh.org/) - Code golf (not dedicated to Perl)
- :weary: [Laziness, Impatience and Hubris](https://www.brainyquote.com/fr/citation/larry-wall_141510) - The three chief virtues of a programmer
- :sunglasses: [DWIM](https://en.wikipedia.org/wiki/DWIM) - Do What I Mean principle (not this [DWIM](http://dwimperl.szabgab.com/windows.html))
- :grin: State of the onion
- :trollface: **ACME** modules - Purely entertainment modules
- :baby_chick: Easy things should be easy and hard things should be possible :chicken:
- :construction_worker: Get the job done :thumbsup:
- :smiling_imp: [Obfuscated Perl Contest]() - [OPC 0](http://www.foo.be/docs/tpj/issues/vol1_3/tpj0103-0010.html), [OPC 1](https://www.foo.be/docs/tpj/issues/vol2_2/tpj0202-0010.html), ~~OPC 2~~, [OPC 3](http://www.foo.be/docs/tpj/issues/vol3_2/tpj0302-0012.html), [OPC 4](https://www.foo.be/docs/tpj/issues/vol4_3/tpj0403-0017.html) and [OPC 5](https://www.foo.be/docs/tpj/issues/vol5_3/tpj0503-0014.html)
- :notes: [Perl Poetry Contest](https://www.foo.be/docs/tpj/issues/vol4_4/tpj0404-0015.html) - [PPC 1](https://www.foo.be/docs/tpj/issues/vol5_1/tpj0501-0012.html), [PPC 2](http://mkweb.bcgsc.ca/intranet/sapj/tpj/issues/vol5_5/sam05050005/tpj0505-0005.htm)
- :jp: Perl Haiku Contest
- :walking: [NeoCPANisms](http://neilb.org/neocpanisms/) - Sit well and (try to) release new dists each month :smirk_cat:

![](https://imgs.xkcd.com/comics/11th_grade.png)

- :poop: **PHP** was sometimes refered as **P**eople **H**ate **P**erl :grin:
- :poop: [Write Only Language](https://en.wikipedia.org/wiki/Write-only_language) - Relatively common :grin:
- :baby_bottle: **Baby Perl** - Programming with a reduced set of builtins and idioms :baby:
- :sunglasses: [Perl idioms](http://world.std.com/~swmcd/steven/perl/idiom.html) - Perl offers powerful idiomatic expressions (see [fluent Perl](https://docstore.mik.ua/orelly/perl3/prog/ch24_04.htm) or [this node](https://www.perlmonks.org/?node_id=519396))
- :smirk: [Principle of least astonishment](https://en.wikipedia.org/wiki/Principle_of_least_astonishment) - Apply to experienced programmers :stuck_out_tongue_winking_eye:
- :ocean: [The CPAN river](http://neilb.org/2015/04/20/river-of-cpan.html) - Metaphor about CPAN dependencies 
- :jack_o_lantern: [The keeper of the pumpkin](https://perldoc.pl/perlhist.html#THE-KEEPERS-OF-THE-PUMPKIN) - The Perl maintainer (currently [Sawyer X](https://github.com/xsawyerx))
- :paperclip: **Perl** is often considered as being **the duct tape of the Internet**
- :dromedary_camel: [Larry Wall Homepage](http://www.wall.org/~larry/) - Prepare your eyes

## :jack_o_lantern: Perl Ecosystem
- :fuelpump: [CPAN](https://www.cpan.org/) - It is commonly accepted that the Perl _killer app_ is CPAN (*"CPAN is the language, Perl is just the syntax"* - [Audrey Tang](https://fr.wikipedia.org/wiki/Audrey_Tang)) 
- :pill: [MetaCPAN](https://metacpan.org/) - Search the CPAN

### News and forums engines
- :family: [YaBB](http://www.yabbforum.com/) - Forum engine
- :speech_balloon: [Everything Engine](https://www.everything2.com/) - News platform engine  and questions/answers platform ([PerlMonks](https://www.perlmonks.org) is powered by this)
- :couple: [Slashcode](https://github.com/SoylentNews/slashcode) - News and questions/answers platform engine ([Slashdot](https://slashdot.org) is powered by this)
- :family: [DuckDuckGo Instant Answer](https://duck.co/ia) - An aggregator of questions/answers platform ([github](https://github.com/duckduckgo/duckduckgo))

### CMS
- :bookmark_tabs: [Movable Type](https://www.movabletype.org/) - CMS
- :page_with_curl: [Imperia CMS](https://www.pirobase-imperia.com/de/produkte/produktuebersicht/imperia-cms) - CMS
- :seat: [ACT](http://act.mongueurs.net/) - CMS for conferences ([github](https://github.com/book/Act))
- :memo: [Bricolage](http://bricolagecms.org) - CMS ([github](https://github.com/bricoleurs/bricolage))
- :bookmark_tabs: [Krang](http://krang.sourceforge.net/) - CMS
- :memo: [WebGui](http://www.webgui.org/) - CMS
- :page_with_curl: [Simpleness](http://cms.simpleness.org/) - CMS
- :bookmark_tabs: [Callisto](https://sourceforge.net/projects/callistocms/) - CMS
- :memo: [Spine](http://spine.sourceforge.net/) - CMS
- :clipboard: [XIMS](http://xims.info/) - CMS
- :memo: [Blaze Blogger](http://blaze.blackened.cz) - CMS
- :page_with_curl: [Galileo](http://galileo-cms.herokuapp.com/page/home) - CMS
- :memo: [Blio](https://github.com/domm/Blio) - CMS
- :camera: [Expose](https://github.com/Jack000/Expose) - Static site generator for photoessays

### Blogging
- :couple: [Bloxsom](http://blosxom.sourceforge.net/) - Blog engine
- :family: [PearlBee](https://github.com/Perl-Evozon/PearlBee) - Blogging platform
- :couple: [Statocles](http://preaction.me/statocles/) - Static blog generator ([github](https://github.com/preaction/Statocles))
- :speech_balloon: [Giblog](https://github.com/yuki-kimoto/giblog) - Static blog generator
- :family: [Plstblog](https://github.com/linkdd/plstblog) - Static blog generator [written by a LinuxFR user](https://linuxfr.org/users/linkdd/journaux/plstblog-un-g%C3%A9n%C3%A9rateur-de-blog-statique-%C3%A9crit-en-perl)
- :speech_balloon: [Riji](https://github.com/Songmu/p5-Riji) - Static blog generator (based on Wallflower)
- :family: [Dreamwidth](https://www.dreamwidth.org) - Shared blogging
- :couple: [Angerwhale](https://github.com/jrockway/angerwhale) - Blogging engine

### Mailing lists engines
- :mailbox: [Sympa](https://www.sympa.org/) - Mailing lists engine
- :mailbox_with_mail: [Minimalist](https://github.com/madroach/minimalist) - Mailing lists engine
- :mailbox_closed: [Dada Mail](https://github.com/justingit/dada-mail) - Mailing lists engine
- :mailbox_with_no_mail: [Majordomo](http://old.greatcircle.com/majordomo) - Mailing lists engine ([github](https://github.com/Distrotech/majordomo))

### Email filtering
- :hocho: [SpamAssassin](https://spamassassin.apache.org/) - Email spam filtering
- :email: [Amavis](https://amavis.org) - Email filter interface
- :mailbox_with_mail: [POP file](http://getpopfile.org) - Email filtering
- :no_entry: [ASSP](http://www.thockar.com/assp-home/) - Anti Spam

### Email
- :beer: [Cider Mail](http://ciderwebmail.org/news/index.html) - Webmail application
- :email: [Ashafix](https://github.com/mbethke/Ashafix) - Postfixadmin port in Perl

### Monitoring
- :chart_with_upwards_trend: [Munin](http://munin-monitoring.org/) - Supervision software (like Nagios and Shinken)
- :chart_with_downwards_trend: [Monitorix](https://github.com/mikaku/Monitorix) -  Lightweight system monitoring tool
- :bar_chart: [MRTG](https://oss.oetiker.ch/mrtg/) - Monitoring traffic load on network links
- :chart_with_downwards_trend: [Webmin](http://www.webmin.com/) - Web interface to administer Unix like machines
- :mag: [Open Smart](http://opensmart.sourceforge.net/) - Network and application monitoring
- :chart_with_downwards_trend: [Loggerithim](https://sourceforge.net/projects/loggerithim/) -  Monitoring and remote management package
- :bar_chart: [OPS View](https://www.opsview.com/) - Network and application monitoring
- :hourglass_flowing_sand: [Net Disco](http://netdisco.org/) - Network management tool
- :smoking: [Smoke Ping](https://oss.oetiker.ch/smokeping) - Monitor network latency
- :vhs: [Stormons](https://sourceforge.net/projects/stormons/) - Monitoring and mapping SAN storage devices.
- :chart_with_upwards_trend: [Proclet](https://github.com/kazeburo/Proclet) - Minimalist supervisor
- :battery: [Rainbarf](https://github.com/creaktive/rainbarf) - Fancy resource usage charts

### Logs analyzers
- :chart_with_upwards_trend: [AWStats](https://awstats.sourceforge.io) - Weberver logs analyzer ([github](https://github.com/eldy/awstats))
- :octopus: [Octopussy](https://octopussy.pm) - Log analyzer
- :chart_with_upwards_trend: [Squid](http://squidanalyzer.darold.net) - Log analyzer
- :chart_with_downwards_trend: [W3Perl](http://w3perl.com) - Log analyzer
- :bar_chart: [Yaala](http://www.yaala.org) - Log analyzer
- :chart_with_upwards_trend: [Log Watch](https://sourceforge.net/projects/logwatch) - Log analyzer
- :mag: [SEC](http://simple-evcorr.github.io) - Log analyzer
- :satellite: [Cricket](http://cricket.sourceforge.net) - Collect and print data series
- :chart_with_downwards_trend: [Torrus](http://torrus.org) - Collect and print data series

### Job queues
- :octopus: [Minion](https://github.com/mojolicious/minion) - A high performance job queue
- :construction_worker: [Gearman](http://gearman.org) - Job server
- :suspension_railway: [Qudo](https://github.com/nekokak/qudo) - Job queue manager
- :mountain_railway: [Resque](https://github.com/diegok/resque-perl) - Job queue manager
- :aerial_tramway: [TheSchwartz](https://github.com/akiym/TheSchwartz) - Job queue manager 

### Tickets trackers
- :bug: [Request Tracker](https://bestpractical.com/request-tracker) - Bug tracker ([github](https://github.com/bestpractical/rt))
- :honeybee: [OTRS](https://otrs.com) - Ticket tracker ([github](https://github.com/OTRS/otrs))
- :ant: [BugZilla](https://www.bugzilla.org) - Bug tracker ([github](https://github.com/bugzilla/bugzilla))

### Wiki
- :pencil2: [Oddmuse](https://oddmuse.org) - Wiki engine
- :pencil: [Ikiwiki](http://ikiwiki.info) - Wiki engine
- :memo: [TWiki](https://twiki.org) - Wiki engine
- :pencil2: [FosWiki](https://foswiki.org) - Wiki engine ([github](https://github.com/foswiki))

### E-Commerce
- :credit_card:  [Interchange](https://www.interchangecommerce.org/i/dev) - E-Commerce platform
- :moneybag: [Surf Shop](http://www.surfshopcart.com) - Shopping cart
- :money_with_wings: [Agora Cart](http://www.agoracart.com) - Shopping cart
- :phone: [Ledger SMB](https://ledgersmb.org) - ERP

### Backup tools
- :floppy_disk: [RSnapshot](https://github.com/rsnapshot/rsnapshot) -  Backup utility based on rsync
- :minidisc: [ABT](https://github.com/mguyard/another-backup-tool) - Another Backup tool
- :cd: [Backup PC](https://backuppc.github.io/backuppc) - Backup tool

### Games
- :new: [Tau Station](https://taustation.space/) - A text based web space game 
- :red_circle: [Frozen Bubble](https://fr.wikipedia.org/wiki/Frozen_Bubble) - Very famous game
- :video_game: [Lacuna Expanse](https://github.com/plainblack/Lacuna-Server-Open) - Space game
- :house: [Construder](https://github.com/elmex/Construder) - Minecraft-like game 

### Web application framework
- :cloud: [Mojolicious](https://mojolicious.org/) - Web framework created by [Sebastian Riedel](https://github.com/kraih) ([CPAN profile](https://metacpan.org/author/SRI)) 
- :dizzy: [Catalyst](http://www.catalystframework.org/) - Web framework
- :dancer: [Dancer](http://perldancer.org/) - Minimalist Web framework created by [Alexis Sukrieh](https://metacpan.org/author/SUKRIA) (see [Dancer 1](https://github.com/PerlDancer/Dancer) and [Dancer 2](https://github.com/PerlDancer/Dancer2))
- :crocodile: [Jifty](https://metacpan.org/pod/Jifty) - Web framework
- :cloud: [Cyclone 3](http://www.cyclone3.org/) - Web application framework
- :snake: [Amon](https://github.com/tokuhirom/Amon) - Web application framework
- :sheep: [Poet](https://github.com/jonswar/perl-poet) - Web application framework
- :elephant: [Gantry](https://metacpan.org/pod/Gantry) - Web application framework
- :bird: [Kossy](https://github.com/kazeburo/Kossy) - Simple web application framework
- :panda_face: [Squatting](https://github.com/beppu/squatting) - Web microframework
- :wolf: [Tatsumaki](https://github.com/miyagawa/Tatsumaki) - Non-blocking web framework based on Plack and AnyEvent
- :grapes: [Raison](https://github.com/khrt/Raisin) - REST API micro framework
- :whale2: [Maypole](https://metacpan.org/pod/Maypole) - MVC web application framework
- :dolphin: [Angelos](https://github.com/dann/angelos) - Web application framework
- :fish: [Web::Simple](http://git.shadowcat.co.uk/gitweb/gitweb.cgi?p=catagits/Web-Simple.git) - Simple web application framework
- :ram: [Ark](https://github.com/ark-framework/ark) - Lightweight Catalyst-ish web application framework
- :tiger: [Shenker](https://github.com/spiritloose/Schenker) - Web application framework
- :ox: [Noe](https://github.com/yusukebe/Noe) - Web application framework
- :leopard: [Kamui](https://github.com/nekokak/p5-Kamui) - Web application framework based on Plack
- :snail: [Web Nano](https://github.com/zby/WebNano) - Really minimalistic web framework. 

### PSGI adapters and web servers
- :pig: [Plack](https://github.com/plack/Plack) - PSGI toolkit and server adapter
- :boar: [HTTP::Server::Simple](https://github.com/bestpractical/http-server-simple) - Simple standalone HTTP daemon
- :tiger: [HTTP::Daemon](https://github.com/libwww-perl/HTTP-Daemon) - Simple http server class
- :rabbit: [HTTP::Tiny](https://github.com/chansen/p5-http-tiny) - Minimalist HTTP client
- :dog: [Continuity](https://metacpan.org/pod/Continuity) - Library to simplify web applications (including a web server)
- :mouse: [Starman](https://github.com/miyagawa/Starman) - High-performance preforking PSGI server
- :cat: [Twiggy](https://github.com/miyagawa/Twiggy) - AnyEvent HTTP server for PSGI
- :bear: [Starlet](https://github.com/kazuho/Starlet) - Simple and high-performance PSGI server
- :frog: [Corona](https://github.com/miyagawa/Corona) - Asynchronous PSGI server
- :racehorse: [Gazelle](https://github.com/kazeburo/Gazelle) - Preforked Plack handler for performance freaks
- :horse: [Arriba](https://github.com/odyniec/p5-Arriba) - PSGI server with [SPDY](https://en.wikipedia.org/wiki/SPDY) support
- :hamster: [Perlbal](https://github.com/perlbal/Perlbal) - HTTP load balancer
- :ox: [HTTP::Engine](https://github.com/http-engine/HTTP-Engine) - Web server
- :dog2: [Feersum](https://github.com/stash/Feersum) - PSGI engine based on EV/libev
- :japanese_ogre: [Server::Starter](https://github.com/kazuho/p5-Server-Starter) - Super Daemon to handle hot deployment of server programs

### Templating
- :wave: [Mason](https://github.com/jonswar/perl-mason) - Templating system
- :clap: [EmbPerl](https://metacpan.org/pod/Embperl) - Templating system
- :snake: [DTL::Fast](https://metacpan.org/pod/DTL::Fast) - Perl5 port of Django templating language ([:octocat:sources](https://github.com/hurricup/DTL-Fast))

### Compiler and alternative interpreters
- :wrench: [Compiler Perlito](https://github.com/fglock/Perlito) - Perl to Java and Perl to JavaScript
- :muscle: [RPerl](http://rperl.org/) - Restricted Perl, an optimizing compiler ([github](https://github.com/wbraswell/rperl))
- :wrench: [CPerl](https://github.com/perl11/cperl) - Alternative Perl interpreter
- :gift: [PAR:Packer](https://github.com/rschupp/PAR-Packer) - Generate standalone executables
- :hammer: [TinyPerl](http://tinyperl.sourceforge.net/) - Very compact Perl binary to be shipped with your scripts
- :money_with_wings: [StaticPerl](http://software.schmorp.de/pkg/App-Staticperl.html) - Helper script to create self contained statically linked Perl binary + script
- :wrench: [Compiler PerlC](http://marginalhacks.com/Hacks/perlc/) - Perl to C compiler
- :dromedary_camel: [Relocatable Perl](https://github.com/skaji/relocatable-perl) - Patched Perl binary to make it relocatable

### Assets management
- :cd: [FusionInventory](http://fusioninventory.org/) - IT assets web inventory
- :dvd: [OCS NG](https://ocsinventory-ng.org/) - IT assets web inventory
- :books: [Koha](https://en.wikipedia.org/wiki/Koha_(software)) - Integrated Library System ([gitweb](http://git.koha-community.org/gitweb/))
- :green_book: [Evergreen ILS](http://evergreen-ils.org) - Library management

### Git 
- :octocat: [GitWeb](https://github.com/git/git/blob/master/gitweb/gitweb.perl) - Web interface to git repositories (bundled with git)
- :octopus: [Gitolite](https://gitolite.com/gitolite/) - Git hosting ([github](https://github.com/sitaramc/gitolite))
- :turtle: [GitPrep](http://gitprep.yukikimoto.com/) - Portable github system ([github](https://github.com/yuki-kimoto/gitprep))

### Database tooling
- :minidisc: [MySQL Tuner](https://github.com/major/MySQLTuner-perl) - MySQL configuration and tuning
- :cd: [Sqitch](https://github.com/sqitchers/sqitch) - Database change management application
- :vhs: [ETL](https://sourceforge.net/projects/eplsiteetl) - Data migration helper
- :dvd: [QDepo](https://sourceforge.net/projects/tpda-qrt) - Graphical software to convert various DB data to various office formats

### IDE
- :computer: [Padre](http://padre.perlide.org/) - IDE ([github](https://github.com/PadreIDE/Padre)) for Windows/OSX/Linux :door: :apple: :penguin:
- :tv: [Open Perl IDE](https://sourceforge.net/projects/open-perl-ide/) - IDE for Windows :door:
- :camel: [Plugin for Intellij IDEA](https://plugins.jetbrains.com/plugin/7796-perl) - Perl5 support plugin compatible with any JetBrains IDE on Linux/Mac/Windows ([:octocat:sources](https://github.com/Camelcade/Perl5-IDEA))

### Continuous Integration
- :camel: [Crafty](https://github.com/vti/crafty) - Simple CI server
- :penguin: A part of [openSUSE Buid Service](https://build.opensuse.org/) ([github d'OBS build scripts](https://github.com/openSUSE/obs-build) and [OBS backend](https://github.com/openSUSE/open-build-service/tree/master/src/backend)) and other repositories on [openSUSE github](https://github.com/openSUSE) - The **Open Build Service** platform is an infrastructure to build packages for multiple package managers and distributions and architectures.
- :turtle: [App::Stew](https://github.com/vti/stew) - In-app package manager

### Desktop
- :movie_camera: **Shutter** - Screenshot utility
- :computer: [Ravada](https://github.com/UPC/ravada) - Remote Virtual Desktops Manager
- :feet: [Perl Executing Browser](https://github.com/ddmitov/perl-executing-browser) - HTML5 user interface for Perl 5 desktop applications
- :pencil2: [Kephra](http://kephra.sourceforge.net/site/en/home_news.shtml) - Editor
- :eggplant: [GUIDeFATE](https://github.com/saiftynet/GUIDeFATE) - Design GUI in ASCII art

### Tooling for devs
- :older_man: [GNU Automake](https://www.gnu.org/software/automake/) - Automatically generates Makefile.in files 
- :mag: [Cloc](https://github.com/AlDanial/cloc) - Count line of code 
- :wrench: [Devel::hdb](https://github.com/brummett/Devel-hdb) - Another Perl debugger
- :tada: [Diff So Fancy](https://github.com/so-fancy/diff-so-fancy) - The best-lookin' diffs
- :fire: [Flame Graphs](https://github.com/brendangregg/FlameGraph) - Profiled code visualization
- :rainbow: [Markdown](https://daringfireball.net/projects/markdown/) - Markdown was initially created by **John Gruber** and **Aaron Schwartz** and implemented in Perl
- :wrench: [Daiku](https://github.com/tokuhirom/Daiku) - Kind of make
- :1234: [PDL](http://pdl.perl.org/) - For scientific calculations
- :handbag: [Fink Project](http://finkproject.org/) - Tool to help porting software from UNIX like to macOS
- :arrows_counterclockwise: [Reply](https://github.com/doy/reply) - Perl REPL
- :heavy_dollar_sign: [Ack](https://beyondgrep.com) - Grep replacement

### Sysadmin
- :pill: [Pinto](https://github.com/thaljef/Pinto) - Create local CPAN repositories
- :cow: [Cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) - The cow that can speak
- :underage: [Web Sorrow](https://code.google.com/archive/p/web-sorrow) - Security scanner
- :family: [LemonLDAP::NG](https://www.lemonldap-ng.org/welcome/) - WebSSO, Access Management and Identity Federation
- :octopus: [Plain VM](https://github.com/mgechev/plainvm) - Controle multiple VMs
- :baggage_claim: [Urpmi](https://en.wikipedia.org/wiki/Urpmi) - Package manager

### Hosting
- :cloud: [cPanel](https://cpanel.net/) - Hosting platform
- :satellite: [Perloku](https://github.com/judofyr/perloku) - Deploy Perl apps on Heroku

### Uncategorized 
- :watermelon: [OpenFoodFacts](https://github.com/openfoodfacts/openfoodfacts-server) - Open database about food
- :nut_and_bolt: [EPrints](https://www.eprints.org) - Software to build Open Access repositories ([github](https://github.com/eprints/eprints))
- :mag: [Dezi](https://dezi.org) - Search platform
- :octocat: [PRC](https://github.com/kyzn/PRC) - Linking maintainers with contributors
- :jp: [LANraragi](https://github.com/Difegue/LANraragi) - Web application for reading manga
- :gun: [Nipe](https://github.com/GouveaHeitor/nipe) - Script to make Tor network your default gateway

### Other Perl lists
- :octocat: [Another Repository List](https://github.com/kaxap/arl/blob/master/README-Perl.md) - List of popular git repositories
- :cocktail: [A Perl Products List](https://perlmaven.com/perl-based-open-source-products) - Perl products according to Perl Maven (a lot of them are already in the list above)
- :rocket: [Awesome Perl](https://github.com/hachiojipm/awesome-perl/blob/master/README.md) - Curated list of awesome Perl stuff
- :purple_heart: [Awesome Perl (again)](https://github.com/uhub/awesome-perl) - Another curated list of awesome Perl stuff
- :pill: [CPAN in a nutshell](https://github.com/eserte/srezic-misc/blob/master/cpan_in_a_nutshell/cpan_in_a_nutshell.pod) - List of Perl modules

## :ghost: Execute Perl online
- :new: [Perl Banjo](https://perlbanjo.com/) - Share runnable Perl code :heart: :muscle:
- :doughnut: [Web Perl](https://webperl.zero-g.net/) - WebAssembly + Emscripten ([demo](https://webperl.zero-g.net/democode/index.html) and [source](https://github.com/haukex/webperl))
- :candy: [TIO](https://tio.run/#perl5) - Try It Online
- :cake: [Perlbot](https://perl.bot/) - Run and share Perl code

## :boom: Execute Perl online (sites not dedicated to Perl)
- :banana: [Tutorial Points](https://www.tutorialspoint.com/execute_perl_online.php)
- :corn: [Rextester](https://rextester.com/l/perl_online_compiler)
- :cookie: [JDoodle](https://www.jdoodle.com/execute-perl-online)
- :icecream: [Paiza](https://paiza.io/en/projects/new?language=perl)
- :melon: [Coding Ground](http://www.compileonline.com/execute_perl_online.php)
- :hamburger: [JS.do](https://js.do/perl/)

## :bear: Lint Perl online
- :heavy_check_mark: [Kritika.io](https://kritika.io/) - Static code analyzer
- :zap: [PerlCritic](http://perlcritic.com) - Web frontend to [Perl::Critic](https://github.com/Perl-Critic/Perl-Critic)

## :books: Books 
- :books: [Some books](https://perldoc.pl/perlbook.html) and [some others](https://learn.perl.org/books/) 

![](https://i.imgur.com/Z3F34XQ.jpg)

- :closed_book: [Programming Perl](https://en.wikipedia.org/wiki/Programming_Perl) (Camel book)
- :green_book: [Perl cookbook](https://en.wikipedia.org/wiki/Perl_Cookbook) (Ram book)
- :blue_book: [Learning Perl](https://en.wikipedia.org/wiki/Learning_Perl)  (Llama book)
- :orange_book: [Intermediate Perl](https://en.wikipedia.org/wiki/Intermediate_Perl) (Alpaca book)
- :notebook: [Mastering Perl](http://shop.oreilly.com/product/9780596527242.do)
- :notebook_with_decorative_cover: [Modern Perl](http://modernperlbooks.com/)
- :ledger: [Perl Best Practices](https://en.wikipedia.org/wiki/Perl_Best_Practices)
- :orange_book: [Perl hacks](http://shop.oreilly.com/product/9780596526740.do)
- :green_book: [High Order Perl](https://en.wikipedia.org/wiki/Higher-Order_Perl)
- :blue_book: [Beginning Perl](http://shop.oreilly.com/product/9781118013847.do) (Curtis "Ovid" Poe)
- :green_book: Beginning Perl (Simon Cozens) - Free [E-Book](https://www.perl.org/books/beginning-perl/)
- :closed_book: Beginning Perl (James D Lee)
- :notebook: [Perl pocket reference](http://shop.oreilly.com/product/0636920018476.do)
- :construction: [A practical guide to testing](https://leanpub.com/perl-testing)
- :orange_book: XML and Perl
- :green_book: [Perl and XML](http://shop.oreilly.com/product/9780596002053.do)
- :blue_book: Perl for system administration
- :green_book: Programming the perl DBI
- :notebook: CGI programming with Perl
- :closed_book: Perl & LWP
- :orange_book: [Perl graphics Programming](http://shop.oreilly.com/product/9780596002190.do)
- :blue_book: Perl for dummies
- :notebook: [Mastering algorithms with Perl](http://shop.oreilly.com/product/9781565923980.do)
- :orange_book: Impatient Perl
- :closed_book: Extreme Perl
- :blue_book: [Web, Graphics & Perl/Tk Programming](http://shop.oreilly.com/product/9780596003111.do)
- :closed_book: [Games, Diversions and Perl Culture](http://shop.oreilly.com/product/9780596003128.do)
- :green_book: Perl Template Toolkit
- :notebook_with_decorative_cover: Web Services avec Perl
- :orange_book: [Perl for Oracle DBAs](http://shop.oreilly.com/product/9780596002107.do)
- :blue_book: [Advanced Perl Programming](http://shop.oreilly.com/product/9780596004569.do)
- :notebook: Perl Testing
- :closed_book: Practical vim
- :blue_book: Perl one liners
- :closed_book: Practical mod_perl
- :green_book: Mod_perl pocket reference
- :blue_book: Mod_perl 2 user guide
- :notebook: Object Oriented Perl
- :closed_book: Perl in a nutshell
- :green_book: Perl testing a developer notebook
- :blue_book: Beginning Perl for bioinformatics
- :closed_book: [Mastering Perl for Bioinformatics](http://shop.oreilly.com/product/9781565923140.do)
- :notebook: Network programming with Perl
- :orange_book: Perl by example
- :notebook_with_decorative_cover: Perl black book
- :ledger: Extending and embedding Perl
- :blue_book: Mod_perl developer cookbooks
- :blue_book: Effective Perl programming
- :orange_book: Perl core language little black book
- :green_book: Writing apache modules with Perl and C
- :blue_book: Running weblogs with Slash
- :orange_book: Core Perl
- :closed_book: Perl for the Web
- :notebook: [Data Munging with Perl](https://datamungingwithperl.com/)
- :notebook_with_decorative_cover: [MySQL and Perl for the Web](http://www.kitebird.com/mysql-perl/)
- :notebook: [Open Source Web Development with LAMP](http://www.opensourcewebbook.com/)
- :green_book: [Learning Perl/Tk](http://shop.oreilly.com/product/9781565923140.do)
- :blue_book: [Mastering Perl/Tk](http://shop.oreilly.com/product/9781565927162.do)
- :orange_book: [Perl/Tk Pocket Reference](http://shop.oreilly.com/product/9781565925175.do)
- :notebook: Pro Perl debugging
- :closed_book: Regular Expression Pocket Reference
- :orange_book: Perl Debugger Pocket Reference
- :notebook_with_decorative_cover: Writing CGI applications with Perl
- :blue_book: Automating System administration with Perl
- :green_book: Minimal Perl
- :closed_book: Embedding Perl in HML web MASON
- :orange_book: Perl for website management
- :notebook: Picking up Perl
- :notebook_with_decorative_cover: Real World SQL Server Administration with Perl
- :blue_book: Perl 5 internals
- :notebook: Practical text mining with perl
- :orange_book: Beginning perl web development 
- :blue_book: Programming for linguist Perl for language researchers
- :notebook: Perl for C programmers
- :orange_book: Effective Perl programming
- :blue_book: Learning Perl the hard way
- :notebook: Perl the programmer's companion
- :green_book: Programming with Perl modules
- :green_book: Beginning Perl Web development from novice to professional
- :orange_book: [Single Page Application with Perl Dancer](https://leanpub.com/dancer-spa/) - E-Book about Dancer webframework
- :construction: [Mojolicious book](https://metacpan.org/pod/release/KRAIH/Mojo-0.999904/lib/Mojolicious/Book.pod)
- :closed_book: [Perl Golf History](http://terje2.frox25.no-ip.org/perlgolf_history_070109.pdf) - E-Book about coding competition 
- :notebook_with_decorative_cover: [Testing Strategies for Modern Perl](http://www.theperlshop.com/in/testing-modern-perl)
- :notebook: [A practical guide to testing in modern Perl](https://leanpub.com/perl-testing)
- :orange_book: RT Essentials
- :blue_book: Automating Windows with Perl
- :closed_book: Perl Developer's Dictionary
- :orange_book: Instant CGI/Perl
- :notebook_with_decorative_cover: Web Programming with Perl 5
- :blue_book: Official Guide to Programming with CGI.pm
- :notebook: CGI Developer's Resource: Web programming in Tcl and Perl
- :blue_book: Cross Platform Perl
- :closed_book: Developing CGI Applications with Perl
- :blue_book: Perl 5 Interactive Course
- :orange_book: Teach Yourself CGI Programming with Perl 5 in a week
- :green_book: Penetration Testing with Perl
- :closed_book: Hands-On Penetration Testing with Python
- :orange_book: Perl Scripting for Windows Security
- :green_book: Perl and Apache: Your visual blueprint for developing dynamic Web content
- :notebook: Developing Web Applications with Perl, memcached, MySQL and Apache
- :orange_book: Minimal Perl: For UNIX and Linux People
- :blue_book: Building Tag Clouds in Perl and PHP
- :green_book: Wicked Cool Perl Scripts
- :notebook: Pro Perl
- :orange_book: Perl Medic: Transforming Legacy Code
- :green_book: Computer Science & Perl Programming
- :orange_book: Programming PERL in the .NET Environment
- :notebook: Teach Yourself Perl in 21 Days
- :orange_book: Teach Yourself Perl in 24 Hours
- :green_book: Perl Debugged
- :orange_book: Programming Web Graphics with Perl and GNU Software
- :notebook: Web Client Programming with Perl
- :orange_book: Learning Perl on Win32 Systems
- :green_book: Win32 Perl Programming: The Standard Extensions, Second Edition
- :blue_book: Welcome to Perl Country :jp:
- :notebook: How to Write Perl :jp:
- :orange_book: Introduction to Perl :jp:
- :green_book: Philippe Banquet, Les fondamentaux du langage Perl 5 : Apprentissage par la pratique :fr:
- :blue_book: Perl moderne :fr:
- :notebook: Perl reference de poche :fr:
- :notebook_with_decorative_cover: Perl en action :fr:
- :blue_book: Introductions a Perl/Tk: Interfaces graphiques avec Perl :fr: 

# :rocket: Develop with Perl
## :arrow_down: Install CPAN modules
The **modern way** consists to use [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm) (cpanminus). The tool is able to get the requested module and resolve dependencies. For instance, to install the excellent module [XML::LibXML](https://metacpan.org/pod/XML::LibXML) from [Shlomif](https://github.com/shlomif) which is a wrapper of [libxml2](http://www.xmlsoft.org/), we can do ``sudo cpanm XML::LibXML``, that produces the following output (truncated) :
    
```bash
--> Working on XML::LibXML
Fetching http://www.cpan.org/authors/id/S/SH/SHLOMIF/XML-LibXML-2.0201.tar.gz ... OK
==> Found dependencies: Alien::Libxml2
--> Working on Alien::Libxml2
Fetching http://www.cpan.org/authors/id/P/PL/PLICEASE/Alien-Libxml2-0.09.tar.gz ... OK
[...]
Building and testing Alien-Libxml2-0.09 ... OK
Successfully installed Alien-Libxml2-0.09
Configuring XML-LibXML-2.0201 ... OK
Building and testing XML-LibXML-2.0201 ... OK
Successfully installed XML-LibXML-2.0201 (upgraded from 2.0128)
13 distributions installed
```

Reinstalling a set of CPAN modules can be done simply by launching a bunch of `cpanm` commands or by specifying dependencies in a [cpanfile](https://metacpan.org/pod/cpanfile) (and using then [carton](https://metacpan.org/pod/Carton) or `cpanm --installdeps .` for the setup).

## :heavy_check_mark: Linters
Executable by hand or directly integrated in your scripts, IDE or editors (vim users : [ale](https://github.com/w0rp/ale/) or [syntastic](https://github.com/vim-syntastic/syntastic)).

- [`perl -c`](https://perldoc.pl/perlrun.html), to check the syntax. Be careful that it does more than only checking syntax, it actually _executes_ the blocks `BEGIN` and `END` (compilation step). This _design_ is [the reason why](https://github.com/w0rp/ale/issues/1186) the default _linter_ used by the plugin [vim ale](https://github.com/w0rp/ale) is no longer `perl -c` (nor even `perl -w`). 
The syntax checking in Perl is great (as well as the error messages from the interpreter... I :heart: Perl)

- [Perl::Critic](https://metacpan.org/pod/Perl::Critic), that *criticize*  your coding style but do not check syntax. For instance, the file `bad.pl` contains :
    
```perl
use strict;
print "toto" }{
```

And `perl -c bad.pl` prints :
    
```
Unmatched right curly bracket at bad.pl line 3, at end of line
syntax error at bad.pl line 3, near ""toto" }"
Missing right curly or square bracket at bad.pl line 3, at end of line
bad.pl had compilation errors.
```
    
But `perlcritic bad.pl` tells us that eveything is fine `bad.pl source OK` (but is not happy with the missing  `use strict`).

- A module that was part of the core distribution of Perl but was finally removed in Perl **5.19** : [B::Lint](https://metacpan.org/pod/B::Lint).
While we are here, how to know the history of a module in the core distribution ? Use **corelist** ! `corelist B::Lint` that gives us : 
    
```
Data for 2017-09-22
B::Lint was first released with perl 5.005, deprecated (will be CPAN-only) in v5.17.9 and removed from v5.19.0
```
    
If a module goes out of core distribution it's not dramatic as it continues to be available in CPAN of course.

- And [Perl::Lint](https://metacpan.org/pod/Perl::Lint) that focus on speed while being compatible with **Perl::Critic**.

## :hammer_and_pick: How to compile perl
See [how to compile perl](https://www.cpan.org/src/) 

Actually it will give this :
    
```bash
wget https://www.cpan.org/src/5.0/perl-5.30.0.tar.gz
tar -xzf perl-5.30.0.tar.gz
cd perl-5.30.0
./Configure -des -Dprefix=$HOME/localperl
make
make test
make install
```

## :pill: Compile modules
If we decide to use or not a module like [cpanm](https://metacpan.org/pod/distribution/App-cpanminus/bin/cpanm), at the end the module is compiled using [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) or [Module::Build](https://metacpan.org/pod/Module::Build). [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) is a _core module_, while [Module::Build](https://metacpan.org/pod/Module::Build) was added then removed (**5.9 → 5.19**). **David Golden** explains in a blog post why [he requested to remove Module::Build](https://xdg.me/blog/paying-respect-to-modulebuild/).

### ExtUtils::MakeMaker
The module [ExtUtils::MakeMaker](https://metacpan.org/pod/ExtUtils::MakeMaker) generate a **Makefile** from `Makefile.PL` :
    
``` bash
perl Makefile.PL
make
make install
```

### Module::Build
The module [Module::Build](https://metacpan.org/pod/Module::Build) serves the same goal but generates a file **Build** from the file `BUILD.PL` :
    
```
perl Build.PL
./Build
./Build test
./Build install
```

# :headphones: How to contribute ?

Please read [CONTRIBUTING.md](CONTRIBUTING.md)
