# Sinatra Landing Page Boilerplate

Landing page boilerplate built with Sinatra 3.0.3, Ruby 3.1.2, [Tailwind CSS 3.2.4](https://tailwindcss.com) and [heroicons](https://heroicons.com) integrated.

## Pre-requisites

You will need to have Ruby 3.1.2 installed on your system. I recommended you to follow the [GoRails Setup Ruby on Rails Guide](https://gorails.com/setup) for install Ruby language in your system.

## Getting Started

Once you have Ruby 3.1.2 properly installed and configured you can make:
```
git clone https://github.com/tolesco/sinatra-landing-page.git
cd sinatra-landing-page
bundle install
ruby app.rb
```
The app will be accessible through your [localhost:4567](http://localhost:4567) address.

### ENV Variables

If you need to use ENV variables in development make a copy of `.env-example` named `.env`, then remove `.env-example` file and edit `.env` file with your ENV variables:
```
cp .env-example .env
rm .env-example
```

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## Contact

Francisco Rodríguez - [@tolesco](https://github.com/tolesco/) - tolesco@gmail.com
