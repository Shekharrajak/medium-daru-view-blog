source "http://rubygems.org"

ruby "2.5.3"

# iruby dependencies

# For rbczmq gem we need to install autogen otherwise you may
# get this error: "autogen.sh: error: could not find libtool.
# libtool is required to run autogen.sh. ZeroMQ autogen failed!"

# Mac user must do `brew install autogen`,
# if autogen is not installed
# Debian user must do `sudo apt install libtool-bin`,
# if libtool is not present
# gem 'rbczmq'
# gem 'ffi-rzmq'

# To run `iruby notebook` we need Python, ipython notebook,
# and jupyter.
# Please install according to the OS.
# Follow this : https://github.com/SciRuby/iruby
gem 'iruby'

# fetch from the github master branch
gem "daru", git: 'https://github.com/SciRuby/daru.git'
gem "nyaplot", git: 'https://github.com/SciRuby/nyaplot.git'
gem 'google_visualr', git: 'https://github.com/winston/google_visualr.git'

gem 'daru-data_tables', git: 'https://github.com/Shekharrajak/daru-data_tables.git'

# daru-view for visualizing
gem "daru-view", git: 'https://github.com/SciRuby/daru-view.git'

# daru-io fomr importing data through avrious formate to daru dataframe
gem "daru-io", git: 'https://github.com/SciRuby/daru-io.git'

# used in tutorials :
# Nyaplot | Creating Visualizations with DataFrame  | from daru examples
# gem 'distribution'
