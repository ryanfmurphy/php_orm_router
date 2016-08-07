# PHP ORM/Router

Lightweight PHP URL Router and ORM Framework

## Rebuilding Repository, thanks for your patience!

2016-08-07 - I am rebuilding the repository because I ran into serious problems with nested dependencies using `git subtree`.  This version of the repo contains as subtrees `db_viewer`, `dash`, and `orm_router`, but that isn't working out because git subtree is not perfect yet - I am seeing problems where I do a `git subtree push` and it says I'm up-to-date, but then I try to do a `git subtree pull` and it says my branch is behind.

Moving to a simpler tried-and-true (if imperfect) technique of including the subprojects as files directly but forgetting about sharing the history with those repos.

Stay tuned for the link of the new repo.  (Hint:  it will most likely be https://github.com/ryanfmurphy/php_orm_router).

## Getting Started

* Make sure your web server is setup to route all URLs through `/index.php`.
* Fill out a `or_config.php` file based on `or_config_example.php`.
* Define your models in the `models/` folder, based on the examples in `examples/models/`.
* Define your controller in the `controllers/` folder, based on the examples in `examples/contractors/`.
  You can name it whatever you want, the application will automatically find it and include it.

