# TextMate Bundle for Ruby on Rails Development

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/carlosbrando/ruby-on-rails-tmbundle.git "Ruby on Rails.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/carlosbrando/ruby-on-rails-tmbundle/tarball/master
    tar zxf carlosbrando-ruby-on-rails-tmbundle*.tar.gz
    rm carlosbrando-ruby-on-rails-tmbundle*.tar.gz
    mv carlosbrando-ruby-on-rails-tmbundle* "Ruby on Rails.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'
