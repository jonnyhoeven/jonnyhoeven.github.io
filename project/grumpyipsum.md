---
title: Grumpy Ipsum
type: project
date: 2020-05-21
image: /images/grumpyipsum.jpg
githost: https://github.com
user: jonnyhoeven
project: grumpyipsum
branch: master
fetchReadme: true
languages: Vue, PHP
intro: Grumpy ipsum, the crowd-sourced negative Lorem Ipsum generator
    This web project uses vue frontend with a laravel/eloquent backend to crowdsource negative content
    for use instead of positive content. The project is a work in progress and is not yet ready for users.
---
<script setup>
import ArticleItem from '/components/ArticleItem.vue';
</script>
<ArticleItem :frontmatter="$frontmatter"/>
