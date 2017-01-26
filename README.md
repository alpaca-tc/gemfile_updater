Generate diff of `Gemfile.lock`

After create pull-request

```
# Generate access token https://github.com/settings/tokens
export OCTOKIT_ACCESS_TOKEN=328.....
./bin/gem_updater --repository alpaca-tc/gem_updater --pull-request 1
```

**output**

```
addressable: https://github.com/sporkmonger/addressable/compare/addressable-2.3.8...addressable-2.5.0
compare_linker: https://github.com/masutaka/compare_linker/compare/v1.2.1...v1.3.4
faraday: https://github.com/lostisland/faraday/compare/v0.9.2...v0.11.0
httpclient: https://github.com/nahi/httpclient/compare/v2.7.1...v2.8.3
octokit: https://github.com/octokit/octokit.rb/compare/v4.2.0...v4.6.2
sawyer: https://github.com/lostisland/sawyer/compare/v0.6.0...v0.8.1
```
