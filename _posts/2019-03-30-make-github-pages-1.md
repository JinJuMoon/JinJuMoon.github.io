---
layout: post
title : Making Github pages pt.1
---

<p>
<strong>1. 루비 개발환경 설치하기</strong><br><br>
루비와 rvm을 설치합니다.<br>
<code>& ruby install code</code><br>
<code>& rvm istall ruby 0.0.0</code>
</p>



<br><br><br>
<p>
<strong>2. Jekyll과 bundler 설치하기</strong><br><br>
정적 페이지를 자동으로 구현해주는 Jekyll과 패키지를 한 번에 내려받을 수 있도록 해주는 bundler를 설치합니다.<br>
<code>$ gem install jekyll bundler</code><br>
</p>



<br><br><br>
<p>
<strong>3. jekyll 사이트 생성하기</strong><br><br>
이제 아래 명령어를 입력하면 ./myblog 디렉토리와 함께 사이트가 생성됩니다.<br>
<code>$ jekyll new myblog</code><br><br>

생성된 myblog디렉토리로 이동합니다.<br>
<code>& cd myblog</code>
</p>



<br><br><br>
<p>
<strong>4. 사이트 빌드하기</strong><br><br>
사이트가 빌드합니다.<br>
<code>$ bundle exec jekyll serve</code><br>
브라우저로 http://localhost:4000에 접속하면 사이트를 볼 수 있습니다.
</p>
