# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Jekyll과 관련 플러그인
gem 'jekyll', '~> 3.9.2' # github-pages에서 요구하는 Jekyll 버전
gem "jekyll-feed"
gem "jekyll-readme-index"
gem "jemoji"
gem "webrick"

# GitHub Pages 플러그인 추가
group :jekyll_plugins do
  gem "github-pages", "~> 227" # 명시적으로 github-pages 버전 고정
end