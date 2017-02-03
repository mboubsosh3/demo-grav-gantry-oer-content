---
title: 'Blog Page'
hide_git_repo_link: false
git_repo_link_url: 'https://github.com/paulhibbitts/demo-grav-gantry-oer-content/tree/master/pages/03.blog-page'
git_repo_link_text: 'Edit Blog Items'
sitemap:
    changefreq: monthly
content:
    items: '@self.children'
    leading: 0
    columns: 2
    limit: 10
    order:
        by: date
        dir: desc
    show_date: false
    pagination: true
    url_taxonomy_filters: true
blog_url: blog
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---

