K. 19.10.14 ~ 22

# input 입력 길이 제한 + only number + 최대 길이 입력시 버튼 활성화

> **input의 type과 상관없이 기능 구현**

* type="text" / type="tel" : max-length 사용 시, 길이 제한 O
* type="number" : max-length 사용 시, 길이 제한 X.


**[확인 브라우저]**
* IE 9+
* firefox
* chrome


**[참고 사이트]**
* [keycode](https://blog.lael.be/post/75)


**[참고 사항]**
* addEventListener: IE 9+
* classList: IE 10+
 : 클래스 추가/제거 시, IE 10+ 일 경우, 사용 가능
 : IE 10 미만을 고려해야 한다면, setAttribute 사용해서 제어 가능


**[지식보완이 필요한 부분]**
* stopPropagation, preventDefault 의 정확한 기능 및 브라우저 별 차이점
 : keyCode 막는데 stopPropagation을 사용하면 IE에서는 의도대로 동작되지 않음. (== 문자 입력 가능)
 : cherom에서는 의도대로 동작. (== 문자 입력 불가능)
* getElementById와 querySelector의 차이점.
* 클래스 제어할 수 있는 다른 방법 
* 정규식을 사용해서 기능 구현할 수 있는 방법
