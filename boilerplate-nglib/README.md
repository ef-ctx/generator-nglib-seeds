# How To

```
npm install -g yo generator-nglib
mkdir cx.foobar
cd cx.foobar
yo nglib --config https://raw.githubusercontent.com/ef-ctx/generator-nglib-seeds/master/boilerplate-nglib/.yo-rc.json --tpl git@github.com:ef-ctx/generator-nglib-seeds.git --tpl-path boilerplate-nglib/templates --tpl-branch v0.0.1
```

To skip existing cache of the template repo (if you are not using proper tags, of course) add `--tpl-refresh`.

Full documentation of the generator can be found here: https://github.com/cork-labs/generator-nglib