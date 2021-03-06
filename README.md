# ElixirConf 2016 Summary

A collection of links that cover what happened during ElixirConf 2016. Please feel free to submit a PR!

## Day 0

#### SimAlchemy by [James Edward Gray](https://github.com/jeg2)

- Slides
    + [Process Basics](https://github.com/sabondano/elixirconf-2016/blob/master/process_basics_slides.pdf)
    + [GenServer and Friends](https://github.com/sabondano/elixirconf-2016/blob/master/genserver_and_friends_slides.pdf)
    + [Supervisors](https://github.com/sabondano/elixirconf-2016/blob/master/supervisors_slides.pdf)
    + [OTP Strategy](https://github.com/sabondano/elixirconf-2016/blob/master/otp_strategy_slides.pdf)
- Links:
    + [Simulations](https://github.com/JEG2/simulations)
    + [Event Sourcing](http://martinfowler.com/eaaDev/EventSourcing.html)

## Day 1

### Talks

#### Erlang Solutions Message
- "supercharged observer" https://www.erlang-solutions.com/products/wombat-oam.html

#### Opening Keynote by [Chris McCord](https://twitter.com/chris_mccord)

- [Video](#)
- [Slides](#)
- Links:
    + [2m connections in Phoenix](http://www.phoenixframework.org/blog/the-road-to-2-million-websocket-connections)
    + [Programming Phoenix book](http://bit.ly/phoenix_book) - Discount code: `ElixirConfUS2016_phoenix`
    + [Phoenix Presence blog post](https://dockyard.com/blog/2016/03/25/what-makes-phoenix-presence-special-sneak-peek)
    + [Nerves - Embedded Elixir](http://nerves-project.org/)
    + [New folder structure for Phoenix](https://twitter.com/antondom/status/771341202071384064)
    + [Phoenix Presence docs](https://hexdocs.pm/phoenix/Phoenix.Presence.html)
    + [Phoenix Presence podcast on the changelog](https://changelog.com/208/)
    + [CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)

#### Abstractions: A Tale of Keys and Values by [Ernie Miller](https://github.com/erniemiller)

- [Video](#)
- [Slides](#)
- Links: ...

#### Implementing binary protocols with Elixir by [Ole Michaelis](https://twitter.com/CodeStars)

- [Video](#)
- [Slides](https://slidr.io/nesQuick/implementing-binary-protocols-with-elixir)
- Links:
    + https://github.com/nesQuick/elixir-hpack
    + https://http2.github.io/http2-spec/compression.html
    + https://http2.github.io/http2-spec/
    + http://daniel.haxx.se/http2/
    + https://github.com/ninenines/cowlib/blob/master/src/cow_hpack.erl
    + http://elixir-lang.org/docs/stable/elixir/Bitwise.html#%3C%3C%3C/2
    + http://www.slideshare.net/peychevi/http2-and-quick-protocols-optimizing-the-web-stack
    + https://ma.ttias.be/architecting-websites-http2-era/
    + https://benramsey.com/talks/2015/05/phptek-http2/
    + https://speakerdeck.com/summerwind/2-prioritization
    + http://chimera.labs.oreilly.com/books/1230000000545/ch12.html#HTTP2_HEADER_COMPRESSION
    + http://tools.ietf.org/html/rfc6585
    + https://http2.golang.org/
    + https://aprescott.com/posts/spdy-colon-headers
    + https://tools.ietf.org/html/draft-ietf-httpbis-header-compression-12
    + http://news.netcraft.com/archives/2015/06/25/june-2015-web-server-survey.html

#### pg2 and You: Getting Distributed with Elixir by [Eric Entin](https://twitter.com/antipax)

- [Video](#)
- [Slides](#)
- Links:
    + [pg2 docs](http://erlang.org/doc/man/pg2.html)
    + [phoenix pubsub](https://github.com/phoenixframework/phoenix_pubsub)
    + [RePG2](https://github.com/antipax/repg2)
    + [gen_server](http://erlang.org/doc/man/gen_server.html)
    + [global](http://erlang.org/doc/man/global.html)
    + [net_kernel](http://erlang.org/doc/man/net_kernel.html)

#### The future of deployment in Elixir by [Paul Schoenfelder](https://twitter.com/gotbones)

- [Video](#)
- [Slides](#)
- Links:
    + [Distillery](https://github.com/bitwalker/distillery)
    + [edeliver](https://github.com/boldpoker/edeliver)
    + [OpenShift](https://www.openshift.com)

#### Code Spelunking for Knowledge and Profit by [Brian Cardarella](https://twitter.com/bcardarella)

- [Video](#)
- [Slides](#)
- Links:
    + [Ecto](https://github.com/elixir-ecto/ecto)
    + [Phoenix.Naming](https://hexdocs.pm/phoenix/Phoenix.Naming.html)
    + [Compile.Phoenix](https://github.com/phoenixframework/phoenix/blob/master/lib/mix/tasks/compile.phoenix.ex)
    + [Kernel.pop_in/2](https://dockyard.com/blog/2016/06/05/elixir-1-3-kernel-pop-in)
    + [ExUnit.Case.register_attribute/3](http://elixir-lang.org/docs/stable/ex_unit/ExUnit.Case.html#register_attribute/3)
    + [elixir_rewrite](https://github.com/elixir-lang/elixir/blob/master/lib/elixir/src/elixir_rewrite.erl)
    + [Kernel.SpecialForms](http://elixir-lang.org/docs/stable/elixir/Kernel.SpecialForms.html)

#### Giving up the Object-Oriented Ghost by [Zoe Laco](https://twitter.com/morganlaco)

- [Video](#)
- [Slides](http://slides.com/morganlaco/deck-2/live)
- Links: ...

#### Nerves: Connected beyond the Node by [Justin Schneck](https://twitter.com/mobileoverlord)

- [Video](#)
- [Slides](#)
- Links: ...
    
#### Selling Food With Elixir by [Chris Bell](https://twitter.com/cjbell_)

- [Video](#)
- [Slides](#)
- Links:
    + [The app Chris built for his client](http://cavagrill.com/)
    + [gen_retry](https://github.com/appcues/gen_retry)
    + [ets](http://erlang.org/doc/man/ets.html)
    + [immortal](https://github.com/danielberkompas/immortal)
    + [httpotion](https://github.com/myfreeweb/httpotion)
    + [httpoison](https://github.com/edgurgel/httpoison)

#### Debugging techniques in Elixir by [Erich Kist](https://twitter.com/erichkist)

- [Video](#)
- [Slides](https://speakerdeck.com/erichkist/debugging-techniques-in-elixir-elixirconf-2016)
- Links: ...

#### Migrating an invoicing system to Elixir/Erlang by [Norberto Ortigoza](https://twitter.com/hiphoox)

- [Video](#)
- [Slides](#)
- Links: ...

#### Building "learn to touch type" glove with Elixir and Arduino by [Tetiana Dushenkivska](https://twitter.com/tetiana12345678)

- [Video](#)
- [Slides](#)
- Links: ...

#### Phoenix Beyond the Browser - Realtime Applications with Phoenix and Swift by [David Stump](https://twitter.com/davidstump)

- [Video](#)
- [Slides](#)
- Links:
    + [All resources](https://github.com/davidstump/phoenix_beyond_the_browser)
    + [Birdsong](https://github.com/sjrmanning/Birdsong)
    + [SwiftPhoenixClient](https://github.com/davidstump/SwiftPhoenixClient)
    + [RayWenderlich](https://www.raywenderlich.com/)
    + [SwiftPlaygrounds](https://www.apple.com/swift/playgrounds/)
    + [phoenix_chat_example](https://github.com/chrismccord/phoenix_chat_example)

#### No REST for the wicked: Building a GraphQL API by [Ben Wilson](https://twitter.com/benwilson512)

- [Video](#)
- [Slides](#)
- Links:
    + [Absinthe GraphQL](https://github.com/absinthe-graphql/absinthe)

#### Measuring your Elixir Application by [Renan Ranelli](https://twitter.com/renanranelli)

- [Video](#)
- [Slides](#)
- Links:
    + [Grafana](http://grafana.org/)
    + [InfluxDB](https://influxdata.com/)
    + [collectd](https://collectd.org/)
    + [haproxy](http://www.haproxy.org/)
    + [clojurescript](https://github.com/clojure/clojurescript)
    + [exometer](https://github.com/Feuerlabs/exometer)
    + [elixometer](https://github.com/pinterest/elixometer)
    + [vmstats](https://github.com/ferd/vmstats)

#### Edgelixir: Distributed Graph Processing in Elixir by [Nathan Lapierre](https://twitter.com/n_lap)

- [Video](#)
- [Slides](#)
- Links: ...

#### Lightning Talks
- [René Föhring](https://twitter.com/rrrene)
    + [Credo](https://github.com/rrrene/credo)
    + [ElixirStatus](http://elixirstatus.com/)
- [Pete Gamache](https://twitter.com/gamache)
    + [gen_retry](https://github.com/appcues/gen_retry)
    + [slides](http://www.slideshare.net/petegamache/genretry-simple-exponential-backoff-in-elixir)
- [Faheem Mughal](https://twitter.com/hallx)
    + [poolboy](https://github.com/devinus/poolboy)
- [Rockwell Schrock](https://twitter.com/Schrockwell)
    + [authy](https://github.com/schrockwell/authy)
- [Luke Imhoff](https://twitter.com/kronicdeth)
    + [RabbitMQ](https://www.rabbitmq.com/)
- [Jay Hayes](https://twitter.com/iamvery)
    + [Ratchet](https://github.com/iamvery/ratchet)
    + [Phoenix Ratchet](https://github.com/iamvery/phoenix_ratchet)
    + [slatchet](https://github.com/iamvery/slatchet)
- [Josh Adams](https://twitter.com/knewter)
    + [DailyDrip](https://www.dailydrip.com/)
- [Casey Rosenthal](https://twitter.com/caseyrosenthal)
    + [SimianArmy](https://github.com/Netflix/SimianArmy)
    + [Principles of Chaos](http://principlesofchaos.org/)
    + [ChaosCommunity](http://chaos.community/)
- [Przemyslaw Krowinski](https://twitter.com/sanesquid)
    + [game](https://github.com/archdragon/game_engine_elixir_phoenix)
- [Fernand Galiana](https://twitter.com/kitesurfer)
    + [Kubernetes](http://kubernetes.io/)
    + [Docker Compose](https://docs.docker.com/compose/)
- Sorry, didn't catch your name
    + [Mocks](http://blog.plataformatec.com.br/2015/10/mocks-and-explicit-contracts/)
    + [Bypass blog post](https://www.inverse.com/article/10674-here-s-how-inverse-tests-external-apis-in-elixir-with-bypass)
- [Gabe Klein](https://github.com/gabeklein)
    + [Socks](https://github.com/gabeklein/Socks)

## Day 2

### Talk

#### Keynote by [José Valim](https://twitter.com/josevalim) 

- [Video](#)
- [Slides](#)
- [Notes on slides](https://gist.github.com/sanmiguel/d73056adb6cffc9954327d8fcd89cd48)
- Links:
    + [GenStage announcement](http://elixir-lang.org/blog/2016/07/14/announcing-genstage/)
    + [GenStage](https://github.com/elixir-lang/gen_stage)
    + ["Musketeer: all for one, one for all in data processing systems"](http://www.cs.utexas.edu/users/ncrooks/2015-eurosys-musketeer.pdf). Gog, _et al_. University of Cambridge, 2015. 

#### String Theory by [James Edward Gray II](https://twitter.com/JEG2) and [Nathan Long](https://twitter.com/sleeplessgeek)

- [Video](#)
- [Slides](#)
- Links: ...

#### Refactoring Techniques for Elixir, Ecto, and Phoenix by [Gary Rennie](https://twitter.com/TheGazler)

- [Video](#)
- [Slides](#)
- Links: ...

#### Building umbrella project by [Wojtek Mach](https://twitter.com/wojtekmach)

- [Video](#)
- [Slides](#)
- Links:
    + [Umbrella apps](http://elixir-lang.org/getting-started/mix-otp/dependencies-and-umbrella-apps.html)
    + [Architecture: The Lost Years (RubyConf 2011)](https://www.youtube.com/watch?v=WpkDN78P884)
    + [Wrangling Large Rails Codebases (Rocky Mountain Ruby 2012)](https://www.youtube.com/watch?v=FElnETSIMuo)
    + [The Art of Destroying Software (Leetspeek 2014)](https://vimeo.com/108441214)
    + [AcmeBank source](https://github.com/wojtekmach/acme_bank)
    + [ExAdmin](https://github.com/smpallen99/ex_admin)
    + [distillery](https://github.com/bitwalker/distillery)

#### Collaborative Music with Elm and Phoenix by [Josh Adams](https://twitter.com/knewter)

- [Video](#)
- [Slides](#)
- Links: ...

#### Leveling Up With Ecto by [Darin Wilson](https://twitter.com/darinwilson)

- [Video](#)
- [Slides](#)
- Links:
    + [MusicDB example](https://github.com/darinwilson/music_db)
    + [ecto](https://github.com/elixir-ecto/ecto)

#### Building Available and Partition Tolerant Systems with Phoenix Tracker by [Gabi Zuniga](https://twitter.com/gabiz)

- [Video](#)
- [Slides](#)
- Links: ...

#### From Front End to Full Stack with Elixir and Phoenix by [Lauren Tan](https://twitter.com/sugarpirate_)

- [Video](#)
- [Slides](#)
- Links: ...

#### Nerves + Phoenix Saves a Father's Sanity! by [Joel Byler](https://twitter.com/joelbyler)

- [Video](#)
- [Slides](#)
- Links: ...

#### Concurrent Feature Testing with Wallaby by [Chris Keathley](https://twitter.com/ChrisKeathley)

- [Video](#)
- [Slides](#)
- Links: ...

#### The new calendar types in Elixir 1.3 by [Lau Taarnskov](https://twitter.com/lauT)

- [Video](#)
- [Slides](#)
- Links: ...

#### Painless Test Driven Development with Elixir and Phoenix by [Kat Tornwall](https://twitter.com/ktornwall)

- [Video](#)
- [Slides](#)
- Links: ...

#### Dialyzer: Optimistic Type Checking for Erlang and Elixir by [Jason Voegele](https://twitter.com/jvoegele)

- [Video](#)
- [Slides](#)
- Links: ...

#### The Joy of Connecting Elixir to the Physical World by [Frank Hunleth](https://twitter.com/fhunleth)

- [Video](#)
- [Slides](#)
- Links: ...

#### Elixir in Elixir by [Jay Hayes](https://twitter.com/iamvery)

- [Video](#)
- [Slides](#)
- Links: ...

#### WebRTC and Phoenix, when μ seconds aren't fast enough by [Jason Stiebs](https://twitter.com/peregrine)

- [Video](#)
- [Slides](#)
- Links: ...

---

## Training

### Talks

#### Phoenix - Getting realtime with channels

- Links:
    + [Sketchpad](https://github.com/chrismccord/sketchpad)

#### Taking Off with Phoenix

- Links:

#### SimAlchemy

- Links:

#### Badge Hacking with Nerves

- Links:

#### Learning Elixir through TruStory

- Links:
