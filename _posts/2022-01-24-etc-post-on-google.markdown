---
layout: post
title:  "[etc] Google Search Console, Analytics, AdSense"
date:   2022-01-24 10:00:00 +0900
categories: jekyll blog
---
### 목차
1. [서론](#1-서론)
2. [Search Console](#2-search-console)
3. [Analytics](#3-analytics)
4. [AdSense](#4-adsense)
5. [결론](#5-결론)
6. [Link](#6-link)

## 1. 서론
블로그는 내가 배운 것들을 다시 복습해보는 역할도 있겠지만,  
문제에 대해 여러 사람들이 보고 배우는 것과 다른 의견을 들어보는 것으로  
더 나은 블로그를 꾸밀 수 있다고 생각했다.  
그래서 웹과 관련된 Google의 3가지 서비스를 블로그에 적용시켜보려 한다.

## 2. Search Console
<https://google.com/>{:target="_blank"}에 나의 글이 검색되게 해주는 서비스이다.([Link<sup>1</sup>](https://search.google.com/search-console?hl=ko){:target="_blank"})  
URL을 등록하면 끝난다.추가적으로 `sitemap.xml`과 `robot.txt`를 추가하여  
자동적으로 색인을 갱신하는 작업을 하고 있다.

## 3. Analytics
현재 블로그의 Traffic을 분석하는 서비스이다.([Link<sup>2</sup>](https://www.google.com/analytics/?hl=ko){:target="_blank"})  
URL을 등록한 후 Tracking ID를 블로그 `root`폴더의 `_config.yml`에 추가하면 된다.  
(Jekyll Theme마다 Tracking ID를 추가할 수 있는 형식의 유무가 다르다.  
현재 블로그에서 사용중인 `minima`는 해당 형식을 직접 추가해주어야 한다.)

## 4. AdSense
블로그에 Traffic에 따라 수익을 내주는(수익구조는 확실하지 않다.) 서비스이다.([Link<sup>3</sup>](https://www.google.com/intl/ko_kr/adsense/start/){:target="_blank"})  
수익이 나면 좋겠지만 그러기엔 힘들 것 같고, 이후 GCP 사용에 있어 Google의 서비스를  
미리 써보는 예행연습정도로 생각하면 되겠다.

## 5. 결론
이 글을 쓰기 전부터 조금 시도는 해보았는데, 이래저래 시행착오가 많다.  
하나씩 정리될 때마다 추가적으로 업데이트 할 예정이다.

## 6. Link
*1. Google Search Console*  
<https://search.google.com/search-console?hl=ko>{:target="_blank"}  
*2. Google Analystics*  
<https://www.google.com/analytics/?hl=ko>{:target="_blank"}  
*3. Google AdSense*  
<https://www.google.com/intl/ko_kr/adsense/start/>{:target="_blank"}