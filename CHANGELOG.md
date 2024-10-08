# Changelog

## 1.3.1 [☰](https://github.com/varyonic/arbo/compare/v1.3.0...v1.3.1)

* Fix patch of ActionView capture: OutputBuffer. [#5] by [@varyonic]

## 1.3.0 [☰](https://github.com/varyonic/arbo/compare/v1.2.0...v1.3.0)

* Support Rails 7.1. [#3] by [@varyonic]
* Update documentation including fresh theme. [#4] by [@varyonic]

## 1.2.0 [☰](https://github.com/varyonic/arbo/compare/v1.1.1...v1.2.0)

* Fix rendering `link_to` with a block in a arbre template. [#64][] by [@varyonic][]
* Fix deprecation warning about single arity template handlers on Rails 6. [#110][] by [@aramvisser][]
* Fix ruby 2.7 kwargs warnings. [#205][] by [@deivid-rodriguez][]
* Support nested attribute hashes rendered as hyphenated attributes. [#451][] [@Ikariusrb][]

* Implement `render_in` alternative to `to_s`. [#1][] by [@varyonic][]
* Remove build_head and build_body from HTML::Document tag. [#2][] by [@varyonic][]

## 1.1.1 [☰](https://github.com/activeadmin/arbre/compare/v1.1.0...v1.1.1)

* Use mime-types 2.x for Ruby 1.9 by [@timoschilling][]
* Verify Ruby 2.3 support. [#59][] by [@dlackty][] 

## 1.1.0 [☰](https://github.com/activeadmin/arbre/compare/v1.0.3...v1.1.0)

* Tag option `for` sets the attribute when value is a string or symbol [#49][] by [@ramontayag][]

## 1.0.3 [☰](https://github.com/activeadmin/arbre/compare/v1.0.2...v1.0.3)

* Performance improvements [#40][] by [@alexesDev][]
* Added all void elements as self-closing tags [#39][] by [@OscarBarrett][]
* Missing tags added [#36][] / [#39][] by [@dtaniwaki][] and [@OscarBarrett][]

## 1.0.2 [☰](https://github.com/activeadmin/arbre/compare/v1.0.1...v1.0.2)

* make `Element#inspect` behave correctly in Ruby 2.0 [#16][] by [@seanlinsley][]
* prevent `Arbre::Element#flatten` infinite recursion [#32][] by [@seanlinsley][]
* make `find_by_class` correctly find children by class [#33][] by [@kaapa][]

## 1.0.1 [☰](https://github.com/activeadmin/arbre/compare/v1.0.0...v1.0.1)

* Template handler converts to string to satisfy Rack::Lint [#6][] by [@jpmckinney][]
* Fix to `Tag#add_class` when passing a string of classes to Tag build method
  [#4][] by [@gregbell][]
* Not longer uses the default separator [#7][] by [@LTe][]

## 1.0.0 [☰](https://github.com/activeadmin/arbre/compare/v1.0.0.rc4...v1.0.0)

* Added support for the use of `:for` with non Active Model objects

## 1.0.0.rc4 [☰](https://github.com/activeadmin/arbre/compare/v1.0.0.rc3...v1.0.0.rc4)

* Fix issue where user could call `symbolize_keys!` on a
  HashWithIndifferentAccess which doesn't implement the method

## 1.0.0.rc3 [☰](https://github.com/activeadmin/arbre/compare/v1.0.0.rc2...v1.0.0.rc3)

* Implemented `Arbre::HTML::Tag#default_id_for_prefix`

## 1.0.0.rc2 [☰](https://github.com/activeadmin/arbre/compare/v1.0.0.rc1...v1.0.0.rc2)

* Fixed bug where Component's build methods were being rendered within the
  parent context.

## 1.0.0.rc1

Initial release and extraction from Active Admin

[#4]: https://github.com/activeadmin/arbre/issues/4
[#6]: https://github.com/activeadmin/arbre/issues/6
[#7]: https://github.com/activeadmin/arbre/issues/7
[#16]: https://github.com/activeadmin/arbre/issues/16
[#32]: https://github.com/activeadmin/arbre/issues/32
[#33]: https://github.com/activeadmin/arbre/issues/33
[#36]: https://github.com/activeadmin/arbre/issues/36
[#39]: https://github.com/activeadmin/arbre/issues/39
[#40]: https://github.com/activeadmin/arbre/issues/40
[#49]: https://github.com/activeadmin/arbre/issues/49
[#59]: https://github.com/activeadmin/arbre/issues/59
[#64]: https://github.com/activeadmin/arbre/pull/64
[#110]: https://github.com/activeadmin/arbre/pull/110
[#205]: https://github.com/activeadmin/arbre/pull/205
[#451]: https://github.com/activeadmin/arbre/pull/451

[#1]: https://github.com/varyonic/arbo/pull/1
[#2]: https://github.com/varyonic/arbo/pull/2
[#3]: https://github.com/varyonic/arbo/pull/3
[#4]: https://github.com/varyonic/arbo/pull/4
[#5]: https://github.com/varyonic/arbo/pull/5

[@aramvisser]: https://github.com/aramvisser
[@deivid-rodriguez]: https://github.com/deivid-rodriguez
[@LTe]: https://github.com/LTe
[@OscarBarrett]: https://github.com/OscarBarrett
[@alexesDev]: https://github.com/alexesDev
[@dtaniwaki]: https://github.com/dtaniwaki
[@gregbell]: https://github.com/gregbell
[@Ikariusrb]: https://github.com/Ikariusrb
[@jpmckinney]: https://github.com/jpmckinney
[@kaapa]: https://github.com/kaapa
[@ramontayag]: https://github.com/ramontayag
[@seanlinsley]: https://github.com/seanlinsley
[@timoschilling]: https://github.com/timoschilling
[@varyonic]: https://github.com/varyonic
