---
layout: default
title: OpenHack - Your City?
---

## Your City?

We'd love to start OpenHack in as many cities as possible. This site is meant to facilitate starting new OpenHack groups, but isn't meant to actually "run" or "RSVP" for groups. If you want to add your city, here's what you should do:

1. Fork, and clone the [openhack.github.com](https://github.com/openhack/openhack.github.com) repo.
2. Install Ruby (sorry!), `gem install bundler; bundle`
3. Run `rake city NAME=YOUR_CITY_NAME`.<br />So if you live in "Bananas, NY", it would be `rake city NAME='Bananas, NY'`. This should make a `bananas` directory with an `index.markdown` file for your city. __EXTRA CREDIT__: pass the specific ADDRESS where your group meets to get a more detailed pin on the map. Example: `rake city NAME='Baltimore, MD' ADDRESS='2400 Boston St Baltimore MD 21224'`
4. Edit the `index.markdown` file with information about your meetup! Run `rake` to see the site in action on `http://localhost:4000`.
5. Also edit `_config.yml` to correct the name of your city and its state/country.
6. Commit your changes, push to your fork, and submit a pull request to the main repo. Once accepted, we'll add you to the main repo so you can update your city's page at any point.

And that's it! If you have feedback on this process, just open up an [issue](https://github.com/openhack/openhack.github.com/issues) and ask a question!
