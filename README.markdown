# This gem is deprecated!

Sequel instrumentation is now supported in the newrelic_rpm gem as of version 3.9.0.229

Please remove the newrelic-sequel gem from your Gemfile and replace it with newrelic_rpm ~> 3.9

Newrelic Sequel
===============
**Sequel instrumentation for Newrelic.**

Usage
-----

1. Install gem

 >gem install newrelic-sequel

2. Config dependencies in application.rb

 >config.gem "newrelic_rpm"

Dependencies
------------

1. newrelic_rpm > 3.0, <= 3.8.1.221
2. sequel > 3.22

License
-------

Copyright (C) 2012 REA Group Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.