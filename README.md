##### Atom and all repositories under Atom will be archived on December 15, 2022. Learn more in our [official announcement](https://github.blog/2022-06-08-sunsetting-atom/)
 # Atom 비행 매뉴얼

이것은 Atom 책입니다. 당신이 Atom을 사용하고, 해킹하기 위해서 알아야 하는 모든 것이 이 비행 매뉴얼에 있습니다. 

당신은 https://flight-manual.atom.io 에서 이책을 찾을 수 있습니다. 

이 책은 크리에이티브 커먼즈 라이센스를 따릅니다. 

[![atom-표지](https://cloud.githubusercontent.com/assets/378023/8718108/54c10686-2bdc-11e5-8d26-f7f807d63171.png)](https://github.com/atom/docs/releases/latest)

## 라이센스

이 책은 크리에이트 커먼즈 BY-SA  라이센스로 출간 되었습니다. 만약 당신이 이 일에 기여 하려면, 당신은 당신의 콘텐츠가 동일한 라이센스아래에서 출간 되는 것이 허락되는것을 동의해야 합니다. 상세한 내용은 [라이센스 파일](LICENSE.md)에서 확인해 보십시오.

## 현재 단계

To check the current progress and planned content of the book, check out the [outline](outline.md). This is a good place to start if you're looking for something to add.

## 지역 변화를 테스트 / Testing Changes Locally

### 전제조건

* 당신의 시스템에 [Ruby](https://www.ruby-lang.org/en/documentation/installation/)가 설치 되어 있어야 합니다. 필요한 버전은 [`.ruby-version`](.ruby-version)에서 확인 할 수 있습니다.
* Ruby Gem이 설치 되어 있어야 합니다. `gem install bundler` 명령어로 확인 할 수 있습니다. 
* [Node](https://nodejs.org/en/download/) 역시 설치 되어 있어야 합니다. 필요한 버전은 [`package.json`](package.json)에서 확인 할 수 있습니다. .

### 의존성 해결하기

당신은 의존성을 해결하기 위해서 쉘상에서 `script/bootstrap`를 실행해야 합니다. 

``` sh
$ script/bootstrap
```

### 사이트 시작하기

당신은 `script/server` 명령어로 사이트를 시작 할 수 있습니다. 

``` sh
$ script/server
Loading site data...
Compiling site...
…

Site compiled in 5.81s.
```

서버가 켜져 있는 동안, 당신은 http://localhost:4000 에서 브라우져로 볼 수 있습니다. 

## 기여하기

당신이 변경을 만들거나, 콘텐츠를 추가하거나, 뭔가를 발전시기키를 원한다면,  [기여자 가이드](CONTRIBUTING.md)를 확인해 주십시오. 
