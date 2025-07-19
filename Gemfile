source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
gem "jekyll", "~> 4.3.3"

# This is the default theme for new Jekyll sites.
gem "minima", "~> 2.5"

# 如果要使用GitHub Pages，请取消下面一行的注释并注释掉上面两行
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-paginate"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock Jekyll-sass-converter to 2.0 for now
gem "jekyll-sass-converter", "~> 3.0"

# When using Ruby 3.0+, we need webrick
gem "webrick", "~> 1.8" 