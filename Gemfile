# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 7.3"

# Jekyll 插件
group :jekyll_plugins do
  gem "jekyll-seo-tag", "~> 2.8"    # SEO meta 标签
  gem "jekyll-sitemap", "~> 1.4"    # Sitemap 生成
  gem "jekyll-paginate", "~> 1.1"   # 分页支持
end

# Windows 和 JRuby 平台兼容
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem 'wdm', '>= 0.1.0', :platforms => [:windows]

# http_parser.rb 在 JRuby 上需限制版本
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
