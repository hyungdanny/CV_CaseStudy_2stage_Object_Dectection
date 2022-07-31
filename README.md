# 2 stage Object Dectection 
### Near duplicate image detection
## Index
  - [Scoping](#Scoping) 
  - [기획](#기획)
  - [데이터셋 설명](#데이터셋 설명)
  - [오류 원인 분석](#오류 원인 분석)
  - [결과](#결과)
  - [한계점과 해결방안](#한계점과 해결방안)
  - [Used or Referenced Projects](Used-or-Referenced-Projects)
-->
## About RepositoryTemplate
<!--Wirte one paragraph of project description -->  
 - 이 프로젝트는 코드스테이츠 AI 부트캠프 10기 과정을 수료하기위해 진행한 마지막 프로젝트입니다.
 - 컴퓨터비젼 분야에 관심을 갖게 되어 이 분야를 좀 더 깊게 탐구하기 위하여 프로젝트를 기획했습니다.
 - 2stage 탐지모델의 대표인 R-CNN 계열 모델을 시초부터 최신 모델을 구축하면서 어떤 문제점을 개선하면서 발전해왔는지 직접 확인하는 것이 목표입니다.
 - 데이터는 DeepFashion2를 선정하였고 이유는 Annotaion이 잘 되어있고 연구자가 패션에 관심이 있기 때문입니다.
 - 주목할 점은 같은 데이터를 사용하되 다른 모델을 적용시키면서 성능이 얼마나 개선이 되고 어떤 차이를 가지는 지 확인하는 것입니다. 

## Scoping (프로젝트 정의)
1. 문제 정의 : 여러 상황에서 촬영된 이미지따라 동일한 사물이지만 다른 사물로 인식하는 오류를 개선한다. 
2. 데이터 : DeepFashion2
3. 기대하는 결과값 : 2stage CV 중 R-CNN 군의 모델을 탐구하며 성능을 개선시키고 어떻게 발전하는지 과정을 파악한다. 

프로젝트를 통해 얻고자 하는 결과값은 무엇인가?(Y 값)
성과 지표(key metrics)를 설정한다.
예를 들자면 아래와 같은 성과 지표를 의미한다.
Accuracy: 음성 인식 정확도가 어느정도여야 하는지?
Latency: 음성 인식을 하는데 시간이 얼마나 걸리는지?
Throughput: 초당 쿼리 처리수은 얼마나 되는지?
프로젝트를 수행하는 데 시간이 얼마나 걸리는지?



## Authors


## Reference

```

```
