# Postfix newrelic

## Prerequisites

| Compatibility for...	| Requirements |
|-----------------------|--------------|
| Ruby                  | 1.8.7 (including REE), 1.9.2, 1.9.3, 2.0.0, and 2.1.0; JRuby 1.6 and above; Rubinius 2.x |
| OS                    | UNIX-like operating systems such as Linux, Solaris, Mac OS X |
| Security requirements | As a standard security measure for data collection, your app server must support SHA-2 (256-bit). SHA-1 is not supported. |


## Installation and Running

Download the [latest release](https://github.com/Micka33/postfix-newrelic/releases/latest)

```
wget https://github.com/Micka33/postfix-newrelic/archive/vX.tar.gz
unzip vX.tar.gz
cd postfix-newrelic-master
bundle install
bundle exec ./newrelic_postfix_agent
```

Edit `config/newrelic_plugin.yml` and replace "YOUR_LICENSE_KEY_HERE" with your licence key.

Run `bundle exec ./newrelic_postfix_agent`

