---
title: ';'
layout: default
permalink: /sh/
---

**shell;**

(컴퓨터 환경이라든가.. 뭐 설치 팁이라던가 그런것들. 쉘 로그.. 짤막하게!)

---

**yosemite (10.10)**

---

> - **cmus**
>   - brew install cmus
> 
> - **mpv**
>   - brew install mpv --with-bundle
>   - brew linkapps mpv
> 
> - **jekyll + github pages**
>   - sudo gem install bundler
>   - cd sync-www-doohoyi.github.io/
>   - bundle
>     - *permission error!*
>     - sudo gem install nokogiri -v '1.6.8.1'
>     - *error! again without version option.*
>     - sudo gem install nokogiri
>     - *installed 1.7.0.. 'bundle' again.*
>     - bundle
>     - *failed https://github.com/sparklemotion/nokogiri/issues/1483#issuecomment-262929221*
>     - brew unlink xz
>     - bundle
>     - *pass*
>     - brew link xz
>   - bundle exec jekyll serve
> - **supercollider @ emacs**
>   - frequently used key combo
>     - C-c C-o : start sclang
>     - C-c C-c : eval current line
>     - C-M-x   : eval current region
>     - C-c C-h : view help @ w3m
>
{: #sh}

<style>
#sh ul li {
    margin-left: 20px;
}
#sh ul li ul li {
    margin-left: 40px;
}
</style>
