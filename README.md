# sitelooper plugin marketplace

The Claude Code plugin marketplace for [sitelooper](https://github.com/restspace/sitelooper):
write browser tests in plain English and get standalone Playwright specs that run in CI with no model.

```
/plugin marketplace add restspace/sitelooper-plugin
/plugin install sitelooper@sitelooper
```

The plugin needs Node.js 20 or later and the CLI (`npm install -g sitelooper`); its skills check for it
and ask before installing. See the [plugin README](plugin/README.md).

This repo is generated: the plugin's source lives in
[restspace/sitelooper/plugin](https://github.com/restspace/sitelooper/tree/main/plugin) and is copied
here on each release. Report issues and send pull requests there.

License: MIT
