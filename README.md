# Amortizer

A simple gem to calculate amortizing loan payments, as part of training at Samyukti

## Installation

Add this line to your application's Gemfile:

    gem 'amortizer'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install amortizer

## Usage

    require 'amortizer'

    loan = Amortizer::Loan.new(100000, 10, 100)
    loan.payment

## Contributing

1. Fork it ( http://github.com/<my-github-username>/amortizer/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
