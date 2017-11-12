# Awesome Go [![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [awesome-go chat channel](http://gophers.slack.com/messages/awesome-go)

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
	- [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [![flac](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/eaburns/flac&show=star)](https://github.com/eaburns/flac)[flac](https://github.com/eaburns/flac) - Native Go FLAC decoder.
* [![flac](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mewkiz/flac&show=star)](https://github.com/mewkiz/flac)[flac](https://github.com/mewkiz/flac) - Native Go FLAC decoder.
* [![gaad](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Comcast/gaad&show=star)](https://github.com/Comcast/gaad)[gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
* [![go-sox](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/krig/go-sox&show=star)](https://github.com/krig/go-sox)[go-sox](https://github.com/krig/go-sox) - libsox bindings for go.
* [![go_mediainfo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zhulik/go_mediainfo&show=star)](https://github.com/zhulik/go_mediainfo)[go_mediainfo](https://github.com/zhulik/go_mediainfo) - libmediainfo bindings for go.
* [![gosamplerate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dh1tw/gosamplerate&show=star)](https://github.com/dh1tw/gosamplerate)[gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
* [![id3v2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bogem/id3v2&show=star)](https://github.com/bogem/id3v2)[id3v2](https://github.com/bogem/id3v2) - Fast and stable ID3 parsing and writing library for Go.
* [![mix](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-mix/mix&show=star)](https://github.com/go-mix/mix)[mix](https://github.com/go-mix/mix) - Sequence-based Go-native audio mixer for music apps.
* [![mp3](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tcolgate/mp3&show=star)](https://github.com/tcolgate/mp3)[mp3](https://github.com/tcolgate/mp3) - Native Go MP3 decoder.
* [![music-theory](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-music-theory/music-theory&show=star)](https://github.com/go-music-theory/music-theory)[music-theory](https://github.com/go-music-theory/music-theory) - Music theory models in Go.
* [![PortAudio](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gordonklaus/portaudio&show=star)](https://github.com/gordonklaus/portaudio)[PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.
* [![portmidi](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rakyll/portmidi&show=star)](https://github.com/rakyll/portmidi)[portmidi](https://github.com/rakyll/portmidi) - Go bindings for PortMidi.
* [![taglib](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wtolson/go-taglib&show=star)](https://github.com/wtolson/go-taglib)[taglib](https://github.com/wtolson/go-taglib) - Go bindings for taglib.
* [![vorbis](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mccoyst/vorbis&show=star)](https://github.com/mccoyst/vorbis)[vorbis](https://github.com/mccoyst/vorbis) - "Native" Go Vorbis decoder (uses CGO, but has no dependencies).
* [![waveform](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mdlayher/waveform&show=star)](https://github.com/mdlayher/waveform)[waveform](https://github.com/mdlayher/waveform) - Go package capable of generating waveform images from audio streams.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [![authboss](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/volatiletech/authboss&show=star)](https://github.com/volatiletech/authboss)[authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.
* [![casbin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hsluoyz/casbin&show=star)](https://github.com/hsluoyz/casbin)[casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [![cookiestxt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mengzhuo/cookiestxt&show=star)](https://github.com/mengzhuo/cookiestxt)[cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides parser of cookies.txt file format.
* [![Go-AWS-Auth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smartystreets/go-aws-auth&show=star)](https://github.com/smartystreets/go-aws-auth)[Go-AWS-Auth](https://github.com/smartystreets/go-aws-auth) - AWS (Amazon Web Services) request signing library.
* [![go-jose](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/square/go-jose&show=star)](https://github.com/square/go-jose)[go-jose](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
* [![go-oauth2-server](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/RichardKnop/go-oauth2-server&show=star)](https://github.com/RichardKnop/go-oauth2-server)[go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - Standalone, specification-compliant,  OAuth2 server written in Golang.
* [![gologin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dghubble/gologin&show=star)](https://github.com/dghubble/gologin)[gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
* [![gorbac](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mikespook/gorbac&show=star)](https://github.com/mikespook/gorbac)[gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
* [![goth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/markbates/goth&show=star)](https://github.com/markbates/goth)[goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
* [![httpauth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goji/httpauth&show=star)](https://github.com/goji/httpauth)[httpauth](https://github.com/goji/httpauth) - HTTP Authentication middleware.
* [![jwt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/robbert229/jwt&show=star)](https://github.com/robbert229/jwt)[jwt](https://github.com/robbert229/jwt) - Clean and easy to use implementation of JSON Web Tokens (JWT).
* [![jwt-auth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/adam-hanna/jwt-auth&show=star)](https://github.com/adam-hanna/jwt-auth)[jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
* [![jwt-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dgrijalva/jwt-go&show=star)](https://github.com/dgrijalva/jwt-go)[jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).
* [![loginsrv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tarent/loginsrv&show=star)](https://github.com/tarent/loginsrv)[loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
* [![oauth2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/golang/oauth2&show=star)](https://github.com/golang/oauth2)[oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.
* [![osin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/RangelReale/osin&show=star)](https://github.com/RangelReale/osin)[osin](https://github.com/RangelReale/osin) - Golang OAuth2 server library.
* [![permissions2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xyproto/permissions2&show=star)](https://github.com/xyproto/permissions2)[permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.
* [![securecookie](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chmike/securecookie&show=star)](https://github.com/chmike/securecookie)[securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
* [![session](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/icza/session&show=star)](https://github.com/icza/session)[session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
* [![sessiongate-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/f0rmiga/sessiongate-go&show=star)](https://github.com/f0rmiga/sessiongate-go)[sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - Go session management using the SessionGate Redis module.
* [![sessions](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/adam-hanna/sessions&show=star)](https://github.com/adam-hanna/sessions)[sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
* [![traefik](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/containous/traefik&show=star)](https://github.com/containous/traefik)[traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
* [![yubigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/GeertJohan/yubigo&show=star)](https://github.com/GeertJohan/yubigo)[yubigo](https://github.com/GeertJohan/yubigo) - Yubikey client package that provides a simple API to integrate the Yubico Yubikey into a go application.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [![argv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cosiner/argv&show=star)](https://github.com/cosiner/argv)[argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
* [![cli](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mkideal/cli&show=star)](https://github.com/mkideal/cli)[cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
* [![cli](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/teris-io/cli&show=star)](https://github.com/teris-io/cli)[cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
* [![cli-init](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tcnksm/gcli&show=star)](https://github.com/tcnksm/gcli)[cli-init](https://github.com/tcnksm/gcli) - The easy way to start building Golang command line applications.
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [![cobra](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/spf13/cobra&show=star)](https://github.com/spf13/cobra)[cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* [![complete](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/posener/complete&show=star)](https://github.com/posener/complete)[complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
* [![docopt.go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/docopt/docopt.go&show=star)](https://github.com/docopt/docopt.go)[docopt.go](https://github.com/docopt/docopt.go) - Command-line arguments parser that will make you smile.
* [![drive](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/odeke-em/drive&show=star)](https://github.com/odeke-em/drive)[drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* [![env](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codingconcepts/env&show=star)](https://github.com/codingconcepts/env)[env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
* [![flag](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cosiner/flag&show=star)](https://github.com/cosiner/flag)[flag](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
* [![go-arg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alexflint/go-arg&show=star)](https://github.com/alexflint/go-arg)[go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
* [![go-flags](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jessevdk/go-flags&show=star)](https://github.com/jessevdk/go-flags)[go-flags](https://github.com/jessevdk/go-flags) - go command line option parser.
* [![kingpin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alecthomas/kingpin&show=star)](https://github.com/alecthomas/kingpin)[kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands.
* [![liner](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/peterh/liner&show=star)](https://github.com/peterh/liner)[liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
* [![mitchellh/cli](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mitchellh/cli&show=star)](https://github.com/mitchellh/cli)[mitchellh/cli](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
* [![mow.cli](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jawher/mow.cli&show=star)](https://github.com/jawher/mow.cli)[mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
* [![pflag](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/spf13/pflag&show=star)](https://github.com/spf13/pflag)[pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
* [![readline](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chzyer/readline&show=star)](https://github.com/chzyer/readline)[readline](https://github.com/chzyer/readline) - Pure golang implementation that provides most features in GNU-Readline under MIT license.
* [![sflags](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/octago/sflags&show=star)](https://github.com/octago/sflags)[sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.
* [![ukautz/clif](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ukautz/clif&show=star)](https://github.com/ukautz/clif)[ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework.
* [![urfave/cli](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/urfave/cli&show=star)](https://github.com/urfave/cli)[urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
* [![wlog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dixonwille/wlog&show=star)](https://github.com/dixonwille/wlog)[wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
* [![wmenu](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dixonwille/wmenu&show=star)](https://github.com/dixonwille/wmenu)[wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompts users to make choices.

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [![aurora](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/logrusorgru/aurora&show=star)](https://github.com/logrusorgru/aurora)[aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that supports fmt.Printf/Sprintf.
* [![chalk](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ttacon/chalk&show=star)](https://github.com/ttacon/chalk)[chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
* [![color](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fatih/color&show=star)](https://github.com/fatih/color)[color](https://github.com/fatih/color) - Versatile package for colored terminal output.
* [![colourize](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/TreyBastian/colourize&show=star)](https://github.com/TreyBastian/colourize)[colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
* [![go-ataman](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/workanator/go-ataman&show=star)](https://github.com/workanator/go-ataman)[go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
* [![go-colorable](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/go-colorable&show=star)](https://github.com/mattn/go-colorable)[go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows.
* [![go-colortext](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/daviddengcn/go-colortext&show=star)](https://github.com/daviddengcn/go-colortext)[go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
* [![go-isatty](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/go-isatty&show=star)](https://github.com/mattn/go-isatty)[go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
* [![gocui](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jroimartin/gocui&show=star)](https://github.com/jroimartin/gocui)[gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* [![gommon/color](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/labstack/gommon/tree/master/color&show=star)](https://github.com/labstack/gommon/tree/master/color)[gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
* [![mpb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vbauerster/mpb&show=star)](https://github.com/vbauerster/mpb)[mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
* [![progressbar](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/schollz/progressbar&show=star)](https://github.com/schollz/progressbar)[progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
* [![termbox-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nsf/termbox-go&show=star)](https://github.com/nsf/termbox-go)[termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
* [![termtables](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/apcera/termtables&show=star)](https://github.com/apcera/termtables)[termtables](https://github.com/apcera/termtables) - Go port of the Ruby library [![terminal-tables](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tj/terminal-table&show=star)](https://github.com/tj/terminal-table)[terminal-tables](https://github.com/tj/terminal-table) for simple ASCII table generation as well as providing markdown and HTML output.
* [![termui](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gizak/termui&show=star)](https://github.com/gizak/termui)[termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [![blessed-contrib](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yaronn/blessed-contrib&show=star)](https://github.com/yaronn/blessed-contrib)[blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [![uilive](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gosuri/uilive&show=star)](https://github.com/gosuri/uilive)[uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in realtime.
* [![uiprogress](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gosuri/uiprogress&show=star)](https://github.com/gosuri/uiprogress)[uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
* [![uitable](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gosuri/uitable&show=star)](https://github.com/gosuri/uitable)[uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.

## Configuration

*Libraries for configuration parsing.*

* [![config](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/olebedev/config&show=star)](https://github.com/olebedev/config)[config](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
* [![configure](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/paked/configure&show=star)](https://github.com/paked/configure)[configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
* [![env](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/caarlos0/env&show=star)](https://github.com/caarlos0/env)[env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* [![envcfg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tomazk/envcfg&show=star)](https://github.com/tomazk/envcfg)[envcfg](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
* [![envconf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ian-kent/envconf&show=star)](https://github.com/ian-kent/envconf)[envconf](https://github.com/ian-kent/envconf) - Configuration from environment.
* [![envconfig](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vrischmann/envconfig&show=star)](https://github.com/vrischmann/envconfig)[envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
* [![envh](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/antham/envh&show=star)](https://github.com/antham/envh)[envh](https://github.com/antham/envh) - Helpers to manage environment variables.
* [![gcfg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gcfg/gcfg&show=star)](https://github.com/go-gcfg/gcfg)[gcfg](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
* [![goConfig](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/crgimenes/goConfig&show=star)](https://github.com/crgimenes/goConfig)[goConfig](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
* [![godotenv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/joho/godotenv&show=star)](https://github.com/joho/godotenv)[godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* [![gofigure](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ian-kent/gofigure&show=star)](https://github.com/ian-kent/gofigure)[gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
* [![gone/jconf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/One-com/gone/tree/master/jconf&show=star)](https://github.com/One-com/gone/tree/master/jconf)[gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [![hjson](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hjson/hjson-go&show=star)](https://github.com/hjson/hjson-go)[hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
* [![ingo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/schachmat/ingo&show=star)](https://github.com/schachmat/ingo)[ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
* [![ini](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-ini/ini&show=star)](https://github.com/go-ini/ini)[ini](https://github.com/go-ini/ini) - Go package to read and write INI files.
* [![joshbetz/config](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/joshbetz/config&show=star)](https://github.com/joshbetz/config)[joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
* [![mini](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sasbury/mini&show=star)](https://github.com/sasbury/mini)[mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
* [![store](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tucnak/store&show=star)](https://github.com/tucnak/store)[store](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
* [![viper](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/spf13/viper&show=star)](https://github.com/spf13/viper)[viper](https://github.com/spf13/viper) - Go configuration with fangs.
* [![xdg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/OpenPeeDeeP/xdg&show=star)](https://github.com/OpenPeeDeeP/xdg)[xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

## Continuous Integration

*Tools for help with continuous integration.*

* [![drone](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/drone/drone&show=star)](https://github.com/drone/drone)[drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
* [![goveralls](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/goveralls&show=star)](https://github.com/mattn/goveralls)[goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
* [![overalls](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/overalls&show=star)](https://github.com/go-playground/overalls)[overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
* [![roveralls](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/LawrenceWoodman/roveralls&show=star)](https://github.com/LawrenceWoodman/roveralls)[roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [![c6](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/c9s/c6&show=star)](https://github.com/c9s/c6)[c6](https://github.com/c9s/c6) - High performance SASS compatible-implementation compiler written in Go.
* [![gcss](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yosssi/gcss&show=star)](https://github.com/yosssi/gcss)[gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
* [![go-libsass](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wellington/go-libsass&show=star)](https://github.com/wellington/go-libsass)[go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

## Data Structures

*Generic datastructures and algorithms in Go.*

* [![binpacker](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zhuangsirui/binpacker&show=star)](https://github.com/zhuangsirui/binpacker)[binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
* [![bit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yourbasic/bit&show=star)](https://github.com/yourbasic/bit)[bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
* [![bitset](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/willf/bitset&show=star)](https://github.com/willf/bitset)[bitset](https://github.com/willf/bitset) - Go package implementing bitsets.
* [![bloom](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zhenjl/bloom&show=star)](https://github.com/zhenjl/bloom)[bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
* [![bloom](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yourbasic/bloom&show=star)](https://github.com/yourbasic/bloom)[bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
* [![boomfilters](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tylertreat/BoomFilters&show=star)](https://github.com/tylertreat/BoomFilters)[boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* [![concurrent-writer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alin-sinpalean/concurrent-writer&show=star)](https://github.com/alin-sinpalean/concurrent-writer)[concurrent-writer](https://github.com/alin-sinpalean/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
* [![count-min-log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/seiflotfy/count-min-log&show=star)](https://github.com/seiflotfy/count-min-log)[count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
* [![cuckoofilter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/seiflotfy/cuckoofilter&show=star)](https://github.com/seiflotfy/cuckoofilter)[cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
* [![encoding](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zhenjl/encoding&show=star)](https://github.com/zhenjl/encoding)[encoding](https://github.com/zhenjl/encoding) - Integer Compression Libraries for Go.
* [![go-adaptive-radix-tree](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/plar/go-adaptive-radix-tree&show=star)](https://github.com/plar/go-adaptive-radix-tree)[go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
* [![go-datastructures](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Workiva/go-datastructures&show=star)](https://github.com/Workiva/go-datastructures)[go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* [![go-ef](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/amallia/go-ef&show=star)](https://github.com/amallia/go-ef)[go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
* [![go-geoindex](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hailocab/go-geoindex&show=star)](https://github.com/hailocab/go-geoindex)[go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index.
* [![go-rquad](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aurelien-rainone/go-rquad&show=star)](https://github.com/aurelien-rainone/go-rquad)[go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
* [![gods](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/emirpasic/gods&show=star)](https://github.com/emirpasic/gods)[gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [![golang-set](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/deckarep/golang-set&show=star)](https://github.com/deckarep/golang-set)[golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
* [![goset](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zoumo/goset&show=star)](https://github.com/zoumo/goset)[goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* [![goskiplist](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ryszard/goskiplist&show=star)](https://github.com/ryszard/goskiplist)[goskiplist](https://github.com/ryszard/goskiplist) - Skip list implementation in Go.
* [![gota](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kniren/gota&show=star)](https://github.com/kniren/gota)[gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
* [![hilbert](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/hilbert&show=star)](https://github.com/google/hilbert)[hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
* [![hyperloglog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/axiomhq/hyperloglog&show=star)](https://github.com/axiomhq/hyperloglog)[hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
* [![levenshtein](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/agext/levenshtein&show=star)](https://github.com/agext/levenshtein)[levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [![levenshtein](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/agnivade/levenshtein&show=star)](https://github.com/agnivade/levenshtein)[levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
* [![mafsa](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smartystreets/mafsa&show=star)](https://github.com/smartystreets/mafsa)[mafsa](https://github.com/smartystreets/mafsa) - MA-FSA implementation with Minimal Perfect Hashing.
* [![merkletree](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cbergoon/merkletree&show=star)](https://github.com/cbergoon/merkletree)[merkletree](https://github.com/cbergoon/merkletree) - Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.
* [![roaring](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/RoaringBitmap/roaring&show=star)](https://github.com/RoaringBitmap/roaring)[roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.
* [![skiplist](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gansidui/skiplist&show=star)](https://github.com/gansidui/skiplist)[skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
* [![trie](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/derekparker/trie&show=star)](https://github.com/derekparker/trie)[trie](https://github.com/derekparker/trie) - Trie implementation in Go.
* [![ttlcache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/diegobernardes/ttlcache&show=star)](https://github.com/diegobernardes/ttlcache)[ttlcache](https://github.com/diegobernardes/ttlcache) - In-memory LRU string-interface{} map with expiration for golang.
* [![willf/bloom](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/willf/bloom&show=star)](https://github.com/willf/bloom)[willf/bloom](https://github.com/willf/bloom) - Go package implementing Bloom filters.

## Database

*Databases implemented in Go.*

* [![badger](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dgraph-io/badger&show=star)](https://github.com/dgraph-io/badger)[badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
* [![BigCache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/allegro/bigcache&show=star)](https://github.com/allegro/bigcache)[BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* [![bolt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/boltdb/bolt&show=star)](https://github.com/boltdb/bolt)[bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go.
* [![buntdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tidwall/buntdb&show=star)](https://github.com/tidwall/buntdb)[buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [![cache2go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/muesli/cache2go&show=star)](https://github.com/muesli/cache2go)[cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
* [![cockroach](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cockroachdb/cockroach&show=star)](https://github.com/cockroachdb/cockroach)[cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [![couchcache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codingsince1985/couchcache&show=star)](https://github.com/codingsince1985/couchcache)[couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
* [![dgraph](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dgraph-io/dgraph&show=star)](https://github.com/dgraph-io/dgraph)[dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [![diskv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/peterbourgon/diskv&show=star)](https://github.com/peterbourgon/diskv)[diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
* [![eliasdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/krotik/eliasdb&show=star)](https://github.com/krotik/eliasdb)[eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [![forestdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/couchbase/goforestdb&show=star)](https://github.com/couchbase/goforestdb)[forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
* [![GCache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bluele/gcache&show=star)](https://github.com/bluele/gcache)[GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [![geocache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/melihmucuk/geocache&show=star)](https://github.com/melihmucuk/geocache)[geocache](https://github.com/melihmucuk/geocache) - In-memory cache that is suitable for geolocation based applications.
* [![go-cache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pmylund/go-cache&show=star)](https://github.com/pmylund/go-cache)[go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [![goleveldb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/syndtr/goleveldb&show=star)](https://github.com/syndtr/goleveldb)[goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [![LevelDB](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/leveldb&show=star)](https://github.com/google/leveldb)[LevelDB](https://github.com/google/leveldb) key/value database in Go.
* [![groupcache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/golang/groupcache&show=star)](https://github.com/golang/groupcache)[groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [![influxdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/influxdb/influxdb&show=star)](https://github.com/influxdb/influxdb)[influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [![ledisdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/siddontang/ledisdb&show=star)](https://github.com/siddontang/ledisdb)[ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [![levigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jmhodges/levigo&show=star)](https://github.com/jmhodges/levigo)[levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
* [![moss](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/couchbase/moss&show=star)](https://github.com/couchbase/moss)[moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
* [![piladb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fern4lvarez/piladb&show=star)](https://github.com/fern4lvarez/piladb)[piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
* [![prometheus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/prometheus/prometheus&show=star)](https://github.com/prometheus/prometheus)[prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [![rqlite](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rqlite/rqlite&show=star)](https://github.com/rqlite/rqlite)[rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* [![Scribble](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nanobox-io/golang-scribble&show=star)](https://github.com/nanobox-io/golang-scribble)[Scribble](https://github.com/nanobox-io/golang-scribble) - Tiny flat file JSON store.
* [![tempdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rafaeljesus/tempdb&show=star)](https://github.com/rafaeljesus/tempdb)[tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
* [![tidb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pingcap/tidb&show=star)](https://github.com/pingcap/tidb)[tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [![tiedot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/HouzuoGuo/tiedot&show=star)](https://github.com/HouzuoGuo/tiedot)[tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
* [![Tile38](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tidwall/tile38&show=star)](https://github.com/tidwall/tile38)[Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.

*Database schema migration.*

* [![darwin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/GuiaBolso/darwin&show=star)](https://github.com/GuiaBolso/darwin)[darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
* [![go-fixtures](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/RichardKnop/go-fixtures&show=star)](https://github.com/RichardKnop/go-fixtures)[go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
* [![goose](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/steinbacher/goose&show=star)](https://github.com/steinbacher/goose)[goose](https://github.com/steinbacher/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [![gormigrate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gormigrate/gormigrate&show=star)](https://github.com/go-gormigrate/gormigrate)[gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
* [![migrate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattes/migrate&show=star)](https://github.com/mattes/migrate)[migrate](https://github.com/mattes/migrate) - Database migrations. CLI and Golang library.
* [![pravasan](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pravasan/pravasan&show=star)](https://github.com/pravasan/pravasan)[pravasan](https://github.com/pravasan/pravasan) - Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.
* [![soda](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/markbates/pop/tree/master/soda&show=star)](https://github.com/markbates/pop/tree/master/soda)[soda](https://github.com/markbates/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [![sql-migrate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rubenv/sql-migrate&show=star)](https://github.com/rubenv/sql-migrate)[sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.

*Database tools.*

* [![chproxy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Vertamedia/chproxy&show=star)](https://github.com/Vertamedia/chproxy)[chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
* [![go-mysql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/siddontang/go-mysql&show=star)](https://github.com/siddontang/go-mysql)[go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* [![go-mysql-elasticsearch](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/siddontang/go-mysql-elasticsearch&show=star)](https://github.com/siddontang/go-mysql-elasticsearch)[go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [![kingshard](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/flike/kingshard&show=star)](https://github.com/flike/kingshard)[kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [![myreplication](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/2tvenom/myreplication&show=star)](https://github.com/2tvenom/myreplication)[myreplication](https://github.com/2tvenom/myreplication) - MySql binary log replication listener. Supports statement and row based replication.
* [![orchestrator](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/github/orchestrator&show=star)](https://github.com/github/orchestrator)[orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* [![pgweb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sosedoff/pgweb&show=star)](https://github.com/sosedoff/pgweb)[pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* [![pREST](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nuveo/prest&show=star)](https://github.com/nuveo/prest)[pREST](https://github.com/nuveo/prest) - Serve a RESTful API from any PostgreSQL database.
* [![rwdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andizzle/rwdb&show=star)](https://github.com/andizzle/rwdb)[rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
* [![vitess](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/youtube/vitess&show=star)](https://github.com/youtube/vitess)[vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

*SQL query builder, libraries for building and using SQL.*

* [![dat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mgutz/dat&show=star)](https://github.com/mgutz/dat)[dat](https://github.com/mgutz/dat) - Go Postgres Data Access Toolkit.
* [![Dotsql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gchaincl/dotsql&show=star)](https://github.com/gchaincl/dotsql)[Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
* [![goqu](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/doug-martin/goqu&show=star)](https://github.com/doug-martin/goqu)[goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
* [![igor](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/galeone/igor&show=star)](https://github.com/galeone/igor)[igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
* [![ozzo-dbx](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-ozzo/ozzo-dbx&show=star)](https://github.com/go-ozzo/ozzo-dbx)[ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [![scaneo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/variadico/scaneo&show=star)](https://github.com/variadico/scaneo)[scaneo](https://github.com/variadico/scaneo) - Generate Go code to convert database rows into arbitrary structs.
* [![sqrl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/elgris/sqrl&show=star)](https://github.com/elgris/sqrl)[sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
* [![Squirrel](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Masterminds/squirrel&show=star)](https://github.com/Masterminds/squirrel)[Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
* [![xo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/knq/xo&show=star)](https://github.com/knq/xo)[xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [![avatica](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Boostport/avatica&show=star)](https://github.com/Boostport/avatica)[avatica](https://github.com/Boostport/avatica) - Apache Phoenix/Avatica SQL driver for database/sql.
    * [![bgc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/viant/bgc&show=star)](https://github.com/viant/bgc)[bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
    * [![firebirdsql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nakagami/firebirdsql&show=star)](https://github.com/nakagami/firebirdsql)[firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
    * [![go-adodb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/go-adodb&show=star)](https://github.com/mattn/go-adodb)[go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
    * [![go-bqstreamer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rounds/go-bqstreamer&show=star)](https://github.com/rounds/go-bqstreamer)[go-bqstreamer](https://github.com/rounds/go-bqstreamer) - BigQuery fast and concurrent stream insert.
    * [![go-mssqldb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/denisenkom/go-mssqldb&show=star)](https://github.com/denisenkom/go-mssqldb)[go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
    * [![go-oci8](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/go-oci8&show=star)](https://github.com/mattn/go-oci8)[go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
    * [![go-sql-driver/mysql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-sql-driver/mysql&show=star)](https://github.com/go-sql-driver/mysql)[go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
    * [![go-sqlite3](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/go-sqlite3&show=star)](https://github.com/mattn/go-sqlite3)[go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
    * [![gofreetds](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/minus5/gofreetds&show=star)](https://github.com/minus5/gofreetds)[gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
    * [![pgx](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jackc/pgx&show=star)](https://github.com/jackc/pgx)[pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
    * [![pq](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/lib/pq&show=star)](https://github.com/lib/pq)[pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.

* NoSQL Databases
    * [![aerospike-client-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aerospike/aerospike-client-go&show=star)](https://github.com/aerospike/aerospike-client-go)[aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
    * [![arangolite](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/solher/arangolite&show=star)](https://github.com/solher/arangolite)[arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
    * [![asc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/viant/asc&show=star)](https://github.com/viant/asc)[asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
    * [![cayley](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/cayley&show=star)](https://github.com/google/cayley)[cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.
    * [![dsc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/viant/dsc&show=star)](https://github.com/viant/dsc)[dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
    * [![dynago](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/underarmour/dynago&show=star)](https://github.com/underarmour/dynago)[dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB.
    * [![go-couchbase](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/couchbase/go-couchbase&show=star)](https://github.com/couchbase/go-couchbase)[go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
    * [![go-couchdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fjl/go-couchdb&show=star)](https://github.com/fjl/go-couchdb)[go-couchdb](https://github.com/fjl/go-couchdb) - Yet another CouchDB HTTP API wrapper for Go.
    * [![gocb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/couchbase/gocb&show=star)](https://github.com/couchbase/gocb)[gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [![gomemcache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bradfitz/gomemcache/&show=star)](https://github.com/bradfitz/gomemcache/)[gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
    * [![gorethink](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dancannon/gorethink&show=star)](https://github.com/dancannon/gorethink)[gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
    * [![goriak](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zegl/goriak&show=star)](https://github.com/zegl/goriak)[goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV.
    * [mgo](https://godoc.org/labix.org/v2/mgo) - MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
    * [![neo4j](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cihangir/neo4j&show=star)](https://github.com/cihangir/neo4j)[neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
    * [![Neo4j-GO](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/davemeehan/Neo4j-GO&show=star)](https://github.com/davemeehan/Neo4j-GO)[Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
    * [![neoism](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jmcvetta/neoism&show=star)](https://github.com/jmcvetta/neoism)[neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
    * [![redigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/garyburd/redigo&show=star)](https://github.com/garyburd/redigo)[redigo](https://github.com/garyburd/redigo) - Redigo is a Go client for the Redis database.
    * [![redis](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-redis/redis&show=star)](https://github.com/go-redis/redis)[redis](https://github.com/go-redis/redis) - Redis client for Golang.
    * [![redis](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hoisie/redis&show=star)](https://github.com/hoisie/redis)[redis](https://github.com/hoisie/redis) - Simple, powerful Redis client for Go.
    * [![redis](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bsm/redeo&show=star)](https://github.com/bsm/redeo)[redis](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
    * [![xredis](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shomali11/xredis&show=star)](https://github.com/shomali11/xredis)[xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

* Search and Analytic Databases.
    * [![bleve](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/blevesearch/bleve&show=star)](https://github.com/blevesearch/bleve)[bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
    * [![elastic](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/olivere/elastic&show=star)](https://github.com/olivere/elastic)[elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.
    * [![elasticsql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cch123/elasticsql&show=star)](https://github.com/cch123/elasticsql)[elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
    * [![elastigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattbaird/elastigo&show=star)](https://github.com/mattbaird/elastigo)[elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
    * [![goes](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/belogik/goes&show=star)](https://github.com/belogik/goes)[goes](https://github.com/belogik/goes) - Library to interact with Elasticsearch.
    * [![riot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-ego/riot&show=star)](https://github.com/go-ego/riot)[riot](https://github.com/go-ego/riot) - Go Open Source, Distributed, Simple and efficient Search Engine
    * [![skizze](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/seiflotfy/skizze&show=star)](https://github.com/seiflotfy/skizze)[skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

## Date and Time

*Libraries for working with dates and times.*

* [![carbon](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/uniplaces/carbon&show=star)](https://github.com/uniplaces/carbon)[carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
* [![date](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rickb777/date&show=star)](https://github.com/rickb777/date)[date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
* [![dateparse](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/araddon/dateparse&show=star)](https://github.com/araddon/dateparse)[dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
* [![durafmt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hako/durafmt&show=star)](https://github.com/hako/durafmt)[durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go.
* [![feiertage](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wlbr/feiertage&show=star)](https://github.com/wlbr/feiertage)[feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
* [![go-persian-calendar](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yaa110/go-persian-calendar&show=star)](https://github.com/yaa110/go-persian-calendar)[go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
* [![goweek](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/grsmv/goweek&show=star)](https://github.com/grsmv/goweek)[goweek](https://github.com/grsmv/goweek) - Library for working with week entity in golang.
* [![now](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jinzhu/now&show=star)](https://github.com/jinzhu/now)[now](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
* [![NullTime](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kirillDanshin/nulltime&show=star)](https://github.com/kirillDanshin/nulltime)[NullTime](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
* [![timeutil](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/leekchan/timeutil&show=star)](https://github.com/leekchan/timeutil)[timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
* [![tuesday](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/osteele/tuesday&show=star)](https://github.com/osteele/tuesday)[tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [![celeriac](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/svcavallar/celeriac.v1&show=star)](https://github.com/svcavallar/celeriac.v1)[celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
* [![digota](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/digota/digota&show=star)](https://github.com/digota/digota)[digota](https://github.com/digota/digota) - grpc ecommerce microservice.
* [![drmaa](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dgruber/drmaa&show=star)](https://github.com/dgruber/drmaa)[drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
* [![flowgraph](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vectaport/flowgraph&show=star)](https://github.com/vectaport/flowgraph)[flowgraph](https://github.com/vectaport/flowgraph) - MPI-style ready-send coordination layer.
* [![gleam](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chrislusf/gleam&show=star)](https://github.com/chrislusf/gleam)[gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
* [![glow](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chrislusf/glow&show=star)](https://github.com/chrislusf/glow)[glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
* [![go-jump](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dgryski/go-jump&show=star)](https://github.com/dgryski/go-jump)[go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
* [![go-kit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-kit/kit&show=star)](https://github.com/go-kit/kit)[go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [![gorpc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/valyala/gorpc&show=star)](https://github.com/valyala/gorpc)[gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
* [![grpc-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/grpc/grpc-go&show=star)](https://github.com/grpc/grpc-go)[grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* [![hprose](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hprose/hprose-golang&show=star)](https://github.com/hprose/hprose-golang)[hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
* [![jsonrpc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/osamingo/jsonrpc&show=star)](https://github.com/osamingo/jsonrpc)[jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
* [![jsonrpc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ybbus/jsonrpc&show=star)](https://github.com/ybbus/jsonrpc)[jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
* [![KrakenD](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/devopsfaith/krakend&show=star)](https://github.com/devopsfaith/krakend)[KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* [![micro](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/micro/micro&show=star)](https://github.com/micro/micro)[micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform.
* [![NATS](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nats-io/gnatsd&show=star)](https://github.com/nats-io/gnatsd)[NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* [![raft](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hashicorp/raft&show=star)](https://github.com/hashicorp/raft)[raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
* [![raft](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/coreos/etcd/tree/master/raft&show=star)](https://github.com/coreos/etcd/tree/master/raft)[raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [![ringpop-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/uber/ringpop-go&show=star)](https://github.com/uber/ringpop-go)[ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
* [![rpcx](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smallnest/rpcx&show=star)](https://github.com/smallnest/rpcx)[rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* [![sleuth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ursiform/sleuth&show=star)](https://github.com/ursiform/sleuth)[sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [![ZeroMQ](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zeromq/libzmq&show=star)](https://github.com/zeromq/libzmq)[ZeroMQ](https://github.com/zeromq/libzmq)).
* [![tendermint](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tendermint/tendermint&show=star)](https://github.com/tendermint/tendermint)[tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* [![torrent](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/anacrolix/torrent&show=star)](https://github.com/anacrolix/torrent)[torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.
    * [dht](https://godoc.org/github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
    * [![go-peerflix](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Sioro-Neoku/go-peerflix&show=star)](https://github.com/Sioro-Neoku/go-peerflix)[go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.

## Email

*Libraries that implement email creation and sending.*

* [![douceur](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aymerick/douceur&show=star)](https://github.com/aymerick/douceur)[douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
* [![email](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jordan-wright/email&show=star)](https://github.com/jordan-wright/email)[email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
* [![go-dkim](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/toorop/go-dkim&show=star)](https://github.com/toorop/go-dkim)[go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
* [![go-imap](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/emersion/go-imap&show=star)](https://github.com/emersion/go-imap)[go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
* [![go-message](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/emersion/go-message&show=star)](https://github.com/emersion/go-message)[go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
* [![Gomail](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gomail/gomail/&show=star)](https://github.com/go-gomail/gomail/)[Gomail](https://github.com/go-gomail/gomail/) - Gomail is a very simple and powerful package to send emails.
* [![Hectane](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hectane/hectane&show=star)](https://github.com/hectane/hectane)[Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
* [![hermes](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/matcornic/hermes&show=star)](https://github.com/matcornic/hermes)[hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
* [![MailHog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mailhog/MailHog&show=star)](https://github.com/mailhog/MailHog)[MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
* [![SendGrid](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sendgrid/sendgrid-go&show=star)](https://github.com/sendgrid/sendgrid-go)[SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
* [![smtp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mailhog/smtp&show=star)](https://github.com/mailhog/smtp)[smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine.

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [![agora](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/PuerkitoBio/agora&show=star)](https://github.com/PuerkitoBio/agora)[agora](https://github.com/PuerkitoBio/agora) - Dynamically typed, embeddable programming language in Go.
* [![anko](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/anko&show=star)](https://github.com/mattn/anko)[anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
* [![binder](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alexeyco/binder&show=star)](https://github.com/alexeyco/binder)[binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [![gopher-lua](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yuin/gopher-lua&show=star)](https://github.com/yuin/gopher-lua)[gopher-lua](https://github.com/yuin/gopher-lua).
* [![gisp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jcla1/gisp&show=star)](https://github.com/jcla1/gisp)[gisp](https://github.com/jcla1/gisp) - Simple LISP in Go.
* [![go-duktape](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/olebedev/go-duktape&show=star)](https://github.com/olebedev/go-duktape)[go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
* [![go-lua](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Shopify/go-lua&show=star)](https://github.com/Shopify/go-lua)[go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
* [![go-php](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/deuill/go-php&show=star)](https://github.com/deuill/go-php)[go-php](https://github.com/deuill/go-php) - PHP bindings for Go.
* [![go-python](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sbinet/go-python&show=star)](https://github.com/sbinet/go-python)[go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
* [![golua](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aarzilli/golua&show=star)](https://github.com/aarzilli/golua)[golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
* [![gopher-lua](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yuin/gopher-lua&show=star)](https://github.com/yuin/gopher-lua)[gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* [![ngaro](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/db47h/ngaro&show=star)](https://github.com/db47h/ngaro)[ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
* [![otto](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/robertkrimen/otto&show=star)](https://github.com/robertkrimen/otto)[otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go.
* [![purl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ian-kent/purl&show=star)](https://github.com/ian-kent/purl)[purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.

## Files

*Libraries for  handling files and file systems.*

* [![afero](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/spf13/afero&show=star)](https://github.com/spf13/afero)[afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
* [![go-csv-tag](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/artonge/go-csv-tag&show=star)](https://github.com/artonge/go-csv-tag)[go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
* [![go-gtfs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/artonge/go-gtfs&show=star)](https://github.com/artonge/go-gtfs)[go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
* [![notify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rjeczalik/notify&show=star)](https://github.com/rjeczalik/notify)[notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
* [![skywalker](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dixonwille/skywalker&show=star)](https://github.com/dixonwille/skywalker)[skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
* [![tarfs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/posener/tarfs&show=star)](https://github.com/posener/tarfs)[tarfs](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.

## Financial

*Packages for accounting and finance.*

* [![accounting](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/leekchan/accounting&show=star)](https://github.com/leekchan/accounting)[accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang.
* [![decimal](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shopspring/decimal&show=star)](https://github.com/shopspring/decimal)[decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
* [![go-finance](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/FlashBoys/go-finance&show=star)](https://github.com/FlashBoys/go-finance)[go-finance](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.
* [![go-money](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rhymond/go-money&show=star)](https://github.com/rhymond/go-money)[go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
* [![ofxgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aclindsa/ofxgo&show=star)](https://github.com/aclindsa/ofxgo)[ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
* [![vat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dannyvankooten/vat&show=star)](https://github.com/dannyvankooten/vat)[vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.

## Forms

*Libraries for working with forms.*

* [![bind](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/robfig/bind&show=star)](https://github.com/robfig/bind)[bind](https://github.com/robfig/bind) - Bind form data to any Go values.
* [![binding](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mholt/binding&show=star)](https://github.com/mholt/binding)[binding](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.
* [![conform](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/leebenson/conform&show=star)](https://github.com/leebenson/conform)[conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
* [![form](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/form&show=star)](https://github.com/go-playground/form)[form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
* [![formam](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/monoculum/formam&show=star)](https://github.com/monoculum/formam)[formam](https://github.com/monoculum/formam) - decode form's values into a struct.
* [![forms](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/albrow/forms&show=star)](https://github.com/albrow/forms)[forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
* [![gorilla/csrf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gorilla/csrf&show=star)](https://github.com/gorilla/csrf)[gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
* [![nosurf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/justinas/nosurf&show=star)](https://github.com/justinas/nosurf)[nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.

## Game Development

*Awesome game development libraries.*

* [![Azul3D](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/azul3d/engine&show=star)](https://github.com/azul3d/engine)[Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go.
* [![Ebiten](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hajimehoshi/ebiten&show=star)](https://github.com/hajimehoshi/ebiten)[Ebiten](https://github.com/hajimehoshi/ebiten) - simple 2D game library in Go.
* [![engo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/EngoEngine/engo&show=star)](https://github.com/EngoEngine/engo)[engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
* [![GarageEngine](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vova616/GarageEngine&show=star)](https://github.com/vova616/GarageEngine)[GarageEngine](https://github.com/vova616/GarageEngine) - 2d game engine written in Go working on OpenGL.
* [![glop](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/runningwild/glop&show=star)](https://github.com/runningwild/glop)[glop](https://github.com/runningwild/glop) - Glop (Game Library Of Power) is a fairly simple cross-platform game library.
* [![go-astar](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/beefsack/go-astar&show=star)](https://github.com/beefsack/go-astar)[go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
* [![go-collada](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/GlenKelley/go-collada&show=star)](https://github.com/GlenKelley/go-collada)[go-collada](https://github.com/GlenKelley/go-collada) - Go package for working with the Collada file format.
* [![go-sdl2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/veandco/go-sdl2&show=star)](https://github.com/veandco/go-sdl2)[go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* [![go3d](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ungerik/go3d&show=star)](https://github.com/ungerik/go3d)[go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
* [![gonet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xtaci/gonet&show=star)](https://github.com/xtaci/gonet)[gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
* [![goworld](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xiaonanln/goworld&show=star)](https://github.com/xiaonanln/goworld)[goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping
* [![Leaf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/name5566/leaf&show=star)](https://github.com/name5566/leaf)[Leaf](https://github.com/name5566/leaf) - Lightweight game server framework.
* [![nano](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/lonnng/nano&show=star)](https://github.com/lonnng/nano)[nano](https://github.com/lonnng/nano) - Lightweight, facility, high performance golang based game server framework
* [![Oak](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/oakmound/oak&show=star)](https://github.com/oakmound/oak)[Oak](https://github.com/oakmound/oak) - Pure Go game engine.
* [![Pixel](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/faiface/pixel&show=star)](https://github.com/faiface/pixel)[Pixel](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.
* [![raylib-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gen2brain/raylib-go&show=star)](https://github.com/gen2brain/raylib-go)[raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* [![termloop](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/JoelOtter/termloop&show=star)](https://github.com/JoelOtter/termloop)[termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [![efaceconv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/t0pep0/efaceconv&show=star)](https://github.com/t0pep0/efaceconv)[efaceconv](https://github.com/t0pep0/efaceconv) - Code generation tool for high performance conversion from interface{} to immutable type without allocations.
* [![gen](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/clipperhouse/gen&show=star)](https://github.com/clipperhouse/gen)[gen](https://github.com/clipperhouse/gen) - Code generation tool for ‘generics’-like functionality.
* [![go-enum](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/abice/go-enum&show=star)](https://github.com/abice/go-enum)[go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments.
* [![go-linq](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ahmetalpbalkan/go-linq&show=star)](https://github.com/ahmetalpbalkan/go-linq)[go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
* [![goderive](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/awalterschulze/goderive&show=star)](https://github.com/awalterschulze/goderive)[goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types.
* [![interfaces](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rjeczalik/interfaces&show=star)](https://github.com/rjeczalik/interfaces)[interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
* [![jennifer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dave/jennifer&show=star)](https://github.com/dave/jennifer)[jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
* [![pkgreflect](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ungerik/pkgreflect&show=star)](https://github.com/ungerik/pkgreflect)[pkgreflect](https://github.com/ungerik/pkgreflect) - Go preprocessor for package scoped reflection.

## Go Compilers

*Tools for compiling Go to other languages.*

* [![gopherjs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gopherjs/gopherjs&show=star)](https://github.com/gopherjs/gopherjs)[gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
* [![llgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-llvm/llgo&show=star)](https://github.com/go-llvm/llgo)[llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.
* [![tardisgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tardisgo/tardisgo&show=star)](https://github.com/tardisgo/tardisgo)[tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.

## Goroutines

*Tools for managing and working with Goroutines.*

* [![go-floc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/workanator/go-floc&show=star)](https://github.com/workanator/go-floc)[go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
* [![go-flow](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kamildrazkiewicz/go-flow&show=star)](https://github.com/kamildrazkiewicz/go-flow)[go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
* [![GoSlaves](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/themester/GoSlaves&show=star)](https://github.com/themester/GoSlaves)[GoSlaves](https://github.com/themester/GoSlaves) - Simple and Asynchronous Goroutine pool library.
* [![goworker](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/benmanns/goworker&show=star)](https://github.com/benmanns/goworker)[goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* [![grpool](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ivpusic/grpool&show=star)](https://github.com/ivpusic/grpool)[grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
* [![pool](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/pool&show=star)](https://github.com/go-playground/pool)[pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
* [![semaphore](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kamilsk/semaphore&show=star)](https://github.com/kamilsk/semaphore)[semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
* [![tunny](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Jeffail/tunny&show=star)](https://github.com/Jeffail/tunny)[tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
* [![worker-pool](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vardius/worker-pool&show=star)](https://github.com/vardius/worker-pool)[worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
* [![workerpool](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gammazero/workerpool&show=star)](https://github.com/gammazero/workerpool)[workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [![app](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/murlokswarm/app&show=star)](https://github.com/murlokswarm/app)[app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* [![go-astilectron](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asticode/go-astilectron&show=star)](https://github.com/asticode/go-astilectron)[go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* [go-gtk](http://mattn.github.io/go-gtk/) - Go bindings for GTK.
* [![go-qml](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-qml/qml&show=star)](https://github.com/go-qml/qml)[go-qml](https://github.com/go-qml/qml) - QML support for the Go language.
* [![go-sciter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sciter-sdk/go-sciter&show=star)](https://github.com/sciter-sdk/go-sciter)[go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* [![goqt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/visualfc/goqt&show=star)](https://github.com/visualfc/goqt)[goqt](https://github.com/visualfc/goqt) - Golang bindings to the Qt cross-platform application framework.
* [![gotk3](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gotk3/gotk3&show=star)](https://github.com/gotk3/gotk3)[gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
* [![gowd](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dtylman/gowd&show=star)](https://github.com/dtylman/gowd)[gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
* [![qt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/therecipe/qt&show=star)](https://github.com/therecipe/qt)[qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* [![ui](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andlabs/ui&show=star)](https://github.com/andlabs/ui)[ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* [![walk](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/lxn/walk&show=star)](https://github.com/lxn/walk)[walk](https://github.com/lxn/walk) - Windows application library kit for Go.
* [![webview](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zserge/webview&show=star)](https://github.com/zserge/webview)[webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

* [![gosx-notifier](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/deckarep/gosx-notifier&show=star)](https://github.com/deckarep/gosx-notifier)[gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
* [![robotgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-vgo/robotgo&show=star)](https://github.com/go-vgo/robotgo)[robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
* [![systray](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/getlantern/systray&show=star)](https://github.com/getlantern/systray)[systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
* [![trayhost](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shurcooL/trayhost&show=star)](https://github.com/shurcooL/trayhost)[trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [![go-hardware](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rakyll/go-hardware&show=star)](https://github.com/rakyll/go-hardware)[go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [![bild](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/anthonynsimon/bild&show=star)](https://github.com/anthonynsimon/bild)[bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* [![bimg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/h2non/bimg&show=star)](https://github.com/h2non/bimg)[bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
* [![geopattern](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pravj/geopattern&show=star)](https://github.com/pravj/geopattern)[geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
* [![gg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fogleman/gg&show=star)](https://github.com/fogleman/gg)[gg](https://github.com/fogleman/gg) - 2D rendering in pure Go.
* [![gift](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/disintegration/gift&show=star)](https://github.com/disintegration/gift)[gift](https://github.com/disintegration/gift) - Package of image processing filters.
* [![go-cairo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ungerik/go-cairo&show=star)](https://github.com/ungerik/go-cairo)[go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
* [![go-gd](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bolknote/go-gd&show=star)](https://github.com/bolknote/go-gd)[go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library.
* [![go-nude](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/koyachi/go-nude&show=star)](https://github.com/koyachi/go-nude)[go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go.
* [![go-opencv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/lazywei/go-opencv&show=star)](https://github.com/lazywei/go-opencv)[go-opencv](https://github.com/lazywei/go-opencv) - Go bindings for OpenCV.
* [![go-webcolors](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jyotiska/go-webcolors&show=star)](https://github.com/jyotiska/go-webcolors)[go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
* [![gocv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hybridgroup/gocv&show=star)](https://github.com/hybridgroup/gocv)[gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
* [![govatar](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/o1egl/govatar&show=star)](https://github.com/o1egl/govatar)[govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
* [![imagick](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gographics/imagick&show=star)](https://github.com/gographics/imagick)[imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
* [![imaginary](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/h2non/imaginary&show=star)](https://github.com/h2non/imaginary)[imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
* [![imaging](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/disintegration/imaging&show=star)](https://github.com/disintegration/imaging)[imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
* [![img](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hawx/img&show=star)](https://github.com/hawx/img)[img](https://github.com/hawx/img) - Selection of image manipulation tools.
* [![ln](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fogleman/ln&show=star)](https://github.com/fogleman/ln)[ln](https://github.com/fogleman/ln) - 3D line art rendering in Go.
* [![mpo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/donatj/mpo&show=star)](https://github.com/donatj/mpo)[mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
* [![picfit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/thoas/picfit&show=star)](https://github.com/thoas/picfit)[picfit](https://github.com/thoas/picfit) - An image resizing server written in Go.
* [![pt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fogleman/pt&show=star)](https://github.com/fogleman/pt)[pt](https://github.com/fogleman/pt) - Path tracing engine written in Go.
* [![resize](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nfnt/resize&show=star)](https://github.com/nfnt/resize)[resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* [![rez](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bamiaux/rez&show=star)](https://github.com/bamiaux/rez)[rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
* [![smartcrop](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/muesli/smartcrop&show=star)](https://github.com/muesli/smartcrop)[smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
* [![svgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ajstarks/svgo&show=star)](https://github.com/ajstarks/svgo)[svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
* [![tga](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ftrvxmtrx/tga&show=star)](https://github.com/ftrvxmtrx/tga)[tga](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [![connectordb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/connectordb/connectordb&show=star)](https://github.com/connectordb/connectordb)[connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
* [![devices](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goiot/devices&show=star)](https://github.com/goiot/devices)[devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
* [![eywa](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xcodersun/eywa&show=star)](https://github.com/xcodersun/eywa)[eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
* [![flogo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tibcosoftware/flogo&show=star)](https://github.com/tibcosoftware/flogo)[flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [![gatt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/paypal/gatt&show=star)](https://github.com/paypal/gatt)[gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* [![gobot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hybridgroup/gobot/&show=star)](https://github.com/hybridgroup/gobot/)[gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [![mainflux](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Mainflux/mainflux&show=star)](https://github.com/Mainflux/mainflux)[mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
* [![sensorbee](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sensorbee/sensorbee&show=star)](https://github.com/sensorbee/sensorbee)[sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.

## Logging

*Libraries for generating and working with log files.*

* [![glg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kpango/glg&show=star)](https://github.com/kpango/glg)[glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
* [![glog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/golang/glog&show=star)](https://github.com/golang/glog)[glog](https://github.com/golang/glog) - Leveled execution logs for Go.
* [![go-cronowriter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/utahta/go-cronowriter&show=star)](https://github.com/utahta/go-cronowriter)[go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
* [![go-log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/siddontang/go-log&show=star)](https://github.com/siddontang/go-log)[go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
* [![go-log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ian-kent/go-log&show=star)](https://github.com/ian-kent/go-log)[go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
* [![go-logger](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/apsdehal/go-logger&show=star)](https://github.com/apsdehal/go-logger)[go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
* [![gologger](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sadlil/gologger&show=star)](https://github.com/sadlil/gologger)[gologger](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
* [![gomol](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aphistic/gomol&show=star)](https://github.com/aphistic/gomol)[gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
* [![gone/log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/One-com/gone/tree/master/log&show=star)](https://github.com/One-com/gone/tree/master/log)[gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
* [![log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/apex/log&show=star)](https://github.com/apex/log)[log](https://github.com/apex/log) - Structured logging package for Go.
* [![log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/log&show=star)](https://github.com/go-playground/log)[log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
* [![log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/teris-io/log&show=star)](https://github.com/teris-io/log)[log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
* [![log-voyage](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/firstrow/logvoyage&show=star)](https://github.com/firstrow/logvoyage)[log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
* [![log15](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/inconshreveable/log15&show=star)](https://github.com/inconshreveable/log15)[log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
* [![logdump](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ewwwwwqm/logdump&show=star)](https://github.com/ewwwwwqm/logdump)[logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
* [![logex](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chzyer/logex&show=star)](https://github.com/chzyer/logex)[logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
* [![logger](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/azer/logger&show=star)](https://github.com/azer/logger)[logger](https://github.com/azer/logger) - Minimalistic logging library for Go.
* [![logo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mbndr/logo&show=star)](https://github.com/mbndr/logo)[logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
* [![logrus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Sirupsen/logrus&show=star)](https://github.com/Sirupsen/logrus)[logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* [![logrusly](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sebest/logrusly&show=star)](https://github.com/sebest/logrusly)[logrusly](https://github.com/sebest/logrusly) - [![logrus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sirupsen/logrus&show=star)](https://github.com/sirupsen/logrus)[logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
* [![logutils](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hashicorp/logutils&show=star)](https://github.com/hashicorp/logutils)[logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
* [![logxi](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mgutz/logxi&show=star)](https://github.com/mgutz/logxi)[logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
* [![lumberjack](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/natefinch/lumberjack&show=star)](https://github.com/natefinch/lumberjack)[lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
* [![mlog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jbrodriguez/mlog&show=star)](https://github.com/jbrodriguez/mlog)[mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
* [![ozzo-log](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-ozzo/ozzo-log&show=star)](https://github.com/go-ozzo/ozzo-log)[ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
* [![seelog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cihub/seelog&show=star)](https://github.com/cihub/seelog)[seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
* [![spew](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/davecgh/go-spew&show=star)](https://github.com/davecgh/go-spew)[spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [![stdlog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alexcesaro/log&show=star)](https://github.com/alexcesaro/log)[stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
* [![tail](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hpcloud/tail&show=star)](https://github.com/hpcloud/tail)[tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
* [![xlog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xfxdev/xlog&show=star)](https://github.com/xfxdev/xlog)[xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
* [![xlog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rs/xlog&show=star)](https://github.com/rs/xlog)[xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
* [![zap](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/uber-go/zap&show=star)](https://github.com/uber-go/zap)[zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* [![zerolog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rs/zerolog&show=star)](https://github.com/rs/zerolog)[zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.

## Machine Learning

*Libraries for Machine Learning.*

* [![bayesian](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jbrukh/bayesian&show=star)](https://github.com/jbrukh/bayesian)[bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
* [![CloudForest](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ryanbressler/CloudForest&show=star)](https://github.com/ryanbressler/CloudForest)[CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
* [![fonet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Fontinalis/fonet&show=star)](https://github.com/Fontinalis/fonet)[fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
* [![gago](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/MaxHalford/gago&show=star)](https://github.com/MaxHalford/gago)[gago](https://github.com/MaxHalford/gago) - Multi-population, flexible, parallel genetic algorithm.
* [![go-cluster](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/e-XpertSolutions/go-cluster&show=star)](https://github.com/e-XpertSolutions/go-cluster)[go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
* [![go-fann](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/white-pony/go-fann&show=star)](https://github.com/white-pony/go-fann)[go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
* [![go-galib](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/thoj/go-galib&show=star)](https://github.com/thoj/go-galib)[go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
* [![go-pr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/daviddengcn/go-pr&show=star)](https://github.com/daviddengcn/go-pr)[go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
* [![gobrain](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goml/gobrain&show=star)](https://github.com/goml/gobrain)[gobrain](https://github.com/goml/gobrain) - Neural Networks written in go.
* [![godist](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/e-dard/godist&show=star)](https://github.com/e-dard/godist)[godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
* [![goga](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tomcraven/goga&show=star)](https://github.com/tomcraven/goga)[goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
* [![GoLearn](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sjwhitworth/golearn&show=star)](https://github.com/sjwhitworth/golearn)[GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
* [![golinear](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/danieldk/golinear&show=star)](https://github.com/danieldk/golinear)[golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go.
* [![goml](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cdipaolo/goml&show=star)](https://github.com/cdipaolo/goml)[goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
* [![goRecommend](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/timkaye11/goRecommend&show=star)](https://github.com/timkaye11/goRecommend)[goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
* [![gorgonia](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chewxy/gorgonia&show=star)](https://github.com/chewxy/gorgonia)[gorgonia](https://github.com/chewxy/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
* [![goscore](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asafschers/goscore&show=star)](https://github.com/asafschers/goscore)[goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
* [![gosseract](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/otiai10/gosseract&show=star)](https://github.com/otiai10/gosseract)[gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
* [![libsvm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/datastream/libsvm&show=star)](https://github.com/datastream/libsvm)[libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
* [![mlgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/NullHypothesis/mlgo&show=star)](https://github.com/NullHypothesis/mlgo)[mlgo](https://github.com/NullHypothesis/mlgo) - This project aims to provide minimalistic machine learning algorithms in Go.
* [![neat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jinyeom/neat&show=star)](https://github.com/jinyeom/neat)[neat](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
* [![neural-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/schuyler/neural-go&show=star)](https://github.com/schuyler/neural-go)[neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
* [![probab](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ThePaw/probab&show=star)](https://github.com/ThePaw/probab)[probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
* [![regommend](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/muesli/regommend&show=star)](https://github.com/muesli/regommend)[regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
* [![shield](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/eaigner/shield&show=star)](https://github.com/eaigner/shield)[shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
* [![tfgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/galeone/tfgo&show=star)](https://github.com/galeone/tfgo)[tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.

## Messaging

*Libraries that implement messaging systems.*

* [![Centrifugo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/centrifugal/centrifugo&show=star)](https://github.com/centrifugal/centrifugo)[Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* [![dbus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/godbus/dbus&show=star)](https://github.com/godbus/dbus)[dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
* [![drone-line](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/appleboy/drone-line&show=star)](https://github.com/appleboy/drone-line)[drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://business.line.me/en/services/bot) notifications using a binary, docker or Drone CI.
* [![emitter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/olebedev/emitter&show=star)](https://github.com/olebedev/emitter)[emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
* [![event](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/agoalofalife/event&show=star)](https://github.com/agoalofalife/event)[event](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
* [![EventBus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asaskevich/EventBus&show=star)](https://github.com/asaskevich/EventBus)[EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
* [![gaurun-client](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/osamingo/gaurun-client&show=star)](https://github.com/osamingo/gaurun-client)[gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
* [![Glue](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/desertbit/glue&show=star)](https://github.com/desertbit/glue)[Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
* [![go-notify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/TheCreeper/go-notify&show=star)](https://github.com/TheCreeper/go-notify)[go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
* [![go-nsq](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nsqio/go-nsq&show=star)](https://github.com/nsqio/go-nsq)[go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
* [![go-socket.io](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/googollee/go-socket.io&show=star)](https://github.com/googollee/go-socket.io)[go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* [![go-vitotrol](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/maxatome/go-vitotrol&show=star)](https://github.com/maxatome/go-vitotrol)[go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
* [![Gollum](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/trivago/gollum&show=star)](https://github.com/trivago/gollum)[Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
* [![golongpoll](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jcuga/golongpoll&show=star)](https://github.com/jcuga/golongpoll)[golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
* [![goose](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ian-kent/goose&show=star)](https://github.com/ian-kent/goose)[goose](https://github.com/ian-kent/goose) - Server Sent Events in Go.
* [![gopush-cluster](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Terry-Mao/gopush-cluster&show=star)](https://github.com/Terry-Mao/gopush-cluster)[gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
* [![gorush](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/appleboy/gorush&show=star)](https://github.com/appleboy/gorush)[gorush](https://github.com/appleboy/gorush) - Push notification server using [![APNs2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sideshow/apns2&show=star)](https://github.com/sideshow/apns2)[APNs2](https://github.com/sideshow/apns2) and google [![GCM](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/go-gcm&show=star)](https://github.com/google/go-gcm)[GCM](https://github.com/google/go-gcm).
* [![guble](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smancke/guble&show=star)](https://github.com/smancke/guble)[guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
* [![machinery](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/RichardKnop/machinery&show=star)](https://github.com/RichardKnop/machinery)[machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* [![mangos](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-mangos/mangos&show=star)](https://github.com/go-mangos/mangos)[mangos](https://github.com/go-mangos/mangos) - Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability.
* [![melody](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/olahol/melody&show=star)](https://github.com/olahol/melody)[melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
* [![messagebus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vardius/message-bus&show=star)](https://github.com/vardius/message-bus)[messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
* [![NATS Go Client](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nats-io/nats&show=star)](https://github.com/nats-io/nats)[NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
* [![nsq-event-bus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rafaeljesus/nsq-event-bus&show=star)](https://github.com/rafaeljesus/nsq-event-bus)[nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
* [![oplog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dailymotion/oplog&show=star)](https://github.com/dailymotion/oplog)[oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
* [![pubsub](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tuxychandru/pubsub&show=star)](https://github.com/tuxychandru/pubsub)[pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
* [![RapidMQ](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sybrexsys/RapidMQ&show=star)](https://github.com/sybrexsys/RapidMQ)[RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
* [![sarama](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Shopify/sarama&show=star)](https://github.com/Shopify/sarama)[sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
* [![Uniqush-Push](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/uniqush/uniqush-push&show=star)](https://github.com/uniqush/uniqush-push)[Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
* [![zmq4](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pebbe/zmq4&show=star)](https://github.com/pebbe/zmq4)[zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [![version 3](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pebbe/zmq3&show=star)](https://github.com/pebbe/zmq3)[version 3](https://github.com/pebbe/zmq3) and [![version 2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pebbe/zmq2&show=star)](https://github.com/pebbe/zmq2)[version 2](https://github.com/pebbe/zmq2).

## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit.*

* [![alice](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/magic003/alice&show=star)](https://github.com/magic003/alice)[alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
* [![archiver](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mholt/archiver&show=star)](https://github.com/mholt/archiver)[archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* [![autoflags](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/artyom/autoflags&show=star)](https://github.com/artyom/autoflags)[autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
* [![avgRating](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kirillDanshin/avgRating&show=star)](https://github.com/kirillDanshin/avgRating)[avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
* [![banner](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dimiro1/banner&show=star)](https://github.com/dimiro1/banner)[banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
* [![battery](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/distatus/battery&show=star)](https://github.com/distatus/battery)[battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
* [![bitio](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/icza/bitio&show=star)](https://github.com/icza/bitio)[bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
* [![browscap_go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/digitalcrab/browscap_go&show=star)](https://github.com/digitalcrab/browscap_go)[browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](http://browscap.org/).
* [![captcha](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/steambap/captcha&show=star)](https://github.com/steambap/captcha)[captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
* [![conv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cstockton/go-conv&show=star)](https://github.com/cstockton/go-conv)[conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
* [![datacounter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/miolini/datacounter&show=star)](https://github.com/miolini/datacounter)[datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
* [![errors](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pkg/errors&show=star)](https://github.com/pkg/errors)[errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
* [![go-chat-bot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-chat-bot/bot&show=star)](https://github.com/go-chat-bot/bot)[go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
* [![go-commons-pool](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jolestar/go-commons-pool&show=star)](https://github.com/jolestar/go-commons-pool)[go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
* [![go-multierror](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hashicorp/go-multierror&show=star)](https://github.com/hashicorp/go-multierror)[go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
* [![go-openapi](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-openapi&show=star)](https://github.com/go-openapi)[go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
* [![go-resiliency](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/eapache/go-resiliency&show=star)](https://github.com/eapache/go-resiliency)[go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
* [![go-sarah](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/oklahomer/go-sarah&show=star)](https://github.com/oklahomer/go-sarah)[go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build bot for desired chat services including LINE, Slack, Gitter and more.
* [![go-unarr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gen2brain/go-unarr&show=star)](https://github.com/gen2brain/go-unarr)[go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
* [![go.uuid](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/satori/go.uuid&show=star)](https://github.com/satori/go.uuid)[go.uuid](https://github.com/satori/go.uuid) - Implementation of Universally Unique Identifier (UUID). Supported both creation and parsing of UUIDs.
* [![gofakeit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/brianvoe/gofakeit&show=star)](https://github.com/brianvoe/gofakeit)[gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
* [![goid](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jakehl/goid&show=star)](https://github.com/jakehl/goid)[goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
* [![gopsutil](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shirou/gopsutil&show=star)](https://github.com/shirou/gopsutil)[gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [![gosms](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/haxpax/gosms&show=star)](https://github.com/haxpax/gosms)[gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
* [![gountries](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pariz/gountries&show=star)](https://github.com/pariz/gountries)[gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
* [![hanu](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sbstjn/hanu&show=star)](https://github.com/sbstjn/hanu)[hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
* [![health](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dimiro1/health&show=star)](https://github.com/dimiro1/health)[health](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
* [![healthcheck](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/etherlabsio/healthcheck&show=star)](https://github.com/etherlabsio/healthcheck)[healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
* [![hostutils](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Wing924/hostutils&show=star)](https://github.com/Wing924/hostutils)[hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
* [![indigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/osamingo/indigo&show=star)](https://github.com/osamingo/indigo)[indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
* [![jobs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/albrow/jobs&show=star)](https://github.com/albrow/jobs)[jobs](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
* [![lk](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hyperboloide/lk&show=star)](https://github.com/hyperboloide/lk)[lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
* [![margelet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zhulik/margelet&show=star)](https://github.com/zhulik/margelet)[margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
* [![persian](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mavihq/persian&show=star)](https://github.com/mavihq/persian)[persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
* [![secdl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xor-gate/secdl&show=star)](https://github.com/xor-gate/secdl)[secdl](https://github.com/xor-gate/secdl) - Lighttpd ModSecDownload algorithm ported to go to secure download urls.
* [![shellwords](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Wing924/shellwords&show=star)](https://github.com/Wing924/shellwords)[shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* [![shortid](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/teris-io/shortid&show=star)](https://github.com/teris-io/shortid)[shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
* [![slacker](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shomali11/slacker&show=star)](https://github.com/shomali11/slacker)[slacker](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
* [![stats](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/stats&show=star)](https://github.com/go-playground/stats)[stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
* [![turtle](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hackebrot/turtle&show=star)](https://github.com/hackebrot/turtle)[turtle](https://github.com/hackebrot/turtle) - Emojis for Go.
* [![uuid](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/agext/uuid&show=star)](https://github.com/agext/uuid)[uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
* [![VarHandler](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/azr/generators/tree/master/varhandler&show=star)](https://github.com/azr/generators/tree/master/varhandler)[VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and ouput handling.
* [![werr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/txgruppi/werr&show=star)](https://github.com/txgruppi/werr)[werr](https://github.com/txgruppi/werr) - Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.
* [![xkg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-xkg/xkg&show=star)](https://github.com/go-xkg/xkg)[xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
* [![xstrings](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/huandu/xstrings&show=star)](https://github.com/huandu/xstrings)[xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

## Natural Language Processing

*Libraries for working with human languages.*

* [![dpar](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/danieldk/dpar/&show=star)](https://github.com/danieldk/dpar/)[dpar](https://github.com/danieldk/dpar/) - Transition-based statistical dependency parser.
* [![go-eco](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ThePaw/go-eco&show=star)](https://github.com/ThePaw/go-eco)[go-eco](https://github.com/ThePaw/go-eco) - Similarity, dissimilarity and distance matrices; diversity, equitability and inequality measures; species richness estimators; coenocline models.
* [![go-i18n](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nicksnyder/go-i18n/&show=star)](https://github.com/nicksnyder/go-i18n/)[go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
* [![go-mystem](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dveselov/mystem&show=star)](https://github.com/dveselov/mystem)[go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
* [![go-nlp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nuance/go-nlp&show=star)](https://github.com/nuance/go-nlp)[go-nlp](https://github.com/nuance/go-nlp) - Utilities for working with discrete probability distributions and other tools useful for doing NLP work.
* [![go-stem](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/agonopol/go-stem&show=star)](https://github.com/agonopol/go-stem)[go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
* [![go-unidecode](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mozillazg/go-unidecode&show=star)](https://github.com/mozillazg/go-unidecode)[go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
* [![go2vec](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/danieldk/go2vec&show=star)](https://github.com/danieldk/go2vec)[go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
* [![gojieba](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yanyiwu/gojieba&show=star)](https://github.com/yanyiwu/gojieba)[gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [![jieba](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fxsjy/jieba&show=star)](https://github.com/fxsjy/jieba)[jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
* [![golibstemmer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rjohnsondev/golibstemmer&show=star)](https://github.com/rjohnsondev/golibstemmer)[golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
* [![gounidecode](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fiam/gounidecode&show=star)](https://github.com/fiam/gounidecode)[gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
* [![icu](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goodsign/icu&show=star)](https://github.com/goodsign/icu)[icu](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
* [![libtextcat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goodsign/libtextcat&show=star)](https://github.com/goodsign/libtextcat)[libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
* [![MMSEGO](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/awsong/MMSEGO&show=star)](https://github.com/awsong/MMSEGO)[MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
* [![nlp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Shixzie/nlp&show=star)](https://github.com/Shixzie/nlp)[nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
* [![nlp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/james-bowman/nlp&show=star)](https://github.com/james-bowman/nlp)[nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
* [![paicehusk](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rookii/paicehusk&show=star)](https://github.com/rookii/paicehusk)[paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
* [![petrovich](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/striker2000/petrovich&show=star)](https://github.com/striker2000/petrovich)[petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
* [![porter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/a2800276/porter&show=star)](https://github.com/a2800276/porter)[porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
* [![porter2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zhenjl/porter2&show=star)](https://github.com/zhenjl/porter2)[porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
* [![prose](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jdkato/prose&show=star)](https://github.com/jdkato/prose)[prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more.
* [![RAKE.go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Obaied/RAKE.go&show=star)](https://github.com/Obaied/RAKE.go)[RAKE.go](https://github.com/Obaied/RAKE.go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
* [![segment](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/blevesearch/segment&show=star)](https://github.com/blevesearch/segment)[segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)
* [![sentences](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/neurosnap/sentences&show=star)](https://github.com/neurosnap/sentences)[sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences.
* [![shamoji](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/osamingo/shamoji&show=star)](https://github.com/osamingo/shamoji)[shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
* [![snowball](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goodsign/snowball&show=star)](https://github.com/goodsign/snowball)[snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
* [![stemmer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dchest/stemmer&show=star)](https://github.com/dchest/stemmer)[stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
* [![textcat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pebbe/textcat&show=star)](https://github.com/pebbe/textcat)[textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.
* [![whatlanggo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/abadojack/whatlanggo&show=star)](https://github.com/abadojack/whatlanggo)[whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).
* [![when](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/olebedev/when&show=star)](https://github.com/olebedev/when)[when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.

## Networking

*Libraries for working with various layers of the network.*

* [![arp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mdlayher/arp&show=star)](https://github.com/mdlayher/arp)[arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
* [![buffstreams](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/stabbycutyou/buffstreams&show=star)](https://github.com/stabbycutyou/buffstreams)[buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
* [![canopus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zubairhamed/canopus&show=star)](https://github.com/zubairhamed/canopus)[canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
* [![cidranger](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yl2chen/cidranger&show=star)](https://github.com/yl2chen/cidranger)[cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
* [![dhcp6](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mdlayher/dhcp6&show=star)](https://github.com/mdlayher/dhcp6)[dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
* [![dns](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/miekg/dns&show=star)](https://github.com/miekg/dns)[dns](https://github.com/miekg/dns) - Go library for working with DNS.
* [![ether](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/songgao/ether&show=star)](https://github.com/songgao/ether)[ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
* [![ethernet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mdlayher/ethernet&show=star)](https://github.com/mdlayher/ethernet)[ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
* [![fasthttp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/valyala/fasthttp&show=star)](https://github.com/valyala/fasthttp)[fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [![ftp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jlaffaye/ftp&show=star)](https://github.com/jlaffaye/ftp)[ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](http://tools.ietf.org/html/rfc959).
* [![go-getter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hashicorp/go-getter&show=star)](https://github.com/hashicorp/go-getter)[go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
* [![go-stun](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ccding/go-stun&show=star)](https://github.com/ccding/go-stun)[go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
* [![gobgp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/osrg/gobgp&show=star)](https://github.com/osrg/gobgp)[gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [![golibwireshark](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sunwxg/golibwireshark&show=star)](https://github.com/sunwxg/golibwireshark)[golibwireshark](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
* [![gopacket](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/gopacket&show=star)](https://github.com/google/gopacket)[gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
* [![gopcap](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/akrennmair/gopcap&show=star)](https://github.com/akrennmair/gopcap)[gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
* [![goshark](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sunwxg/goshark&show=star)](https://github.com/sunwxg/goshark)[goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
* [![gosnmp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/soniah/gosnmp&show=star)](https://github.com/soniah/gosnmp)[gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
* [![gotcp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gansidui/gotcp&show=star)](https://github.com/gansidui/gotcp)[gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
* [![grab](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cavaliercoder/grab&show=star)](https://github.com/cavaliercoder/grab)[grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
* [![graval](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/koofr/graval&show=star)](https://github.com/koofr/graval)[graval](https://github.com/koofr/graval) - Experimental FTP server framework.
* [![jazigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/udhos/jazigo&show=star)](https://github.com/udhos/jazigo)[jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
* [![kcp-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xtaci/kcp-go&show=star)](https://github.com/xtaci/kcp-go)[kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
* [![kcptun](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xtaci/kcptun&show=star)](https://github.com/xtaci/kcptun)[kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [![lhttp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fanux/lhttp&show=star)](https://github.com/fanux/lhttp)[lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
* [![linkio](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ian-kent/linkio&show=star)](https://github.com/ian-kent/linkio)[linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
* [![llb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kirillDanshin/llb&show=star)](https://github.com/kirillDanshin/llb)[llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
* [![mdns](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hashicorp/mdns&show=star)](https://github.com/hashicorp/mdns)[mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
* [![portproxy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aybabtme/portproxy&show=star)](https://github.com/aybabtme/portproxy)[portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
* [![publicip](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/polera/publicip&show=star)](https://github.com/polera/publicip)[publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
* [![raw](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mdlayher/raw&show=star)](https://github.com/mdlayher/raw)[raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
* [![sftp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pkg/sftp&show=star)](https://github.com/pkg/sftp)[sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* [![ssh](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gliderlabs/ssh&show=star)](https://github.com/gliderlabs/ssh)[ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* [![sslb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/eduardonunesp/sslb&show=star)](https://github.com/eduardonunesp/sslb)[sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
* [![stun](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-rtc/stun&show=star)](https://github.com/go-rtc/stun)[stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
* [![tcp_server](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/firstrow/tcp_server&show=star)](https://github.com/firstrow/tcp_server)[tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
* [![utp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/anacrolix/utp&show=star)](https://github.com/anacrolix/utp)[utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
* [![water](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/songgao/water&show=star)](https://github.com/songgao/water)[water](https://github.com/songgao/water) - Simple TUN/TAP library.
* [![winrm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/masterzen/winrm&show=star)](https://github.com/masterzen/winrm)[winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
* [![xtcp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xfxdev/xtcp&show=star)](https://github.com/xfxdev/xtcp)[xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication,graceful shutdown,custom protocol.
* [![YANNFF](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/intel-go/yanff&show=star)](https://github.com/intel-go/yanff)[YANNFF](https://github.com/intel-go/yanff) - Framework for rapid development of performant network functions for cloud and bare-metal.

## OpenGL

*Libraries for using OpenGL in Go.*

* [![gl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gl/gl&show=star)](https://github.com/go-gl/gl)[gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
* [![glfw](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gl/glfw&show=star)](https://github.com/go-gl/glfw)[glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
* [![goxjs/gl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goxjs/gl&show=star)](https://github.com/goxjs/gl)[goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
* [![goxjs/glfw](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goxjs/glfw&show=star)](https://github.com/goxjs/glfw)[goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
* [![mathgl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gl/mathgl&show=star)](https://github.com/go-gl/mathgl)[mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [![beego orm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/astaxie/beego/tree/master/orm&show=star)](https://github.com/astaxie/beego/tree/master/orm)[beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [![go-pg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-pg/pg&show=star)](https://github.com/go-pg/pg)[go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [![go-queryset](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jirfag/go-queryset&show=star)](https://github.com/jirfag/go-queryset)[go-queryset](https://github.com/jirfag/go-queryset) - 100% type-safe ORM with code generation and MySQL, PostgreSQL, Sqlite3, SQL Server support based on GORM.
* [![go-store](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gosuri/go-store&show=star)](https://github.com/gosuri/go-store)[go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
* [![gomodel](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cosiner/gomodel&show=star)](https://github.com/cosiner/gomodel)[gomodel](https://github.com/cosiner/gomodel) - Lightweight, fast, orm-like library helps interactive with database.
* [![GORM](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jinzhu/gorm&show=star)](https://github.com/jinzhu/gorm)[GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* [![gorp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gorp/gorp&show=star)](https://github.com/go-gorp/gorp)[gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* [![lore](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/abrahambotros/lore&show=star)](https://github.com/abrahambotros/lore)[lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
* [![Marlow](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dadleyy/marlow&show=star)](https://github.com/dadleyy/marlow)[Marlow](https://github.com/dadleyy/marlow) - Generated ORM from project structs for compile time safety assurances.
* [![pop/soda](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/markbates/pop&show=star)](https://github.com/markbates/pop)[pop/soda](https://github.com/markbates/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [![QBS](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/coocood/qbs&show=star)](https://github.com/coocood/qbs)[QBS](https://github.com/coocood/qbs) - Stands for Query By Struct. A Go ORM.
* [![reform](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-reform/reform&show=star)](https://github.com/go-reform/reform)[reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
* [![SQLBoiler](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/volatiletech/sqlboiler&show=star)](https://github.com/volatiletech/sqlboiler)[SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
* [![upper.io/db](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/upper/db&show=star)](https://github.com/upper/db)[upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
* [![Xorm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-xorm/xorm&show=star)](https://github.com/go-xorm/xorm)[Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go.
* [![Zoom](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/albrow/zoom&show=star)](https://github.com/albrow/zoom)[Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

## Package Management

*Libraries for package and dependency management.*

* [![dep](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/golang/dep&show=star)](https://github.com/golang/dep)[dep](https://github.com/golang/dep) - Go dependency tool.
* [![gigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/LyricalSecurity/gigo&show=star)](https://github.com/LyricalSecurity/gigo)[gigo](https://github.com/LyricalSecurity/gigo) - PIP-like dependency tool for golang, with support for private repositories and hashes.
* [![glide](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Masterminds/glide&show=star)](https://github.com/Masterminds/glide)[glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
* [![godep](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tools/godep&show=star)](https://github.com/tools/godep)[godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
* [![gom](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/gom&show=star)](https://github.com/mattn/gom)[gom](https://github.com/mattn/gom) - Go Manager - bundle for go.
* [![goop](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nitrous-io/goop&show=star)](https://github.com/nitrous-io/goop)[goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
* [![gop](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/lunny/gop&show=star)](https://github.com/lunny/gop)[gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH
* [![gopm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gpmgo/gopm&show=star)](https://github.com/gpmgo/gopm)[gopm](https://github.com/gpmgo/gopm) - Go Package Manager.
* [![govendor](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kardianos/govendor&show=star)](https://github.com/kardianos/govendor)[govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
* [![gpm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pote/gpm&show=star)](https://github.com/pote/gpm)[gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go.
* [![gvt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/FiloSottile/gvt&show=star)](https://github.com/FiloSottile/gvt)[gvt](https://github.com/FiloSottile/gvt) - `gvt` is a simple vendoring tool made for Go native vendoring (aka GO15VENDOREXPERIMENT), based on gb-vendor.
* [![johnny-deps](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/johnny-deps&show=star)](https://github.com/VividCortex/johnny-deps)[johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
* [![nut](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jingweno/nut&show=star)](https://github.com/jingweno/nut)[nut](https://github.com/jingweno/nut) - Vendor Go dependencies.
* [![VenGO](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/DamnWidget/VenGO&show=star)](https://github.com/DamnWidget/VenGO)[VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

## Query Language

* [![graphql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tmc/graphql&show=star)](https://github.com/tmc/graphql)[graphql](https://github.com/tmc/graphql) - graphql parser + utilities.
* [![graphql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sevki/graphql&show=star)](https://github.com/sevki/graphql)[graphql](https://github.com/sevki/graphql) - GraphQL implementation in go.
* [![graphql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/neelance/graphql-go&show=star)](https://github.com/neelance/graphql-go)[graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* [![graphql-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/graphql-go/graphql&show=star)](https://github.com/graphql-go/graphql)[graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
* [![jsonql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/elgs/jsonql&show=star)](https://github.com/elgs/jsonql)[jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang.

## Resource Embedding

* [![esc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mjibson/esc&show=star)](https://github.com/mjibson/esc)[esc](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
* [![fileb0x](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/UnnoTed/fileb0x&show=star)](https://github.com/UnnoTed/fileb0x)[fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
* [![go-embed](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pyros2097/go-embed&show=star)](https://github.com/pyros2097/go-embed)[go-embed](https://github.com/pyros2097/go-embed) - Generates go code to embed resource files into your library or executable.
* [![go-resources](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/omeid/go-resources&show=star)](https://github.com/omeid/go-resources)[go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
* [![go.rice](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/GeertJohan/go.rice&show=star)](https://github.com/GeertJohan/go.rice)[go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.
* [![statics](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/statics&show=star)](https://github.com/go-playground/statics)[statics](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
* [![statik](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rakyll/statik&show=star)](https://github.com/rakyll/statik)[statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
* [![templify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wlbr/templify&show=star)](https://github.com/wlbr/templify)[templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
* [![vfsgen](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shurcooL/vfsgen&show=star)](https://github.com/shurcooL/vfsgen)[vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [![blas](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ziutek/blas&show=star)](https://github.com/ziutek/blas)[blas](https://github.com/ziutek/blas) - Implementation of BLAS (Basic Linear Algebra Subprograms).
* [![chart](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vdobler/chart&show=star)](https://github.com/vdobler/chart)[chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
* [![evaler](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/soniah/evaler&show=star)](https://github.com/soniah/evaler)[evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
* [![ewma](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/ewma&show=star)](https://github.com/VividCortex/ewma)[ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
* [![geom](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/skelterjohn/geom&show=star)](https://github.com/skelterjohn/geom)[geom](https://github.com/skelterjohn/geom) - 2D geometry for golang.
* [![go-dsp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mjibson/go-dsp&show=star)](https://github.com/mjibson/go-dsp)[go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
* [![go-fn](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ematvey/go-fn&show=star)](https://github.com/ematvey/go-fn)[go-fn](https://github.com/ematvey/go-fn) - Mathematical functions written in Go language, that are not covered by math pkg.
* [![go-gt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ThePaw/go-gt&show=star)](https://github.com/ThePaw/go-gt)[go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
* [![go.matrix](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/skelterjohn/go.matrix&show=star)](https://github.com/skelterjohn/go.matrix)[go.matrix](https://github.com/skelterjohn/go.matrix) - linear algebra for go (has been stalled).
* [![gocomplex](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/varver/gocomplex&show=star)](https://github.com/varver/gocomplex)[gocomplex](https://github.com/varver/gocomplex) - Complex number library for the Go programming language.
* [![goent](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kzahedi/goent&show=star)](https://github.com/kzahedi/goent)[goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures
* [![gofrac](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/anschelsc/gofrac&show=star)](https://github.com/anschelsc/gofrac)[gofrac](https://github.com/anschelsc/gofrac) - (goinstallable) fractions library for go with support for basic arithmetic.
* [![gohistogram](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/gohistogram&show=star)](https://github.com/VividCortex/gohistogram)[gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
* [![gonum/mat64](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gonum/matrix&show=star)](https://github.com/gonum/matrix)[gonum/mat64](https://github.com/gonum/matrix) - The general purpose package for matrix computation. Package mat64 provides basic linear algebra operations for float64 matrices.
* [![gonum/plot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gonum/plot&show=star)](https://github.com/gonum/plot)[gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* [![goraph](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gyuho/goraph&show=star)](https://github.com/gyuho/goraph)[goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorith visualization).
* [![gosl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cpmech/gosl&show=star)](https://github.com/cpmech/gosl)[gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [![gostat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ematvey/gostat&show=star)](https://github.com/ematvey/gostat)[gostat](https://github.com/ematvey/gostat) - Statistics library for the go language.
* [![graph](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yourbasic/graph&show=star)](https://github.com/yourbasic/graph)[graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
* [![ode](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ChristopherRabotin/ode&show=star)](https://github.com/ChristopherRabotin/ode)[ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
* [![pagerank](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alixaxel/pagerank&show=star)](https://github.com/alixaxel/pagerank)[pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
* [![PiHex](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/claygod/PiHex&show=star)](https://github.com/claygod/PiHex)[PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
* [![sparse](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/james-bowman/sparse&show=star)](https://github.com/james-bowman/sparse)[sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
* [![stats](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/montanaflynn/stats&show=star)](https://github.com/montanaflynn/stats)[stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* [![streamtools](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nytlabs/streamtools&show=star)](https://github.com/nytlabs/streamtools)[streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
* [![vectormath](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/spate/vectormath&show=star)](https://github.com/spate/vectormath)[vectormath](https://github.com/spate/vectormath) - Vectormath for Go, an adaptation of the scalar C functions from Sony's Vector Math library, as found in the Bullet-2.79 source code (currently inactive).

## Security

*Libraries that are used to help make your application more secure.*

* [![acmetool](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hlandau/acme&show=star)](https://github.com/hlandau/acme)[acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* [![BadActor](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jaredfolkins/badactor&show=star)](https://github.com/jaredfolkins/badactor)[BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
* [![go-yara](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hillu/go-yara&show=star)](https://github.com/hillu/go-yara)[go-yara](https://github.com/hillu/go-yara) - Go Bindings for [![YARA](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/plusvic/yara&show=star)](https://github.com/plusvic/yara)[YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
* [![goSecretBoxPassword](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dwin/goSecretBoxPassword&show=star)](https://github.com/dwin/goSecretBoxPassword)[goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
* [![lego](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xenolf/lego&show=star)](https://github.com/xenolf/lego)[lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* [![memguard](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/awnumar/memguard&show=star)](https://github.com/awnumar/memguard)[memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* [![passlib](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hlandau/passlib&show=star)](https://github.com/hlandau/passlib)[passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library.
* [![secure](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/unrolled/secure&show=star)](https://github.com/unrolled/secure)[secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
* [![simple-scrypt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/elithrar/simple-scrypt&show=star)](https://github.com/elithrar/simple-scrypt)[simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
* [![ssh-vault](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ssh-vault/ssh-vault&show=star)](https://github.com/ssh-vault/ssh-vault)[ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.

## Serialization

*Libraries and tools for binary serialization.*

* [![asn1](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/PromonLogicalis/asn1&show=star)](https://github.com/PromonLogicalis/asn1)[asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
* [![bambam](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/glycerine/bambam&show=star)](https://github.com/glycerine/bambam)[bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
* [![colfer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pascaldekloe/colfer&show=star)](https://github.com/pascaldekloe/colfer)[colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
* [![go-capnproto](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/glycerine/go-capnproto&show=star)](https://github.com/glycerine/go-capnproto)[go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
* [![go-codec](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ugorji/go&show=star)](https://github.com/ugorji/go)[go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
* [![gogoprotobuf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gogo/protobuf&show=star)](https://github.com/gogo/protobuf)[gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [![goprotobuf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/golang/protobuf&show=star)](https://github.com/golang/protobuf)[goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [![jsoniter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/json-iterator/go&show=star)](https://github.com/json-iterator/go)[jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* [![mapstructure](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mitchellh/mapstructure&show=star)](https://github.com/mitchellh/mapstructure)[mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
* [![php_session_decoder](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yvasiyarov/php_session_decoder&show=star)](https://github.com/yvasiyarov/php_session_decoder)[php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
* [![structomap](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tuvistavie/structomap&show=star)](https://github.com/tuvistavie/structomap)[structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.

## Server Applications

* [![algernon](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xyproto/algernon&show=star)](https://github.com/xyproto/algernon)[algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* [![Caddy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mholt/caddy&show=star)](https://github.com/mholt/caddy)[Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [![devd](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cortesi/devd&show=star)](https://github.com/cortesi/devd)[devd](https://github.com/cortesi/devd) - Local webserver for developers.
* [![etcd](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/coreos/etcd&show=star)](https://github.com/coreos/etcd)[etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* [![Fider](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/getfider/fider&show=star)](https://github.com/getfider/fider)[Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
* [![minio](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/minio/minio&show=star)](https://github.com/minio/minio)[minio](https://github.com/minio/minio) - Minio is a distributed object storage server.
* [nsq](http://nsq.io/) - A realtime distributed messaging platform.
* [![yakvs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sci4me/yakvs&show=star)](https://github.com/sci4me/yakvs)[yakvs](https://github.com/sci4me/yakvs) - Small, networked, in-memory key-value store.

## Template Engines

*Libraries and tools for templating and lexing.*

* [![ace](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yosssi/ace&show=star)](https://github.com/yosssi/ace)[ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* [![amber](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/eknkc/amber&show=star)](https://github.com/eknkc/amber)[amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* [![damsel](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dskinner/damsel&show=star)](https://github.com/dskinner/damsel)[damsel](https://github.com/dskinner/damsel) - Markup language featuring html outlining via css-selectors, extensible via pkg html/template and others.
* [![ego](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/benbjohnson/ego&show=star)](https://github.com/benbjohnson/ego)[ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
* [![fasttemplate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/valyala/fasttemplate&show=star)](https://github.com/valyala/fasttemplate)[fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](http://golang.org/pkg/text/template/).
* [![gofpdf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jung-kurt/gofpdf&show=star)](https://github.com/jung-kurt/gofpdf)[gofpdf](https://github.com/jung-kurt/gofpdf) - PDF document generator with high level support for text, drawing and images.
* [![grender](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dannyvankooten/grender&show=star)](https://github.com/dannyvankooten/grender)[grender](https://github.com/dannyvankooten/grender) - small wrapper around html/template for file-based templates that support extending other template files.
* [![hero](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shiyanhui/hero&show=star)](https://github.com/shiyanhui/hero)[hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* [![jet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/CloudyKit/jet&show=star)](https://github.com/CloudyKit/jet)[jet](https://github.com/CloudyKit/jet) - Jet template engine.
* [![kasia.go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ziutek/kasia.go&show=star)](https://github.com/ziutek/kasia.go)[kasia.go](https://github.com/ziutek/kasia.go) - Templating system for HTML and other text documents - go implementation.
* [![liquid](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/osteele/liquid&show=star)](https://github.com/osteele/liquid)[liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
* [![mustache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hoisie/mustache&show=star)](https://github.com/hoisie/mustache)[mustache](https://github.com/hoisie/mustache) - Go implementation of the Mustache template language.
* [![pongo2](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/flosch/pongo2&show=star)](https://github.com/flosch/pongo2)[pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* [![quicktemplate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/valyala/quicktemplate&show=star)](https://github.com/valyala/quicktemplate)[quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
* [![raymond](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aymerick/raymond&show=star)](https://github.com/aymerick/raymond)[raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
* [![Razor](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sipin/gorazor&show=star)](https://github.com/sipin/gorazor)[Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang.
* [![Soy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/robfig/soy&show=star)](https://github.com/robfig/soy)[Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
* [![velvet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gobuffalo/velvet&show=star)](https://github.com/gobuffalo/velvet)[velvet](https://github.com/gobuffalo/velvet) - Complete handlebars implementation in Go.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [![assert](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/assert&show=star)](https://github.com/go-playground/assert)[assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
    * [![badio](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cavaliercoder/badio&show=star)](https://github.com/cavaliercoder/badio)[badio](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
    * [![baloo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/h2non/baloo&show=star)](https://github.com/h2non/baloo)[baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    * [![bro](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/marioidival/bro&show=star)](https://github.com/marioidival/bro)[bro](https://github.com/marioidival/bro) - Watch files in directory and run tests for them.
    * [![cupaloy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bradleyjkemp/cupaloy&show=star)](https://github.com/bradleyjkemp/cupaloy)[cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    * [![dbcleaner](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/khaiql/dbcleaner&show=star)](https://github.com/khaiql/dbcleaner)[dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
    * [![dsunit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/viant/dsunit&show=star)](https://github.com/viant/dsunit)[dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
    * [![frisby](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/verdverm/frisby&show=star)](https://github.com/verdverm/frisby)[frisby](https://github.com/verdverm/frisby) - REST API testing framework.
    * [ginkgo](http://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    * [![go-carpet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/msoap/go-carpet&show=star)](https://github.com/msoap/go-carpet)[go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
    * [![go-mutesting](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zimmski/go-mutesting&show=star)](https://github.com/zimmski/go-mutesting)[go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
    * [![go-vcr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dnaeon/go-vcr&show=star)](https://github.com/dnaeon/go-vcr)[go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    * [![goblin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/franela/goblin&show=star)](https://github.com/franela/goblin)[goblin](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
    * [gocheck](http://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    * [![GoConvey](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smartystreets/goconvey/&show=star)](https://github.com/smartystreets/goconvey/)[GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
    * [![godog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/DATA-DOG/godog&show=star)](https://github.com/DATA-DOG/godog)[godog](https://github.com/DATA-DOG/godog) - Cucumber or Behat like BDD framework for Go.
    * [![gofight](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/appleboy/gofight&show=star)](https://github.com/appleboy/gofight)[gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
    * [gomega](http://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    * [![GoSpec](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/orfjackal/gospec&show=star)](https://github.com/orfjackal/gospec)[GoSpec](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    * [![gospecify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/stesla/gospecify&show=star)](https://github.com/stesla/gospecify)[gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    * [![gosuite](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pavlo/gosuite&show=star)](https://github.com/pavlo/gosuite)[gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
    * [![Hamcrest](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rdrdr/hamcrest&show=star)](https://github.com/rdrdr/hamcrest)[Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    * [![httpexpect](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gavv/httpexpect&show=star)](https://github.com/gavv/httpexpect)[httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    * [![restit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yookoala/restit&show=star)](https://github.com/yookoala/restit)[restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    * [![testfixtures](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-testfixtures/testfixtures&show=star)](https://github.com/go-testfixtures/testfixtures)[testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    * [![Testify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/stretchr/testify&show=star)](https://github.com/stretchr/testify)[Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
    * [![wstest](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/posener/wstest&show=star)](https://github.com/posener/wstest)[wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

* Mock
    * [![counterfeiter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/maxbrunsfeld/counterfeiter&show=star)](https://github.com/maxbrunsfeld/counterfeiter)[counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
    * [![go-sqlmock](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/DATA-DOG/go-sqlmock&show=star)](https://github.com/DATA-DOG/go-sqlmock)[go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    * [![go-txdb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/DATA-DOG/go-txdb&show=star)](https://github.com/DATA-DOG/go-txdb)[go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
    * [![gock](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/h2non/gock&show=star)](https://github.com/h2non/gock)[gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
    * [![gomock](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/golang/mock&show=star)](https://github.com/golang/mock)[gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [![govcr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/seborama/govcr&show=star)](https://github.com/seborama/govcr)[govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
    * [![minimock](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gojuno/minimock&show=star)](https://github.com/gojuno/minimock)[minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
    * [![mockhttp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tv42/mockhttp&show=star)](https://github.com/tv42/mockhttp)[mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.

* Fuzzing and delta-debugging/reducing/shrinking.
    * [![go-fuzz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dvyukov/go-fuzz&show=star)](https://github.com/dvyukov/go-fuzz)[go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [![gofuzz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/gofuzz&show=star)](https://github.com/google/gofuzz)[gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.
    * [![Tavor](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zimmski/tavor&show=star)](https://github.com/zimmski/tavor)[Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

* Selenium and browser control tools.
    * [![cdp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mafredri/cdp&show=star)](https://github.com/mafredri/cdp)[cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
    * [![chromedp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/knq/chromedp&show=star)](https://github.com/knq/chromedp)[chromedp](https://github.com/knq/chromedp) - Way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    * [![ggr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aandryashin/ggr&show=star)](https://github.com/aandryashin/ggr)[ggr](https://github.com/aandryashin/ggr) - Lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs.
    * [![selenoid](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aandryashin/selenoid&show=star)](https://github.com/aandryashin/selenoid)[selenoid](https://github.com/aandryashin/selenoid) - alternative Selenium hub server that launches browsers within containers.

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [![align](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Guitarbum722/align&show=star)](https://github.com/Guitarbum722/align)[align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
    * [![allot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sbstjn/allot&show=star)](https://github.com/sbstjn/allot)[allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
    * [![bbConvert](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/CalebQ42/bbConvert&show=star)](https://github.com/CalebQ42/bbConvert)[bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
    * [![blackfriday](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/russross/blackfriday&show=star)](https://github.com/russross/blackfriday)[blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
    * [![bluemonday](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/microcosm-cc/bluemonday&show=star)](https://github.com/microcosm-cc/bluemonday)[bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
    * [![colly](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asciimoo/colly&show=star)](https://github.com/asciimoo/colly)[colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers
    * [![doi](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hscells/doi&show=star)](https://github.com/hscells/doi)[doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
    * [![editorconfig-core-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/editorconfig/editorconfig-core-go&show=star)](https://github.com/editorconfig/editorconfig-core-go)[editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
    * [![enca](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/endeveit/enca&show=star)](https://github.com/endeveit/enca)[enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](http://cihar.com/software/enca/).
    * [![genex](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alixaxel/genex&show=star)](https://github.com/alixaxel/genex)[genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [![go-humanize](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dustin/go-humanize&show=star)](https://github.com/dustin/go-humanize)[go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
    * [![go-nmea](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/adrianmo/go-nmea&show=star)](https://github.com/adrianmo/go-nmea)[go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
    * [![go-pkg-rss](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jteeuwen/go-pkg-rss&show=star)](https://github.com/jteeuwen/go-pkg-rss)[go-pkg-rss](https://github.com/jteeuwen/go-pkg-rss) - This package reads RSS and Atom feeds and provides a caching mechanism that adheres to the feed specs.
    * [![go-runewidth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattn/go-runewidth&show=star)](https://github.com/mattn/go-runewidth)[go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
    * [![go-slugify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mozillazg/go-slugify&show=star)](https://github.com/mozillazg/go-slugify)[go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
    * [![go-vcard](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/emersion/go-vcard&show=star)](https://github.com/emersion/go-vcard)[go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard.
    * [![gofeed](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mmcdole/gofeed&show=star)](https://github.com/mmcdole/gofeed)[gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
    * [![gographviz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/awalterschulze/gographviz&show=star)](https://github.com/awalterschulze/gographviz)[gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
    * [![gommon/bytes](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/labstack/gommon/tree/master/bytes&show=star)](https://github.com/labstack/gommon/tree/master/bytes)[gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - Format bytes to string.
    * [![gonameparts](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/polera/gonameparts&show=star)](https://github.com/polera/gonameparts)[gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
    * [![goq](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andrewstuart/goq&show=star)](https://github.com/andrewstuart/goq)[goq](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
    * [![GoQuery](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/PuerkitoBio/goquery&show=star)](https://github.com/PuerkitoBio/goquery)[GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
    * [![goregen](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zach-klippenstein/goregen&show=star)](https://github.com/zach-klippenstein/goregen)[goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
    * [![gotext](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/leonelquinteros/gotext&show=star)](https://github.com/leonelquinteros/gotext)[gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
    * [![guesslanguage](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/endeveit/guesslanguage&show=star)](https://github.com/endeveit/guesslanguage)[guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
    * [![inject](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/facebookgo/inject&show=star)](https://github.com/facebookgo/inject)[inject](https://github.com/facebookgo/inject) - Package inject provides a reflect based injector.
    * [![mxj](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/clbanning/mxj&show=star)](https://github.com/clbanning/mxj)[mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
    * [![sh](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mvdan/sh&show=star)](https://github.com/mvdan/sh)[sh](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [![slug](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gosimple/slug&show=star)](https://github.com/gosimple/slug)[slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
    * [![Slugify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/avelino/slugify&show=star)](https://github.com/avelino/slugify)[Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string.
    * [![toml](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/BurntSushi/toml&show=star)](https://github.com/BurntSushi/toml)[toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
    * [![gotabulate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bndr/gotabulate&show=star)](https://github.com/bndr/gotabulate)[gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
    * [![kace](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codemodus/kace&show=star)](https://github.com/codemodus/kace)[kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
    * [![parseargs-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nproc/parseargs-go&show=star)](https://github.com/nproc/parseargs-go)[parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
    * [![parth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codemodus/parth&show=star)](https://github.com/codemodus/parth)[parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
    * [![radix](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yourbasic/radix&show=star)](https://github.com/yourbasic/radix)[radix](https://github.com/yourbasic/radix) - fast string sorting algorithm.
    * [![xj2go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/stackerzzq/xj2go&show=star)](https://github.com/stackerzzq/xj2go)[xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.
    * [![xurls](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mvdan/xurls&show=star)](https://github.com/mvdan/xurls)[xurls](https://github.com/mvdan/xurls) - Extract urls from text.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [![amazon-product-advertising-api](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ngs/go-amazon-product-advertising-api&show=star)](https://github.com/ngs/go-amazon-product-advertising-api)[amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [![anaconda](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ChimeraCoder/anaconda&show=star)](https://github.com/ChimeraCoder/anaconda)[anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* [![aws-sdk-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/aws/aws-sdk-go&show=star)](https://github.com/aws/aws-sdk-go)[aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* [![brewerydb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/naegelejd/brewerydb&show=star)](https://github.com/naegelejd/brewerydb)[brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* [![cachet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andygrunwald/cachet&show=star)](https://github.com/andygrunwald/cachet)[cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [![circleci](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jszwedko/go-circleci&show=star)](https://github.com/jszwedko/go-circleci)[circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* [![clarifai](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/samuelcouch/clarifai&show=star)](https://github.com/samuelcouch/clarifai)[clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [![discordgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bwmarrin/discordgo&show=star)](https://github.com/bwmarrin/discordgo)[discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* [![ethrpc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/onrik/ethrpc&show=star)](https://github.com/onrik/ethrpc)[ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* [![facebook](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/huandu/facebook&show=star)](https://github.com/huandu/facebook)[facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* [![fcm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/maddevsio/fcm&show=star)](https://github.com/maddevsio/fcm)[fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* [![gads](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/emiddleton/gads&show=star)](https://github.com/emiddleton/gads)[gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* [![gami](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bit4bit/gami&show=star)](https://github.com/bit4bit/gami)[gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* [![gcm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Aorioli/gcm&show=star)](https://github.com/Aorioli/gcm)[gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* [![geo-golang](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codingsince1985/geo-golang&show=star)](https://github.com/codingsince1985/geo-golang)[geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](http://open.mapquestapi.com/nominatim/), [OpenCage](http://geocoder.opencagedata.com/api.html), [HERE](https://developer.here.com/rest-apis/documentation/geocoder), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [![ghost](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/neuegram/ghost&show=star)](https://github.com/neuegram/ghost)[ghost](https://github.com/neuegram/ghost) - Go Library for accessing the Snapchat API.
* [![github](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/go-github&show=star)](https://github.com/google/go-github)[github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [![githubql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shurcooL/githubql&show=star)](https://github.com/shurcooL/githubql)[githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* [![go-hacknews](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/PaulRosset/go-hacknews&show=star)](https://github.com/PaulRosset/go-hacknews)[go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* [![go-imgur](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/koffeinsource/go-imgur&show=star)](https://github.com/koffeinsource/go-imgur)[go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [![go-jira](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andygrunwald/go-jira&show=star)](https://github.com/andygrunwald/go-jira)[go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [![go-marathon](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gambol99/go-marathon&show=star)](https://github.com/gambol99/go-marathon)[go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* [![go-myanimelist](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nstratos/go-myanimelist&show=star)](https://github.com/nstratos/go-myanimelist)[go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [![go-sptrans](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sergioaugrod/go-sptrans&show=star)](https://github.com/sergioaugrod/go-sptrans)[go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [![go-telegraph](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/toby3d/go-telegraph&show=star)](https://github.com/toby3d/go-telegraph)[go-telegraph](https://github.com/toby3d/go-telegraph) - Telegraph publishing platform API client.
* [![go-tgbot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/olebedev/go-tgbot&show=star)](https://github.com/olebedev/go-tgbot)[go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.
* [![go-trending](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andygrunwald/go-trending&show=star)](https://github.com/andygrunwald/go-trending)[go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [![trending repositories](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/trending&show=star)](https://github.com/trending)[trending repositories](https://github.com/trending) and [![developers](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/trending/developers&show=star)](https://github.com/trending/developers)[developers](https://github.com/trending/developers) at Github.
* [![go-twitch](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/knspriggs/go-twitch&show=star)](https://github.com/knspriggs/go-twitch)[go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* [![go-twitter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dghubble/go-twitter&show=star)](https://github.com/dghubble/go-twitter)[go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [![go-unsplash](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hbagdi/go-unsplash&show=star)](https://github.com/hbagdi/go-unsplash)[go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [![go-xkcd](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nishanths/go-xkcd&show=star)](https://github.com/nishanths/go-xkcd)[go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* [![goamz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mitchellh/goamz&show=star)](https://github.com/mitchellh/goamz)[goamz](https://github.com/mitchellh/goamz) - Popular fork of [goamz](https://launchpad.net/goamz) which adds some missing API calls to certain packages.
* [![golyrics](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mamal72/golyrics&show=star)](https://github.com/mamal72/golyrics)[golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [![GoMusicBrainz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/michiwend/gomusicbrainz&show=star)](https://github.com/michiwend/gomusicbrainz)[GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* [![google](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/google/google-api-go-client&show=star)](https://github.com/google/google-api-go-client)[google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [![google-analytics](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chonthu/go-google-analytics&show=star)](https://github.com/chonthu/go-google-analytics)[google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* [![google-cloud](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/GoogleCloudPlatform/gcloud-golang&show=star)](https://github.com/GoogleCloudPlatform/gcloud-golang)[google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* [![google-email-audit-api](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ngs/go-google-email-audit-api&show=star)](https://github.com/ngs/go-google-email-audit-api)[google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [![gostorm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jsgilmore/gostorm&show=star)](https://github.com/jsgilmore/gostorm)[gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [![govkbot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nikepan/govkbot&show=star)](https://github.com/nikepan/govkbot)[govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
* [![hipchat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andybons/hipchat&show=star)](https://github.com/andybons/hipchat)[hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* [![hipchat (xmpp)](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/daneharrigan/hipchat&show=star)](https://github.com/daneharrigan/hipchat)[hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* [![Medium](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Medium/medium-sdk-go&show=star)](https://github.com/Medium/medium-sdk-go)[Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* [![megos](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/andygrunwald/megos&show=star)](https://github.com/andygrunwald/megos)[megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* [![micha](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/onrik/micha&show=star)](https://github.com/onrik/micha)[micha](https://github.com/onrik/micha) - Go Library for Telegram bot api.
* [![minio-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/minio/minio-go&show=star)](https://github.com/minio/minio-go)[minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* [![mixpanel](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dukex/mixpanel&show=star)](https://github.com/dukex/mixpanel)[mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [![patreon-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mxpv/patreon-go&show=star)](https://github.com/mxpv/patreon-go)[patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* [![paypal](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/logpacker/paypalsdk&show=star)](https://github.com/logpacker/paypalsdk)[paypal](https://github.com/logpacker/paypalsdk) - Wrapper for PayPal payment API.
* [![playlyfe](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/playlyfe/playlyfe-go-sdk&show=star)](https://github.com/playlyfe/playlyfe-go-sdk)[playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* [![pushover](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gregdel/pushover&show=star)](https://github.com/gregdel/pushover)[pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* [![rrdaclient](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Omie/rrdaclient&show=star)](https://github.com/Omie/rrdaclient)[rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* [![shopify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rapito/go-shopify&show=star)](https://github.com/rapito/go-shopify)[shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [![slack](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nlopes/slack&show=star)](https://github.com/nlopes/slack)[slack](https://github.com/nlopes/slack) - Slack API in Go.
* [![smite](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sergiotapia/smitego&show=star)](https://github.com/sergiotapia/smitego)[smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* [![spotify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rapito/go-spotify&show=star)](https://github.com/rapito/go-spotify)[spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [![steam](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sostronk/go-steam&show=star)](https://github.com/sostronk/go-steam)[steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* [![stripe](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/stripe/stripe-go&show=star)](https://github.com/stripe/stripe-go)[stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* [![tbot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yanzay/tbot&show=star)](https://github.com/yanzay/tbot)[tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
* [![telebot](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tucnak/telebot&show=star)](https://github.com/tucnak/telebot)[telebot](https://github.com/tucnak/telebot) - Telegram bot framework written in Go.
* [![telegram-bot-api](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Syfaro/telegram-bot-api&show=star)](https://github.com/Syfaro/telegram-bot-api)[telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
* [![textbelt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dietsche/textbelt&show=star)](https://github.com/dietsche/textbelt)[textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* [![TheMovieDb](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jbrodriguez/go-tmdb&show=star)](https://github.com/jbrodriguez/go-tmdb)[TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - Simple golang package to communicate with [themoviedb.org](https://themoviedb.org).
* [![translate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/poorny/translate&show=star)](https://github.com/poorny/translate)[translate](https://github.com/poorny/translate) - Go online translation package.
* [![Trello](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/adlio/trello&show=star)](https://github.com/adlio/trello)[Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* [![tumblr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mattcunningham/gumblr&show=star)](https://github.com/mattcunningham/gumblr)[tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* [![webhooks](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/webhooks&show=star)](https://github.com/go-playground/webhooks)[webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* [![zooz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gojuno/go-zooz&show=star)](https://github.com/gojuno/go-zooz)[zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* [![abutil](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bahlo/abutil&show=star)](https://github.com/bahlo/abutil)[abutil](https://github.com/bahlo/abutil) - Collection of often-used Golang helpers.
* [![apm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/topfreegames/apm&show=star)](https://github.com/topfreegames/apm)[apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
* [![boilr](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tmrts/boilr&show=star)](https://github.com/tmrts/boilr)[boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [![chyle](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/antham/chyle&show=star)](https://github.com/antham/chyle)[chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
* [![circuitbreaker](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rubyist/circuitbreaker&show=star)](https://github.com/rubyist/circuitbreaker)[circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
* [clockwerk](http://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
* [![command](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/txgruppi/command&show=star)](https://github.com/txgruppi/command)[command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
* [![coop](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rakyll/coop&show=star)](https://github.com/rakyll/coop)[coop](https://github.com/rakyll/coop) - Cheat sheet for some of the common concurrent flows in Go.
* [![copy-pasta](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jutkko/copy-pasta&show=star)](https://github.com/jutkko/copy-pasta)[copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
* [![ctop](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bcicen/ctop&show=star)](https://github.com/bcicen/ctop)[ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [![Death](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vrecan/death&show=star)](https://github.com/vrecan/death)[Death](https://github.com/vrecan/death) - Managing go application shutdown with signals.
* [![Deepcopier](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ulule/deepcopier&show=star)](https://github.com/ulule/deepcopier)[Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
* [![delve](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/derekparker/delve&show=star)](https://github.com/derekparker/delve)[delve](https://github.com/derekparker/delve) - Go debugger.
* [![dlog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kirillDanshin/dlog&show=star)](https://github.com/kirillDanshin/dlog)[dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
* [![ergo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cristianoliveira/ergo&show=star)](https://github.com/cristianoliveira/ergo)[ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* [![evaluator](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nullne/evaluator&show=star)](https://github.com/nullne/evaluator)[evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* [![excelize](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/360EntSecGroup-Skylar/excelize&show=star)](https://github.com/360EntSecGroup-Skylar/excelize)[excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [![fastlz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/digitalcrab/fastlz&show=star)](https://github.com/digitalcrab/fastlz)[fastlz](https://github.com/digitalcrab/fastlz) - Wrap over [FastLz](http://fastlz.org/) (free, open-source, portable real-time compression library) for GoLang.
* [![filetype](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/h2non/filetype&show=star)](https://github.com/h2non/filetype)[filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [![filler](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yaronsumel/filler&show=star)](https://github.com/yaronsumel/filler)[filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
* [![fzf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/junegunn/fzf&show=star)](https://github.com/junegunn/fzf)[fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [![generate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/generate&show=star)](https://github.com/go-playground/generate)[generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
* [![gentleman](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/h2non/gentleman&show=star)](https://github.com/h2non/gentleman)[gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
* [![git-time-metric](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/git-time-metric/gtm&show=star)](https://github.com/git-time-metric/gtm)[git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
* [![GJSON](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tidwall/gjson&show=star)](https://github.com/tidwall/gjson)[GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [![go-astitodo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asticode/go-astitodo&show=star)](https://github.com/asticode/go-astitodo)[go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
* [![go-bind-plugin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wendigo/go-bind-plugin&show=star)](https://github.com/wendigo/go-bind-plugin)[go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
* [![go-cron](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rk/go-cron&show=star)](https://github.com/rk/go-cron)[go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
* [![go-debug](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tj/go-debug&show=star)](https://github.com/tj/go-debug)[go-debug](https://github.com/tj/go-debug) - Conditional debug logging for Golang libraries & applications.
* [![go-dry](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ungerik/go-dry&show=star)](https://github.com/ungerik/go-dry)[go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
* [![go-funk](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/thoas/go-funk&show=star)](https://github.com/thoas/go-funk)[go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [![go-httpheader](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mozillazg/go-httpheader&show=star)](https://github.com/mozillazg/go-httpheader)[go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
* [![go-rate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/beefsack/go-rate&show=star)](https://github.com/beefsack/go-rate)[go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
* [![go-respond](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nicklaw5/go-respond&show=star)](https://github.com/nicklaw5/go-respond)[go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
* [![go-sitemap-generator](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ikeikeikeike/go-sitemap-generator&show=star)](https://github.com/ikeikeikeike/go-sitemap-generator)[go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
* [![go-torch](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/uber/go-torch&show=star)](https://github.com/uber/go-torch)[go-torch](https://github.com/uber/go-torch) - Stochastic flame graph profiler for Go programs.
* [![go-trigger](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sadlil/go-trigger&show=star)](https://github.com/sadlil/go-trigger)[go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
* [![go-underscore](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tobyhede/go-underscore&show=star)](https://github.com/tobyhede/go-underscore)[go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
* [![goback](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/carlescere/goback&show=star)](https://github.com/carlescere/goback)[goback](https://github.com/carlescere/goback) - Go simple exponential backoff package.
* [![godaemon](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/godaemon&show=star)](https://github.com/VividCortex/godaemon)[godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons.
* [![godropbox](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dropbox/godropbox&show=star)](https://github.com/dropbox/godropbox)[godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [![gohper](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cosiner/gohper&show=star)](https://github.com/cosiner/gohper)[gohper](https://github.com/cosiner/gohper) - Various tools/modules help for development.
* [![gojq](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/elgs/gojq&show=star)](https://github.com/elgs/gojq)[gojq](https://github.com/elgs/gojq) - JSON query in Golang.
* [![gojson](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ChimeraCoder/gojson&show=star)](https://github.com/ChimeraCoder/gojson)[gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
* [![golarm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/msempere/golarm&show=star)](https://github.com/msempere/golarm)[golarm](https://github.com/msempere/golarm) - Fire alarms with system events.
* [![golog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mlimaloureiro/golog&show=star)](https://github.com/mlimaloureiro/golog)[golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
* [![gopencils](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bndr/gopencils&show=star)](https://github.com/bndr/gopencils)[gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
* [![goplaceholder](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/michiwend/goplaceholder&show=star)](https://github.com/michiwend/goplaceholder)[goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
* [![goreleaser](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goreleaser/goreleaser&show=star)](https://github.com/goreleaser/goreleaser)[goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [![goreporter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wgliang/goreporter&show=star)](https://github.com/wgliang/goreporter)[goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [![goreq](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/franela/goreq&show=star)](https://github.com/franela/goreq)[goreq](https://github.com/franela/goreq) - Minimal and simple request library for Go language.
* [![goreq](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smallnest/goreq&show=star)](https://github.com/smallnest/goreq)[goreq](https://github.com/smallnest/goreq) - Enhanced simplified HTTP client based on gorequest.
* [![gorequest](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/parnurzeal/gorequest&show=star)](https://github.com/parnurzeal/gorequest)[gorequest](https://github.com/parnurzeal/gorequest) - Simplified HTTP client with rich features for Go.
* [![goseaweedfs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/linxGnu/goseaweedfs&show=star)](https://github.com/linxGnu/goseaweedfs)[goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
* [![gotenv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/subosito/gotenv&show=star)](https://github.com/subosito/gotenv)[gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
* [![goxlsxwriter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fterrag/goxlsxwriter&show=star)](https://github.com/fterrag/goxlsxwriter)[goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
* [![gpath](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tenntenn/gpath&show=star)](https://github.com/tenntenn/gpath)[gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
* [![grequests](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/levigross/grequests&show=star)](https://github.com/levigross/grequests)[grequests](https://github.com/levigross/grequests) - Elegant and simple `net/http` wrapper that follows Python's requests library.
* [![gron](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/roylee0704/gron&show=star)](https://github.com/roylee0704/gron)[gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [![htcat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/htcat/htcat&show=star)](https://github.com/htcat/htcat)[htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
* [![httpcontrol](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/facebookgo/httpcontrol&show=star)](https://github.com/facebookgo/httpcontrol)[httpcontrol](https://github.com/facebookgo/httpcontrol) - Package httpcontrol allows for HTTP transport level control around timeouts and retries.
* [![hub](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/github/hub&show=star)](https://github.com/github/hub)[hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [![hystrix-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/afex/hystrix-go&show=star)](https://github.com/afex/hystrix-go)[hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [![immortal](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/immortal/immortal&show=star)](https://github.com/immortal/immortal)[immortal](https://github.com/immortal/immortal) - *nix cross-platform (OS agnostic) supervisor.
* [![intrinsic](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mengzhuo/intrinsic&show=star)](https://github.com/mengzhuo/intrinsic)[intrinsic](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
* [![JobRunner](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bamzi/jobrunner&show=star)](https://github.com/bamzi/jobrunner)[JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
* [![jsonapi-errors](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/AmuzaTkts/jsonapi-errors&show=star)](https://github.com/AmuzaTkts/jsonapi-errors)[jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
* [![jsonf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/miolini/jsonf&show=star)](https://github.com/miolini/jsonf)[jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
* [![jsongo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ricardolonga/jsongo&show=star)](https://github.com/ricardolonga/jsongo)[jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
* [![jsonhal](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/RichardKnop/jsonhal&show=star)](https://github.com/RichardKnop/jsonhal)[jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
* [![kazaam](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Qntfy/kazaam&show=star)](https://github.com/Qntfy/kazaam)[kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
* [![lrserver](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jaschaephraim/lrserver&show=star)](https://github.com/jaschaephraim/lrserver)[lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
* [![mc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/minio/mc&show=star)](https://github.com/minio/mc)[mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
* [![mergo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/imdario/mergo&show=star)](https://github.com/imdario/mergo)[mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
* [![minify](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tdewolff/minify&show=star)](https://github.com/tdewolff/minify)[minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
* [![mmake](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tj/mmake&show=star)](https://github.com/tj/mmake)[mmake](https://github.com/tj/mmake) - Modern Make.
* [![moldova](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/StabbyCutyou/moldova&show=star)](https://github.com/StabbyCutyou/moldova)[moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
* [![mp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sanbornm/mp&show=star)](https://github.com/sanbornm/mp)[mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
* [![mssqlx](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/linxGnu/mssqlx&show=star)](https://github.com/linxGnu/mssqlx)[mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
* [![multitick](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/multitick&show=star)](https://github.com/VividCortex/multitick)[multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
* [![myhttp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/inancgumus/myhttp&show=star)](https://github.com/inancgumus/myhttp)[myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
* [![netbug](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/e-dard/netbug&show=star)](https://github.com/e-dard/netbug)[netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
* [![ngrok](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/inconshreveable/ngrok&show=star)](https://github.com/inconshreveable/ngrok)[ngrok](https://github.com/inconshreveable/ngrok) - Introspected tunnels to localhost.
* [![okrun](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xta/okrun&show=star)](https://github.com/xta/okrun)[okrun](https://github.com/xta/okrun) - go run error steamroller.
* [![onecache](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/adelowo/onecache&show=star)](https://github.com/adelowo/onecache)[onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
* [![panicparse](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/maruel/panicparse&show=star)](https://github.com/maruel/panicparse)[panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [![peco](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/peco/peco&show=star)](https://github.com/peco/peco)[peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [![pester](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sethgrid/pester&show=star)](https://github.com/sethgrid/pester)[pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
* [![pm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/pm&show=star)](https://github.com/VividCortex/pm)[pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
* [![profile](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pkg/profile&show=star)](https://github.com/pkg/profile)[profile](https://github.com/pkg/profile) - Simple profiling support package for Go.
* [![rclient](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zpatrick/rclient&show=star)](https://github.com/zpatrick/rclient)[rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
* [![realize](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tockins/realize&show=star)](https://github.com/tockins/realize)[realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [![request](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mozillazg/request&show=star)](https://github.com/mozillazg/request)[request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
* [![rerate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/abo/rerate&show=star)](https://github.com/abo/rerate)[rerate](https://github.com/abo/rerate) - Redis-based rate counter and rate limiter for Go.
* [![rerun](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ivpusic/rerun&show=star)](https://github.com/ivpusic/rerun)[rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
* [![resty](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-resty/resty&show=star)](https://github.com/go-resty/resty)[resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
* [![retry](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kamilsk/retry&show=star)](https://github.com/kamilsk/retry)[retry](https://github.com/kamilsk/retry) - Functional mechanism based on context to perform actions repetitively until successful.
* [![robustly](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/robustly&show=star)](https://github.com/VividCortex/robustly)[robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
* [![scheduler](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/carlescere/scheduler&show=star)](https://github.com/carlescere/scheduler)[scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
* [![sling](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dghubble/sling&show=star)](https://github.com/dghubble/sling)[sling](https://github.com/dghubble/sling) - Go HTTP requests builder for API clients.
* [![spinner](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/briandowns/spinner&show=star)](https://github.com/briandowns/spinner)[spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [![sqlx](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jmoiron/sqlx&show=star)](https://github.com/jmoiron/sqlx)[sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [![Storm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asdine/storm&show=star)](https://github.com/asdine/storm)[Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [![structs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/PumpkinSeed/structs&show=star)](https://github.com/PumpkinSeed/structs)[structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
* [![Task](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-task/task&show=star)](https://github.com/go-task/task)[Task](https://github.com/go-task/task) - simple "Make" alternative.
* [![toolbox](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/viant/toolbox&show=star)](https://github.com/viant/toolbox)[toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
* [![ugo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alxrm/ugo&show=star)](https://github.com/alxrm/ugo)[ugo](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
* [![UNIS](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/esemplastic/unis&show=star)](https://github.com/esemplastic/unis)[UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
* [![usql](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/knq/usql&show=star)](https://github.com/knq/usql)[usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [![util](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shomali11/util&show=star)](https://github.com/shomali11/util)[util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
* [![wuzz](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asciimoo/wuzz&show=star)](https://github.com/asciimoo/wuzz)[wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
* [![xferspdy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/monmohan/xferspdy&show=star)](https://github.com/monmohan/xferspdy)[xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.
* [![xlsx](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tealeg/xlsx&show=star)](https://github.com/tealeg/xlsx)[xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.

## Validation

*Libraries for validation.*

* [![govalidator](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asaskevich/govalidator&show=star)](https://github.com/asaskevich/govalidator)[govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* [![govalidator](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/thedevsaddam/govalidator&show=star)](https://github.com/thedevsaddam/govalidator)[govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* [![ozzo-validation](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-ozzo/ozzo-validation&show=star)](https://github.com/go-ozzo/ozzo-validation)[ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [![validate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/markbates/validate&show=star)](https://github.com/markbates/validate)[validate](https://github.com/markbates/validate) - This package provides a framework for writing validations for Go applications.
* [![validator](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/validator&show=star)](https://github.com/go-playground/validator)[validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.

## Version Control

*Libraries for version control.*

* [![gh](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rjeczalik/gh&show=star)](https://github.com/rjeczalik/gh)[gh](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
* [![git2go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/libgit2/git2go&show=star)](https://github.com/libgit2/git2go)[git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* [![go-vcs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sourcegraph/go-vcs&show=star)](https://github.com/sourcegraph/go-vcs)[go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
* [![hgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/beyang/hgo&show=star)](https://github.com/beyang/hgo)[hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

## Video

*Libraries for manipulating video.*

* [![gmf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/3d0c/gmf&show=star)](https://github.com/3d0c/gmf)[gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* [![go-astisub](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/asticode/go-astisub&show=star)](https://github.com/asticode/go-astisub)[go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
* [![goav](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/giorgisio/goav&show=star)](https://github.com/giorgisio/goav)[goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.
* [![gst](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ziutek/gst&show=star)](https://github.com/ziutek/gst)[gst](https://github.com/ziutek/gst) - Go bindings for GStreamer.
* [![libgosubs](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wargarblgarbl/libgosubs&show=star)](https://github.com/wargarblgarbl/libgosubs)[libgosubs](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
* [![v4l](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/korandiz/v4l&show=star)](https://github.com/korandiz/v4l)[v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

## Web Frameworks

*Full stack web frameworks.*

* [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
* [![Air](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sheng/air&show=star)](https://github.com/sheng/air)[Air](https://github.com/sheng/air) - Ideal RESTful web framework for Go.
* [![Beego](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/astaxie/beego&show=star)](https://github.com/astaxie/beego)[Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [![Echo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/labstack/echo&show=star)](https://github.com/labstack/echo)[Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* [![Fireball](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zpatrick/fireball&show=star)](https://github.com/zpatrick/fireball)[Fireball](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
* [![Florest](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jabong/florest-core&show=star)](https://github.com/jabong/florest-core)[Florest](https://github.com/jabong/florest-core) - High-performance workflow based REST API framework.
* [![Gem](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gem/gem&show=star)](https://github.com/go-gem/gem)[Gem](https://github.com/go-gem/gem) - Simple and fast web framework, friendly to REST API.
* [![Gin](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gin-gonic/gin&show=star)](https://github.com/gin-gonic/gin)[Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [![Gizmo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/NYTimes/gizmo&show=star)](https://github.com/NYTimes/gizmo)[Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* [![go-json-rest](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ant0ine/go-json-rest&show=star)](https://github.com/ant0ine/go-json-rest)[go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [![go-relax](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codehack/go-relax&show=star)](https://github.com/codehack/go-relax)[go-relax](https://github.com/codehack/go-relax) - Framework of pluggable components to build RESTful API's.
* [![go-rest](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ungerik/go-rest&show=star)](https://github.com/ungerik/go-rest)[go-rest](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
* [![goa](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/raphael/goa&show=star)](https://github.com/raphael/goa)[goa](https://github.com/raphael/goa) - Framework for developing microservices based on the design of Ruby's Praxis.
* [![Goat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bahlo/goat&show=star)](https://github.com/bahlo/goat)[Goat](https://github.com/bahlo/goat) - Minimalistic REST API server in Go.
* [![Golf](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dinever/golf&show=star)](https://github.com/dinever/golf)[Golf](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
* [![Gondola](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rainycape/gondola&show=star)](https://github.com/rainycape/gondola)[Gondola](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
* [![gongular](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mustafaakin/gongular&show=star)](https://github.com/mustafaakin/gongular)[gongular](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
* [![Macaron](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-macaron/macaron&show=star)](https://github.com/go-macaron/macaron)[Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* [![mango](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/paulbellamy/mango&show=star)](https://github.com/paulbellamy/mango)[mango](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
* [![Microservice](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/claygod/microservice&show=star)](https://github.com/claygod/microservice)[Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
* [![neo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ivpusic/neo&show=star)](https://github.com/ivpusic/neo)[neo](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
* [![Resoursea](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/resoursea/api&show=star)](https://github.com/resoursea/api)[Resoursea](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
* [REST Layer](http://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
* [![Revel](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/revel/revel&show=star)](https://github.com/revel/revel)[Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* [![rex](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goanywhere/rex&show=star)](https://github.com/goanywhere/rex)[rex](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
* [![sawsij](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jaybill/sawsij&show=star)](https://github.com/jaybill/sawsij)[sawsij](https://github.com/jaybill/sawsij) - lightweight, open-source web framework for building high-performance, data-driven web applications.
* [![tango](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/lunny/tango&show=star)](https://github.com/lunny/tango)[tango](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
* [![tigertonic](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rcrowley/go-tigertonic&show=star)](https://github.com/rcrowley/go-tigertonic)[tigertonic](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
* [![traffic](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pilu/traffic&show=star)](https://github.com/pilu/traffic)[traffic](https://github.com/pilu/traffic) - Sinatra inspired regexp/pattern mux and web framework for Go.
* [![utron](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gernest/utron&show=star)](https://github.com/gernest/utron)[utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
* [![violetear](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nbari/violetear&show=star)](https://github.com/nbari/violetear)[violetear](https://github.com/nbari/violetear) - Go HTTP router.
* [![YARF](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yarf-framework/yarf&show=star)](https://github.com/yarf-framework/yarf)[YARF](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
* [![Zerver](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cosiner/zerver&show=star)](https://github.com/cosiner/zerver)[Zerver](https://github.com/cosiner/zerver) - Zerver is an expressive, modular, feature completed RESTful framework.

### Middlewares

#### Actual middlewares

* [![CORS](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rs/cors&show=star)](https://github.com/rs/cors)[CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* [![formjson](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rs/formjson&show=star)](https://github.com/rs/formjson)[formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
* [![Limiter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ulule/limiter&show=star)](https://github.com/ulule/limiter)[Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [![Tollbooth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/didip/tollbooth&show=star)](https://github.com/didip/tollbooth)[Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
* [![XFF](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sebest/xff&show=star)](https://github.com/sebest/xff)[XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

* [![alice](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/justinas/alice&show=star)](https://github.com/justinas/alice)[alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* [![catena](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codemodus/catena&show=star)](https://github.com/codemodus/catena)[catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
* [![chain](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codemodus/chain&show=star)](https://github.com/codemodus/chain)[chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
* [![go-wrap](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-on/wrap&show=star)](https://github.com/go-on/wrap)[go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.
* [![gores](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alioygur/gores&show=star)](https://github.com/alioygur/gores)[gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
* [![interpose](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/carbocation/interpose&show=star)](https://github.com/carbocation/interpose)[interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
* [![muxchain](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/stephens2424/muxchain&show=star)](https://github.com/stephens2424/muxchain)[muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
* [![negroni](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/urfave/negroni&show=star)](https://github.com/urfave/negroni)[negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* [![render](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/unrolled/render&show=star)](https://github.com/unrolled/render)[render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
* [![renderer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/thedevsaddam/renderer&show=star)](https://github.com/thedevsaddam/renderer)[renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
* [![rye](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/InVisionApp/rye&show=star)](https://github.com/InVisionApp/rye)[rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
* [![stats](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/thoas/stats&show=star)](https://github.com/thoas/stats)[stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.
* [![Volatile](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/volatile/core&show=star)](https://github.com/volatile/core)[Volatile](https://github.com/volatile/core) - Minimalist middleware stack promoting flexibility, good practices and clean code.

### Routers

* [![alien](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gernest/alien&show=star)](https://github.com/gernest/alien)[alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
* [![Bone](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-zoo/bone&show=star)](https://github.com/go-zoo/bone)[Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* [![Bxog](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/claygod/Bxog&show=star)](https://github.com/claygod/Bxog)[Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
* [![chi](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-chi/chi&show=star)](https://github.com/go-chi/chi)[chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* [![fasthttprouter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/buaazp/fasthttprouter&show=star)](https://github.com/buaazp/fasthttprouter)[fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [![FastRouter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/razonyang/fastrouter&show=star)](https://github.com/razonyang/fastrouter)[FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
* [![gocraft/web](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gocraft/web&show=star)](https://github.com/gocraft/web)[gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
* [![Goji](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goji/goji&show=star)](https://github.com/goji/goji)[Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
* [![GoRouter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/vardius/gorouter&show=star)](https://github.com/vardius/gorouter)[GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framwework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
* [![gowww/router](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gowww/router&show=star)](https://github.com/gowww/router)[gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
* [![httprouter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/julienschmidt/httprouter&show=star)](https://github.com/julienschmidt/httprouter)[httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [![httptreemux](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dimfeld/httptreemux&show=star)](https://github.com/dimfeld/httptreemux)[httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
* [![lars](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/lars&show=star)](https://github.com/go-playground/lars)[lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
* [![medeina](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/imdario/medeina&show=star)](https://github.com/imdario/medeina)[medeina](https://github.com/imdario/medeina) - Medeina is a HTTP routing tree based on HttpRouter, inspired by Roda and Cuba.
* [![mux](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gorilla/mux&show=star)](https://github.com/gorilla/mux)[mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
* [![ozzo-routing](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-ozzo/ozzo-routing&show=star)](https://github.com/go-ozzo/ozzo-routing)[ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
* [![pat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bmizerany/pat&show=star)](https://github.com/bmizerany/pat)[pat](https://github.com/bmizerany/pat) - Sinatra style pattern muxer for Go’s net/http library, by the author of Sinatra.
* [![pure](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-playground/pure&show=star)](https://github.com/go-playground/pure)[pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
* [![Siesta](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VividCortex/siesta&show=star)](https://github.com/VividCortex/siesta)[Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
* [![vestigo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/husobee/vestigo&show=star)](https://github.com/husobee/vestigo)[vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
* [![xmux](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rs/xmux&show=star)](https://github.com/rs/xmux)[xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
* [![zeus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/daryl/zeus&show=star)](https://github.com/daryl/zeus)[zeus](https://github.com/daryl/zeus) - Very simple and fast HTTP router for Go.

## Windows

* [![d3d9](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gonutz/d3d9&show=star)](https://github.com/gonutz/d3d9)[d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
* [![go-ole](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-ole/go-ole&show=star)](https://github.com/go-ole/go-ole)[go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.

## XML

*Libraries and tools for manipulating XML.*

* [![go-pkg-xmlx](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jteeuwen/go-pkg-xmlx&show=star)](https://github.com/jteeuwen/go-pkg-xmlx)[go-pkg-xmlx](https://github.com/jteeuwen/go-pkg-xmlx) - Extension to the standard Go XML package. Maintains a node tree that allows forward/backwards browsing and exposes some simple single/multi-node search functions.
* [![XML-Comp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xml-comp/xml-comp&show=star)](https://github.com/xml-comp/xml-comp)[XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
* [![xmlwriter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shabbyrobe/xmlwriter&show=star)](https://github.com/shabbyrobe/xmlwriter)[xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
* [![xpath](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/antchfx/xpath&show=star)](https://github.com/antchfx/xpath)[xpath](https://github.com/antchfx/xpath) - XPath package for Go.
* [![xquery](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/antchfx/xquery&show=star)](https://github.com/antchfx/xquery)[xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.

# Tools

*Go software and plugins.*

## Code Analysis

* [![apicompat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bradleyfalzon/apicompat&show=star)](https://github.com/bradleyfalzon/apicompat)[apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
* [![dupl](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mibk/dupl&show=star)](https://github.com/mibk/dupl)[dupl](https://github.com/mibk/dupl) - Tool for code clone detection.
* [![errcheck](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kisielk/errcheck&show=star)](https://github.com/kisielk/errcheck)[errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [![gcvis](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/davecheney/gcvis&show=star)](https://github.com/davecheney/gcvis)[gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [![Go Metalinter](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alecthomas/gometalinter&show=star)](https://github.com/alecthomas/gometalinter)[Go Metalinter](https://github.com/alecthomas/gometalinter) - Metalinter is a tool to automatically apply all static analysis tool and report their output in normalized form.
* [![go-checkstyle](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/qiniu/checkstyle&show=star)](https://github.com/qiniu/checkstyle)[go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style refered to some points in Go Code Review Comments.
* [![go-cleanarch](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/roblaszczak/go-cleanarch&show=star)](https://github.com/roblaszczak/go-cleanarch)[go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
* [![go-outdated](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/firstrow/go-outdated&show=star)](https://github.com/firstrow/go-outdated)[go-outdated](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
* [![goast-viewer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yuroyoro/goast-viewer&show=star)](https://github.com/yuroyoro/goast-viewer)[goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
* [GoCover.io](http://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
* [![GoLint](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/golang/lint&show=star)](https://github.com/golang/lint)[GoLint](https://github.com/golang/lint) - Golint is a linter for Go source code.
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
* [![gosimple](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dominikh/go-tools/tree/master/cmd/gosimple&show=star)](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple)[gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
* [![gostatus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shurcooL/gostatus&show=star)](https://github.com/shurcooL/gostatus)[gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
* [![interfacer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mvdan/interfacer&show=star)](https://github.com/mvdan/interfacer)[interfacer](https://github.com/mvdan/interfacer) - Linter that suggests interface types.
* [![lint](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/surullabs/lint&show=star)](https://github.com/surullabs/lint)[lint](https://github.com/surullabs/lint) - Run linters as part of go test.
* [![staticcheck](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck&show=star)](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck)[staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
* [![tarp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/verygoodsoftwarenotvirus/tarp&show=star)](https://github.com/verygoodsoftwarenotvirus/tarp)[tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
* [![unconvert](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mdempsky/unconvert&show=star)](https://github.com/mdempsky/unconvert)[unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
* [![unused](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dominikh/go-tools/tree/master/cmd/unused&show=star)](https://github.com/dominikh/go-tools/tree/master/cmd/unused)[unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
* [![validate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mccoyst/validate&show=star)](https://github.com/mccoyst/validate)[validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [![go-mode](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dominikh/go-mode.el&show=star)](https://github.com/dominikh/go-mode.el)[go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [![go-plus](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/joefitzgerald/go-plus&show=star)](https://github.com/joefitzgerald/go-plus)[go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [![Goclipse](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/GoClipse/goclipse&show=star)](https://github.com/GoClipse/goclipse)[Goclipse](https://github.com/GoClipse/goclipse) - Eclipse plugin for Go.
* [![gocode](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/nsf/gocode&show=star)](https://github.com/nsf/gocode)[gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* [![GoSublime](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/DisposaBoy/GoSublime&show=star)](https://github.com/DisposaBoy/GoSublime)[GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 2 providing code completion and other IDE-like features.
* [![velour](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/velour/velour&show=star)](https://github.com/velour/velour)[velour](https://github.com/velour/velour) - IRC client for the acme editor.
* [![vim-compiler-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rjohnsondev/vim-compiler-go&show=star)](https://github.com/rjohnsondev/vim-compiler-go)[vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [![vim-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fatih/vim-go&show=star)](https://github.com/fatih/vim-go)[vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [![vscode-go](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/Microsoft/vscode-go&show=star)](https://github.com/Microsoft/vscode-go)[vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [![Watch](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/eaburns/Watch&show=star)](https://github.com/eaburns/Watch)[Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Generate Tools

* [![generic](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/usk81/generic&show=star)](https://github.com/usk81/generic)[generic](https://github.com/usk81/generic) - flexible data type for Go.
* [![genny](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cheekybits/genny&show=star)](https://github.com/cheekybits/genny)[genny](https://github.com/cheekybits/genny) - Elegant generics for Go.
* [gonerics](http://github.com/bouk/gonerics) - Idiomatic Generics in Go.
* [![gotests](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cweill/gotests&show=star)](https://github.com/cweill/gotests)[gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.
* [![re2dfa](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/opennota/re2dfa&show=star)](https://github.com/opennota/re2dfa)[re2dfa](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.

## Go Tools

* [![colorgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/songgao/colorgo&show=star)](https://github.com/songgao/colorgo)[colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
* [![depth](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/KyleBanks/depth&show=star)](https://github.com/KyleBanks/depth)[depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
* [gb](https://getgb.io/) - An easy to use project based build tool for the Go programming language.
* [![go-callvis](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/TrueFurby/go-callvis&show=star)](https://github.com/TrueFurby/go-callvis)[go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* [![go-pkg-complete](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/skelterjohn/go-pkg-complete&show=star)](https://github.com/skelterjohn/go-pkg-complete)[go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
* [![go-swagger](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-swagger/go-swagger&show=star)](https://github.com/go-swagger/go-swagger)[go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [![OctoLinker](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/OctoLinker/browser-extension&show=star)](https://github.com/OctoLinker/browser-extension)[OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
* [![richgo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kyoh86/richgo&show=star)](https://github.com/kyoh86/richgo)[richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
* [![rts](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/galeone/rts&show=star)](https://github.com/galeone/rts)[rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.

## Software Packages

*Software written in Go.*

### DevOps Tools

* [![aptly](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smira/aptly&show=star)](https://github.com/smira/aptly)[aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
* [![aurora](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/xuri/aurora&show=star)](https://github.com/xuri/aurora)[aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
* [![awsenv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/soniah/awsenv&show=star)](https://github.com/soniah/awsenv)[awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
* [![Banshee](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/eleme/banshee&show=star)](https://github.com/eleme/banshee)[Banshee](https://github.com/eleme/banshee) - Anomalies detection system for periodic metrics.
* [![bombardier](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/codesenberg/bombardier&show=star)](https://github.com/codesenberg/bombardier)[bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* [![bosun](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bosun-monitor/bosun&show=star)](https://github.com/bosun-monitor/bosun)[bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [![dogo](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/liudng/dogo&show=star)](https://github.com/liudng/dogo)[dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
* [![drone-jenkins](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/appleboy/drone-jenkins&show=star)](https://github.com/appleboy/drone-jenkins)[drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
* [![drone-scp](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/appleboy/drone-scp&show=star)](https://github.com/appleboy/drone-scp)[drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
* [![Dropship](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chrismckenzie/dropship&show=star)](https://github.com/chrismckenzie/dropship)[Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
* [![easyssh-proxy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/appleboy/easyssh-proxy&show=star)](https://github.com/appleboy/easyssh-proxy)[easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
* [![Gitea](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/go-gitea/gitea&show=star)](https://github.com/go-gitea/gitea)[Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [![Go Metrics](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rcrowley/go-metrics&show=star)](https://github.com/rcrowley/go-metrics)[Go Metrics](https://github.com/rcrowley/go-metrics) - Go port of Coda Hale's Metrics library: https://github.com/codahale/metrics.
* [![go-selfupdate](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sanbornm/go-selfupdate&show=star)](https://github.com/sanbornm/go-selfupdate)[go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
* [![gobrew](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/cryptojuice/gobrew&show=star)](https://github.com/cryptojuice/gobrew)[gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
* [![godbg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sirnewton01/godbg&show=star)](https://github.com/sirnewton01/godbg)[godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [![gonative](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/inconshreveable/gonative&show=star)](https://github.com/inconshreveable/gonative)[gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
* [![govvv](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ahmetalpbalkan/govvv&show=star)](https://github.com/ahmetalpbalkan/govvv)[govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
* [![gox](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mitchellh/gox&show=star)](https://github.com/mitchellh/gox)[gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* [![goxc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/laher/goxc&show=star)](https://github.com/laher/goxc)[goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [![grapes](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yaronsumel/grapes&show=star)](https://github.com/yaronsumel/grapes)[grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
* [![GVM](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/moovweb/gvm&show=star)](https://github.com/moovweb/gvm)[GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [![Hey](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rakyll/hey&show=star)](https://github.com/rakyll/hey)[Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* [![kala](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ajvb/kala&show=star)](https://github.com/ajvb/kala)[kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
* [![kubernetes](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kubernetes/kubernetes&show=star)](https://github.com/kubernetes/kubernetes)[kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [![Moby](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/moby/moby&show=star)](https://github.com/moby/moby)[Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [![Mora](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/emicklei/mora&show=star)](https://github.com/emicklei/mora)[Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
* [![ostent](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ostrost/ostent&show=star)](https://github.com/ostrost/ostent)[ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
* [![Packer](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mitchellh/packer&show=star)](https://github.com/mitchellh/packer)[Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [![Pewpew](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/bengadbois/pewpew&show=star)](https://github.com/bengadbois/pewpew)[Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
* [![Rodent](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alouche/rodent&show=star)](https://github.com/alouche/rodent)[Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
* [![s3gof3r](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rlmcpherson/s3gof3r&show=star)](https://github.com/rlmcpherson/s3gof3r)[s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
* [![Scaleway-cli](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/scaleway/scaleway-cli&show=star)](https://github.com/scaleway/scaleway-cli)[Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
* [![sg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ChristopherRabotin/sg&show=star)](https://github.com/ChristopherRabotin/sg)[sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the reponse code and data between each call for specific server stress based on its previous response.
* [![skm](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/TimothyYe/skm&show=star)](https://github.com/TimothyYe/skm)[skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
* [![StatusOK](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/sanathp/statusok&show=star)](https://github.com/sanathp/statusok)[StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [![Vegeta](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tsenart/vegeta&show=star)](https://github.com/tsenart/vegeta)[Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [![webhook](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/adnanh/webhook&show=star)](https://github.com/adnanh/webhook)[webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
* [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
* [![winrm-cli](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/masterzen/winrm-cli&show=star)](https://github.com/masterzen/winrm-cli)[winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

### Other Software
* [![borg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/crufter/borg&show=star)](https://github.com/crufter/borg)[borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* [![boxed](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tejo/boxed&show=star)](https://github.com/tejo/boxed)[boxed](https://github.com/tejo/boxed) - Dropbox based blog engine.
* [![Cherry](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/rafael-santiago/cherry&show=star)](https://github.com/rafael-santiago/cherry)[Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
* [![Circuit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gocircuit/circuit&show=star)](https://github.com/gocircuit/circuit)[Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [![Comcast](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tylertreat/Comcast&show=star)](https://github.com/tylertreat/Comcast)[Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [![confd](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kelseyhightower/confd&show=star)](https://github.com/kelseyhightower/confd)[confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [![DDNS](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/skibish/ddns&show=star)](https://github.com/skibish/ddns)[DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [![Documize](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/documize/community&show=star)](https://github.com/documize/community)[Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
* [![fleet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/coreos/fleet&show=star)](https://github.com/coreos/fleet)[fleet](https://github.com/coreos/fleet) - Distributed init System.
* [![Go Package Store](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shurcooL/Go-Package-Store&show=star)](https://github.com/shurcooL/Go-Package-Store)[Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
* [![gocc](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/goccmack/gocc&show=star)](https://github.com/goccmack/gocc)[gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
* [![GoDNS](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/timothyye/godns&show=star)](https://github.com/timothyye/godns)[GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.
* [![GoDocTooltip](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/diankong/GoDocTooltip&show=star)](https://github.com/diankong/GoDocTooltip)[GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at funciton list.
* [Gogland](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
* [![Gor](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/buger/gor&show=star)](https://github.com/buger/gor)[Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [hugo](http://gohugo.io/) - Fast and Modern Static Website Engine.
* [![ide](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/thestrukture/ide&show=star)](https://github.com/thestrukture/ide)[ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
* [![ipe](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/dimiro1/ipe&show=star)](https://github.com/dimiro1/ipe)[ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
* [![JayDiff](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/yazgazan/jaydiff&show=star)](https://github.com/yazgazan/jaydiff)[JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
* [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
* [![Leaps](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jeffail/leaps&show=star)](https://github.com/jeffail/leaps)[Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
* [limetext](http://limetext.org/) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
* [![LiteIDE](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/visualfc/liteide&show=star)](https://github.com/visualfc/liteide)[LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [![mockingjay](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/quii/mockingjay-server&show=star)](https://github.com/quii/mockingjay-server)[mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
* [![myLG](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mehrdadrad/mylg&show=star)](https://github.com/mehrdadrad/mylg)[myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [![naclpipe](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/unix4fun/naclpipe&show=star)](https://github.com/unix4fun/naclpipe)[naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
* [![nes](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fogleman/nes&show=star)](https://github.com/fogleman/nes)[nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* [![orange-cat](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/noraesae/orange-cat&show=star)](https://github.com/noraesae/orange-cat)[orange-cat](https://github.com/noraesae/orange-cat) - Markdown previewer written in Go.
* [![Orbit](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/gulien/orbit&show=star)](https://github.com/gulien/orbit)[Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
* [![peg](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pointlander/peg&show=star)](https://github.com/pointlander/peg)[peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
* [![Postman](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/zachlatta/postman&show=star)](https://github.com/zachlatta/postman)[Postman](https://github.com/zachlatta/postman) - Command-line utility for batch-sending email.
* [![restic](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/restic/restic&show=star)](https://github.com/restic/restic)[restic](https://github.com/restic/restic) - De-duplicating backup program.
* [![rkt](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/coreos/rkt&show=star)](https://github.com/coreos/rkt)[rkt](https://github.com/coreos/rkt) - App Container runtime that integrates with init systems, is compatible with other container formats like Docker, and supports alternative execution engines like KVM.
* [![Seaweed File System](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/chrislusf/seaweedfs&show=star)](https://github.com/chrislusf/seaweedfs)[Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [![shell2http](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/msoap/shell2http&show=star)](https://github.com/msoap/shell2http)[shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
* [![snap](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/intelsdi-x/snap&show=star)](https://github.com/intelsdi-x/snap)[snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* [![Stack Up](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/pressly/sup&show=star)](https://github.com/pressly/sup)[Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
* [![Tenyks](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/kyleterry/tenyks&show=star)](https://github.com/kyleterry/tenyks)[Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
* [![toto](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/blogcin/ToTo&show=star)](https://github.com/blogcin/ToTo)[toto](https://github.com/blogcin/ToTo) - Simple proxy server written in Go language, can be used together with browser.
* [![toxiproxy](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/shopify/toxiproxy&show=star)](https://github.com/shopify/toxiproxy)[toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [![vFlow](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/VerizonDigital/vflow&show=star)](https://github.com/VerizonDigital/vflow)[vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
* [![websysd](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/ian-kent/websysd&show=star)](https://github.com/ian-kent/websysd)[websysd](https://github.com/ian-kent/websysd) - Web based process manager (like Marathon or Upstart).
* [![wellington](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/wellington/wellington&show=star)](https://github.com/wellington/wellington)[wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [![autobench](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/davecheney/autobench&show=star)](https://github.com/davecheney/autobench)[autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [![go-benchmark-app](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/mrLSD/go-benchmark-app&show=star)](https://github.com/mrLSD/go-benchmark-app)[go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [![go-benchmarks](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tylertreat/go-benchmarks&show=star)](https://github.com/tylertreat/go-benchmarks)[go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [![go-http-routing-benchmark](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/julienschmidt/go-http-routing-benchmark&show=star)](https://github.com/julienschmidt/go-http-routing-benchmark)[go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* [![go-type-assertion-benchmark](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/hgfischer/go-type-assertion-benchmark&show=star)](https://github.com/hgfischer/go-type-assertion-benchmark)[go-type-assertion-benchmark](https://github.com/hgfischer/go-type-assertion-benchmark) - Naive performance test of two ways to do type assertion in Go.
* [![go-web-framework-benchmark](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/smallnest/go-web-framework-benchmark&show=star)](https://github.com/smallnest/go-web-framework-benchmark)[go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* [![go_serialization_benchmarks](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/alecthomas/go_serialization_benchmarks&show=star)](https://github.com/alecthomas/go_serialization_benchmarks)[go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* [![gocostmodel](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/PuerkitoBio/gocostmodel&show=star)](https://github.com/PuerkitoBio/gocostmodel)[gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* [![golang-micro-benchmarks](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/amscanne/golang-micro-benchmarks&show=star)](https://github.com/amscanne/golang-micro-benchmarks)[golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - Tiny collection of Go micro benchmarks. The intent is to compare some language features to others.
* [![golang-sql-benchmark](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/tyler-smith/golang-sql-benchmark&show=star)](https://github.com/tyler-smith/golang-sql-benchmark)[golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [![gospeed](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/feyeleanor/GoSpeed&show=star)](https://github.com/feyeleanor/GoSpeed)[gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [![kvbench](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/jimrobinson/kvbench&show=star)](https://github.com/jimrobinson/kvbench)[kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* [![skynet](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/atemerev/skynet&show=star)](https://github.com/atemerev/skynet)[skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [![speedtest-resize](https://gh-social-count-label.herokuapp.com/lable?host=https://github.com/fawick/speedtest-resize&show=star)](https://github.com/fawick/speedtest-resize)[speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

## Conferences

* [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA
* [dotGo](http://www.dotgo.eu) - Paris, France
* [GoCon](http://gocon.connpass.com/) - Tokyo, Japan
* [GolangUK](http://golanguk.com/) - London, UK
* [GopherChina](http://gopherchina.org) - Shanghai, China
* [GopherCon](http://www.gophercon.com/) - Denver, USA
* [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, BR
* [GopherCon Dubai](http://www.gophercon.ae/) - Dubai, UAE
* [GopherCon India](http://www.gophercon.in/) - Pune, India
* [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore
* [GothamGo](http://gothamgo.com/) - New York City, USA

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go Bootcamp](http://golangbootcamp.com)
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)

## Meetups

* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## Websites

* [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
* [Flipboard - Go Magazine](https://flipboard.com/section/the-golang-magazine-bVP7nS) - Collection of Go articles and tutorials.
* [Go Blog](http://blog.golang.org) - The official Go blog.
* [Go Challenge](http://golang-challenge.org/) - Learn Go by solving problems and getting feedback from Go experts.
* [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
* [Go Report Card](https://goreportcard.com) - A report card for your Go package.
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
* [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
* [Golang Flow](http://golangflow.io) - Post Updates, News, Packages and more.
* [Golang News](https://golangnews.com) - Links and news about Go programming.
* [golang-graphics](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
* [gowalker.org](https://gowalker.org) - Go Project API documentation.
* [r/Golang](https://www.reddit.com/r/golang) - News about Go.
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.

### Tutorials

* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
