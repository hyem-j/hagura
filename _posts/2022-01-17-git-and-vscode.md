---
layout: post
title:  "Github VScode 연동"
---

IDE를 통하여 조금 더 편하게 포스트를 작성하기 위하여 VScode에 연동해보겠습니다.

### Repository 복사
***
Github 에서 Vscode 에서 사용하고자 하는 repository의 주소를 복사합니다.

![address]({{site.baseurl}}/assets/images/220117/address.png)

Vscode 실행 후 아래 그림에서 보이는 것과 같이 **clone repository** 을 선택합니다. 그 후, 위에서 복사해온 repository 주소를 입력합니다. 

![clone]({{site.baseurl}}/assets/images/220117/clone.png)

다음과 같이 code가 복사된 것을 확인할 수 있습니다.

![success]({{site.baseurl}}/assets/images/220117/clone_success.png)

### Post Upload
***
새로운 게시글을 업로드해보겠습니다. 저는 포스트를 작성할 것이므로 _posts 폴더에 새로운 파일을 추가해줍니다. 그 후, source control 에 들어가서 확인해보면 다음과 같이 새로운 파일이 추가된 것을 확인할 수 있습니다.

![success]({{site.baseurl}}/assets/images/220117/change.png)

Github에 업로드하기 위해서 commit과 push를 해주어야 합니다. 그림의 2번 항목에 원하시는 "message" 를 입력 후 3번을 누르면 commit이 완료됩니다.

push까지 완료를 해야 파일이 github에 올라가게 되는데요. 다음 그림과 같이 ...항목을 눌러서 push를 눌러주시면 됩니다.

![push]({{site.baseurl}}/assets/images/220117/push.png)

github 계정과 vscode가 연결이 안 되어있는 경우 연결하라는 창이 뜰 수 있는데요. "allow"를 선택하셔서 github 계정과 연결해주시면 됩니다.

![login]({{site.baseurl}}/assets/images/220117/login.png)

오늘은 손쉬운 포스팅을 위하여 github과 vscode를 연결하는 법에 대해 알아보았습니다. 도움이 되면 좋겠어요. 다음 번에는 다른 정보로 찾아올게요 :)