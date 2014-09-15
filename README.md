Clojure-Resources
=================

This is a compilation of links and resources for learning about **Clojure**, **ClojureScript**, **Om** and more broadly, **LISP**. It is still in very early stages. Please feel free to add resources by issuing a pull request (preferred) or by getting in touch. For now it is mostly a dump of my bookmarks, but I intend to go through them one by one and write a quick note about each one (or delete those that I don't find useful after all). Totally unordered at this point.

## Clojure
* **[Clojure Homepage](http://clojure.org)**
* **[Clojure Google Group](https://groups.google.com/forum/#!forum/clojure)**
* **[Clojure Cheat Sheet](http://grimoire.arrdem.com/)**
* **[Inspecting the content of channels in core.async](http://tgk.github.io/2013/10/inspect-core-async-channels.html)**
* **[Monger, a Clojure client for MongoDB](http://clojuremongodb.info/articles/getting_started.html)**
* **[Overtone](https://github.com/overtone/overtone)**: make music from your REPL
* **[Live Coding. Live Synths. Live Music.](http://meta-ex.com)**: music made with CLojure and Overtone
* **[The Clojure Toolbox](http://www.clojure-toolbox.com)**: a categorised directory of libraries and tools for Clojure
* **[Clojure Copter - Control for the AR Parrot Drone](https://github.com/gigasquid/clj-drone)**
* **[ckirkendall/fresnel](https://github.com/ckirkendall/fresnel)**: A library for composing lenses and working with complex state objects
* **[Clojure Users - Linkedin Group](https://www.linkedin.com/groups?home=&gid=1058217)**
* **[clj-time/clj-time on GitHub](https://github.com/clj-time/clj-time)**: wrapper for Joda Time
* **[Clojure compilation](http://clojure.org/compilation)**: helped me learn more about ahead-of-time compilation (AOT).
* **[xsc/pandect on GitHub](https://github.com/xsc/pandect)**: Fast and easy-to-use Message Digest, Checksum and HMAC library. I use it in the Clojure version of my **[BirdWatch](https://github.com/matthiasn/BirdWatch)** project & it works like a charm.
* **[Clojure Documentation](http://clojure-doc.org)**: community-driven documentation project
* **[clojure/data.priority-map on GitHub](https://github.com/clojure/data.priority-map)**: implementation of a priority map in Clojure. Useful when you want a sorted map that is sorted based on the values, not the keys.
* **[damballa/parkour on GitHub](https://github.com/damballa/parkour)**: Hadoop MapReduce in idiomatic Clojure.
* **[Clojure for the Brave and True - Writing Macros](http://www.braveclojure.com/writing-macros/)**: before this article, I did not know that there was a connection between hair growth potion and macros. Well, I still don't know that. But entertaining nonetheless. And I now understand macros.
* **[clojure/core.typed](https://github.com/clojure/core.typed)**: An optional type system for Clojure
* **[Organizing Your Project: a Librarian's Tale](http://www.braveclojure.com/organization/)**: useful chapter from the **[Clojure for the Brave and True](http://www.braveclojure.com/)** book about code organization and namespaces. It's a little long but it still covers the topic well enough.
* [**Clojure Gazette**](http://www.clojuregazette.com): Weekly Newsletter to inspire Clojure programmers.
* **[SICP distilled](https://www.kickstarter.com/projects/1751759988/sicp-distilled)**: Kickstarter project aimed at translating **SICP** (see in the last section) into Clojure. This looks really cool, you should go fund it while you still can. I have done the same.

## Learn the language
* **[Clojure from the ground up](http://aphyr.com/tags/Clojure-from-the-ground-up)**: very encouraging series of articles for beginners. I also really appreciate the introduction.
* **[Clojure for the Brave and True (a Book for Beginners)](http://www.braveclojure.com)**: great intro, I particularly enjoyed the introduction to Emacs in conjunction with Clojure
* **[Introduction to Clojure](http://clojure-doc.org/articles/tutorials/introduction.html)**: short introduction to the Clojure basics. With this, it should be possible to learn the language itself on a rainy afternoon.

## ClojureScript
* **[clojure/clojurescript - GitHub](https://github.com/clojure/clojurescript)**
* **[ClojureScript Google Group](https://groups.google.com/forum/#!forum/clojurescript)**
* **[ClojureScript-in-ClojureScript REPL](http://clojurescript.net)**
* **[ClojureScript One](http://clojurescriptone.com)**
* **[Translations from JavaScript](http://www.polymer-project.org)**: plenty of JavaScript code snippets and their translation to ClojureScript
* **[Calling javascript functions from clojurescript](http://odyssomay.github.io/2011/10/10/calling-javascript-functions-from-clojurescript.html)**
* **[Specljs and ClojureScript](http://speclj.com/specljs)**
* **[tailrecursion/cljs-priority-map on GitHub](https://github.com/tailrecursion/cljs-priority-map)**: ClojureScript port of clojure/data.priority-map

## Structuring an application
* **[stuartsierra/component on GitHub](https://github.com/stuartsierra/component)**: okay, so this one had been on my list for a while. Started watching Stuart's video a few times. Now I finally got around to using it. And all I can say is you really have to take a closer look at this. It makes structuring a larger application so much more straightforward. And the earlier you do, the more pain you save later. Rewriting an existing application is doable, but somewhat painful.
* **[danielsz/system on GitHub](https://github.com/danielsz/system)**: set of readymade components on top of the component library above.
* **[palletops/leaven on GitHub](https://github.com/palletops/leaven)**: lightweight component model for both Clojure and ClojureScript.
* **[palletops/bakery on GitHub](https://github.com/palletops/bakery)**: A library of components for leaven, the component library above.
 
## Web development / Om
* **[weavejester/compojure on GitHub](https://github.com/weavejester/compojure)**: a truly concise routing library for Clojure web applications.
* **[swannodette/om - GitHub](https://github.com/swannodette/om)**: a **ClojureScript** library on top of Facebook's **[React library](http://facebook.github.io/react/)**. React and ClojureScript are a great match as React is particularly well suited for rendering **immutable** data structures.
* **[A slice of React, Clojurescript and Om](http://www.lexicallyscoped.com/2013/12/25/slice-of-reactjs-and-cljs.html)**: article rewriting some React samples using **Om**
* **[Om: Enhancing Facebook's React with Immutability](http://www.infoq.com/news/2014/01/om-react)**
* **[ptaoussanis/sente on GitHub](https://github.com/ptaoussanis/sente)**: powerful library for connecting a Clojure server application and a ClojureScript client side application via the WebSockets protocol. I'm using this successfully in my **[BirdWatch](https://github.com/matthiasn/birdwatch/)** project.
* **[Compojure apps, in the style of Sinatra - Adam Bard, 09/2014](http://adambard.com/blog/sinatra-docs-in-clojure/)**: excellent introduction to Compojure, inspired by Sinatra's getting started guide.

## core.async
* **[clojure/core.async on GitHub](https://github.com/clojure/core.async/)**
* **[Clojure core.async API Reference](https://clojure.github.io/core.async/)**: descriptions oftentimes too short to fully understand how to use the constructs in my opinion, but at least a starting point
* **[Combining & Controlling Channels with core.async's merge and mix](http://yobriefca.se/blog/2014/06/01/combining-and-controlling-channels-with-core-dot-asyncs-merge-and-mix/)**
* **[Mastering Time with Clojure core.async](http://sssslide.com/speakerdeck.com/hlship/mastering-time-with-clojure-core-dot-async)**
* **[core.async and Blocking IO](http://martintrojer.github.io/clojure/2013/07/07/coreasync-and-blocking-io/)**: article discussing blocking IO and how to deal with it and why non-blocking is preferable. Great, concise read.
* **[Code Read of core.async Timeouts](http://hueypetersen.com/posts/2013/07/10/code-read-of-core-async-timeouts/)**
* **[Publish and Subscribe with core.async's pub and sub](http://yobriefca.se/blog/2014/06/04/publish-and-subscribe-with-core-dot-asyncs-pub-and-sub/)**: useful and well-written introduction to the topic of Publish-Subscribe. I like the idea of a channel-driven **[Rube Goldberg machine](https://en.wikipedia.org/wiki/Rube_Goldberg_machine)**. Can we have crazy animations with that as well?

## Tooling
* **[Leiningen](http://leiningen.org)**: for automating Clojure projects without setting your hair on fire (from the project website). Hard to imagine using Clojure without it.
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

## Distributed computing
* **[Avout](https://github.com/liebke/avout)**: Distributed State in Clojure, provides a distributed implementation of **[Clojure's Software Transactional Memory (STM)](http://clojure.org/refs)**

## Blog posts
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

## Videos
* **[Simple Made Easy - Rich Hickey](http://www.infoq.com/presentations/Simple-Made-Easy)**: one of my favorite presentations. Like overall. Strongly receommended.
* **[Hammock Driven Development - Rich Hickey](https://www.youtube.com/watch?v=f84n5oFoZBc)**
* **[Clojure - Rich Hickey](http://www.infoq.com/presentations/hickey-clojure)**
* **[Are we there yet? - Rich Hickey](http://www.infoq.com/presentations/Are-We-There-Yet-Rich-Hickey)**
* **[Reducers - A Library and Model for Collection Processing - Rich Hickey ](http://www.infoq.com/presentations/Clojure-Reducers)**
* **[The Language of the System - Rich Hickey, Conj 2012](https://www.youtube.com/watch?v=ROor6_NGIWU)**: less about Clojure and more about the design of systems in general. Well worth watching (like all of Rich Hickey's talks, really).
* **[Design, Composition and Performance - Rich Hickey](http://www.infoq.com/presentations/Design-Composition-Performance)**
* **[Clojure core.async - Rich Hickey](http://www.infoq.com/presentations/clojure-core-async)**
* **[Core.async - Communicating Sequential Processes using Channels, in Clojure - Rich Hickey](Core.async - Communicating Sequential Processes using Channels, in Clojure)**
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
* **[Cognicast](http://thinkrelevance.com/blog/tags/podcast)**
* **[Functional Geekery](http://www.functionalgeekery.com)**

## LISP
* **[Structure and Interpretation of Computer Programs](http://mitpress.mit.edu/sicp/)**
* **[The Nature of Lisp](http://www.defmacro.org/ramblings/lisp.html)**
* **[Structure and Interpretation of Computer Programs - Lecture Videos](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)**: recorded in 1986
* **[Lispcast.com](http://www.lispcast.com)**: Eric Normand's blog 

