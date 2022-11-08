# Rails reference installs

We’re in the process of upgrading to a current version of
[Ruby on Rails][rails]. To help with the process, we’ve
generated default installations for multiple versions
([currently 4.2 through 7.0](./versions)) using
[the `rails new` command][rails new] with no added arguments — a reference point
for each version. In addition, we’ve written
[a `diff-versions` script](./diff-versions) to iterate through each version
increment, summarizing the changes.

Like Rails itself, this code is [provided under the MIT license](./LICENSE).

  [rails]: https://rubyonrails.org/
  [rails new]: https://guides.rubyonrails.org/getting_started.html#creating-the-blog-application "Rails Guide: ‘Creating the blog application’"
