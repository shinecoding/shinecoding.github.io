---
title: "디버깅하는 법"
excerpt: "이클립스와 개발자도구를 이용한 디버깅"

categories:
  -Blog
tags:
  -Blog
last_modified_at: 2021-05-18T17:30:00-05:00
---

### **디버깅**

- 멈출 라인 왼쪽에 우클릭 후 Toggle Breakpoint 후 서버 실행
- 해당 기능을 실행
- 그 후의 라인부터 F6을 눌러서 한줄한줄 실행할 수 있다.
- F8 은 다음 브레이크 포인트로 이동한다.

※Breakpoint 대신 debugger; 적어도됌

![debug](https://github.com/shinecoding/shinecoding.github.io/blob/d10818e8718f1325387ad543961b40deccd5436e/assets/images/debug/Untitled.png)

- 브레이크 포인트란 코드가 실행되다가 일시적으로 멈추게 되는 지점이다. 이 지점부터 사용자가 순차적으로 코드를 진행시키며 코드를 분석할 수 있다.

![debug](https://github.com/shinecoding/shinecoding.github.io/blob/d10818e8718f1325387ad543961b40deccd5436e/assets/images/debug/Untitled1.png)

- 이클립스 상단 메뉴를 보면 실행 아이콘 옆에 벌레 모양의 아이콘이 있다. 이게 디버그 모드 아이콘이다. 디버그 모드를 실행하려면 이 아이콘을 클릭하거나 F11(디버그 단축키)을 누르면 된다.

- 여기서 디버그를 진행하려면 F6을 누르면 된다. 그러면 브레이크 포인트로부터 한 줄씩 내려가며 코드가 실행된다. 현재 디버그를 건너뛰고 싶다면 F8을 누르면 된다. F8을 누르면 다음 디버그 포인트로 이동된다. 만약 디버그 포인트가 지정되지 않았다면 디버그가 종료된다.

### 개발자도구(F12)를 통한 디버깅

- 원하는 기능 우클릭 후 Elements화면에서 찾아서 복사
- Search에서 검색하면 Sources 화면에서 보임
- F12를 이용해서 한줄한줄 디버깅, 끝낼 때는 F8

![debug](https://github.com/shinecoding/shinecoding.github.io/blob/d10818e8718f1325387ad543961b40deccd5436e/assets/images/debug/Untitled2.png)
