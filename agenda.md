================================================================

Mon Jan 26

* internship / mentor
    * mike
* Garry
* signup
    * different files
    * problems
* FAQ
* code-sprint
    * Eclipse Foundation > Location Tech (WG) > Geo*
    * expectations
* style
    * convention over configuration: `/etc/*.d`
    * [elements of style](https://drive.google.com/a/utexas.edu/file/d/0B-J1EsugIjXudkdhcV9qLXdmbzg/view?usp=sharing)
    * [scala](https://github.com/paypal/scala-style-guide)
    * hype cycle
* geo*
    * learning Scala
    * why scala?
    * REPL

================================================================

Wed Jan 28

* talk details
* kato
    * 12 are not on kato
* Derek Ngo
    * Worst case scenario, if the current (or beta) version of ios-driver is not compatible with the newest xcode,
      what options do we have?
* poll

* environment
    * `.bashrc` vs `.bash_profile`
    * editor
    * checked-in
    * pom.xml
        - http://logging.apache.org/log4j/2.x/maven-artifacts.html

================================================================

Mon Feb 2

* http://bit.ly/1DorocK

* example: style for quality (Linux)

* testing
    * manual vs automated
    * unit
    * functional
    * integration
    * acceptance

    * regression

    * system
    * database

    * non-functional
        * compliance
        * security
        * documentation

        * endurance
        * load
        * performance
        * stress

        * recovery
        * scalability
        * usability
        * volume
        * localization
        * compatibility

================================================================

Wed Feb 4

* testing: scientific method (reproducability)

* why is it so hard to set up?

* compatibility testing

* process - discipline
    * waterfall
        - http://upload.wikimedia.org/wikipedia/commons/e/e2/Waterfall_model.svg
    * agile
        - http://agilemanifesto.org/
        - http://upload.wikimedia.org/wikipedia/commons/5/58/Scrum_process.svg
        - http://www.agilelearninglabs.com/wp-content/uploads/2012/02/sprint-cycle.jpg
    * TDD
    * BDD behavior / business (https://cukes.info/)
    * top down vs bottom up

================================================================

Sat-Sun Feb 7-8

* [code sprint](code-sprint.md)

================================================================

Mon Feb 9

* groups re-organized
* stand-up
* retrospective
* architecture
* demo
* debug walkthrough
* environment?
* testing?
* reproducible?
* documentation?
* agile manifesto?
* answer these 2 questions:
    - what can we demo?
    - how does it work?

================================================================

Wed 11 Feb

* demo
* git as distributed data store
    - init / commit / log
    - clone / fetch / push
    - origin / remotes
    - forks
* repo sharing
    - github organization
* branches
    - branch / merge / rebase
    - reset
    - cherry-pick
    - stash

================================================================

Mon 16 Feb

* Guest Lecture: Scott Killen

================================================================

Wed 18 Feb

* gist
* review monday
* review stand-ups
* meet with mentors - Fri ?

* branching models
    - development | release | maintenance
    - what are customers using
    - what is release candidate
    - what is leading edge development
    - what is personal development
    - how do i share unfinished work
    - how do i review changes before merging
* branching models (no forks)
    - small: master
    - medium: _dev -> develop -> master
    - large: topic -> develop -> release -> master
* forking models
    - small: fork master -> shared master
    - medium: fork develop -> shared develop -> release...
    - large: fork topic -> shared topic -> shared develop -> release...

================================================================

Mon 23 Feb

* discuss good user stories
    - As a [user role], I want to [goal], so I can [reason].
    - example: https://github.com/mmccartney/cs378-open-source-software-engineering/blob/master/plans/sample.md
    - assignment due Wednesday

* working time

================================================================

Wed 25 Feb

* Guest Lecture: Cedric Williams

================================================================

Mon 2 Mar

* pull request
    - https://github.com/selendroid/selendroid/pull/816/files
* who is stuck?
* software organization
    - http://docs.oracle.com/javase/7/docs/api/java/util/List.html
    - http://docs.oracle.com/javase/7/docs/api/java/util/Map.html
    - http://h71000.www7.hp.com/doc/732final/9996/9996pro_contents.html
    - http://h71000.www7.hp.com/doc/732final/9996/9996pro_069.html#brass_102
    - http://h71000.www7.hp.com/doc/732final/9996/9996pro_076.html#brassxxx
    - http://h71000.www7.hp.com/doc/732final/9996/9996pro_076.html#brass_114
    - http://h71000.www7.hp.com/doc/732final/9996/9996pro_080.html#brass_126
    - http://docs.oracle.com/javase/7/docs/api/overview-summary.html
    - https://golang.org/pkg/
    - https://docs.python.org/2/library/index.html
    - http://www.scala-lang.org/api/current/#package
    - https://developer.paypal.com/docs/api/

================================================================

Wed 4 Mar

* working time

================================================================

Mon 9 Mar

* discuss TestNG
    - @BeforeClass, @AfterClass
    - @BeforeMethod, @AfterMethod
    - testng.xml

* discuss mid-term

* working time

================================================================

Wed 11 Mar

* mid-term exam

================================================================

Mon 23 Mar

* discuss status
    - walked through experience of asking for help
    - avoiding having a single gatekeeper for knowledge
    - the utility of a good FAQ

* discuss debugging
    - walked through https://github.com/ios-driver/ios-driver/blob/dev/server/src/main/java/org/uiautomation/ios/utils/DeviceUUIDsMap.java

* working time
