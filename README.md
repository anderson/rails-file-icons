Rails File Icons
---

Simple file icons that use the Rails Asset Pipeline.

## Installation

Add this line to your application's Gemfile:

    gem 'rails-file-icons'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rails-file-icons

## Usage

Render a file icon for a given filename in a view.
    
    <%= image_tag Icon.for_filename('myfile.jpg') %>

Get the image path for a given file extension. (leading dot is irrelevant)

    Icon.for_ext '.jpg'
    > 'fileicons/file_extension_jpg.png'

    Icon.for_ext 'gif'
    > 'fileicons/file_extension_gif.png'

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
