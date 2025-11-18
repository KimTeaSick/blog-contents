# Blog Contents

This repository contains all blog posts and portfolio projects for the blog.

## Structure

```
blog-contents/
├── blog/
│   └── posts/          # Blog post MDX files
└── portfolio/          # Portfolio projects
    └── [project-name]/
        ├── detail.md   # Project details
        └── *.{png,jpg} # Project images
```

## Usage

This repository is intended to be used as a Git submodule in the main blog repository.

```bash
# In the main blog repository
git submodule add <repository-url> contents
git submodule update --init --recursive
```
