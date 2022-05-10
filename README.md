# Error-In-ArrayLoader.php-line-44-on-composer-install-laravel
Unknown package has no name defined ([{"name":"arielmejiadev\/larapex-charts","version":"3.0.1","version_normalized":"3.0.1.0","source":{"t     ype":"git","url":"https:\/\/github.com\/ArielMejiaDev\/larapex-charts.git","reference":"56fc693dc27c7eda0b9925c905a4d34ce5d9669f"},"dist":{     "type":"zip","url":"https:\/\/api.github.com\/repos\/ArielMejiaDev\/larapex-charts\/zipball\/56fc693dc27c7eda0b9925c905a4d34ce5d9669f","ref     erence":"56fc693dc27c7eda0b9925c905a4d34ce5d9669f","shasum":""},"require":{"ext-json":"*","illuminate\/support":"^8.0","php":"^7.4|^8.0"},"     require-dev":{"orchestra\/testbench":"^6.0","phpunit\/phpunit":"^9.0"},"time":"2021-07-27T05:55:46+00:00","type":"library","extra":{"larave     l":{"providers", etc.............


**in my case, i take the pull on server from github and it change the vender file of server.
so, as per solution run the composer file again to solve issues by command **
```
composer install
```

# solution

remove the update vender folder 
```
rm -rf vendor/
111


also remove the composer.lock file to install the composer again.
```
rm composer.lock
```

now run install command
```
composer install
```

hope it save your day.


