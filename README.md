

gui-qa-example, a basic working example testing GUI using Rspec, Capybara, WebMock &amp; Sinatra, allowing mocked tests or against backend. First ensure you have python3.6, Django installed.

    sudo pip install Django
install mitm proxy 

    sudo apt-get install libxml2-dev libxslt-dev -y
    sudo apt-get install python3-dev python3-pip libffi-dev libssl-dev -y
    sudo pip3 install mitmproxy

install the relevant ruby
    curl -sSL https://get.rvm.io | grep -v __rvm_print_headline | bash -s stable --ruby
if you have problems hereafter try to reboot after rvm install
    rvm install 2.2.4
    rvm use --default 2.2.4
    gem install bundler -v '= 1.11.2'
at root directory of the project run 
    bundle install
