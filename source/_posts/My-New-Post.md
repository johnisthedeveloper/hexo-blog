---
title: My New Post
date: 2023-06-18 14:38:32
tags:
---
v7.0.0 (RC1) Latest
@yoshinorin yoshinorin released this Mar 18
· 1 commit to master since this release
 v7.0.0-rc1
 46fbdcf
Migration Guide
Some of the built-in tags have been dropped (E.g. gist, youtube, jsfiddle, and vimeo). If you use those tags in your existing blog posts, you can install hexo-tag-embed to continue using them with Hexo 7.0.0.

Note

No need to install it if you are not using (or will not use) gist, youtube, jsfiddle, vimeo tags in your post or page.

$ npm i hexo-tag-embed
Breaking Changes
chore: require node14+ by @yoshinorin in #5061
Dropped tag features. Please see Migration Guid section.
refactor: drop gist tag by @yoshinorin in #5067
refactor: drop youtube tag by @yoshinorin in #5064
refactor: drop jsfiddle tag by @yoshinorin in #5066
refactor: drop vimeo tag by @yoshinorin in #5065
Dropped features
refactor: drop external_link boolean type by @yoshinorin in #5063
refactor: drop use_date_for_updated option for updated_option by @yoshinorin in #5062
