# Simple proxy switcher for OS X

This utility can be used for fast switching between several http proxies on OS X.

## Configuration
The proxy information is stored in the configuration file called `config.toml`. The syntax is explained right [here](https://github.com/mojombo/toml). Take a look at the example config, it's dead-simple.

## Usage
`proxy [name]` sets the system proxy to the entry [name] of the config file.

`proxy on` sets the proxy to the last used configuration.

`proxy off` turns off the proxy.

## Note
The proxy is set for all the interfaces at once. That's the default
behaviour at the moment.

## The MIT license
Copyright (c) 2013 Alexey aka @appplemac

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
