Clojure-Resources
=================

This is a compilation of links and resources for learning about **Clojure**, **ClojureScript**, **Om** and more broadly, **LISP**. It is still in very early stages. Please feel free to add resources by issuing a pull request (preferred) or by getting in touch. Please also don't hesitate to suggest a better sort order.

## Clojure
* **[Clojure Homepage](http://clojure.org)**
* **[Clojure Google Group](https://groups.google.com/forum/#!forum/clojure)**
* **[Clojure Cheat Sheet](http://grimoire.arrdem.com/)**
* **[Inspecting the content of channels in core.async](http://tgk.github.io/2013/10/inspect-core-async-channels.html)**
* **[Clojure Copter - Control for the AR Parrot Drone](https://github.com/gigasquid/clj-drone)**
* **[Clojure Users - Linkedin Group](https://www.linkedin.com/groups?home=&gid=1058217)**
* **[Clojure compilation](http://clojure.org/compilation)**: helped me learn more about ahead-of-time compilation (AOT).
* **[xsc/pandect on GitHub](https://github.com/xsc/pandect)**: Fast and easy-to-use Message Digest, Checksum and HMAC library. I use it in the Clojure version of my **[BirdWatch](https://github.com/matthiasn/BirdWatch)** project & it works like a charm.
* **[Clojure Documentation](http://clojure-doc.org)**: community-driven documentation project
* **[Clojure for the Brave and True - Writing Macros](http://www.braveclojure.com/writing-macros/)**: before this article, I did not know that there was a connection between hair growth potion and macros. Well, I still don't know that. But entertaining nonetheless. And I now understand macros.
* **[Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)**: an introduction to core Clojure concepts 
* [**Clojure Gazette**](http://www.clojuregazette.com): Weekly Newsletter to inspire Clojure programmers.
* **[SICP distilled](https://www.kickstarter.com/projects/1751759988/sicp-distilled)**: Kickstarter project aimed at translating **SICP** (see in the last section) into Clojure. This looks really cool, you should go fund it while you still can. I have done the same.
* **[Clojurecademy](https://clojurecademy.com)**: Learning Clojure Interactively(Hands-On).

## Clojure libraries
* **[clj-time/clj-time on GitHub](https://github.com/clj-time/clj-time)**: wrapper for Joda Time
* **[clojure/data.priority-map on GitHub](https://github.com/clojure/data.priority-map)**: implementation of a priority map in Clojure. Useful when you want a sorted map that is sorted based on the values, not the keys.
* **[damballa/parkour on GitHub](https://github.com/damballa/parkour)**: Hadoop MapReduce in idiomatic Clojure.
* **[Monger, a Clojure client for MongoDB](http://clojuremongodb.info/articles/getting_started.html)**
* **[Overtone](https://github.com/overtone/overtone)**: make music from your REPL
* **[Live Coding. Live Synths. Live Music.](http://meta-ex.com)**: music made with Clojure and Overtone
* **[The Clojure Toolbox](http://www.clojure-toolbox.com)**: a categorised directory of libraries and tools for Clojure
* **[aengelberg/loco on GitHub](https://github.com/aengelberg/loco)**: A Constraint Programming library for Clojure. I can see how this can be useful in an application.
* **[clojure/core.typed](https://github.com/clojure/core.typed)**: An optional type system for Clojure
* **[ckirkendall/fresnel](https://github.com/ckirkendall/fresnel)**: A library for composing lenses and working with complex state objects
* **[MichaelDrogalis/dire on GitHub](https://github.com/MichaelDrogalis/dire)**: Erlang-style supervisor error handling for Clojure. I have not tried it yet, but it does look like an interesting concept, particularly after having worked with supervisors within the actor model for a while. Has anyone used this in a real application?
* **[prismatic/schema on GitHub](https://github.com/Prismatic/schema)**: Clojure(Script) library for declarative data description and validation
* **[22rbrush/clara-rules on GitHub](https://github.com/rbrush/clara-rules)**: Forward-chaining rules in Clojure
* **[ptaoussanis/carmine on GitHub](https://github.com/ptaoussanis/carmine)**: Clojure Redis client & message queue
* **[killme2008/defun on GitHub](https://github.com/killme2008/defun)**: A macro to define clojure functions with parameter pattern matching just like erlang or elixir. Looks useful.
* **[AvisoNovate/rook on GitHub](https://github.com/AvisoNovate/rook)**: Sane, smart, fast, Clojure web services
* **[sjl/metrics-clojure on GitHub](https://github.com/sjl/metrics-clojure)**: A thin façade around Coda Hale's metrics library.
* **[dakrone/clj-http on GitHub](https://github.com/dakrone/clj-http)**: An idiomatic clojure http client wrapping the apache client.
* **[http-kit/http-kit on GitHub](https://github.com/http-kit/http-kit)**: http-kit is a minimalist, event-driven, high-performance Clojure HTTP server/client library with WebSocket and asynchronous support
* **[greglook/puget on GitHub](https://github.com/greglook/puget)**: Canonical Colorizing Clojure Printer
* **[funcool/buddy on GitHub](https://github.com/funcool/buddy)**: Security library for Clojure
* **[mpenet/jet on GitHub](https://github.com/mpenet/jet)**: Jetty9 ring server adapter with WebSocket support via core.async and Jetty9 based HTTP & WebSocket clients (jvm based, no cljs)
* **[raines/fs on GitHub](https://github.com/Raynes/fs)**: useful library for manipulating files and working with the filesystem
* **[clj.qrgen on GitHub](https://github.com/killme2008/clj.qrgen)**: generate QR code, for example for serving code as PNG file in ring handler
* **[eggsyntax/datawalk on GitHub](https://github.com/eggsyntax/datawalk)**: Interactively explore complex data structures at the REPL with minimum keystrokes

## Learn the language
* **[Clojure from the ground up](http://aphyr.com/tags/Clojure-from-the-ground-up)**: very encouraging series of articles for beginners. I also really appreciate the introduction.
* **[Clojure for the Brave and True (a Book for Beginners)](http://www.braveclojure.com)**: great intro, I particularly enjoyed the introduction to Emacs in conjunction with Clojure
* **[Introduction to Clojure](http://clojure-doc.org/articles/tutorials/introduction.html)**: short introduction to the Clojure basics. With this, it should be possible to learn the language itself on a rainy afternoon.
* **[Clojure.core: Batteries (almost) included - Adam Bard (06/2013)](http://adambard.com/blog/clojure-batteries-included/)**:  a guided tour through some of the many libraries available from the Clojure team that don't come distributed with Clojure. 
* **[bbatsov/clojure-style-guide on GitHub](https://github.com/bbatsov/clojure-style-guide)**: A community coding style guide for the Clojure programming language
* **[Library Coding Standards (last edit 04/2014)](http://dev.clojure.org/display/community/Library+Coding+Standards)**: coding standards on http://dev.clojure.org
* **[clojure-cookbook/clojure-cookbook on GitHub](https://github.com/clojure-cookbook/clojure-cookbook)**: This is the home of O'Reilly's Clojure Cookbook

## ClojureScript
* **[clojure/clojurescript - GitHub](https://github.com/clojure/clojurescript)**
* **[ClojureScript Google Group](https://groups.google.com/forum/#!forum/clojurescript)**
* **[ClojureScript-in-ClojureScript REPL](http://clojurescript.net)**
* **[ClojureScript One](http://clojurescriptone.com)**
* **[Translations from JavaScript](http://www.polymer-project.org)**: plenty of JavaScript code snippets and their translation to ClojureScript
* **[Calling javascript functions from clojurescript](http://odyssomay.github.io/2011/10/10/calling-javascript-functions-from-clojurescript.html)**
* **[Specljs and ClojureScript](http://speclj.com/specljs)**
* **[tailrecursion/cljs-priority-map on GitHub](https://github.com/tailrecursion/cljs-priority-map)**: ClojureScript port of clojure/data.priority-map
* **[mfikes/goby - GitHub](https://github.com/mfikes/goby)**: Develop iOS apps with ClojureScript
* **[swannodette/mies - GitHub](https://github.com/swannodette/mies)**: Minimal ClojureScript project template
* **[ClojureScript: JavaScript Interop - 09/2014](http://www.spacjer.com/blog/2014/09/12/clojurescript-javascript-interop/)**: Blog post about interacting with JavaScript
* **[andrewmcveigh/cljs-time - GitHub](https://github.com/andrewmcveigh/cljs-time)**: A clj-time inspired date library for clojurescript
* **[shaunlebron/ClojureScript-Syntax-in-15-minutes on GitHub](https://github.com/shaunlebron/ClojureScript-Syntax-in-15-minutes)**: cljs syntax is simple
* **[bensu/doo on GitHub](https://github.com/bensu/doo)**: finally a pleasant experience for running tests on the JavaScript side

## ClojureScript libraries
* **[lbradstreet/cljs-uuid-utils - GitHub](https://github.com/lbradstreet/cljs-uuid-utils)**: Micro lib with ClojureScript implementation of a random, type 4 UUID generator compatible with cljs.core/UUID
* **[yogthos/markdown-clj on GitHub](https://github.com/yogthos/markdown-clj)**: library for rendering markdown into HTML

## Structuring an application
* **[Organizing Your Project: a Librarian's Tale](http://www.braveclojure.com/organization/)**: useful chapter from the **[Clojure for the Brave and True](http://www.braveclojure.com/)** book about code organization and namespaces. It's a little long but it still covers the topic well enough.
* **[stuartsierra/component on GitHub](https://github.com/stuartsierra/component)**: okay, so this one had been on my list for a while. Started watching Stuart's video a few times. Now I finally got around to using it. And all I can say is you really have to take a closer look at this. It makes structuring a larger application so much more straightforward. And the earlier you do, the more pain you save later. Rewriting an existing application is doable, but somewhat painful.
* **[danielsz/system on GitHub](https://github.com/danielsz/system)**: set of readymade components on top of the component library above.
* **[palletops/leaven on GitHub](https://github.com/palletops/leaven)**: lightweight component model for both Clojure and ClojureScript.
* **[palletops/bakery on GitHub](https://github.com/palletops/bakery)**: A library of components for leaven, the component library above.
* **[MichaelDrogalis/onyx on GitHub](https://github.com/MichaelDrogalis/onyx)**: Distributed, fault tolerant data processing for Clojure. It does sound like an interesting and very ambitious concept for building distributed applications. On my list of things to maybe try at some point.
* **[Building a System in Clojure](https://leanpub.com/building-a-system-in-clojure)**: book by the maintainer of this repository about structuring complex applications.
 
## Web development / Om
* **[Keechma](https://keechma.com/)**: a pluggable micro framework for Reagent
* **[weavejester/compojure on GitHub](https://github.com/weavejester/compojure)**: a truly concise routing library for Clojure web applications.
* **[Luminus](http://www.luminusweb.net/)**: a Clojure micro-framework in style of Flask/Sinatra
* **[swannodette/om - GitHub](https://github.com/swannodette/om)**: a **ClojureScript** library on top of Facebook's **[React library](http://facebook.github.io/react/)**. React and ClojureScript are a great match as React is particularly well suited for rendering **immutable** data structures.
* **[A slice of React, Clojurescript and Om](http://www.lexicallyscoped.com/2013/12/25/slice-of-reactjs-and-cljs.html)**: article rewriting some React samples using **Om**
* **[Om: Enhancing Facebook's React with Immutability](http://www.infoq.com/news/2014/01/om-react)**
* **[Reagent](https://github.com/reagent-project/reagent-core)**: alternative ClojureSCript React wrapper
* **[ptaoussanis/sente on GitHub](https://github.com/ptaoussanis/sente)**: powerful library for connecting a Clojure server application and a ClojureScript client side application via the WebSockets protocol. I'm using this successfully in my **[BirdWatch](https://github.com/matthiasn/birdwatch/)** project.
* **[Compojure apps, in the style of Sinatra - Adam Bard, 09/2014](http://adambard.com/blog/sinatra-docs-in-clojure/)**: excellent introduction to Compojure, inspired by Sinatra's getting started guide.
* **[noprompt/garden on GitHub](https://github.com/noprompt/garden)**: Generate CSS with Clojure

## core.async
* **[clojure/core.async on GitHub](https://github.com/clojure/core.async/)**
* **[Implementation details of core.async Channels - Rich Hickey (07/2014)](https://vimeo.com/100518968)**
* **[Slides for the talk above](http://cdn.cognitect.com/presentations/2014/insidechannels.pdf)**
* **[Clojure core.async API Reference](https://clojure.github.io/core.async/)**: descriptions oftentimes too short to fully understand how to use the constructs in my opinion, but at least a starting point
* **[Combining & Controlling Channels with core.async's merge and mix](http://yobriefca.se/blog/2014/06/01/combining-and-controlling-channels-with-core-dot-asyncs-merge-and-mix/)**
* **[Mastering Time with Clojure core.async](http://sssslide.com/speakerdeck.com/hlship/mastering-time-with-clojure-core-dot-async)**
* **[core.async and Blocking IO](http://martintrojer.github.io/clojure/2013/07/07/coreasync-and-blocking-io/)**: article discussing blocking IO and how to deal with it and why non-blocking is preferable. Great, concise read.
* **[Code Read of core.async Timeouts](http://hueypetersen.com/posts/2013/07/10/code-read-of-core-async-timeouts/)**
* **[Publish and Subscribe with core.async's pub and sub](http://yobriefca.se/blog/2014/06/04/publish-and-subscribe-with-core-dot-asyncs-pub-and-sub/)**: useful and well-written introduction to the topic of Publish-Subscribe. I like the idea of a channel-driven **[Rube Goldberg machine](https://en.wikipedia.org/wiki/Rube_Goldberg_machine)**. Can we have crazy animations with that as well?

## Transducers
* **[Inside Transducers - Rich Hickey (11/2014)](https://www.youtube.com/watch?v=4KqUvG8HPYo)**: A talk about transducers and core.async.
* **[Transducers - Rich Hickey (09/2014)](https://www.youtube.com/watch?v=6mTbuzafcII)**: Rich Hickey talks about **Transducers**. Excellent talk as usual, must see.
* **[TRANSDUCERS ARE COMING - Rich Hickey (08/2014)](http://blog.cognitect.com/blog/2014/8/6/transducers-are-coming)**: Introduction of the concept by Rich Hickey himself
* **[Green Eggs and Transducers - Carin Meier (09/2014)](http://gigasquidsoftware.com/blog/2014/09/06/green-eggs-and-transducers/)**: A quick tour of Clojure Transducers with core.async with Dr. Seuss as a guide.
* **[Understanding Transducers - Elben Shira (09/2014)](http://elbenshira.com/blog/understanding-transducers/)**: "This article explores transducers by ignoring transducers. Instead we will examine two ordinary functions, map and filter. We'll play with them and scrutinize them." 
* **[richhickey/transducerfun.clj on GitHub](https://gist.github.com/richhickey/b5aefa622180681e1c81)**: Gist with some code
* **[ptaoussanis / transducers.clj - GitHub Gist](https://gist.github.com/ptaoussanis/e537bd8ffdc943bbbce7)**: well-documented code snippet

## Tooling
* **[Leiningen](http://leiningen.org)**: for automating Clojure projects without setting your hair on fire (from the project website). Hard to imagine using Clojure without it.
* **[Signing and Promoting your Clojure libraries on Clojars (03/2013)](http://thornydev.blogspot.de/2013/03/signing-and-promoting-your-clojure.html)**: helpful guide for signing Clojars artifacts
* **[How Clojure Babies are Made: What Leiningen Is](http://www.flyingmachinestudios.com/programming/how-clojure-babies-are-made-what-leiningen-is/)**: fun read, helps understand what Leiningen really is
* **[How Clojure Babies Are Made: Understanding lein run](http://www.flyingmachinestudios.com/programming/how-clojure-babies-are-made-lein-run/)**: this article helps you understand how gruesome a place the world would be without Leiningen
* **[overtone/emacs-live - GitHub](https://github.com/overtone/emacs-live)**
* **[clojure-emacs/cider - GitHub](https://github.com/clojure-emacs/cider)**
* **[Clojure with Emacs](http://clojure-doc.org/articles/tutorials/emacs.html)**
* **[LightTable](http://www.lighttable.com)**: IDE for Clojure and ClojureScript. Great for people who (still) struggle with Emacs.
* **[Riemann](http://riemann.io)**: Riemann monitors distributed systems. Looks really useful for understanding systems under load.
* **[lein-difftest on GitHub](https://github.com/brentonashworth/lein-difftest)**: plugin for pretty test output (like green for success). Hasn't been worked on since 2012, but still working.
* **[lein-quickie on GitHub](https://github.com/jakepearson/quickie)**: plugin for leiningen that automatically re-runs your tests when it detects file system changes. Works as expected.
* **[dsabanin/clj-pid on GitHub](https://github.com/dsabanin/clj-pid)**: Tiny Clojure library to get current process ID and save/read PID files. Useful when deploying an uberjar.
* **[A Pretty Printer for Clojure](https://clojure.github.io/clojure/doc/clojure/pprint/PrettyPrinting.html)**: always useful when trying to read Clojure's datastructures as a human being.
* **[Dockerizing a Clojure Application - Ryan Neufeld (09/2014)](http://www.rkn.io/2014/09/13/clojure-docker/)**: something I've been wanting to do for a while.
* **[jonase/kibit on GitHub](https://github.com/jonase/kibit)**: There's a function for that! Static code analyzer for Clojure.
* **[kovasb/session on GitHub](https://github.com/kovasb/session)**: clojure-based live-coding environment
* **[jonase/eastwood on GitHub](https://github.com/jonase/eastwood)**: a Clojure lint tool
* **[AvisoNovate/pretty on GitHub](https://github.com/AvisoNovate/pretty/)**: Library for helping print things prettily, in Clojure - ANSI fonts, formatted exceptions
* **[JonyEpsilon/gorilla-repl on GitHub](https://github.com/JonyEpsilon/gorilla-repl)**: A rich REPL for Clojure in the notebook style. <http://gorilla-repl.org>
* **[dakrone/lein-bikeshed on GitHub](https://github.com/dakrone/lein-bikeshed): A Leiningen plugin designed to tell you your code is bad, and that you should feel bad

## Distributed computing
* **[Avout](https://github.com/liebke/avout)**: Distributed State in Clojure, provides a distributed implementation of **[Clojure's Software Transactional Memory (STM)](http://clojure.org/refs)**

## Data analysis
* **[Incanter](https://github.com/incanter/incanter)**: Clojure-based, **R-like statistical computing and graphics environment** for the JVM

## Blog posts
* **[Planet Clojure](http://planet.clojure.in)**: Planet Clojure is a meta blog that collects posts from the blogs of various Clojure hackers and contributors.
* **[Do Things: a Clojure Language Crash Course](http://www.braveclojure.com/do-things/)**
* **[Relevance Blog](http://thinkrelevance.com/blog)**
* **[My Clojure Workflow, Reloaded - Stuart Sierra](http://thinkrelevance.com/blog/2013/06/04/clojure-workflow-reloaded)**
* **[A Closer Look at Transit](http://swannodette.github.io/2014/07/23/a-closer-look-at-transit/)**
* **[WHY I'M PRODUCTIVE IN CLOJURE](http://yogthos.net/#/blog/49-Why+I'm+Productive+in+Clojure)**
* **[Ten reasons to use Clojure/ClojureScript on your next web dev project - Adam Bard](http://adambard.com/blog/ten-reasons-to-use-clojure/)**
* **[Learn X in Y minutes Where X=clojure](http://learnxinyminutes.com/docs/clojure/)**
* **[A simple Clojurescript app - Adam Bard](http://adambard.com/blog/a-simple-clojurescript-app/)**
* **[Distributed Communicating Sequential Processes (CSP) - David Pollak](http://blog.goodstuff.im/intro_dragonmark)**
* **[Inspecting the content of channels in core.async](http://tgk.github.io/2013/10/inspect-core-async-channels.html)**
* **[Why Clojure will win](http://michaelochurch.wordpress.com/2013/08/07/why-clojure-will-win/)**
* **[Building Clojure Services at Scale](http://blog.josephwilk.net/clojure/building-clojure-services-at-scale.html)**
* **[Appointment scheduling in Clojure with Loco](http://programming-puzzler.blogspot.de/2014/03/appointment-scheduling-in-clojure-with.html)**: introduction to contraints programming with Loco (above in the libraries section) using scheduling as an example.
* **[My Top Clojure Articles - Adam Bard (07/2014)](http://adambard.com/blog/greatest-clojure-hits/)**: haven't read them yet, but I like his other articles, so these are on my reading list. Looks like interesting stuff.
* **[Building a System in Clojure - Part 1 (09/2014)](http://matthiasnehlsen.com/blog/2014/09/24/Building-Systems-in-Clojure-1/)**: first of my series of articles about building a system in Clojure.
* **["Good Enough" error handling in Clojure - Adam Bard (05/2013)](http://adambard.com/blog/acceptable-error-handling-in-clojure/)**: I enjoyed this article about error handling.
* **[Clojure Tutorials on Semaphore Community](https://semaphoreci.com/community/tags/clojure)** - a collection of Clojure related tutorials covering testing, deployment, continuous integration and other topics.
* **[API Authentication with Liberator and Friend](http://sritchie.github.io/2014/01/17/api-authentication-with-liberator-and-friend/)**: useful blog post when you have API authentication needs

## Videos
* **[Talk Transcripts](https://github.com/matthiasn/talk-transcripts)**: transcripts of interesting talks
* **[The Functional Final Frontier - David Nolen (10/2014)](http://www.infoq.com/presentations/om-clojurescript-facebook-react)**: David Nolen talks about Om and functional UI programming **[transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Nolen_David/FunctionalFinalFrontier.md)**
* **[Transducers - Rich Hickey (09/2014)](https://www.youtube.com/watch?v=6mTbuzafcII)**: Rich Hickey talks about **Transducers**. Excellent talk as usual, must see. **[transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/Transducers.md)**
* **[Simple Made Easy - Rich Hickey](http://www.infoq.com/presentations/Simple-Made-Easy)**: one of my favorite presentations. Like overall. Highly recommended. **[transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/SimpleMadeEasy.md)**
* **[Hammock Driven Development - Rich Hickey](https://www.youtube.com/watch?v=f84n5oFoZBc)** **[transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/HammockDrivenDev.md)**
* **[Clojure - Rich Hickey](http://www.infoq.com/presentations/hickey-clojure)**
* **[Are we there yet? - Rich Hickey](http://www.infoq.com/presentations/Are-We-There-Yet-Rich-Hickey)**
* **[Reducers - A Library and Model for Collection Processing - Rich Hickey ](http://www.infoq.com/presentations/Clojure-Reducers)** **[transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/Reducers.md)**
* **[The Language of the System - Rich Hickey, Conj 2012](https://www.youtube.com/watch?v=ROor6_NGIWU)**: less about Clojure and more about the design of systems in general. Well worth watching (like all of Rich Hickey's talks, really). **[transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/LanguageSystem.md)**
* **[Design, Composition and Performance - Rich Hickey](http://www.infoq.com/presentations/Design-Composition-Performance)**
* **[Clojure core.async - Rich Hickey](http://www.infoq.com/presentations/clojure-core-async)** **[transcript](http://www.infoq.com/presentations/clojure-core-async)**
* **[ClojureScript: Lisp's Revenge - David Nolen](https://www.youtube.com/watch?v=MTawgp3SKy8)**
* **[Activity Stream Processing in Clojure - Travis Vachon](https://www.youtube.com/watch?v=0l7Va3-wXeI)**
* **[Expert to Expert: Rich Hickey and Brian Beckman - Inside Clojure](https://www.youtube.com/watch?v=wASCH_gPnDw)**
* **[ClojureScript - Better Semantics at Low Low Prices! - David Nolen](http://www.infoq.com/presentations/ClojureScript-Optimizations)**
* **[Pete Hunt - The Secrets of React's Virtual DOM (FutureJS 2014)](https://www.youtube.com/watch?v=-DX3vJiqxm4)**
* **[Clojure in the Large - Stuart Sierra](http://www.infoq.com/presentations/Clojure-Large-scale-patterns-techniques)**
* **[Quick Intro to Live Programming with Overtone](https://vimeo.com/22798433)**
* **[EuroClojure 2014 videos](https://vimeo.com/channels/781458)**: 18 recorded presentations, plenty of interesting stuff
* **[Mobile App Development with ClojureScript and Cordova](http://www.hakkalabs.co/articles/mobile-app-development-clojurescript-cordova#!)**: talk given at the NYC Clojure Users Group in July 2014 about building a hybrid app with **[Apache Cordova](http://cordova.apache.org)**, **ClojureScript**, **cor.async** and **Om**. Looks promising.
* **[Components Just Enough Structure - Stuart Sierra, Clojure/West 2014](https://www.youtube.com/watch?v=13cmHf_kt-Q)**: presentation on the Components library.
* [**LispCast Videos**](http://www.purelyfunctional.tv/): For-pay video courses teaching Clojure.

## Slides
* **[Mastering time with Clojure core.async](http://sssslide.com/speakerdeck.com/hlship/mastering-time-with-clojure-core-dot-async)**

## Podcasts
* **[The Cognicast](http://blog.cognitect.com/cognicast/)**: podcast by **[Cognitect](http://cognitect.com)**, the guys behind Clojure.
* **[defn](https://defn.audio)**: the number one vegetarian Clojure podcast by Vijay Kiran and Ray McDermott. Casual, fun and NSFW interviews with Clojure luminaries.
* **[Functional Geekery](http://www.functionalgeekery.com)**: podcast on all things functional programming, sometimes featuring Clojure as well.

## Comparisons with other languages
* **[Clojure vs Scala (12/2013)](http://programming-puzzler.blogspot.de/2013/12/clojure-vs-scala.html)**: comparing Clojure and Scala. I agree that Clojure guides you towards simpler solutions.
* **[Clojure's core.typed vs Haskell - A Project Euler showdown (09/2013)](http://adambard.com/blog/core-typed-vs-haskell/)**: comparing the approaches to two mathematical problems in Haskell and Clojure / core.typed.
* **[MODERN CONCURRENCY: ERLANG, SCALA, GO, CLOJURE (2013)](http://kachayev.github.io/talks/kharkivpy%230/#/)**: slideshow comparing approaches to concurrency in different languages. NOTE: this appears to **predate core.async**. But **CSP-style channels** are mentioned for **golang**, so the same applies to Clojure with core.async in addition to STM and **agents**.

## LISP
* **[Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp/)**
* **[The Nature of Lisp](http://www.defmacro.org/ramblings/lisp.html)**
* **[Structure and Interpretation of Computer Programs - Lecture Videos](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)**: recorded in 1986
* **[Lispcast.com](http://www.lispcast.com)**: Eric Normand's blog 

