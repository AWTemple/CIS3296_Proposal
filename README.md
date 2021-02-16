# Dart - YAML Parsing

## Project Abstract
Dart is a high-performance JSON library that integrates the upsides of JSON's dynamic typing into the statically-typed C++ language. It provides easily accessible, brief syntax for working with JSON while still providing competitive network performance. While Dart does not, itself, parse JSON, it integrates with some of the fastest JSON parsers available to ensure performance isn't sacrificed in that regard. In sum, this allows Dart to be practical for real-time JSON stream processing, while also being highly accessible for programmer use.

## Project Relevance
This project links with several educational topics of the class--Remote Procedure Calls and Code Optimization--and also obviously comes with a heavy focus on Version Control Software since the project is open-source on github. Dart has several open issues for requested help, which would allow for good practice using VCS for branched updates and code review for an already-published project.

## Conceptual Design
My proposed contribution isn't highly creative; I opted to work on one of the help-requested issues for the project: to finish YAML parsing capabilities. YAML is a super-set of JSON, and is thus obviously similar in being both a human-readable and machine-readable language. Dart currently partially supports YAML parsing, but the software is bugged. The project thus needs bug-fixing as well as expanded parsing capabilities, as stated by the help request ticket on the github repository. While certainly not the most glamorous of projects, I think it would be very pragmatic practice for open-source software development.

## URL and Building
<https://github.com/target/libdart>

***Building***
- The Dart readme contains more detailed installation instructions than I can give:
- <https://github.com/target/libdart#compilation-and-installation>
- The JSON Parser --<https://github.com/Tencent/rapidjson>-- and YAML Parser --<https://github.com/yaml/libyaml>-- need to be installed ahead of time.

**Running**
- Dart is not a runnable program so much as a C++ Library. Simply use #include <dart.h> after building with the makefile.

## Required Resources
- Experience with C++ and optimally JSON and YAML
- Hardware and software requirements are not taxing, but some kind of networking will likely be needed to properly test the library in actual usage.
