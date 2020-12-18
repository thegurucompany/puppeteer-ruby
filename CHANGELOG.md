### master [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.25...master)]

* xxx

### 0.0.25 [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.23...0.0.25)]

New feature:

* **Cookie** feature: `Page#set_cookie`, `Page#cookies`

### 0.0.23 [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.22...0.0.23)]

New feature:

* **GeoLocation** feature
* grant/clear permission

Bugfix/Improvement:

* Refactoring for events ([#31](https://github.com/YusukeIwaki/puppeteer-ruby/pull/31))
* Improve SEND/RECV handling in CDPSession ([#34](https://github.com/YusukeIwaki/puppeteer-ruby/pull/34))

### 0.0.22 [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.21...0.0.22)]

Bugfix

* Make `Puppeteer#default_args` to work
* Respect Firefox launch options
* Respect `default_viewport: nil`

### 0.0.21 [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.20...0.0.21)]

Bugfix/Improvement:

* Update DeviceDescriptors (list of emulatable devices)
* Fix bug on inputing "(" ([#25](https://github.com/YusukeIwaki/puppeteer-ruby/pull/25))

### 0.0.20 [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.19...0.0.20)]

New feature

* Dialog-handling feature

### 0.0.19 [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.18...0.0.19)]

New feature

* **Firefox support**

Bugfix/Improvement

* Allow `Page#keyboard` with block ([#18](https://github.com/YusukeIwaki/puppeteer-ruby/pull/18))

### 0.0.18 [[diff](https://github.com/YusukeIwaki/puppeteer-ruby/compare/0.0.17...0.0.18)]

New feature

* **Firefox support**

Bugfix/Improvement

* Allow `Page#keyboard` with block ([#18](https://github.com/YusukeIwaki/puppeteer-ruby/pull/18))
