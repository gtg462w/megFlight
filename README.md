megFlight
=========

enterprise distribution of iOS apps served on a static html page

Usage
-----
    ruby ./megFlight.rb /tmp/myapp.ipa \                                      # the IPA
      'com.example.my_app' \                                                  # the identifier in the manfiest.plist
      "My App" \                                                              # the title of the page/app
      'powered by <strong><a href="http://example.com">Myself</a></strong>' \ # the subtitle
      'http://example.com/apps/myApp'                                         # the host the files will be served from
