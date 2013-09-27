# kata-base

A minimal setup to do a code kata in Ruby with RSpec.

### How to use this

There's a pair of files `spec/kata_spec.rb` and `lib/kata.rb` where you can start writing code.

When adding new files, the only thing to keep in mind is to `require 'filename'` in the corresponding spec.

Run all specs with `bundle exec rspec`.
