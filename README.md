# Capistrano Remote Cache With Project Root Deployment Strategy

This library extends the RemoteCache strategy in order to
support deployment from internal folders, e.g. yours
`Rails.root` resides inside `/yourapp`.

## Installation

Add this line to your application's Gemfile:

    gem 'capistrano-remote-cache-with-project-root'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install capistrano-remote-cache-with-project-root

## Usage

Add these lines to your Capistrano recipe:

    set :deploy_via, "remote_cache_with_project_root"
    set :project_root, "relative/path/to/your/project"

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
