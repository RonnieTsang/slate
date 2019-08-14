# 错误码

The Kittn API uses the following error codes:

错误码 | 含义
---------- | -------
400 | 无效的请求
401 | 未授权 -- API请求的key是错误的
403 | 已禁止 -- 该请求仅限于管理员权限
404 | Not Found -- The specified kitten could not be found.
405 | Method Not Allowed -- You tried to access a kitten with an invalid method.
406 | Not Acceptable -- You requested a format that isn't json.
410 | Gone -- The kitten requested has been removed from our servers.
418 | I'm a teapot.
429 | Too Many Requests -- You're requesting too many kittens! Slow down!
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
