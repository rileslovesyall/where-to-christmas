Where to Christmas 
==================

Objective
---------
This app is meant to create a connection between people hosting holiday parties/events and people who are looking for a place to hang out. Perhaps you're in a new-to-you city away from family, perhaps you're traveling for work or pleasure, or perhaps you're just lonely in a big city. Whatever the case may be, the holidays can be pretty lonely for some people, while others have an excess of cheer but no easy way to share it. Using this app, people can be **Hosts** or **Guests**. Hosts have **Events** where they can allow a certain number of guests, and they can screen guests based on the guest profile and any guest reviews. (Maybe there could be a verfication system-- guests must use another account, FB or Gmail or Twitter that can be linked to to show they are real?)

Starting off, this will be related to Christmas, but I want to expand it, so you can set what Holiday your event is celebrating. 

Configuration
----------
Written in Ruby 2.2.3 and Rails 4.2.5
Includes Gemfile-- just clone, then run ```gem install bundler``` and ```bundle install``` to get going.

Database Config/Initialization
------------------------------
Run ```rake db:setup``` to get going with the database seeds, or just ```rake db:migrate``` to start with an empty database.

Testing
-------
Created with RSPec test suite. 
