---
layout: news_post
title: "루비 2.6.5 릴리스"
author: "nagachika"
translator: "yous"
date: 2019-10-01 11:00:00 +0000
lang: ko
---

루비 2.6.5가 릴리스되었습니다.

이 릴리스는 보안 수정을 포함합니다.
자세한 사항은 아래 글을 확인해보세요.

* [CVE-2019-16255: Shell#[] 및 Shell#test의 코드 주입 취약점]({% link ko/news/_posts/2019-10-01-code-injection-shell-test-cve-2019-16255.md %})
* [CVE-2019-16254: WEBrick의 HTTP 응답 분할 취약점(추가 수정)]({% link ko/news/_posts/2019-10-01-http-response-splitting-in-webrick-cve-2019-16254.md %})
* [CVE-2019-15845: File.fnmatch 및 File.fnmatch?의 NUL 주입 취약점]({% link ko/news/_posts/2019-10-01-nul-injection-file-fnmatch-cve-2019-15845.md %})
* [CVE-2019-16201: WEBrick Digest 인증의 정규 표현식 서비스 거부 취약점]({% link ko/news/_posts/2019-10-01-webrick-regexp-digestauth-dos-cve-2019-16201.md %})

자세한 내용은 [커밋 로그](https://github.com/ruby/ruby/compare/v2_6_4...v2_6_5)를 확인해주세요.

## 다운로드

{% assign release = site.data.releases | where: "version", "2.6.5" | first %}

* <{{ release.url.bz2 }}>

      SIZE: {{ release.size.bz2 }}
      SHA1: {{ release.sha1.bz2 }}
      SHA256: {{ release.sha256.bz2 }}
      SHA512: {{ release.sha512.bz2 }}

* <{{ release.url.gz }}>

      SIZE: {{ release.size.gz }}
      SHA1: {{ release.sha1.gz }}
      SHA256: {{ release.sha256.gz }}
      SHA512: {{ release.sha512.gz }}

* <{{ release.url.xz }}>

      SIZE: {{ release.size.xz }}
      SHA1: {{ release.sha1.xz }}
      SHA256: {{ release.sha256.xz }}
      SHA512: {{ release.sha512.xz }}

* <{{ release.url.zip }}>

      SIZE: {{ release.size.zip }}
      SHA1: {{ release.sha1.zip }}
      SHA256: {{ release.sha256.zip }}
      SHA512: {{ release.sha512.zip }}

## 릴리스 코멘트

많은 커미터, 개발자, 버그를 신고해준 사용자들이 이 릴리스를 만드는 데 도움을 주었습니다.
그들의 기여에 감사드립니다.
