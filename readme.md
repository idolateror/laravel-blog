# Laravel Blog

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

[中文README](/README_zh.md)

详细的安装教程在这里：[https://lufficc.com/blog/how-to-install-my-blog](https://lufficc.com/blog/how-to-install-my-blog)

how-to-install-my-blog ：[https://lufficc.com/blog/how-to-install-my-blog](https://lufficc.com/blog/how-to-install-my-blog)

<br>
A fast and powerful blog system powed by laravel 5.3. Click [here](https://lufficc.com/blog) to view.

This blog is for my own use. I used to use hexo and github pages as my blog, but it's not flexible. Thus I write this
blog. What I want to say is laravel is the best php framework I've ever seen.

Later I will share some experience of writing this blog, welcome your watch.

If you find bugs , glad you to issue.

## Features

1. Markdown editor,upload images to qiniu cloud by drag or from clipboard.
1. Comment system. 
1. Github login.
1. Separate models from controllers with repository design pattern.
1. Cache with redis database `0` and session with redis database `1`.
1. Images and files management.
1. ~~Pjax support.~~
1. Google analytics,admin management.
1. Posts with category, tags,code highlight and different status. 
1. XSS protection
1. More customs...
 
## Requires

1. "php": ">=5.6.4"
1. "mysql": ">=5.7"
1. Redis is must.

## install

```
git clone https://github.com/lufficc/laravel-blog.git

cd laravel-blog

// compelete your .env file

composer update

php artisan migrate

php artisan serve

// that's all

```

## attention

Please config your .env,you can copy `.env.example` and complete it:
```

// qiniu cloud for file upload
QINIU_AK= 
QINIU_SK=
QINIU_BUCKET=


// github oauth2 for github login
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
GITHUB_REDIRECT=

// default user avatar 
AVATAR=

```




## screen shots

<img src="https://static.lufficc.com/image/6e349fb9cbb7ec3813569724fee36e8a.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/0ed12f108e87a8cb8ec5a3bd0d364baa.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/76e6dc58db7b497e9a6e1adab447b2df.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/b3e71ec1f7a6ada81985540e5b7aed48.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/5da149dba4f57db2d6b45079f2911dcd.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/85ac3814b42a1fe97ac0d97d88f28cb0.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/863db4bf6604dd1e6196799b130f1276.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/773ac32bff0373f0028ec801e812c07e.jpeg" >
<br><br>
<img src="https://static.lufficc.com/image/9d1a2c7a3c97a29440c7def9868c1f38.jpeg" >

## Thanks

[laravel-china](https://laravel-china.org/)

## License

This blog is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
