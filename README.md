# Update
Didn't work out of the box for custom tracing using `trace_execution_scoped`. Have to add `MethodTracer` at appropriate places.

# RailsAPINewrelic (Rails 3 and 4)

This gem fixes New Relic reporting from
[rails-api](https://github.com/rails-api/rails-api) applications.  See
[rails-api#34](https://github.com/rails-api/rails-api/issues/34) for a
description of the problem.

## Installation

Add this line to your application's Gemfile:

    gem "rails-api-newrelic"

And then execute:

    $ bundle

## Usage

Just install this gem and you should start seeing data in New Relic.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am "Add some feature"`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
