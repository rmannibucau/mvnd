# Changelog

## [Unreleased](https://github.com/mvndaemon/mvnd/tree/HEAD)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.2.0...HEAD)

**Closed issues:**

- Enable some output per module or globally [\#292](https://github.com/mvndaemon/mvnd/issues/292)
- Support short variants of boolean properties [\#279](https://github.com/mvndaemon/mvnd/issues/279)
- \[ENHANCEMENT\] mvnd failed while I purposely disabled ~/.m2 directory [\#278](https://github.com/mvndaemon/mvnd/issues/278)
- mvnd fails when version range is used in extensions.xml [\#275](https://github.com/mvndaemon/mvnd/issues/275)
- mvnd 0.2.0 can no longer resolve our Artifactory server \(works for 0.1.1 in same shell\) [\#274](https://github.com/mvndaemon/mvnd/issues/274)
- Crash with Java 17 [\#272](https://github.com/mvndaemon/mvnd/issues/272)

**Merged pull requests:**

- Document how to install bash completion [\#290](https://github.com/mvndaemon/mvnd/pull/290) ([famod](https://github.com/famod))
- DAG width wrong for parent runtime deployment triple [\#286](https://github.com/mvndaemon/mvnd/pull/286) ([ppalaga](https://github.com/ppalaga))
- Support short variants of boolean properties [\#280](https://github.com/mvndaemon/mvnd/pull/280) ([ppalaga](https://github.com/ppalaga))

## [0.2.0](https://github.com/mvndaemon/mvnd/tree/0.2.0) (2020-12-16)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.1.1...0.2.0)

**Implemented enhancements:**

- Use client terminal width to format help [\#251](https://github.com/mvndaemon/mvnd/issues/251)
- Add a `--serial/-1` command option to toggle maven-like behavior [\#248](https://github.com/mvndaemon/mvnd/issues/248)
- Let -h/--help display also mvnd specific options [\#243](https://github.com/mvndaemon/mvnd/issues/243)
- Bash completion [\#215](https://github.com/mvndaemon/mvnd/issues/215)

**Closed issues:**

- mvnd.rb not support mac now [\#273](https://github.com/mvndaemon/mvnd/issues/273)
- Maven-like rolling output when the build happens to be linear [\#269](https://github.com/mvndaemon/mvnd/issues/269)
- Support Homebrew on Linux [\#268](https://github.com/mvndaemon/mvnd/issues/268)
- A new daemon is always started with OpenJDK 8 [\#266](https://github.com/mvndaemon/mvnd/issues/266)
- Fix `getCurrentProject\(\)` [\#262](https://github.com/mvndaemon/mvnd/issues/262)
- No reuse of daemons, no build speedup. [\#261](https://github.com/mvndaemon/mvnd/issues/261)
- No reuse of daemons - error on daemon creation - unknown signal TSTP \(Windows 10, Bellsoft Liberica JDK\) [\#260](https://github.com/mvndaemon/mvnd/issues/260)
- mvnd is affected by CVE-2020-17521 vulnerability [\#259](https://github.com/mvndaemon/mvnd/issues/259)
- Document --status, --stop and --purge in -h/--help [\#249](https://github.com/mvndaemon/mvnd/issues/249)
- The mvnd client creates a mvnd.daemonStorage\_IS\_UNDEFINED folder [\#246](https://github.com/mvndaemon/mvnd/issues/246)
- mvnd --help produces no output [\#238](https://github.com/mvndaemon/mvnd/issues/238)
- Wrong display of number of projects to build [\#236](https://github.com/mvndaemon/mvnd/issues/236)

**Merged pull requests:**

- Maven-like rolling output when the build happens to be linear [\#271](https://github.com/mvndaemon/mvnd/pull/271) ([ppalaga](https://github.com/ppalaga))
- A new daemon is always started on Java 8  [\#267](https://github.com/mvndaemon/mvnd/pull/267) ([ppalaga](https://github.com/ppalaga))
- Deprecate mvnd.builder.rule\* and mvnd.builder.rules.provider.\* features [\#265](https://github.com/mvndaemon/mvnd/pull/265) ([ppalaga](https://github.com/ppalaga))
- Fix getCurrentProject, \#fixes \#262 [\#263](https://github.com/mvndaemon/mvnd/pull/263) ([gnodet](https://github.com/gnodet))
- Fix SERIAL command line option [\#257](https://github.com/mvndaemon/mvnd/pull/257) ([gnodet](https://github.com/gnodet))
- Bash completion  [\#255](https://github.com/mvndaemon/mvnd/pull/255) ([ppalaga](https://github.com/ppalaga))
- Maven like behaviour and other small improvements [\#253](https://github.com/mvndaemon/mvnd/pull/253) ([gnodet](https://github.com/gnodet))
- Use client terminal width to format help [\#252](https://github.com/mvndaemon/mvnd/pull/252) ([gnodet](https://github.com/gnodet))
- Document --status, --stop and --purge in -h/--help  [\#250](https://github.com/mvndaemon/mvnd/pull/250) ([ppalaga](https://github.com/ppalaga))
- Fix the mvnd.sh client log configuration, fixes \#246 [\#247](https://github.com/mvndaemon/mvnd/pull/247) ([gnodet](https://github.com/gnodet))
- Fix project name and number of projects displayed on the client, fixe… [\#245](https://github.com/mvndaemon/mvnd/pull/245) ([gnodet](https://github.com/gnodet))
- Let -h/--help display also mvnd specific options \#243 [\#244](https://github.com/mvndaemon/mvnd/pull/244) ([ppalaga](https://github.com/ppalaga))
- mvnd --help produces no output \#238 [\#242](https://github.com/mvndaemon/mvnd/pull/242) ([ppalaga](https://github.com/ppalaga))
- Upgrade JLine [\#258](https://github.com/mvndaemon/mvnd/pull/258) ([gnodet](https://github.com/gnodet))
- Bump groovy.version from 3.0.0 to 3.0.7 [\#254](https://github.com/mvndaemon/mvnd/pull/254) ([dependabot[bot]](https://github.com/apps/dependabot))

## [0.1.1](https://github.com/mvndaemon/mvnd/tree/0.1.1) (2020-11-27)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.1.0...0.1.1)

**Closed issues:**

- mvn -Dmvnd.noBuffering=true has no effect [\#239](https://github.com/mvndaemon/mvnd/issues/239)

**Merged pull requests:**

- mvn -Dmvnd.noBuffering=true has no effect  [\#240](https://github.com/mvndaemon/mvnd/pull/240) ([ppalaga](https://github.com/ppalaga))

## [0.1.0](https://github.com/mvndaemon/mvnd/tree/0.1.0) (2020-11-18)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.12...0.1.0)

**Implemented enhancements:**

- The daemon created by the client should survive if the client is interrupted using Ctrl+C [\#193](https://github.com/mvndaemon/mvnd/issues/193)

**Closed issues:**

- Performance regression after 668d4e4 [\#231](https://github.com/mvndaemon/mvnd/issues/231)
- The daemon is probably leaking memory [\#18](https://github.com/mvndaemon/mvnd/issues/18)
- Move mvnd logback config file into \[MVND\_HOME\]/conf and use the standard name for the mvn specific config file [\#226](https://github.com/mvndaemon/mvnd/issues/226)
- Duration properties are not passed correctly to the daemon [\#225](https://github.com/mvndaemon/mvnd/issues/225)
- When the build does not produce any output, the elapsed time can be sluggish [\#224](https://github.com/mvndaemon/mvnd/issues/224)
- Use the `mvnd.` prefix for all property names [\#221](https://github.com/mvndaemon/mvnd/issues/221)
- Exit code not propagated from the daemon to mvnd client [\#220](https://github.com/mvndaemon/mvnd/issues/220)
- pom.xml changes not honored \(post 0.0.10 regression\) [\#218](https://github.com/mvndaemon/mvnd/issues/218)
- Messages associated with projectId from the previous build in the terminal and daemon log [\#216](https://github.com/mvndaemon/mvnd/issues/216)
- Provide an automatic purge of daemon logs [\#196](https://github.com/mvndaemon/mvnd/issues/196)
- Document that mvnd may conflict with oh-my-zsh's alias for `mvn deploy` [\#148](https://github.com/mvndaemon/mvnd/issues/148)
- ${my.property:-default} style defaults defined in logback.xml do not work [\#39](https://github.com/mvndaemon/mvnd/issues/39)

**Merged pull requests:**

- Upgrade to GraalVM 20.3.0 [\#235](https://github.com/mvndaemon/mvnd/pull/235) ([ppalaga](https://github.com/ppalaga))
- Output revision with -v/--version [\#233](https://github.com/mvndaemon/mvnd/pull/233) ([ppalaga](https://github.com/ppalaga))
- Avoid environment lookups and value conversions on hot paths [\#232](https://github.com/mvndaemon/mvnd/pull/232) ([ppalaga](https://github.com/ppalaga))
- Use more recent version of DeLaGuardo/setup-graalvm action [\#230](https://github.com/mvndaemon/mvnd/pull/230) ([gnodet](https://github.com/gnodet))
- Make sure our CachingProjectBuilder is used, fixes \#218 [\#228](https://github.com/mvndaemon/mvnd/pull/228) ([gnodet](https://github.com/gnodet))
- Move mvnd logback config file into \[MVND\_HOME\]/conf and use the stand… [\#227](https://github.com/mvndaemon/mvnd/pull/227) ([gnodet](https://github.com/gnodet))
- Clean the names of properties, fixes \#221 [\#223](https://github.com/mvndaemon/mvnd/pull/223) ([gnodet](https://github.com/gnodet))
- Exit code not propagated from the daemon to mvnd client [\#222](https://github.com/mvndaemon/mvnd/pull/222) ([ppalaga](https://github.com/ppalaga))
- Messages associated with projectId from the previous build in the ter… [\#217](https://github.com/mvndaemon/mvnd/pull/217) ([ppalaga](https://github.com/ppalaga))
- Ignore INT and TSTP signals in the daemon [\#214](https://github.com/mvndaemon/mvnd/pull/214) ([gnodet](https://github.com/gnodet))
- Automatic purge of daemon logs [\#213](https://github.com/mvndaemon/mvnd/pull/213) ([gnodet](https://github.com/gnodet))

## [0.0.12](https://github.com/mvndaemon/mvnd/tree/0.0.12) (2020-11-12)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.11...0.0.12)

**Implemented enhancements:**

- Fail fast if the daemon can not be started [\#162](https://github.com/mvndaemon/mvnd/issues/162)
- Client: have just one event queue and one consuming thread [\#133](https://github.com/mvndaemon/mvnd/issues/133)
- Opt out of implicit -T [\#132](https://github.com/mvndaemon/mvnd/issues/132)
- Better support for dumb terminals [\#131](https://github.com/mvndaemon/mvnd/issues/131)
- Option to default to a simple log when using a single thread [\#116](https://github.com/mvndaemon/mvnd/issues/116)

**Fixed bugs:**

- Should support core extensions [\#114](https://github.com/mvndaemon/mvnd/issues/114)

**Closed issues:**

- NoClassDefFoundError: org.slf4j.LoggerFactory [\#200](https://github.com/mvndaemon/mvnd/issues/200)
- Support multiple level of properties file, discriminate between daemons, allow configuring min/max memory [\#188](https://github.com/mvndaemon/mvnd/issues/188)
- Support for interactive sessions [\#180](https://github.com/mvndaemon/mvnd/issues/180)
- Do not create runtime files/directories in installation directory [\#179](https://github.com/mvndaemon/mvnd/issues/179)
- Allow passing additional jvm args to the daemon [\#174](https://github.com/mvndaemon/mvnd/issues/174)
- mvndaemon.org domain transfer [\#153](https://github.com/mvndaemon/mvnd/issues/153)
- Implement build cancellation [\#127](https://github.com/mvndaemon/mvnd/issues/127)
- Provide a `mvnd.daemon` option to disable daemon for easier debugging [\#43](https://github.com/mvndaemon/mvnd/issues/43)

**Merged pull requests:**

- Store registry under ~/.m2 where we already have mvnd.properties [\#211](https://github.com/mvndaemon/mvnd/pull/211) ([ppalaga](https://github.com/ppalaga))
- Make TerminalOutput.dumb final, activate TerminalOutput.noBuffering with -B/--batch-mode, mvnd.rollingWindowSize default 0 [\#209](https://github.com/mvndaemon/mvnd/pull/209) ([ppalaga](https://github.com/ppalaga))
- Fix the readInputLoop so that messages are all delivered and processe… [\#205](https://github.com/mvndaemon/mvnd/pull/205) ([gnodet](https://github.com/gnodet))
- Improve display with an easy opt-out option and support for dumb term… [\#204](https://github.com/mvndaemon/mvnd/pull/204) ([gnodet](https://github.com/gnodet))
- Minor improvements [\#203](https://github.com/mvndaemon/mvnd/pull/203) ([gnodet](https://github.com/gnodet))
- Pad the status line elements so that they do not move as the build is progressing [\#202](https://github.com/mvndaemon/mvnd/pull/202) ([ppalaga](https://github.com/ppalaga))
- Reduce the number of Message subclasses [\#201](https://github.com/mvndaemon/mvnd/pull/201) ([ppalaga](https://github.com/ppalaga))
- Implement build cancelation [\#199](https://github.com/mvndaemon/mvnd/pull/199) ([ppalaga](https://github.com/ppalaga))
- Client: have just one event queue and one consuming thread  [\#198](https://github.com/mvndaemon/mvnd/pull/198) ([ppalaga](https://github.com/ppalaga))
- Non daemon option, fixes \#43 [\#197](https://github.com/mvndaemon/mvnd/pull/197) ([gnodet](https://github.com/gnodet))
- Minor refactorings [\#192](https://github.com/mvndaemon/mvnd/pull/192) ([ppalaga](https://github.com/ppalaga))
- Allow passing additional jvm args to the daemon, fixes \#174 [\#191](https://github.com/mvndaemon/mvnd/pull/191) ([gnodet](https://github.com/gnodet))
- Refactor [\#190](https://github.com/mvndaemon/mvnd/pull/190) ([gnodet](https://github.com/gnodet))
- Refactor usage of properties in the client / daemon, fixes \#188 [\#189](https://github.com/mvndaemon/mvnd/pull/189) ([gnodet](https://github.com/gnodet))
- Support for interactive sessions \#180 [\#187](https://github.com/mvndaemon/mvnd/pull/187) ([gnodet](https://github.com/gnodet))
- Add JVM memory expiration checks, use a specific timeout for checks [\#186](https://github.com/mvndaemon/mvnd/pull/186) ([gnodet](https://github.com/gnodet))
- Fix spelling error in console logs [\#185](https://github.com/mvndaemon/mvnd/pull/185) ([dsyer](https://github.com/dsyer))
- Deliver the same slf4j version as Maven 3.6.3 and manage jcl-over-slf… [\#184](https://github.com/mvndaemon/mvnd/pull/184) ([ppalaga](https://github.com/ppalaga))
- Issue 162 [\#182](https://github.com/mvndaemon/mvnd/pull/182) ([gnodet](https://github.com/gnodet))
- Issue 114 [\#181](https://github.com/mvndaemon/mvnd/pull/181) ([gnodet](https://github.com/gnodet))
- Separate BuildStarted message to avoid serializing via Propertries.\[l… [\#178](https://github.com/mvndaemon/mvnd/pull/178) ([ppalaga](https://github.com/ppalaga))
- More fine grained status on build start [\#177](https://github.com/mvndaemon/mvnd/pull/177) ([ppalaga](https://github.com/ppalaga))
- User's preference for -T can be stored as mvnd.threads in ~/.m2/mvnd.… [\#176](https://github.com/mvndaemon/mvnd/pull/176) ([ppalaga](https://github.com/ppalaga))

## [0.0.11](https://github.com/mvndaemon/mvnd/tree/0.0.11) (2020-10-29)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.10...0.0.11)

**Fixed bugs:**

- Problem with the native client running in Cygwin [\#156](https://github.com/mvndaemon/mvnd/issues/156)
- Killed or crashed daemon process kept in the registry until mvnd --stop is called [\#154](https://github.com/mvndaemon/mvnd/issues/154)

**Closed issues:**

- exec-maven-plugin fails to run maven wrapper when run via maven daemon [\#171](https://github.com/mvndaemon/mvnd/issues/171)
- Error when using axistools-maven-plugin [\#87](https://github.com/mvndaemon/mvnd/issues/87)
- Support for failsafe? [\#86](https://github.com/mvndaemon/mvnd/issues/86)
- ProjectBuildLogAppender not found when starting the daemon [\#165](https://github.com/mvndaemon/mvnd/issues/165)
- mvnd --status complains about Unexpected output of ps -o rss= when the process is not alive anymore [\#163](https://github.com/mvndaemon/mvnd/issues/163)
- mvnd native executable is not passing -Dkey=val to the daemon [\#157](https://github.com/mvndaemon/mvnd/issues/157)
- Messages bigger than 65535 utf code points crash the server [\#155](https://github.com/mvndaemon/mvnd/issues/155)
- Add a spinner, progress or something indicating that the build is going on [\#150](https://github.com/mvndaemon/mvnd/issues/150)
- Provide a homebrew package [\#106](https://github.com/mvndaemon/mvnd/issues/106)
- Warning "Unable to create a system terminal" when running maven daemon [\#36](https://github.com/mvndaemon/mvnd/issues/36)

**Merged pull requests:**

- Cygwin support, fixes \#156 [\#173](https://github.com/mvndaemon/mvnd/pull/173) ([gnodet](https://github.com/gnodet))
- Improve terminal output [\#172](https://github.com/mvndaemon/mvnd/pull/172) ([ppalaga](https://github.com/ppalaga))
- Fixup 67d5b4b Remove leftovers [\#170](https://github.com/mvndaemon/mvnd/pull/170) ([ppalaga](https://github.com/ppalaga))
- Improvements [\#169](https://github.com/mvndaemon/mvnd/pull/169) ([gnodet](https://github.com/gnodet))
- Use a single cache removal strategy [\#168](https://github.com/mvndaemon/mvnd/pull/168) ([gnodet](https://github.com/gnodet))
- ProjectBuildLogAppender not found when starting the daemon \#165 [\#166](https://github.com/mvndaemon/mvnd/pull/166) ([ppalaga](https://github.com/ppalaga))
- Killed or crashed daemon process kept in the registry until mvnd --st… [\#164](https://github.com/mvndaemon/mvnd/pull/164) ([ppalaga](https://github.com/ppalaga))
- mvnd native executable is not passing -Dkey=val to the daemon [\#159](https://github.com/mvndaemon/mvnd/pull/159) ([ppalaga](https://github.com/ppalaga))
- Improve the error message that reports a daemon crash [\#158](https://github.com/mvndaemon/mvnd/pull/158) ([ppalaga](https://github.com/ppalaga))
- Upgrade to jansi 2.0, fix windows output [\#151](https://github.com/mvndaemon/mvnd/pull/151) ([gnodet](https://github.com/gnodet))

## [0.0.10](https://github.com/mvndaemon/mvnd/tree/0.0.10) (2020-10-26)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.9...0.0.10)

**Closed issues:**

- Provide build output when cancelling a job [\#142](https://github.com/mvndaemon/mvnd/issues/142)
- mvnd --status throws NumberFormatException in 0.0.9 [\#147](https://github.com/mvndaemon/mvnd/issues/147)

**Merged pull requests:**

- mvnd --status throws NumberFormatException in 0.0.9 [\#149](https://github.com/mvndaemon/mvnd/pull/149) ([ppalaga](https://github.com/ppalaga))
- Add Twitter badge to README [\#146](https://github.com/mvndaemon/mvnd/pull/146) ([ppalaga](https://github.com/ppalaga))
- Mention Homebrew tap in the README, show asciinema cast instead of a … [\#145](https://github.com/mvndaemon/mvnd/pull/145) ([ppalaga](https://github.com/ppalaga))

## [0.0.9](https://github.com/mvndaemon/mvnd/tree/0.0.9) (2020-10-25)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.8...0.0.9)

**Closed issues:**

- Split daemon module into daemon and dist [\#130](https://github.com/mvndaemon/mvnd/issues/130)
- mvnd --status to display memory usage [\#129](https://github.com/mvndaemon/mvnd/issues/129)
- Test with two threads at least [\#128](https://github.com/mvndaemon/mvnd/issues/128)
- Warn if the environment of the client does not match the environment of the daemon [\#122](https://github.com/mvndaemon/mvnd/issues/122)
- Give a meaningful name to the mvnd process [\#118](https://github.com/mvndaemon/mvnd/issues/118)
- Building... output detail of how many modules in total and left to build [\#112](https://github.com/mvndaemon/mvnd/issues/112)
- Run with min 1 cpu core left to the user [\#111](https://github.com/mvndaemon/mvnd/issues/111)
- Connection timeout when trying to execute any build [\#63](https://github.com/mvndaemon/mvnd/issues/63)
- Client hangs forever if the daemon crashes [\#47](https://github.com/mvndaemon/mvnd/issues/47)

**Merged pull requests:**

- Remove the superfluous Serializer interface and its implemetation [\#141](https://github.com/mvndaemon/mvnd/pull/141) ([ppalaga](https://github.com/ppalaga))
- Do not add mvnd-client.jar to daemon's class path [\#140](https://github.com/mvndaemon/mvnd/pull/140) ([ppalaga](https://github.com/ppalaga))
- Have unique test project module names [\#139](https://github.com/mvndaemon/mvnd/pull/139) ([ppalaga](https://github.com/ppalaga))
- Split daemon module into daemon and dist \#130 [\#138](https://github.com/mvndaemon/mvnd/pull/138) ([ppalaga](https://github.com/ppalaga))
- Polish client status line [\#137](https://github.com/mvndaemon/mvnd/pull/137) ([ppalaga](https://github.com/ppalaga))
- mvnd --status to display memory usage \#129 [\#136](https://github.com/mvndaemon/mvnd/pull/136) ([ppalaga](https://github.com/ppalaga))
- Test with two threads at least \#128 [\#135](https://github.com/mvndaemon/mvnd/pull/135) ([ppalaga](https://github.com/ppalaga))
- Simplify logging [\#134](https://github.com/mvndaemon/mvnd/pull/134) ([ppalaga](https://github.com/ppalaga))
- Improvements [\#126](https://github.com/mvndaemon/mvnd/pull/126) ([gnodet](https://github.com/gnodet))
- Display warning in case of environment mismatch \#122 [\#125](https://github.com/mvndaemon/mvnd/pull/125) ([gnodet](https://github.com/gnodet))
- Improvements [\#124](https://github.com/mvndaemon/mvnd/pull/124) ([gnodet](https://github.com/gnodet))
- Issue 47 [\#123](https://github.com/mvndaemon/mvnd/pull/123) ([gnodet](https://github.com/gnodet))
- Fixup \#111 Document the number of utilized cores and use 1 core at least [\#121](https://github.com/mvndaemon/mvnd/pull/121) ([ppalaga](https://github.com/ppalaga))
- Rename ServerMain to MavenDaemon to be more explicit, fixes \#118 [\#120](https://github.com/mvndaemon/mvnd/pull/120) ([gnodet](https://github.com/gnodet))
- Leave 1 processor unused on the daemon by default, fixes \#111 [\#119](https://github.com/mvndaemon/mvnd/pull/119) ([gnodet](https://github.com/gnodet))
- Improve progress display [\#113](https://github.com/mvndaemon/mvnd/pull/113) ([gnodet](https://github.com/gnodet))
- Skip tests when releasing [\#110](https://github.com/mvndaemon/mvnd/pull/110) ([ppalaga](https://github.com/ppalaga))

## [0.0.8](https://github.com/mvndaemon/mvnd/tree/0.0.8) (2020-10-19)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.7...0.0.8)

**Closed issues:**

- Unnecessary directory in the 0.0.7 zip archive [\#107](https://github.com/mvndaemon/mvnd/issues/107)

**Merged pull requests:**

- Upload the artifacts from the correct directory [\#109](https://github.com/mvndaemon/mvnd/pull/109) ([ppalaga](https://github.com/ppalaga))
- Unnecessary directory in the 0.0.7 zip archive \#107 [\#108](https://github.com/mvndaemon/mvnd/pull/108) ([ppalaga](https://github.com/ppalaga))

## [0.0.7](https://github.com/mvndaemon/mvnd/tree/0.0.7) (2020-10-19)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.6...0.0.7)

**Closed issues:**

- The system streams should be captured and redirected to the client with a per-thread association to the module being build [\#100](https://github.com/mvndaemon/mvnd/issues/100)
- Isolate the integration tests from the local environment [\#97](https://github.com/mvndaemon/mvnd/issues/97)
- Add mvn.cmd [\#93](https://github.com/mvndaemon/mvnd/issues/93)
- Test a scenario using mvn [\#92](https://github.com/mvndaemon/mvnd/issues/92)
- Re-layout the distro so that mvn is not in bin [\#91](https://github.com/mvndaemon/mvnd/issues/91)
- Replace deprecated GitHub actions commands [\#85](https://github.com/mvndaemon/mvnd/issues/85)
- The output of modules being built in parallel is interleaved [\#78](https://github.com/mvndaemon/mvnd/issues/78)
- Show test output while running [\#77](https://github.com/mvndaemon/mvnd/issues/77)
- Explain project better in README [\#75](https://github.com/mvndaemon/mvnd/issues/75)
- The test output is missing in the console [\#21](https://github.com/mvndaemon/mvnd/issues/21)

**Merged pull requests:**

- Issue 100 [\#105](https://github.com/mvndaemon/mvnd/pull/105) ([gnodet](https://github.com/gnodet))
- Replace deprecated GitHub actions commands \#85 [\#104](https://github.com/mvndaemon/mvnd/pull/104) ([ppalaga](https://github.com/ppalaga))
- Isolate the integration tests from the local environment [\#101](https://github.com/mvndaemon/mvnd/pull/101) ([ppalaga](https://github.com/ppalaga))
- Partial revert to fix windows integration test [\#99](https://github.com/mvndaemon/mvnd/pull/99) ([gnodet](https://github.com/gnodet))
- Add NOTICE LICENSE and README to the distro [\#98](https://github.com/mvndaemon/mvnd/pull/98) ([ppalaga](https://github.com/ppalaga))
- Re-layout the distro so that mvn is not in bin [\#96](https://github.com/mvndaemon/mvnd/pull/96) ([ppalaga](https://github.com/ppalaga))
- Test a scenario using mvn \#92 [\#95](https://github.com/mvndaemon/mvnd/pull/95) ([ppalaga](https://github.com/ppalaga))
- Improvements [\#94](https://github.com/mvndaemon/mvnd/pull/94) ([gnodet](https://github.com/gnodet))
- Honor the -X / --debug / --quiet arguments on the command line [\#90](https://github.com/mvndaemon/mvnd/pull/90) ([gnodet](https://github.com/gnodet))
- Fix mvn [\#89](https://github.com/mvndaemon/mvnd/pull/89) ([gnodet](https://github.com/gnodet))
- Fix display [\#88](https://github.com/mvndaemon/mvnd/pull/88) ([gnodet](https://github.com/gnodet))
- Use Visual Studio 2019 pre-installed on Windows CI workers to save some [\#84](https://github.com/mvndaemon/mvnd/pull/84) ([ppalaga](https://github.com/ppalaga))
- Use a maven proxy for integration tests to speed them up [\#83](https://github.com/mvndaemon/mvnd/pull/83) ([gnodet](https://github.com/gnodet))
- Improvements [\#81](https://github.com/mvndaemon/mvnd/pull/81) ([gnodet](https://github.com/gnodet))
- Replace the jpm library with the jdk ProcessHandle interface, \#36 [\#80](https://github.com/mvndaemon/mvnd/pull/80) ([gnodet](https://github.com/gnodet))
- Provide smarter output on the client, fixes \#77 [\#79](https://github.com/mvndaemon/mvnd/pull/79) ([gnodet](https://github.com/gnodet))
- Explain project better in README \#75 [\#76](https://github.com/mvndaemon/mvnd/pull/76) ([ppalaga](https://github.com/ppalaga))

## [0.0.6](https://github.com/mvndaemon/mvnd/tree/0.0.6) (2020-09-29)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.5...0.0.6)

**Closed issues:**

- Goals of mvnd [\#71](https://github.com/mvndaemon/mvnd/issues/71)
- CachingProjectBuilder ignored [\#72](https://github.com/mvndaemon/mvnd/issues/72)
- Keep a changelog file [\#64](https://github.com/mvndaemon/mvnd/issues/64)

**Merged pull requests:**

- Wait for the deamon to become idle before rebuilding in UpgradesInBom… [\#74](https://github.com/mvndaemon/mvnd/pull/74) ([ppalaga](https://github.com/ppalaga))
- Added a changelog automatic update gh action [\#70](https://github.com/mvndaemon/mvnd/pull/70) ([oscerd](https://github.com/oscerd))
- Fixup publishing new versions via sdkman vendor API \#67 [\#69](https://github.com/mvndaemon/mvnd/pull/69) ([ppalaga](https://github.com/ppalaga))
-  CachingProjectBuilder ignored [\#73](https://github.com/mvndaemon/mvnd/pull/73) ([ppalaga](https://github.com/ppalaga))

## [0.0.5](https://github.com/mvndaemon/mvnd/tree/0.0.5) (2020-09-17)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.4...0.0.5)

**Closed issues:**

- Publish new versions via sdkman vendor API [\#67](https://github.com/mvndaemon/mvnd/issues/67)
- Cannot re-use daemon with sdkman java 8.0.265.hs-adpt [\#65](https://github.com/mvndaemon/mvnd/issues/65)
- List mvnd on sdkman.io [\#48](https://github.com/mvndaemon/mvnd/issues/48)

**Merged pull requests:**

- Publish new versions via sdkman vendor API [\#68](https://github.com/mvndaemon/mvnd/pull/68) ([ppalaga](https://github.com/ppalaga))
- Cannot re-use daemon with sdkman java 8.0.265.hs-adpt [\#66](https://github.com/mvndaemon/mvnd/pull/66) ([ppalaga](https://github.com/ppalaga))
- Upgrade to GraalVM 20.2.0 [\#62](https://github.com/mvndaemon/mvnd/pull/62) ([ppalaga](https://github.com/ppalaga))

## [0.0.4](https://github.com/mvndaemon/mvnd/tree/0.0.4) (2020-08-20)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.3...0.0.4)

**Closed issues:**

- Question: when running mvnd, it looks like regular mvn is still running [\#60](https://github.com/mvndaemon/mvnd/issues/60)
- Question: is there a way to limit the concurrency? [\#59](https://github.com/mvndaemon/mvnd/issues/59)

**Merged pull requests:**

- Allow \<mvnd.builder.rule\> entries to be separated by whitespace [\#61](https://github.com/mvndaemon/mvnd/pull/61) ([ppalaga](https://github.com/ppalaga))

## [0.0.3](https://github.com/mvndaemon/mvnd/tree/0.0.3) (2020-08-15)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.2...0.0.3)

**Closed issues:**

- Require Java 8+ instead of Java 11+ at runtime [\#56](https://github.com/mvndaemon/mvnd/issues/56)
- Using MAVEN\_HOME may clash with other tools [\#53](https://github.com/mvndaemon/mvnd/issues/53)
- Could not notify CliPluginRealmCache [\#49](https://github.com/mvndaemon/mvnd/issues/49)

**Merged pull requests:**

- Use amd64 arch label also on Mac [\#58](https://github.com/mvndaemon/mvnd/pull/58) ([ppalaga](https://github.com/ppalaga))

## [0.0.2](https://github.com/mvndaemon/mvnd/tree/0.0.2) (2020-08-14)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/0.0.1...0.0.2)

**Merged pull requests:**

- Fix \#56 Require Java 8+ instead of Java 11+ at runtime [\#57](https://github.com/mvndaemon/mvnd/pull/57) ([ppalaga](https://github.com/ppalaga))
- Include native clients in platform specific distros [\#55](https://github.com/mvndaemon/mvnd/pull/55) ([ppalaga](https://github.com/ppalaga))
- Fix \#53 Using MAVEN\_HOME may clash with other tools [\#54](https://github.com/mvndaemon/mvnd/pull/54) ([ppalaga](https://github.com/ppalaga))
- Add curl -L flag to cope with redirects [\#51](https://github.com/mvndaemon/mvnd/pull/51) ([fvaleri](https://github.com/fvaleri))
- Fix \#49 Could not notify CliPluginRealmCache [\#50](https://github.com/mvndaemon/mvnd/pull/50) ([ppalaga](https://github.com/ppalaga))

## [0.0.1](https://github.com/mvndaemon/mvnd/tree/0.0.1) (2020-07-30)

[Full Changelog](https://github.com/mvndaemon/mvnd/compare/844f3ddd7f4278b2ba097d817def4c3b46d574e7...0.0.1)

**Closed issues:**

- Running maven daemon fails on windows [\#35](https://github.com/mvndaemon/mvnd/issues/35)
- Add some integration tests [\#23](https://github.com/mvndaemon/mvnd/issues/23)
- Class loader clash during Quarkus augmentation [\#22](https://github.com/mvndaemon/mvnd/issues/22)
- Allow to plug a custom rule resolver  [\#19](https://github.com/mvndaemon/mvnd/issues/19)
- Chaotic output if the console's height is less then the number of threads [\#17](https://github.com/mvndaemon/mvnd/issues/17)
- Concurrency issues while handling log events in the daemon [\#16](https://github.com/mvndaemon/mvnd/issues/16)
- Do not display exceptions stack trace when trying to stop already stopped daemons [\#15](https://github.com/mvndaemon/mvnd/issues/15)
- Concurrent access to the local repository [\#14](https://github.com/mvndaemon/mvnd/issues/14)
- Support for hidden dependencies [\#12](https://github.com/mvndaemon/mvnd/issues/12)
- mvnd should fail cleanly with unknown CLI options [\#11](https://github.com/mvndaemon/mvnd/issues/11)
- Properly configure logging in the client [\#10](https://github.com/mvndaemon/mvnd/issues/10)
- mvnd does not pick the BoM from the source tree [\#9](https://github.com/mvndaemon/mvnd/issues/9)
- Add a correct NOTICE file [\#8](https://github.com/mvndaemon/mvnd/issues/8)
- Do not require the mvn in PATH to come from mvnd dist [\#7](https://github.com/mvndaemon/mvnd/issues/7)
- Provide an option to kill/stop the daemon [\#6](https://github.com/mvndaemon/mvnd/issues/6)
- Options / system properties are not reset in the daemon after a build [\#5](https://github.com/mvndaemon/mvnd/issues/5)
- Add a LICENSE file [\#4](https://github.com/mvndaemon/mvnd/issues/4)
- The mvn output appears all at once at the very end [\#3](https://github.com/mvndaemon/mvnd/issues/3)
- mvnd -version does not work [\#2](https://github.com/mvndaemon/mvnd/issues/2)
- mvnd fails if there is no .mvn/ dir in the user home [\#42](https://github.com/mvndaemon/mvnd/issues/42)
- Cannot clean on Windows as long as mvnd keeps a plugin from the tree loaded [\#40](https://github.com/mvndaemon/mvnd/issues/40)
- Maven mojo change ignored [\#33](https://github.com/mvndaemon/mvnd/issues/33)
- differences between `mvn clean install` and `mvnd clean install` [\#25](https://github.com/mvndaemon/mvnd/issues/25)

**Merged pull requests:**

- Fix \#42 mvnd fails if there is no .mvn/ dir in the user home [\#46](https://github.com/mvndaemon/mvnd/pull/46) ([ppalaga](https://github.com/ppalaga))
- Fix \#40 Cannot clean on Windows as long as mvnd keeps a plugin from t… [\#45](https://github.com/mvndaemon/mvnd/pull/45) ([ppalaga](https://github.com/ppalaga))
- Add code formatter plugins [\#44](https://github.com/mvndaemon/mvnd/pull/44) ([ppalaga](https://github.com/ppalaga))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
