##### Atom and all repositories under Atom will be archived on December 15, 2022. Learn more in our [official announcement](https://github.blog/2022-06-08-sunsetting-atom/)
 # Atom 비행 매뉴얼

이것은 Atom 책입니다. Everything you need to know in order to use and hack Atom is in this Flight Manual.

당신은 https://flight-manual.atom.io 에서 이책을 찾을 수 있습니다. 

이 책은 크리에이티브 커먼즈 라이센스를 따릅니다. 

[![atom-표지](https://cloud.githubusercontent.com/assets/378023/8718108/54c10686-2bdc-11e5-8d26-f7f807d63171.png)](https://github.com/atom/docs/releases/latest)

## 라이센스

This book is published under the Creative Commons BY-SA license. If you contribute to the work, you will have to agree to allow your content to be published under the self same license. Check out [the license file](LICENSE.md) for more details.

## 현재 단계

To check the current progress and planned content of the book, check out the [outline](outline.md). This is a good place to start if you're looking for something to add.

## 지역 변화를 테스트 / Testing Changes Locally

### 전제조건

* You'll need [Ruby installed on your system](https://www.ruby-lang.org/en/documentation/installation/). The required version can be found in [`.ruby-version`](.ruby-version).
* You'll need the bundler Ruby Gem installed. You can do this with `gem install bundler`.
* You'll need [Node installed](https://nodejs.org/en/download/), too. The required version can be found in [`package.json`](package.json).

### Fetching dependencies

You can always fetch the latest dependencies by opening the command line and running `script/bootstrap`:

``` sh
$ script/bootstrap
```

### 사이트 시작하기

You can start the site with `script/server`:

``` sh
$ script/server
Loading site data...
Compiling site...
…

Site compiled in 5.81s.
```

While the server is running, you can see the site in your browser at http://localhost:4000.

## 기여하기

If you'd like to help out by making a change, adding content or improving something, take a look at the [contributor's guide](CONTRIBUTING.md).
