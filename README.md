# php-same-site-issue

Hi, you can get rid of this problem by updating your php.ini file. Valid for PHP7.3 and above.

--

Find:
```bash
;session.cookie_secure =
```

Replace:
```bash
session.cookie_secure = 1
session.cookie_samesite = "None"
```
--


