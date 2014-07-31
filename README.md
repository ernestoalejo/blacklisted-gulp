blacklisted-gulp
================

Search blacklisted gulp plugins in your project.


Install
-------

```shell
sudo npm install -g blacklisted-gulp
```


Run
---

In the root of your project (where your package.json is) run this command:


```shell
blacklisted-gulp
```

It will output the name of the gulp plugins you're using right now that are in the blacklist. It will return the reason or replacement too.

If no plugin is blacklisted the application will not output anything.
