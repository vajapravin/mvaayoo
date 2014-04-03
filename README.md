# Mvaayoo

mVaayoo™ is a cost effective End-to-End Enterprise Mobile Messaging Service with high service level availability, that is unmatched in the industry. mVaayoo™ provides both 1-Way & 2-Way SMS communication including SMS Push, short code and long code services, SMS gateway with APIs, SMS Excel plugin, SMS contest, voting & polling and Voice SMS services. 

## Installation

Add this line to your application's Gemfile:

    gem 'mvaayoo'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mvaayoo

Subscribe http://mvaayoo.com/ to get following credentials

Add content to config/initializers/mvaayoo.rb

	MVAAYOO_USER = 'MVAAYOO_USERNAME'
	MVAAYOO_PASSWORD = 'MVAAYOO_PASSWORD'
	MVAAYOO_SENDER_ID = 'MVAAYOO_SENDER_ID'

## Usage
	
	Send Message
	
		Mvaayoo.send_message "hey there!!", "9766847415"

	Get Balance

		Mvaayoo.balance

## Contributing

1. Fork it ( http://github.com/vajapravin/mvaayoo/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

Don't hesitate to write problems [vajapravin23@gmail.com]