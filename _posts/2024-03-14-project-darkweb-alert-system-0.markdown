---
layout: post
title:  "[Project] DarkWeb Alert System - 0"
date:   2024-03-14 12:00:00 +0900
categories: jekyll blog
---

###### 최종 수정: 2024.03.14(목)

### 목차
1. [Introduction](#1-introduction)
2. [Research](#2-research)
3. [Conclusion](#3-conclusion)
4. [Links](#4-links)


## 1. Introduction
위협 인텔리전스(CyberThreat Intelligence)를 다루며,  
다크웹에 게시된 자료를 분석 및 추출하여, 유저에게 필요한 정보를 제공하는 프로젝트입니다.  
수집한 자료에 대한 **개인적인 이해**를 기반으로 작성하였습니다.  
(오류가 있을 경우 <ymiwm0322@kakao.com>{:target="_blank"}으로 알려주시면 감사하겠습니다.)


## 2. Research
- **OSINT(Open-Source INTelligence)**란?  
실행 가능한 인텔리전스를 생성하기 위해  
오픈 소스(비공개 소스 및 공개적으로 사용 가능한 정보, Publicly Available Information(PAI))  
에서 수집한 데이터의 컬렉션 및 분석 자료를 말합니다.<a href="https://en.wikipedia.org/wiki/Open-source_intelligence" target="_blank"><sup>[1]</sup></a>
<br><br>
- **Forensic Artifact**란?  
포렌식 가치를 가진 포렌식 오브젝트를 말합니다.  
데이터 혹은 현상에 대한 증거(로그, 레지스터, 하이브 등)를 포함합니다.<a href="https://www.geeksforgeeks.org/windows-forensic-analysis/" target="_blank"><sup>[2]</sup></a>
<br><br>
- **Onion Routing**이란?  
컴퓨터 네트워크 상의 익명 통신을 위한 기술입니다.  
어니언 네트워크에서 메세지는 암호화된 층으로 캡슐화되어 있습니다.  
암호화된 데이터는 "Onion Routers"라 불리는 네트워크 지점을 거쳐 전송됩니다.  
각 계층의 껍질을 벗기면 데이터의 다음 목적지가 나타납니다.  
마지막 계층이 복호화되면 메세지는 목적지에 도착합니다.  
중개자는 당시의 선, 후행 노드의 위치밖에 알 수 없기 때문에 송신자는 익명으로 남습니다.<a href="https://en.wikipedia.org/wiki/Onion_routing" target="_blank"><sup>[3]</sup></a>
<br><br>
- **DDW(Deep Dark Web)**이란?
![Web Iceberg](/assets/images/2024/03/14/deep-web-iceberg.jpg)  
그림과 같이 일반 브라우저 및 검색 엔진에 의해 찾을 수 없는 도메인을 포함,  
익명성을 띄는 웹 사이트 일체를 말합니다.<a href="https://www.expressvpn.com/blog/dark-web-vs-deep-web/" target="_blank"><sup>[4]</sup></a>
<br><br>
- **Threat Actor Profiling**이란?  
위협 행위자에 대한 분석을 수행합니다.  
사용하는 공격 벡터 및 활동 시간 등 여러가지 요소를 포함합니다.
<br><br>
- **DDW 접근 방법**  
PC - (VPN) - (VM) - Tor Browser - DDW(Deep Dark Web)  
    - VPN: 특정 도메인에 접근 시 필요
    - VM: 데이터 수집 간 악성 파일에 의한 피해 방지
<br><br>
- **Dark Web Services**  
Dark Web 상 익명 서비스 리스트입니다.(HiddenWiki<a href="https://thehiddenwiki.org/" target="_blank"><sup>[5]</sup></a>)


## 3. Conclusion
Deep Web 관련 프로젝트 시작에 필요한 지식에 대해 알아봤습니다.  
다음 포스트는 카테고리 설정 및 기획, 설계를 진행해보겠습니다.


## 4. Links
*1. Wikipedia - Open-source intelligence*  
<https://en.wikipedia.org/wiki/Open-source_intelligence>{:target="_blank"}  
*2. Geeksforgeeks - Windows Forensic Analysis*  
<https://www.geeksforgeeks.org/windows-forensic-analysis/>{:target="_blank"}  
*3. Wikipedia - Onion routing*  
<https://en.wikipedia.org/wiki/Onion_routing>{:target="_blank"}  
*4. ExpressVPN - Dark web VS Deep web*  
<https://www.expressvpn.com/blog/dark-web-vs-deep-web/>{:target="_blank"}  
*5. Hidden Wiki*  
<https://thehiddenwiki.org>{:target="_blank"}