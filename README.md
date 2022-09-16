# flash-card
플래시 카드 토이프로젝트입니다.  

플래시 카드란 간격을 두고 암기하는 학습법입니다.  

10분, 1시간, 내일, 모래, 내일모래, 다음주, 다음달, 다음분기, 내년, 4년 후로 카드를 묶을 수 있습니다.  
맞출때 마다 다음 묶음에 넣습니다.  

```JavaScript
const interval = {
  tenMin : 600000, // 10분 뒤
  hr : 3600000, // 1시간 뒤
  oneDay : 0, // 내일
  twoDay : 0, // 모래
  threeDay : 0, // 내일모래
  week : 0, // 다음주
}
```

```JavaScript
const date = New Date();
```

https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Date

간단한 맞춤법 문제, 영단어 문제로 출발할 것입니다. 나중에는 코딩 문제로 확장할 것입니다.  


# 이 프로젝트를 하는 이유
요구사항 정의같은 꼼수로 1일1커밋도 가능합니다.
간단해서 진행합니다. 그리고 실제로 제가 사용할 예정입니다. 저는 맞춤법, 영어스펠링에 상당히 약합니다. 그래서 더티코더(dirty programmer)가 되기 쉽상입니다. 
