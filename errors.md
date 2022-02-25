- fatal: refusing to merge unrelated histories

+ git pull origin 브런치명 --allow-unrelated-histories

이 명령 옵션은 이미 존재하는 두 프로젝트의 기록(history)을 저장하는
드문 상황에 사용된다고 한다.
즉, git에서는 서로 관련 기록이 없는 이질적인 두 프로젝트를 병합할 때
기본적으로 거부하는데, 이것을 허용해 주는 것이다.

[출처](https://gdtbgl93.tistory.com/63)


- Untracked files:
    + (use "git add <file>..." to include in what will be committed)

이름에 띄어쓰기 들어가면 인식이 안되니 따옴표로 묶어주기


 