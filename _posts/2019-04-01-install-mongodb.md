---
title: "mongodb  설치하기"
date: 2019-04-01
tags: [mongodb, mongoose, database, noSQL]
---

mongoose를 사용하려면 먼저 mongodb를 설치해야 한다. mongodb 사용법은 아래와 같다.

## 1. mongodb 설치하기

```
brew install mongodb
```

만약 다음과 같은 에러가 뜬다면
```
Error: /usr/local is not writable. You should change the ownership
and permissions of /usr/local back to your user account:
  sudo chown -R $(whoami) /usr/local
```

Homebrew를 재설치한다.
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## 2. mongodb 실행하기

```
brew services start mongod
```

## 3. mongodb 연결 후 사용하기

```
mongod
```
