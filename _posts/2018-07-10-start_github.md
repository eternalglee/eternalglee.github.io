---
layout: post
title: '스타뜨 깃헙'
author: Glee
date: 2018-07-10 02:40
tags: [github]
image: /files/covers/github-meetup-01.jpg
---

### 제가 Github pages로 사이트를 만들어보려구요. (feat.디자이너)  
(글 한번 날려먹어서 약 5일동안 멘탈 정리 후, 다시 적어봄)  

## 1. 왜 github pages로 만들고자했는가.  
진행중이던 다수의 프로젝트들이 마무리 단계에 들어섰다.  
다른 프로젝트에 들어가기 전, 팀원들이 지금 생각하고 했던 것들을 글로 남겨두면 좋을 것 같단 생각을 했다.  
잠깐 머릿속을 스치는 생각들로 글로 남기면 그것은 온전히 우리의 것이 되니까.  
그래서 기업블로그 자료를 조사하다 github pages로 만들어진 사이트들을 보게 되었다. 그 중에서도 인상깊었던 몇가지 블로그들을 소개하고 넘어가자.  

- 참고하기 좋은 기업블로그들  
 - [리디북스 블로그](http://www.ridicorp.com/blog/)  
   : 다루는 영역이 다양하다. 보통 기술블로그에서 많이 보이는 개발적인 영역부터 디자인영역까지 세분화되어있다.  
   : 프레젠테이션 공유 사이트인 http://speakerdeck.com를 사용하여 기획 문서들을 공유하고있다.  
   : 리디북스 이지혜디자이너의 github blog(http://jihyeleee.com/)도 추천한다. 나는 이분이 나왔던 **[팟캐스트]**(http://pod.ssenhosting.com/rss/dspectrum/designtable.xml)를 통해 github에 대한 존재를 처음 알게되었다. 
   
 - [도도포인트 스포카 블로그](https://spoqa.github.io/)  
    : 깔끔한 기업블로그의 정석.  
    : 디자이너로서 읽어도 모르는 글이 가득이지만, 그럼에도 그들의 성장과정을 엿볼 수 있다.
    : 자체 제작 폰트를 활용하여 가독성도 높고 사이트도 깔끔하다. 글도 꽤 자주 올라온다.

 - [배달의민족 기술블로그](http://woowabros.github.io/)  
    : 홈페이지처럼 카테고리를 나눠놔서 사용자가 쉽게 원하는 글을 찾을 수 있도록 한 배려가 돋보인다.  
    : 마찬가지로 읽어도 모르는 글이 가득이지만, 신입사원 인터뷰나 경험담을 솔직하게 올린 글들을 흥미롭게 읽었다.  
  
 - [카카오 기술블로그](http://tech.kakao.com/)  
    : 빠지면 서운한 카카오 블로그. 가장 마음에 드는 화면구성이었다. 웹폰트도 카카오전용서체를 사용했다.  
    : 다른 블로그들과는 다르게 검색영역이 있고 푸터도 깔끔하게 자리하고있다.  
    : 공부를 위해 해당 레파지토리를 fork해서 다운 받아 구성요소를 꼼꼼히 체크해볼 수 있어 좋았다.  


## 2. 왜 Meetup을 하게 되었는가.
![정말 죽을뻔했다.](https://pbs.twimg.com/media/CXugZgnUEAAyyr0.jpg)
물론 나 혼자 해봤다. 거의 2주정도 죽을 쒔다.  
디자이너분들 중에서도 github으로 블로그를 시도한 분들이 많아 그분들의 이야기를 먼저 읽었다. 정독했다.  
어렵고 많은 좌절이 기다리고 있을것이라고 했다. 그래서 준비과정이 많이 필요하다고 했다.  
그래서 동일하게 따라했다. 하지만 페이지는 뜨지 않았다.  
친하지도 않은 터미널에 루비를 깔고 잼을 깔고 지킬을 깔았지만 그들은 엇갈린 태엽처럼 서로 맞물리지않았다.  
깊은 밀림 속을 나 혼자 해메고 있는 느낌, 검색하면 검색할수록 숲의 깊은 곳으로 더 빨려가는 기분이었다.  
그렇게 2주를 헤매고 Dong개발자님께 SOS를 요청했다. 그런데 그 분은 다같이 스터디를 하면 어떨까요?라고 대답하셨다.  
왠지 이상한 답을 받은 기분이었지만 뭐 어때. 나 혼자 헤매는 것보다 같이 헤매는게 덜 외롭겠지.  


## 3. 그래서 어떻게 깔았나.  
의외로 답은 간단했다. 물론 그 간단한 답 내가 못찾았다.  
다른 개발자님께도 제가 이런걸 하고있는데여~ 어떤거같아여~ 라고 여쭤봤는데 개발자님 그 다음날 답 들고 오심.  
딱봐도 2시간 정도 보시고 바로 파악하신 느낌. 난 2주 걸려도 해결 못했는데. 허허허  
개발자님이 말씀해주신 방법은, 아주 간단한 방법이다.  
터미널 켜고 루비 깔고 지킬깔고 이렇게 터미널로 명령어 칠 필요가 없다는 것.  

1. **[지킬 테마 사이트](http://jekyllthemes.org/)** 에 들어간 후 원하는 테마를 고른다.  
2. 해당 테마의 github 사이트로 이동한다.  
3. fork버튼을 눌러 내 github으로 가져온다.  
4. 내 github으로 오면 방금 가져온 테마명으로 레파지토리가 생성되어있다.  
5. 그 레파지토리의 이름을 내 계정이름을 넣어 변경해준다. (ex. theme.github.io > userid.github.io)  
6. 해당 레파지토리에 있는 초록색 버튼 'clone or download'버튼을 눌러 주소를 복사한다.<br />clone은 터미널로 복사해오라는 명령을 할 때 내 깃헙주소를 복사해줌.<br />download는 zip파일로 내 깃헙을 다운 받을 수 있음<br />*여기서 로컬과 서버에서 버전차이가 발생할 텐데, 서버를 기준으로 업데이트 치는 방법을임개발자님이 알려주시기로함.
7. 터미널을 열어 다운받을 디렉토리로 이동 후, git clone 아까 복사한 주소 를 넣어 다운받아준다.  
8. 테마에 쓰인 소스를 내가 원하는대로 수정해주고 터미널 명령어를 입력해 다시 git 서버로 보내준다.  
9. git status를 입력하여 해당 폴더에 변경된 내역이 있는지 확인한다.  
10. git commit -m "" 입력하고 ""안에 수정내용을 적는다.  
11. git status를 한번 더 입력하여 커밋이 잘되었는지 확인한다.  
12. git push origin master를 입력하여 서버에 완전히 반영해준다.  

나는 마지막 터미널 명령어를 자기전마다 한 스무번씩 반복했다. 무식하니까. 이렇게해야 명령어가 외워진다.  
덕분에 이제 터미널도 좀 다룰줄 알고 애가 뭘 말하는지 눈치도 까게되었다. 흐흐  
github에 대한 이야기는 여기서 마무리하고 다음 이야기는 첫 Meetup에 대한 이야기를 적어봐야겠다.  










