# Awesome Lua

A curated list of awesome Lua frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Lua](#awesome-Lua)
    - [Environment Management](#environment-management)
    - [Package Management](#package-management)
    - [Distribution](#distribution)
    - [Build Tools](#build-tools)
    - [Interactive Interpreter](#intferactive-interpreter)
    - [Filesystem](#filesystem)
    - [Date and Time](#date-and-time)
    - [Lua Implementations](#lua-implementations)
    - [Text Processing](#text-processing)
    - [Natural Language Processing](#natural-language-processing)
    - [Documentation](#documentation)
    - [Configuration](#configuration)
    - [Command-line Tools](#command-line-tools)
    - [Downloader](#downloader)
    - [Imagery](#imagery)
    - [Audio](#audio)
    - [Video](#video)
    - [Geolocation](#geolocation)
    - [HTTP](#http)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [ORM](#orm)
    - [Web Frameworks](#web-frameworks)
    - [Permissions](#permissions)
    - [CMS](#cms)
    - [RESTful API](#restful-api)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Template Engine](#template-engine)
    - [Queue](#queue)
    - [Search](#search)
    - [News Feed](#news-feed)
    - [Asset Management](#asset-management)
    - [Caching](#caching)
    - [Email](#email)
    - [Internationalization](#internationalization)
    - [URL Manipulation](#url-manipulation)
    - [HTML Manipulation](#html-manipulation)
    - [Web Crawling](#web-crawling)
    - [Web Content Extracting](#web-content-extracting)
    - [Forms](#forms)
    - [Data Validation](#data-validation)
    - [Anti-spam](#anti-spam)
    - [Tagging](#tagging)
    - [Admin Panels](#admin-panels)
    - [Static Site Generator](#static-site-generator)
    - [Processes and Threads](#processes-and-threads)
    - [Networking](#networking)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
    - [RPC Servers](#rpc-servers)
    - [Cryptography](#cryptography)
    - [GUI](#gui)
    - [Game Development](#game-development)
    - [Logging](#logging)
    - [Testing](#testing)
    - [Code Analysis and Linter](#code-analysis-and-linter)
    - [Debugging Tools](#debugging-tools)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Data Visualization](#data-visualization)
    - [Computer Vision](#computer-vision)
    - [Machine Learning](#machine-learning)
    - [Functional Programming](#functional-programming)
    - [MapReduce](#mapreduce)
    - [Third-party APIs](#third-party-apis)
    - [DevOps Tools](#devops-tools)
    - [Job Scheduler](#job-scheduler)
    - [Foreign Function Interface](#foreign-function-interface)
    - [High Performance](#high-performance)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Hardware](#hardware)
    - [Miscellaneous](#miscellaneous)
    - [Editor Plugins](#editor-plugins)
- [Resources](#resources)
    - [Websites](#websites)
    - [Weekly](#weekly)
    - [Twitter](#twitter)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Environment Management

*Libraries for Lua version and environment management.*


## Package Management

*Libraries for package and dependency management.*

* [LuaDist](http://luadist.org/) - LuaDist is a true multi-platform package management system that aims to provide both source and binary repository of modules for the Lua programming language. 
* [Luaforge](http://luaforge.net/projects/) - LuaForge was a software project hosring website set up in 2004 by André Carregal and the Kepler Project, to promote development of Lua software modules. 
* [LuaRocks](http://www.luarocks.org/) - LuaRocks is a system that allows the versioning of Lua packages and their dependencies. LuaRocks guarantees that every package installed will continue to work, even if its dependencies are updated. 


## Distribution

*Libraries to create packaged executables for release distribution.*

* [LuaBinaries](http://luabinaries.sourceforge.net/) - LuaBinaries is a distribution of the Lua libraries and executables compiled for several platforms.


## Build Tools & IDE

*Compile software from source code.*

* [Decoda](https://github.com/unknownworlds/decoda) - Decoda Lua IDE and debugger.
* [Lake](https://github.com/stevedonovan/Lake) - A Lua-based Build Tool
* [ZeroBrane Studio](https://github.com/pkulchenko/ZeroBraneStudio) - A lightweight Lua-based IDE for Lua with code completion, syntax highlighting, live coding, remote debugger, and code analyzer.



## Interactive Interpreter

*Interactive Lua interpreters.*


## Filesystem

*Libraries for accessing the directory structure and file attributes.*

* [LuaFileSystem](http://keplerproject.github.io/luafilesystem/) - LuaFileSystem is a Lua library developed to complement the set of functions related to file systems offered by the standard Lua distribution.
* [LAR](http://www.keplerproject.org/en/LAR) - LAR stands for Lua ARchive, and consist of a module and a file format that empowers a lua script to load lua modules from within a packaged, compressed file.
* [LuaZip](http://keplerproject.org/luazip/) - LuaZip is a lightweight Lua extension library used to read files stored inside zip files. The API is very similar to the standard Lua I/O library API.
* [LuaExpat](http://matthewwild.co.uk/projects/luaexpat/) - LuaExpat is a SAX XML parser based on the Expat library.
* [lua-path](https://github.com/moteus/lua-path) - File system path manipulation library.

## Date and Time

*Libraries for working with dates and times.*

* [LuaDate](http://tieske.github.io/date) - Date & Time module for Lua 5.1/5.2

## Lua Implementations

*All kinds of lua implementations*

* [UniLua](https://github.com/xebecnan/UniLua) - A pure c# implementation of Lua 5.2 focus on compatibility with Unity
* [Luerl](https://github.com/rvirding/luerl) - An experimental implementation of Lua 5.2 written solely in pure Erlang.
* [MoonScript](http://moonscript.org/) - MoonScript is a dynamic scripting language that compiles into Lua.
* [lua.js](https://github.com/mherkender/lua.js) - An ECMAscript framework to compile and run Lua code, allowing Lua to run in a browser or in Flash.
* [lua.vm.js](https://github.com/kripken/lua.vm.js) - The Lua VM, on the Web.
* [Moonshine](http://moonshinejs.org/) - A lightweight Lua VM for the browser.
* [lua-alchemy](https://github.com/lua-alchemy/lua-alchemy) - Port of the Lua programming language for ActionScript using Alchemy.
* [NeoLua](https://neolua.codeplex.com/) - A Lua implementation for the Dynamic Language Runtime (DLR).NeoLua is implemented in C# and uses the Dynamic Language Runtime. It therefore integrates very well with the .net framework.


## Text Processing

*Libraries for parsing and manipulating texts.*

* [Markdown](http://luaforge.net/projects/markdown/) - A pure-lua implementation of the Markdown text-to-html markup system. 
* 


## Natural Language Processing

*Libraries for working with human languages.*


## Documentation

*Libraries for generating project documentation.*

* [LuaDoc](http://keplerproject.github.io/luadoc/) - LuaDoc is a documentation generator tool for Lua source code. 


## Configuration

*Libraries for storing configuration options.*


## Command-line Tools

*Libraries for building command-line application.*


## Downloader

*Libraries for downloading.*


## Imagery

*Libraries for manipulating images.*


## Audio

*Libraries for manipulating audio.*


## Video

*Libraries for manipulating video and GIFs.*


## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*


## HTTP

*Libraries for working with HTTP.*

* [Xavante](http://keplerproject.github.io/xavante/) - Xavante is a Lua HTTP 1.1 Web server that uses a modular architecture based on URI mapped handlers.


## Database

*Databases implemented in Lua.*

* [Tarantool](https://github.com/tarantool/tarantool) - Tarantool is an efficient NoSQL database and a Lua application server.


## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [LuaDBI](https://code.google.com/p/luadbi) - LuaDBI is a database interface library for Lua. It is designed to provide a RDBMS agnostic API for handling database operations.
    * [LuaLDAP](http://www.keplerproject.org/lualdap/) - LuaLDAP is a simple interface from Lua to an LDAP client, in fact it is a bind to OpenLDAP or to ADSI. 
    * [LuaODBC](http://www.keplerproject.org/luasql/) - ODBC Library for Lua. Also provide LuaSQL compatible module.
    * [LuaSQL](http://www.keplerproject.org/luasql/) - LuaSQL is a simple interface from Lua to a DBMS. 
    * [LuaSQLite3](http://lua.sqlite.org/) - a Lua 5.1 and Lua 5.2 wrapper for the SQLite3 library.
    * [Lsqlite](http://luaforge.net/projects/lsqlite/) - A simple libsqlite3 binding for lua5.0-5.2 that provides 3 functions only and is still fully functional: local db = lsqlite.open(database) results, err = db:exec(statments) db:close() 

* NoSQL Databases


## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* Relational Databases

* NoSQL Databases


## Web Frameworks

*Full stack web frameworks.*

* [CGIlua](http://keplerproject.github.io/cgilua/) - CGILua is a tool for creating dynamic Web pages and manipulating input data from Web forms.
* [Kepler Project](http://www.keplerproject.org/) - Kepler is a community of software developers building open software to help make Lua a viable option for development of web applications.
* [Orbit](http://keplerproject.github.io/orbit/) - Orbit is an MVC web framework for Lua. 
* [WSAPI](http://keplerproject.github.io/wsapi/) - WSAPI is an API that abstracts the web server from Lua web applications. 
* [Tir](https://github.com/zedshaw/Tir) - Tir is an experimental web framework for the Mongrel2 webserver and Lua programming language.
* [Lapis](https://github.com/leafo/lapis) - A web framework for Lua and OpenResty written in MoonScript.
* [aLiLua](https://github.com/oneoo/alilua) - A epoll/kqueue based web server, inculded lua/coevent support (support Linux/MacOS/BSD platform).
* [Bamboo](https://github.com/daogangtang/bamboo) - Bamboo is the web framework of Lua based on Mongrel2, ZeroMQ and NoSQL database.
* [MOOCHINE](https://github.com/appwilldev/moochine) - A (very) simple and lightweight web framework based on ngx-openresty.


## Permissions

*Libraries that allow or deny users access to data or functionality.*


## CMS

*Content management systems*

* [Sputnik](http://sputnik.freewisdom.org/) - Sputnik is a software application that powers a dynamic website. 


## RESTful API

*Libraries for developing RESTful APIs.*


## Authentication and OAuth

*Libraries for implementing authentications schemes.*


## Template Engine

*Libraries and tools for templating and lexing.*


## Queue

*Libraries for working with event and task queues.*


## Search

*Libraries and software for indexing and performing search queries on data.*


## News Feed

*Libraries for building user's activities.*


## Asset Management

*Tools for managing, compressing and minifying website assets.*


## Caching

*Libraries for caching data.*


## Email

*Libraries for sending and parsing email.*

* [lua-imap4](https://github.com/vrld/imap4.lua) - Simple IMAP4 protocol wrapper for Lua
* [lua-pop3](https://github.com/moteus/lua-pop3) - POP3 client library for Lua
* [sendmail](https://github.com/moteus/lua-sendmail) - Simple wrapper around luasoket smtp.send


## Internationalization

*Libraries for woking with i18n.*


## URL Manipulation

*Libraries for parsing URLs.*


## HTML Manipulation

*Libraries for working with HTML and XML.*

* [Luatidy](http://www.bessems.biz/luatidy/) - Lua binding for [HTMLtidy](http://tidy.sourceforge.net/)


## Web Crawling

*Libraries for scraping websites.*


## Web Content Extracting

*Libraries for extracting web contents.*


## Forms

*Libraries for working with forms.*


## Data Validation

*Libraries for validating data. Used for forms in many cases.*


## Anti-spam

*Libraries for fighting spam.*


## Tagging

*Libraries for tagging items.*


## Admin Panels

*Libraries for administrative interfaces.*


## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces html files on the output.*


## Processes and Threads

*Libraries for woking with processes or threads*

* [lua-llthreads](https://github.com/Neopallium/lua-llthreads) - Low-Level threads(pthreads or WIN32 threads) for Lua.
* [lua-llthreads2](https://github.com/moteus/lua-llthreads2) - Enhancement version of lua-llthreads rewritten without `LuaNativeObjects` code generator
* [LuaLanes](https://github.com/LuaLanes/lanes) - lightweight, native, lazy evaluating multithreading library for Lua 5.1 and 5.2


## Networking

*Libraries for network programming.*

* [Copas](http://keplerproject.github.io/copas/) - Copas is a dispatcher based on coroutines that can be used by TCP/IP servers.
* [lua-zmq](https://github.com/Neopallium/lua-zmq) - Lua bindings to ZeroMQ 2
* [Luakit](http://mason-larobina.github.io/luakit/) - Fast, small, webkit based browser framework extensible by Lua. 
* [LuaEvent](http://repo.or.cz/w/luaevent.git) - This is a binding of libevent to Lua. It will serve as a drop-in replacement for copas, and eventually support more features (async DNS, HTTP, RPC...)
* [LuaSec](https://github.com/brunoos/luasec) - LuaSec is a binding for OpenSSL library to provide TLS/SSL communication. 
* [LuaSocket](http://w3.impa.br/~diego/software/luasocket/) - LuaSocket is a Lua extension library that is composed by two parts: a C core that provides support for the TCP and UDP transport layers, and a set of Lua modules that add support for functionality commonly needed by applications that deal with the Internet. 
* [LuaNode](https://github.com/ignacio/LuaNode) - LuaNode allows to write performant net servers or clients, using an asynchronous model of computing (the Reactor pattern). You might have seen this model implemented in event processing frameworks like Node.js, EventMachine or Twisted. In fact, LuaNode is heavily based on Node.js, because I wanted to be able to do what Node.js does, but using Lua instead of JavaScript.
* [lzmq](https://github.com/zeromq/lzmq) - A Lua wrapper for the ZeroMQ message library. Supports ZeroMQ version above 3.2.0
* [Ngx_lua](https://github.com/openresty/lua-nginx-module) - Embed the power of Lua into Nginx.
* [Luvit](https://github.com/luvit/luvit) - Luvit is an attempt to do something crazy by taking node.js' awesome architecture and dependencies and seeing how it fits in the Lua language. 
* [Turbo](http://turbolua.org/) - Turbo provides you with all the stuff you need to develop fast web apps, web API's and networking applications. 


## WebSocket

*Libraries for woking with WebSocket.*


## WSGI Servers

*WSGI-compatible web servers.*


## RPC Servers

*RPC-compatible servers.*


## Cryptography

*Cryptography libraries*

* [AesFileEncrypt](https://github.com/moteus/lua-AesFileEncrypt) - A simple file encryption library
* [MD5](http://keplerproject.org/md5/) - MD5 offers basic cryptographic facilities for Lua 5.1: a hash (digest) function, a pair crypt/decrypt based on MD5 and CFB, and a pair crypt/decrypt based on DES with 56-bit keys. 
* [LCrypt](http://luaforge.net/projects/lcrypt/) - LCrypt provides everything needed to implement a basic ssh client or server including symmetric ciphers, hashes, microtime, random strings, big integers, and zlib compression. An example RSA implementation is included. 
* [LuaCrypto](http://luacrypto.luaforge.net/) - LuaCrypto provides a Lua frontend to the OpenSSL cryptographic library. 


## GUI

*Libraries for working with graphical user interface applications.*

* [wxLua](http://wxlua.sourceforge.net/) - wxLua is a Lua scripting language wrapper around the wxWidgets cross-platform C++ GUI library.
* [IUP](http://www.tecgraf.puc-rio.br/iup/) - IUP is a multi-platform toolkit for building graphical user interfaces.
* [Lqt](https://github.com/mkottman/lqt) - lqt is a Lua binding to the Qt framework. It is an automated binding generated from the Qt headers, and covers almost all classes and methods from supported Qt modules.
* [LuaGnome](http://lua-gtk.luaforge.net/en/index.html) - LuaGnome provides a fairly complete binding to Gnome Libraries Lua, including glib 2.x, gdk, gtk 2.x, and a list of supporting libraries. 


## Game Development

*Awesome game development libraries.*

* [Skynet](https://github.com/cloudwu/skynet) - A lightweight online game framework
* [Scut](https://github.com/ScutGame/Scut) - Scut is a free, open source, stable game server framework, which support C#/Python/Lua script, and support Unity3d, Cocos2dx, FlashAir client access.
* [LoveDOS](https://github.com/rxi/lovedos) - A framework for making 2D DOS games in Lua. LoveDOS provides an API based on a subset of the LÖVE API.
* [PacPac](https://github.com/tylerneylon/pacpac) - This is Pac-Man from a parallel universe.
* [aroma](https://github.com/leafo/aroma) - Aroma is game creation framework/platform that targets Chrome's Native Client. It lets you create games that can be distributed through the Chrome Web Store.
* [Cubzh](https://github.com/cubzh/cubzh) - Cubzh is an open-source game engine & gaming platform that allows anyone to rapidly script games using Lua 


## Logging

*Libraries for generating and working with log files.*

* [LuaLogging](http://keplerproject.org/lualogging/) - LuaLogging provides a simple API to use logging features in Lua. Its design was based on log4j. LuaLogging currently supports, through the use of appenders, console, file, email, socket and sql outputs.
* [Lsyslog](https://gitorious.org/lsyslog/lsyslog) - lsyslog is a Lua module that wraps the syslog(3) C API. It has been tested with Lua 5.2 on Linux.
* [Lua-log](https://github.com/moteus/lua-log) - Asynchronous logging library for Lua 5.1/5.2



## Testing

*Libraries for testing codebases and generating test data.*

* [Busted](https://github.com/Olivine-Labs/busted) - Elegant Lua unit testing.


## Code Analysis and Linter

*Libraries and tools for analysing, parsing and manipulation codebases.*

* [Lualint](https://github.com/philips/lualint) - lualint performs luac-based static analysis of global variable usage in Lua source code.


## Debugging Tools

*Libraries for debugging code.*

* [RemDebug](http://keplerproject.org/remdebug/) - RemDebug is a remote debugger for Lua 5.0 and 5.1. It lets you control the execution of another Lua program remotely, setting breakpoints and inspecting the current state of the program. RemDebug can also debug CGILua scripts.
* [LuaProfiler](http://keplerproject.org/luaprofiler/) - LuaProfiler is a time profiler designed to help finding bottlenecks on your Lua program.


## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [SciLua](http://www.scilua.org/) - The aim of this project is to offer a framework for numerical computing which combines the ease of use of scripting languages (Matlab, R, ...) with the high performance of compiled languages (C/C++, Fortran, ...).


## Data Visualization

*Libraries for visualizing data.*


## Computer Vision

*Libraries for computer vision.*


## Machine Learning

*Libraries for Machine Learning.*


## MapReduce

*Framworks and libraries for MapReduce.*


## Functional Programming

*Functional programming in lua*

* [Lua Fun](https://github.com/rtsisyk/luafun) - Lua Fun is a high-performance functional programming library designed for LuaJIT tracing just-in-time compiler.


## Third-party APIs

*Libraries for accessing third party services APIs.*

* [LPeg](http://www.inf.puc-rio.br/~roberto/lpeg/lpeg.html) - LPeg is a new pattern-matching library for Lua, based on Parsing Expression Grammars (PEGs). 

## DevOps Tools

*Software and libraries for DevOps.*


## Job Scheduler

*Libraries for scheduling jobs.*


## Foreign Function Interface

*Libraries for providing foreign function interface.*

* [Alien](http://mascarenhas.github.com/alien) - A C FFI for Lua
* [FFI Library](http://luajit.org/ext_ffi.html) - The FFI library allows calling external C functions and using C data structures from pure Lua code. 
* [LuaFFI](https://github.com/jmckaskill/luaffi) - Standalone FFI library for calling C functions from lua. Compatible with the LuaJIT FFI interface.
* [NLua](https://github.com/NLua/NLua) - NLua is the bind between Lua world and the .NET world.


## High Performance

*Libraries for making Lua faster.*

* [LuaJIT](http://luajit.org/luajit.html) - LuaJIT is a Just-In-Time Compiler (JIT) for the Lua programming language. Lua is a powerful, dynamic and light-weight programming language. It may be embedded or used as a general-purpose, stand-alone language. 
* [Terra](http://terralang.org/) - Terra is a new low-level system programming language that is designed to interoperate seamlessly with the Lua programming language.
* [LLVM-Lua](https://code.google.com/p/llvm-lua/) - JIT/Static compiler for Lua using LLVM on the backend.

## Microsoft Windows

*Lua programming on Microsoft Windows.*

* [lua-pdh](https://github.com/moteus/lua-pdh) - Lua binding to Microsoft Performance Data Helper (PDH) library.


## Hardware

*Libraries for programming with hardware.*


## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [Coxpcall](http://keplerproject.github.io/coxpcall/) - Coxpcall encapsulates the protected calls with a coroutine based loop, so errors can be dealed without the usual pcall/xpcall issues with coroutines. 
* [Penlight](https://github.com/stevedonovan/Penlight) - Penlight brings together a set of generally useful pure Lua modules, focussing on input data handling (such as reading configuration files), functional programming (such as map, reduce, placeholder expressions,etc), and OS path management. Much of the functionality is inspired by the Python standard libraries.


## Algorithms and Design Patterns

*Collections of algorithms and design patterns.*


## Editor Plugins

*Plugins for various editors.*

* Vim
* Emacs
* Sublime Text


# Resources

*Where to discover new Lua libraries.*

* [LuaSearch](http://math2.org/luasearch/) - Navigate Lua Module Documentation

## Websites


## Weekly


## Twitter


# Other Awesome Lists

* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [lists](https://github.com/jnv/lists)

# Contributing

Your contributions are always welcome!

