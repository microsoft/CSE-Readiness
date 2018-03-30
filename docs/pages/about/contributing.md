---
title: Contributing
keywords: contribution
sidebar: home_sidebar
permalink: contributing.html
last_updated: March 7, 2018
folder: about
---

# What is this site?

The CSE Readiness project is designed to be an agile, open source way for us, CSE, to share the best and most useful documentation, videos, blog posts,
to help each other upskill in the various Pillar areas. If you find a great resource, please consider adding it to the right page in the repo.

# Contributing

## Join the team

This project is available on GitHub at [https://github.com/Microsoft/CSE-Readiness](https://github.com/Microsoft/CSE-Readiness). To edit this
project, **please make sure you have joined the Microsoft org at** [opensource.microsoft.com](https://repos.opensource.microsoft.com/microsoft/).

This project welcomes contributions and suggestions.  Because this repo is hosted in the Microsoft open source organization,
most contributions require you to agree to a Contributor License Agreement (CLA) declaring
that you have the right to, and actually do, grant us the rights to use your contribution.
For details, visit [https://cla.microsoft.com](https://cla.microsoft.com).

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Making Changes

Now, how do you actually contribute? Easy! Any time you want to update or change a site, you can either
navigate back to the repo manually, or you can click the "Edit Me" button on any page.
The master branch itself is restricted to the repo admins, so please make any pull requests into the
'Readiness' branch. These changes will be checked on regularly and, upon approval, merged into Master.

When making updates to pages, the only additional ask is that you update the *last_updated* date frontmatter (the code nested in the `---` at the top of each page)
to today.

## Local Testing

To test the site locally, there are a few steps you need to take:

### Install Ruby

This site is based on Jekyll, which runs on Ruby.
If you are on a Mac, Ruby is installed by Default. For Windows, Ruby is available [here](https://rubyinstaller.org/)

### Install the Ruby Developer Kit (Windows only)

Some extensions Jekyll uses require you to natively build the code using the Ruby Development Kit.

1. Go to [RubyInstaller](https://rubyinstaller.org/) for Windows.
2. Under the Development Kit section near the bottom, download one of the For use with Ruby 2.4 and above… options (either the 32-bit or 64-bit version).
3. Run the Executable file to install Ruby.
4. Once the installation is complete, a command prompt will open - run options 1, 2, and 3 to install the msys tools.
5. Check that your PATH variable has been updated to include the /bin/ folder where Ruby was installed (e.g. C:/Ruby24-x64/bin/).

### Install Ruby Gems

For Windows, install [RubyGems](https://rubygems.org/pages/download) by downloading the Zip, navigating to the extracted folder, and running `ruby setup.rb`

On Ubuntu make sure you install the needed dependencies before running the bundle install command:

`sudo apt-get install libz-dev`

Run the command: 

```
rm Gefile.lock
bundle install
```
### Install Jekyll

Now use `gem` to install Jekyll:

{% highlight ruby %}
gem install jekyll
{% endhighlight %}

You can now use Jekyll to create new Jekyll sites following the quick-start instructions on [Jekyllrb.com](http://jekyllrb.com).
This site has already been set up

### Install Bundler

1. Run the command: `gem install bundler`

### Run the site

Now that you have Ruby, Rubygem, Jekyll, and bundler installed, navigate to the /docs folder, and run `bundle exec jekyll serve`. This will build and deploy the site
locally on 127.0.0.1:4000. When working locally, you can leave the server running. When you make edits, Jekyll will automatically rebuild the pages!
The only time you should need to restart your local server is if you make changes to config.yml (which you likely won't need to do).

### Make your changes

Now, you have everything installed and the site should be up and running. All of the documentation pages are found in the /pages folder, organized
by pillar area. The pages all use [Kramdown](https://kramdown.gettalong.org/quickref.html) syntax for easy styling. Simply make your edits, make sure
they look good locally, and create a PR into the 'Readiness' branch.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all others rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
