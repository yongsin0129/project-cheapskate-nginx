使用 :
http://cheapskate-nginx.fly.dev/?target_url=movie/fden92906216/
or
https://cheapskate-nginx.fly.dev/?target_movieID=fden92906216

http://localhost/?target_movieID=fden92906216


proxy pass to target_url
http://www.atmovies.com.tw/movie/fden92906216/
or
http://app2.atmovies.com.tw/poster/futw92659124/

20230417 目前使用下面那個 poster 的網址，可以直接拿到海報

proxy 302 301 redirect
example http://atmovies.com.tw/movie/fsen15751968/
會定向到 http://app2.atmovies.com.tw/film/fsen15751968/
