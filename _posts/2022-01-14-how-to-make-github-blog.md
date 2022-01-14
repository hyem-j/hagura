---
layout: post
title:  "Github Blog 만드는 법"
---


blog를 시작하기로 마음 먹은 후, 어떤 형태의 blog를 운영할까 고민했습니다.
네이버 블로그, Tistory, Wordpress 등 여러 가지를 살펴보다가 제 마음대로 가지고 놀아보고 싶어서 Wordpress로 블로그를 만들기로 했습니다. 구글에서 찾아본 방법대로 도메인 얻는 작업부터 시도하고 있었는데, 아니 이게 왠걸! 일년동안 특정 도메인을 사용하는데 적게는 25만원 정도 들더라구요. 블로그 얼마나 열심히 하게 될지도 모르는데... 그래서 예전에 해봤던 기억을 떠올려서 무료로 사용했던 거 같은 Github blog를 선택했습니다. 그럼 지금부터 Github blog 만드는 방법을 같이 알아보겠습니다.
</br>

### 1. Github 계정 만들기
***
먼저, [Github](https://github.com) 에 들어가서 회원가입을 진행해주세요. 
</br>

### 2. 원하는 Theme 고르기
***
웹사이트 만드는데 고수라면 처음부터 시도해도 되지만 저는 아직 잘 모르니까 다른 분들이 만들어 놓은 사이트를 가져와보도록 할게요. 아래 두 사이트에 들어가면 유료인 Theme 도 있고, 무료인 Theme 도 있어서 마음에 드시는 Theme 를 선택하시면 됩니다.

- https://jekyllthemes.io
- http://jekyllthemes.org

저는 무료로 제공되는 Theme 중에 제 마음에 드는 깔끔한 "Webjeda Hagura" Theme를 골랐어요.
- http://jekyllthemes.org/themes/hagura/

![demo]({{site.baseurl}}/assets/images/220114/hagura_demo.png)

사이트에 들어가면 아래와 같은 화면이 뜨게 되는데 여기서 Demo를 누르시면 blog를 직접 체험해 볼 수 있구요. 여기서 hompage를 누르면 code가 저장된 repository로 이동합니다. 

![hagura]({{site.baseurl}}/assets/images/220114/hagura.png)
</br>

### 3. Code 복사해오기
***
이제 fork 버튼을 누르면 여러분의 repository로 동일한 코드가 들어오게 됩니다. 

![fork]({{site.baseurl}}/assets/images/220114/repository.png)
</br>

### 4. Repository 이름 바꾸기
***
fork를 하고 나면 내 repository에 다음과 같이 코드가 들어오게 됩니다.

![after_fork]({{site.baseurl}}/assets/images/220114/after_fork.png)


이제 한 단계 남았습니다. Settings 에 들어가서 "hagura" 로 되어있는 repository name 을 **[username].github.io** 로 바꿔주세요.

![name]({{site.baseurl}}/assets/images/220114/name_change.png)


저 같은 경우에 https://hyem-j.github.io 를 검색하면 처음에 봤던 Demo 와 같이 blog가 만들어진 걸 확인할 수 있습니다.

![demo]({{site.baseurl}}/assets/images/220114/hagura_demo.png)
</br>

오늘은 Github blog 만드는 방법에 대해서 정리해 봤구요. 다음에는 blog 를 수리해 나가면서 사용했던 것들을 적어 보겠습니다.
