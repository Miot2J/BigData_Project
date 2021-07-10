# BigData_Project
-------
## 한국데이터산업진흥원주관 데이터청년 캠퍼스를 수료하며 만든 팀 프로젝트 

+ Notion Link(To-Do List , 요구사항, 스프린트 기간 설정, 데이터 수집, 데이터 전처리, 머신러닝 모형 생성, 모형 테스트, 시각화 및 서버배포 정리)
https://www.notion.so/86bdc36bb5984f32af2d438395c2b28d?v=5dfe761606b741979dc927b80bb8170c
 
+ 발표 PPT Link  
https://drive.google.com/file/d/1j3RTWmzC5kcxpX5Mem15Y5LduNTqz-QK/view?usp=sharing

### 사용 기술 스택

Python, Java Script, Django, Docker, Nginx, XGBoost, EC2, CSS


### 개요  
+ 문제점 

  시민들의 인터넷 민원 접수 시 처리 부서에 직접 민원을 넣는 방식이 아닌,
  몇명의 담당자가 민원을 일일히 읽고 직접 담당 부서에 배정하고 있음. 

+ 해결방안

  크롤링한 민원 데이터를 자연어 전처리후 XGBoost를 통해 학습된 모형으로 
  민원내용을 입력하면 적정 담당부서를 자동 분류해주는 서비스 생성.
  
 + 결과 
 
    대략 78% 정확도의 민원 담당부서 뷴류 웹 페이지 생성.
    
  + 한계점
  
    한국어에 맞는 형태소 분석기가 존재 하지 않고, 모든 불용어를 제거하는데 시간적 한계가 있었음.
    
   + 기대효과 
   
     불용어를 추가하고 한국어에 맞는 형태소 분석기를 개발 한다면 정확도를 향상 시킬수 있다.
