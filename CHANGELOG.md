# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## API
The API consists of all public Kotlin types from `com.atlassian.performance.tools.concurrency.api` and its subpackages:

  * [source compatibility]
  * [binary compatibility]
  * [behavioral compatibility] with behavioral contracts expressed via Javadoc

[source compatibility]: http://cr.openjdk.java.net/~darcy/OpenJdkDevGuide/OpenJdkDevelopersGuide.v0.777.html#source_compatibility
[binary compatibility]: http://cr.openjdk.java.net/~darcy/OpenJdkDevGuide/OpenJdkDevelopersGuide.v0.777.html#binary_compatibility
[behavioral compatibility]: http://cr.openjdk.java.net/~darcy/OpenJdkDevGuide/OpenJdkDevelopersGuide.v0.777.html#behavioral_compatibility

## [Unreleased]
[Unreleased]: https://bitbucket.org/atlassian/concurrency/branches/compare/master%0Drelease-1.0.0

## [1.0.0] - 2018-08-30
[1.0.0]: https://bitbucket.org/atlassian/concurrency/branches/compare/release-1.0.0%0Drelease-0.0.2

### Changed
- Define the public API.

### Added
- License.

## [0.0.2] - 2018-08-02
[0.0.2]: https://bitbucket.org/atlassian/concurrency/branches/compare/release-0.0.2%0Drelease-0.0.1

### Fixed
- Improve the release process.

## [0.0.1] - 2018-07-27
[0.0.1]: https://bitbucket.org/atlassian/concurrency/branches/compare/release-0.0.1%0Dinitial-commit

### Added
- Migrate concurrency tracing and graceful termination from [JPT submodule].
- Add [README.md](README.md).
- Configure Bitbucket Pipelines.

[JPT submodule]: https://stash.atlassian.com/projects/JIRASERVER/repos/jira-performance-tests/browse/concurrency?at=bff5b4bb5e6d057940693b71b6540dad160529bd
