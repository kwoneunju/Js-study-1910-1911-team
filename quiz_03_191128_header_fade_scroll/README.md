K. 19.11.12

# Header Fade Scroll 구현
> scroll up/down 시, opacity 변경\
scroll의 위치 값에 따라 opacity, height, margin-top 조정

**[확인 브라우저]**
* IE 9+
* firefox
* chrome

**[참고 사항]**
* addEventListener: IE9+

<br/>

### [ Javascript ]
**1. JS로 css style 설정**

* 단일 style 지정:
```
document.querySelector('.bg').**style.height = '100px'**;
document.querySelector('.bg').**style.marginTop = '10px'**;
```
* 다중 style 설정: setAttribute 사용
```
document.querySelector('.bg').**setAttribute('style', 'opacity:1;height:100%;margin:0')**;
```
