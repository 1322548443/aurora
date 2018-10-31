![aurora](./aurora.png "aurora")

# aurora

[![Build Status](https://travis-ci.com/xuri/aurora.svg?branch=master)](https://travis-ci.com/xuri/aurora)
[![Backers on Open Collective](https://opencollective.com/aurora/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/aurora/sponsors/badge.svg)](#sponsors) [![Code Coverage](https://codecov.io/gh/xuri/aurora/branch/master/graph/badge.svg)](https://codecov.io/gh/xuri/aurora)
[![Downloads](https://img.shields.io/github/downloads/xuri/aurora/total.svg)](https://github.com/xuri/aurora/releases)
[![Go Report Card](https://goreportcard.com/badge/github.com/xuri/aurora)](https://goreportcard.com/report/github.com/xuri/aurora)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://github.com/xuri/aurora/blob/master/LICENSE)
[![Release](https://img.shields.io/github/release/xuri/aurora.svg?label=Release)](https://github.com/xuri/aurora/releases)

## Overview

aurora is a web-based Beanstalk queue server console written in Go and works on macOS, Linux and Windows machines. Main idea behind using Go for backend development is to utilize ability of the compiler to produce zero-dependency binaries for multiple platforms. aurora was created as an attempt to build very simple and portable application to work with local or remote Beanstalk server.

[See application screenshots](https://github.com/xuri/aurora/wiki)

## Features

- Cross-platform support macOS/Linux/Windows 32/64-bit
- Simple installation (distributed as a single binary)
- Zero dependencies
- Common list of servers in config for all users + optional Basic Auth
- Full list of available tubes
- Complete statistics about jobs in tubes
- Realtime auto-update with highlighting of changed values
- You can view jobs in ready/delayed/buried states in every tube
- You can add/kick/delete jobs in every tube
- You can select multiple tubes by regExp and clear them
- You can set statistics overview graph for every tube
- You can move jobs between tubes
- Ability to Pause tubes
- Search jobs data field
- Customizable UI (code highlighter, choose columns, edit auto refresh seconds, pause tube seconds)

## Installation

[Precompiled binaries](https://github.com/xuri/aurora/releases) for supported operating systems are available.

## Contributing

Contributions are welcome! Open a pull request to fix a bug, or open an issue to discuss a new feature or change.

## Todo

- Handle 404 error page
- Filter the tubes by name in the overview
- Logout support when Basic Auth has been enabled
- Custom job content hightlight display theme support
- Cookies control, each user can add its own personal Beanstalk server

## Credits

- Client for beanstalk use [beanstalkd/go-beanstalk](https://github.com/beanstalkd/go-beanstalk)
- TOML parser use [BurntSushi/toml](https://github.com/BurntSushi/toml)
- Web UI originally by [ptrofimov/beanstalk_console](https://github.com/ptrofimov/beanstalk_console)
- The logo is originally by [Ali Irawan](http://www.solusiteknologi.co.id/using-supervisord-beanstalkd-laravel/). This artwork is an adaptation.

## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].

[![Contributors](https://opencollective.com/aurora/contributors.svg?width=890&button=false)](https://github.com/xuri/aurora/graphs/contributors)

## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/aurora#backer)]

[![Backers](https://opencollective.com/aurora/backers.svg?width=890)](https://opencollective.com/aurora#backers)

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/aurora#sponsor)]

## Licenses

This program is under the terms of the MIT License. See [LICENSE](https://github.com/xuri/aurora/blob/master/LICENSE) for the full license text.