# Redis Connector Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Security

## [0.0.2] 2020-04-13
- Prevents retry on connect
- Throw exception in case of Redis connection failure
- Facade for Redis client
- Actions use async version of Redis client api
- Register API Builder hooks for graceful disconnect
- Reusable utils to register context for actions

## [0.0.1] 2020-04-08
### Added
- Initial version