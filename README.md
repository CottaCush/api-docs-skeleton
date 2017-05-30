This project is forked from slate. Check it out at [here](https://github.com/lord/slate)

### Installation
`composer create-project --prefer-dist cottacush/api-docs-skeleton <docs_directory>`


### Prerequisites
You're going to need:
 - **Linux or OS X** — Windows may work, but is unsupported.
 - **Ruby, version 2.2.5 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.


### Modifying docs
Docs are in the `source` directory
[Check here](https://github.com/lord/slate/wiki/Markdown-Syntax) to see how markdown syntax


### Running

```shell
cd <docs_directory>

# either run this to run locally 
# static files will be in build directory
bundle install
bundle exec middleman server

# OR run this to run with docker - view at http://localhost:4567
docker-compose up
```

Credits
--------
[Slate](https://github.com/lord/slate)