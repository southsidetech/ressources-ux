Just the Docs
A modern, highly customizable, and responsive Jekyll theme for documentation with built-in search.
Easily hosted on GitHub Pages with few dependencies.

Installation
Use the template
The Just the Docs Template provides the simplest, quickest, and easiest way to create a new website that uses the Just the Docs theme. To get started with creating a site, just click "use the template"!

Note: To use the theme, you do not need to clone or fork the Just the Docs repo! You should do that only if you intend to browse the theme docs locally, contribute to the development of the theme, or develop a new theme based on Just the Docs.

You can easily set the site created by the template to be published on GitHub Pages – the template README file explains how to do that, along with other details.

If Jekyll is installed on your computer, you can also build and preview the created site locally. This lets you test changes before committing them, and avoids waiting for GitHub Pages.1 And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

uses a gem-based approach, i.e. uses a Gemfile and loads the just-the-docs gem
uses the GitHub Pages / Actions workflow to build and publish the site on GitHub Pages
Other than that, you're free to customize sites that you create with the template, however you like. You can easily change the versions of just-the-docs and Jekyll it uses, as well as adding further plugins.

Use RubyGems
Alternatively, you can install the theme as a Ruby Gem, without creating a new site.

Add this line to your Jekyll site's Gemfile:

gem "just-the-docs"
And add this line to your Jekyll site's _config.yml:

theme: just-the-docs
And then execute:

$ bundle
Or install it yourself as:

$ gem install just-the-docs
Alternatively, you can run it inside Docker while developing your site

$ docker-compose up
Usage
View the documentation for usage information.

Contributing
Bug reports, proposals of new features, and pull requests are welcome on GitHub at https://github.com/just-the-docs/just-the-docs. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the Contributor Covenant code of conduct.

Submitting code changes:
Submit an Issue that motivates the changes, using the appropriate template
Discuss the proposed changes with other users and the maintainers
Open a Pull Request
Ensure all CI tests pass
Provide instructions to check the effect of the changes
Await code review
Design and development principles of this theme:
As few dependencies as possible
No build script needed
First class mobile experience
Make the content shine
Development
To set up your environment to develop this theme: fork this repo, the run bundle install from the root directory.

A modern devcontainer configuration for VSCode is included.

Your theme is set up just like a normal Jekyll site! To test your theme, run bundle exec jekyll serve and open your browser at http://localhost:4000. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When this theme is released, only the files in _layouts, _includes, and _sass tracked with Git will be included in the gem.

License
The theme is available as open source under the terms of the MIT License.

Footnotes
It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub. ↩
