# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v9.0.0](https://github.com/voxpupuli/puppet-logstash/tree/v9.0.0) (2025-06-27)

[Full Changelog](https://github.com/voxpupuli/puppet-logstash/compare/v8.1.0...v9.0.0)

**Breaking changes:**

- Drop Ubuntu 18.04 and 20.04 [\#463](https://github.com/voxpupuli/puppet-logstash/pull/463) ([h-haaks](https://github.com/h-haaks))
- Drop CentOS 7 and 8 [\#462](https://github.com/voxpupuli/puppet-logstash/pull/462) ([h-haaks](https://github.com/h-haaks))
- Drop RedHat 7 [\#461](https://github.com/voxpupuli/puppet-logstash/pull/461) ([h-haaks](https://github.com/h-haaks))
- Drop Debian 10 [\#460](https://github.com/voxpupuli/puppet-logstash/pull/460) ([h-haaks](https://github.com/h-haaks))
- Remove EOL SLES 12 [\#457](https://github.com/voxpupuli/puppet-logstash/pull/457) ([thomas-merz](https://github.com/thomas-merz))

**Implemented enhancements:**

- Add Ubuntu 24.04 [\#465](https://github.com/voxpupuli/puppet-logstash/pull/465) ([h-haaks](https://github.com/h-haaks))
- Allow puppet/elastic\_stack 10.x [\#459](https://github.com/voxpupuli/puppet-logstash/pull/459) ([h-haaks](https://github.com/h-haaks))
- metadata.json: Add OpenVox [\#455](https://github.com/voxpupuli/puppet-logstash/pull/455) ([jstraw](https://github.com/jstraw))

**Closed issues:**

- module gets warnings when used with stdlib9. [\#428](https://github.com/voxpupuli/puppet-logstash/issues/428)

## [v8.1.0](https://github.com/voxpupuli/puppet-logstash/tree/v8.1.0) (2024-03-26)

[Full Changelog](https://github.com/voxpupuli/puppet-logstash/compare/v8.0.0...v8.1.0)

**Implemented enhancements:**

- Add Rocky/AlmaLinux/OracleLinux support [\#442](https://github.com/voxpupuli/puppet-logstash/pull/442) ([bastelfreak](https://github.com/bastelfreak))
- Add Ubuntu 22.04 support [\#441](https://github.com/voxpupuli/puppet-logstash/pull/441) ([bastelfreak](https://github.com/bastelfreak))
- Add EL9 support [\#440](https://github.com/voxpupuli/puppet-logstash/pull/440) ([bastelfreak](https://github.com/bastelfreak))
- Add Debian 12 support [\#439](https://github.com/voxpupuli/puppet-logstash/pull/439) ([bastelfreak](https://github.com/bastelfreak))
- Don't hardcode the service provider [\#438](https://github.com/voxpupuli/puppet-logstash/pull/438) ([bastelfreak](https://github.com/bastelfreak))
- replace legacy `merge()` with native puppet code [\#437](https://github.com/voxpupuli/puppet-logstash/pull/437) ([bastelfreak](https://github.com/bastelfreak))

## [v8.0.0](https://github.com/voxpupuli/puppet-logstash/tree/v8.0.0) (2024-01-30)

[Full Changelog](https://github.com/voxpupuli/puppet-logstash/compare/v7.0.0...v8.0.0)

**Breaking changes:**

- Drop Puppet 6 support [\#424](https://github.com/voxpupuli/puppet-logstash/pull/424) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- bump elastic\_stack max version to \<10.0.0 [\#432](https://github.com/voxpupuli/puppet-logstash/pull/432) ([sandwitch](https://github.com/sandwitch))
- Add Puppet 8 support [\#427](https://github.com/voxpupuli/puppet-logstash/pull/427) ([bastelfreak](https://github.com/bastelfreak))
- puppetlabs/stdlib: Allow 9.x [\#426](https://github.com/voxpupuli/puppet-logstash/pull/426) ([bastelfreak](https://github.com/bastelfreak))

## [v7.0.0](https://github.com/voxpupuli/puppet-logstash/tree/v7.0.0) (2023-01-05)

[Full Changelog](https://github.com/voxpupuli/puppet-logstash/compare/6.1.5...v7.0.0)

**Breaking changes:**

- Fix option spelling in jvm.options template [\#412](https://github.com/voxpupuli/puppet-logstash/pull/412) ([travees](https://github.com/travees))

**Implemented enhancements:**

- allow overriding default jvm options [\#417](https://github.com/voxpupuli/puppet-logstash/pull/417) ([juliantaylor](https://github.com/juliantaylor))
- Add a parameter to override the plugin install user [\#414](https://github.com/voxpupuli/puppet-logstash/pull/414) ([thebeanogamer](https://github.com/thebeanogamer))
- New parameter for home directory [\#368](https://github.com/voxpupuli/puppet-logstash/pull/368) ([joernott](https://github.com/joernott))

**Closed issues:**

- Cannot override JVM options for plugins [\#381](https://github.com/voxpupuli/puppet-logstash/issues/381)

**Merged pull requests:**

- Finalize voxpupuli transition [\#420](https://github.com/voxpupuli/puppet-logstash/pull/420) ([h-haaks](https://github.com/h-haaks))
- metadata.json: Adjust modulename/GitHub URLs [\#416](https://github.com/voxpupuli/puppet-logstash/pull/416) ([bastelfreak](https://github.com/bastelfreak))
- migrate .fixtures.yml to git repos [\#410](https://github.com/voxpupuli/puppet-logstash/pull/410) ([bastelfreak](https://github.com/bastelfreak))
- puppet-lint: autofix [\#409](https://github.com/voxpupuli/puppet-logstash/pull/409) ([bastelfreak](https://github.com/bastelfreak))
- Stop using Travis CI [\#406](https://github.com/voxpupuli/puppet-logstash/pull/406) ([jmlrt](https://github.com/jmlrt))
- bump up dependencies [\#405](https://github.com/voxpupuli/puppet-logstash/pull/405) ([anesterova](https://github.com/anesterova))

## [6.1.5](https://github.com/voxpupuli/puppet-logstash/tree/6.1.5) (2018-11-13)

  Honour `restart_on_change` for startup files #377

6.1.4
  Use Upstart for init on Oracle Linux 6

6.1.3
  Allow puppetlabs-stdlib 5.x

6.1.2
  Set cwd to "/tmp" during plugin execs.

6.1.1
  Update init system handling.

6.1.0
  Support centralized pipeline management.

6.0.1
  Fix explicit versions like "5.6.2-1.noarch" #353

6.0.0
  Puppet 3 support removed. Minimum Puppet version is now 4.6.1.
  Puppet 5 supported.
  Logstash 6.x (and 5.x) supported.
  File permissions for config files now match those from the Logstash package.
  elastic/elastic_stack module is now used to manage repositories.
  Logstash multiple pipelines supported.
  Config files resources accept an explicit target path.

5.3.0
  Allow setting environment for plugin resources

5.2.0
  Allow 'http(s):// URLs for plugin install.

5.1.0
  Make config files be owned by root.
  Allow 'file://' URLs for plugin install.
  Sort lines in jvm.options for file.

5.0.4
  Expose $logstash::home_dir

5.0.3
  Sort startup_options to prevent triggering unneeded restarts.

5.0.2
  Do not autmatically add ".conf" to pipeline config filesnames.

5.0.1
  Trivial README update.

5.0.0
  Major re-write for Logstash 5.x.
  Drop support for Logstash <5.0.0.

0.6.4
  Puppet 4 support.

0.6.3
  Documentation updates only. Functionally identical to 0.6.2.

0.6.2
  Allow electrical/file_concat version 1.x.

0.6.1
  Restart service on pattern file change.
  Remove dependency on external PGP server.
  Fix circular dependency on plugin installation.
0.6.0
  Deprecates the logstash-contrib package.
  Supports Gem-based Logstash plugins.
  Not compatible with Logstash versions < 1.5.0.

0.5.1
  Updated system tests to work with LS 1.4.1
  Increase package download timeout
  Add option to use stages for the repo setup instead anchors

0.5.0
  Move beaker testing to use docker
  Large module update to work with the contrib package
  Refactored rspec testing
  Fix inline docs
  Added Puppet 3.5.0 testing
  Fix typo in group name variable ( PR #147 )
  Improve puppet module removal ( PR #149 )
  Reverted PR #149. Caused issues with package removal.
  added lsbdistid = Debian to rspec facts ( PR #146 )
  match other config perms with patterns ( PR #151 )

0.4.3
  Lower puppetlabs-stdlib depdency from 4.0.0 to 3.2.0
  Documentation improvements ( PR #132 #137 )
  Fixed yumrepo call to include description ( PR #138 )
  Added beaker testing
  Fixed bug that sometimes LS starts before all configs are processed.
  Ensure java is installed before installing the package when using package_url
  Fail fast when using package_url and repo config

0.4.2
  Fix config directory for config files to be inline with the init file of the packages
  Update readme ( thanks to PR #130 from phrawzty )
  Added repo management ( based on work of PR #121 from pcfens )

0.4.1
  ** Important Update **
  Ensure exec names are unique. This caused an issue when using the Elasticsearch Puppet module
  Removed a part in the package.pp that should have been removed ( missed with the rewrite )
  Missed a few bits of the rewrite.
  Updated readme to reflect reality regarding configfile define.

0.4.0
  ** NOTE: This is a backwards compability breaking release !! **
  Large rewrite of the entire module described below
  Make the core more dynamic for different service providers
  Add better testing and devided into different files
  Add different ways to install the package except from the repository ( puppet/http/https/ftp/file )
  Update java class to install openjdk 1.7
  Add validation of templates
  Added more test scenario's
  Added puppet parser validate task for added checking
  Improve module removing when set to absent
  Updated readme
  Doc improvements by dan ( phrawzty )
  Added define for managing pattern files
  Added define for managing plugins

0.3.4
  Fixing purging of created directories ( PR #61, #64 by Kayla Green and Jason Koppe )
  Documentation fixes ( PR #65, #67 by Kristian Glass and Andreas Paul )
  Making config dir configurable ( PR #70 by Justin Lambert )
  Permit HTTP(s) for downloading logstash ( PR #71 by Phil Fenstermacher )
  Ensure user/group is passed in the debian init file
  Spec cleanup ( PR #75 by Justin Lambert )
  set logstash logdir perms when using custom jar provider ( PR #74 by Justin Lambert )
  clean up installpath when updating jars ( PR #72 by Justin Lambert )
  fix wrong creates path at jar custom provider ( PR #83 by Daniel Werdermann )
  added 'in progress' for logstash version 1.2.x ( PR #87 by rtoma )
  Add small input/output examples ( PR #89 by Andreas Paul )
  Solving defaults file not being installed in some cases
  http download of jar should require $jardir ( PR #90 by Max Griffiths )
  add ability to install a logstash config file ( PR #93 by Justin Lambert )

0.3.3
  Enable puppet 3.2.x testing
  Fix issue that the config dir was missing in the init files
  Fix variable access deprecation warning ( PR #56 by Richard Peng )

0.3.2
  Fixing issue when using jar file without multi-instance feature
  Added rspec tests to cover this issue

0.3.1
  Missed changes for enabling/disabling multi-instance feature
  Adding a few spec tests for the multi-instance feature

0.3.0
  Update defines for Logstash 1.1.12
  Adding license file
  Deleted old init file removal to avoid issues. ( Issue #50 )
  Allow file owner/group to be variable ( Issue/PR #47 )
  Ensure log directory exists before starting ( PR #53 by Brian Lalor )
  Provide complete containment of the class ( PR #53 by Brian Lalor )
  Update rspec tests for new defines

0.2.0
  Update defines for logstash 1.1.10
  New feature for plugins to automatically transfer files ( Issue #24 )
  Create correct tmp dir ( Issue #35 )
  Change file modes to be more secure ( Issue #36 )
  Update defines for better input validation ( Issue #43 )
  Adding rspec tests for plugin defines
  Fix tmp dir Debian init script ( PR #44 by Dan Carley )

0.1.0
  Don't backup the Jar file or the symlink ( Issue #25 by Garth Kidd )
  First implementation of the multi-instance feature. This will break certain functionality.

0.0.6
  Fix issue that the init file was overwritten
  Ensure we install java first before starting logstash if enabled

0.0.5
  Adding spec tests
  Update Readme ( PR #20 by rjw1 )
  New feature to install java

0.0.4
  Rename Redhat to RedHat for init file ( PR #12 by pkubat )
  Adding Amazon as Operating system ( PR #12 by pkubat )
  Symlinking Jar file to generic name ( PR #12 by pkubat )
  Correting symlink ( PR #14 by Jeff Wong )

0.0.3
  Clarify jarfile usage and validation ( PR #6 by Garth Kidd )
  Add default Debian Init script when non provided and using custom source ( PR #7 by Garth Kidd )
  Add RedHat as OS type ( PR #8 by Dan )
  Skip init script when status = unmanaged ( PR #9 by Tavis Aitken )
  Refactored the custom provider part ( With help of Garth Kidd )

0.0.2
  Adding a way to provide jar and init file instead of depending on a package

0.0.1
  Initial release of the module


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
