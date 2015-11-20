pickles2/px2-mod-plain-html-elements
=========

Plain HTML element modules for [Pickles 2](http://pickles2.pxt.jp/).

## Usage - 使い方

### 1. [Pickles 2](http://pickles2.pxt.jp/) をセットアップ

### 2. composer.json に追記

```
{
    "require": {
        "pickles2/px2-mod-plain-html-elements": "dev-master"
    }
}
```

### 3. composer を更新

```
$ composer update
```

### 4. px-files/config.php に追加

```
// config for Pickles2 Desktop Tool.
@$conf->plugins->px2dt->paths_module_template["PlainHTMLElements"] = "./vendor/pickles2/px2-mod-plain-html-elements/modules/";
```


## License

MIT License


## Author

- (C)Tomoya Koyanagi <tomk79@gmail.com>
- website: <http://www.pxt.jp/>
- Twitter: @tomk79 <http://twitter.com/tomk79/>
