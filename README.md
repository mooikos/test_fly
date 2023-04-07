# test hosting solution for ruby sinatra app

ruby apps docs
- https://fly.io/docs/languages-and-frameworks/ruby/

apps dashboard
- https://fly.io/dashboard

## release steps (with fly)

requires gem in bundle
- `rackup`

install CLI
- `brew install flyctl`

auth CLI
- `fly auth login`

prepare for deployment
- `flyctl launch`
- will generate files
  - `Dockerfile`
  - `fly.toml`

deploy
- `fly deploy`
