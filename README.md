# Rails reference installs

We’re in the process of upgrading to a current version of
[Ruby on Rails][rails]. To help with the process, we’ve generated base
installations for multiple versions ([currently 4.2 through 7.0](./versions))
using [an `install-versions` script](./install-versions) that runs
[the `rails new` command][rails new] for each version. In addition, we’ve
written [a `diff-versions` script](./diff-versions) to iterate through each
version increment, summarizing the changes.

Like Rails itself, this code is [provided under the MIT license](./LICENSE).

  [rails]: https://rubyonrails.org/
  [rails new]: https://guides.rubyonrails.org/getting_started.html#creating-the-blog-application "Rails Guide: ‘Creating the blog application’"
