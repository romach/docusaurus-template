# Docusaurus site template.

[![Join the chat at https://gitter.im/{{FIX:gitter_room_url}}](https://badges.gitter.im/{{FIX:gitter_room_url}}.svg)](https://gitter.im/{{FIX:gitter_room_url}}?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is template for Docusaurus site.

## Key features:

- integration with Circle CI
- integration with https://gitter.im
- "Copy" button in code blocks
- integration with GitHub pages

## Preparation before using:

- configure project in Circle CI;
- create chat room in https://gitter.im;
- substitute `{{FIX:github_user}}` in `/.circleci/config.yml` with you GitHub user name;
- substitute files in `/docs` with your documentation pages;
- substitute files in `/website/blog` with your blog pages;
- customize blocks in `/website/pages/en/index.js`
- customize images in `/website/static/img/`
- customize sidebar in `/website/sidebars.json`
- fix `/website/siteConfig.js`:
    - substitute `{{FIX:github_repository_name}}` with GitHub repository name;
    - substitute `{{FIX:github_user_name}}` with GitHub user name;
    - substitute `{{FIX:gitter_room_name}}` with Gitter room name;
    - substitute `{{FIX:site_title}}` with site title;
    - substitute `{{FIX:site_description}}` with site description;
    - substitute `{{FIX:site_first_level_url}}` with site first level url;
    - substitute `{{FIX:first_name}}` with site author first name;
    - substitute `{{FIX:second_name}}` with site author second name;
    - substitute `{{FIX:ga_tracking_id}}` with Google Analytics tracking id;
    
- delete all `{{FIX:<key>}}` strings from source code;