使用方法 :
1. 使用 target_movieID
https://cheapskate-nginx.fly.dev/movie?target_movieID=fden92906216

2. 使用 完整的 url
https://cheapskate-nginx.fly.dev/proxy?url=http://www.atmovies.com.tw/movie/fden92906216/

以上兩個方式都可以做代理
proxy pass to target_url
http://www.atmovies.com.tw/movie/fden92906216/


P.S. proxy 302 301 redirect
example http://atmovies.com.tw/movie/fsen15751968/
會定向到 http://app2.atmovies.com.tw/film/fsen15751968/
