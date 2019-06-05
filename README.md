# cors_post_cookie
js ajax post api with cookie

## demo page

http://node.tedshd.io/cors_post_cookie/

or

http://api.tedshd.io/cors_post_cookie/

## Usage

### step 1

click **api response php set cookie** button

and api can set cookie **TestCookie=this is test**

### step 2

click **post api** button

api on server side can get cookie & response cookie

```PHP
echo 'Hello ' . htmlspecialchars($_COOKIE["TestCookie"]) . '!';
```
