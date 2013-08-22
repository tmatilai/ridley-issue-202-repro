## Repro for Ridley [issue 202](https://github.com/RiotGames/ridley/issues/202)

```sh
$ bundle exec berks
/Users/tmatilai/.gem/ruby/2.0.0/gems/buff-config-0.3.0/lib/buff/config/ruby.rb:23:in `rescue in initialize': undefined local variable or method `knife' for #<Buff::Config::Ruby::Evaluator:0x007fe6337d7668 @attributes={}> (Buff::Errors::InvalidConfig)
	from /Users/tmatilai/.gem/ruby/2.0.0/gems/buff-config-0.3.0/lib/buff/config/ruby.rb:20:in `initialize'
	from /Users/tmatilai/.gem/ruby/2.0.0/gems/buff-config-0.3.0/lib/buff/config/ruby.rb:14:in `new'
	from /Users/tmatilai/.gem/ruby/2.0.0/gems/buff-config-0.3.0/lib/buff/config/ruby.rb:14:in `parse'
	from /Users/tmatilai/.gem/ruby/2.0.0/gems/buff-config-0.3.0/lib/buff/config/ruby.rb:103:in `from_ruby'
	from /Users/tmatilai/.gem/ruby/2.0.0/gems/buff-config-0.3.0/lib/buff/config/ruby.rb:96:in `initialize'
	from /Users/tmatilai/.gem/ruby/2.0.0/gems/ridley-1.5.2/lib/ridley/chef/config.rb:83:in `initialize'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf.rb:72:in `new'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf.rb:72:in `chef_config'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/config.rb:68:in `<class:Config>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/config.rb:4:in `<module:Berkshelf>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/config.rb:3:in `<top (required)>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/cookbook_generator.rb:3:in `require_relative'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/cookbook_generator.rb:3:in `<class:CookbookGenerator>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/cookbook_generator.rb:2:in `<module:Berkshelf>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/cookbook_generator.rb:1:in `<top (required)>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf.rb:149:in `require_relative'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf.rb:149:in `<top (required)>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/cli.rb:1:in `require'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/lib/berkshelf/cli.rb:1:in `<top (required)>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/bin/berks:3:in `require'
	from /Users/tmatilai/.gem/ruby/2.0.0/bundler/gems/berkshelf-434b8f2324b2/bin/berks:3:in `<top (required)>'
	from /Users/tmatilai/.gem/ruby/2.0.0/bin/berks:23:in `load'
	from /Users/tmatilai/.gem/ruby/2.0.0/bin/berks:23:in `<main>'
```
