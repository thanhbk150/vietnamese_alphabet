# VietnameseAlphabet

This library provides methods to convert Vietnamese text with special characters into the Latin alphabet.

## Installation
Install the gem and add to the application's Gemfile by executing:

    $ bundle add vietnamese_alphabet

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install vietnamese_alphabet

## Usage

```Ruby
VietnameseAlphabet.convert_variation("Tôi yêu Việt Nam")
# => "Toi yeu Viet Nam"


VietnameseAlphabet.to_slug("Tôi yêu Việt Nam")
# => "toi-yeu-viet-nam"
```
