
## DS 직무 프로젝트를 위해 해야하는 일
          1. 이미지기반의 인공지능 공부
          2. ds기반의 인공지능을 공부한다는 식
          3. 학습위주의 내용 책,논문 기술
          4. 내용을 그대로 쓰지말고 기법은 따라해도된다.
          5. 데이터를 회사와 연결해서 작성

## 우리가 꼭 하고 넘어가야 하는 부분
          1. 기업이 원하는 이미지를 확실하게 이미지 크롤링으로 획득 및 라벨링
          2. yolo1~7 기업 선호 버전 확인해보기
          3. 사전학습모델 사용보다는 내가 직접 학습시켜보기
          4. 모델에 대해 어떠한 방식으로 학습하는지 꼭 알아보기
          5. opencv에서의 하이퍼파라미터가 많은데 이 하이퍼파리미터들의 계산되는 과정을 확인해보기


## (회고)

11/04 

         오후 2:55 
         
         전체적인 프로젝트 계획 
          
11/07

         오후 3:55 
         
         이미지 크롤링 진행되는 것을 확인하여 약 500개 가량의 사진 획득

         그러나 라벨링을 진행을 어떻게 진행 해야 할까?
          
         라벨링한 데이터가 몇개 정도 획득해야 충분할까?
          
         -----------------------------------------------------------------------
         
         오후 5:15 
        
         project meeting 1 을 진행 후 여러 과제를 받았다. 

         1. 기업이 원하는 이미지를 확실하게 이미지 크롤링으로 획득 및 라벨링
         2. Yolo1~7 기업 선호 버전 확인해보기
         3. 사전학습모델 사용보다는 내가 직접 학습시켜보기
         4. 모델에 대해 어떠한 방식으로 학습하는지 꼭 알아보기
         5. opencv에서의 하이퍼파라미터가 많은데 이 하이퍼파리미터들의 계산되는 과정을 확인해보기

11/08 

         오전 11:00
         
         이미지 크롤링 허가사이트와 상업적 사용가능한 이미지 사진을 찾으면서 크롤링 하는 것과 라벨링을 진행하는데
         
         너무 오랜 시간이 걸린다 판단하여 aihub에서 140종의 한국음식이미지 각 1000장의 데이터를 얻었다.
         
         ------------------------------------------------------------------------
         
         오후 4:00
         
         이미지를 라벨링 후 전처리를 위해 opencv를 공부
         
         블로그를 통해 여러가지 사용법 확인

11/09

         오전 10:00
         
         vscode를 사용하다 jupyter notebook으로 바꿔서 사용하다 작동이슈로 인해 진행이 멈춤
        
         
11/10

         오후 1:20
         
         modeling을 위해 다양한 CNN모델 찾아보며 확인
         
         ------------------------------------------------------------------
         
         오후 4:40
         
         모델 적용하며 결과 확인
         
11/11

         오후 1:20
         
         모델들을 더 공부 
         
         ------------------------------------------------------------------
         
         

# 프로젝트 개요 및 목적

고객들의 니즈와 참여를 만족시키기 위해서는 가장 간단한 요구만을 부탁드려야 한다.

그렇기에 가장 간단한 방법은 자신의 식단을 사진 하나로 찍는 방법이 가장 간단하며 혹은 소셜미디어를 이용하는 고객들은 자신의 음식사진을 찍는 경우가 많다.

사진 하나만을 고객에게 요구하며 우리는 그에 대한 사진하나로 많은 정보를 얻어야 한다.

그렇기에 우리는 우리 한국인 정서에 맞게 한국인들이 먹는 음식들에 대한 데이터를 중심적으로 모아야 하며

한식 특성상 한 상에 여러가지 반찬이 있는 경우에도 확실하게 인식하여 우리가 얻을 수 있는 정보를 최대한 획득해야 한다.

## 앞으로의 진행과정
          (V) 기업 관련된 이미지 파일 수집
          (V) 이미지 전처리(모두 동일 사이즈로 변환 및 용량 줄이기)  이미지 라벨링
          (V) AI 학습모델 진행 확인해보고 어떠한 방식으로 학습하는 지 알아보기
          

### 참고 Reference 및 기본 주소

회사소개및 앱 소개

https://www.sprintapp.team/ 

스프린트 앱 리뷰

https://play.google.com/store/apps/details?id=dev.lab90.spaceForNutrition

OpenCV 소개

https://velog.io/@jaehyeong/OpenCV%EB%A5%BC-%ED%99%9C%EC%9A%A9%ED%95%9C-%EA%B8%B0%EC%B4%88-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%B2%98%EB%A6%AC-with-Python

https://ddolcat.tistory.com/958

CNN

https://rubber-tree.tistory.com/120
