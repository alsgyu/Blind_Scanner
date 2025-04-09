# 2024 이노씽크 메이커톤


## 주제
인천지역 안전 및 재난 문제 해결 시제품 개발

## 개요
알권리는 누구에게나 있다

제품의 바코드 통해 정보를 읽어와 각 사용자에게 맞는 성분별 권장 섭취 비율, 알레르기 정보를 알려주는 프로그램을 만들면 어떨까
- 저시력자의 식품 정보 알권리 보장을 통한 식품 안전 문제 해결
---

## 1. .env 파일 만들기
  
```bash
SUPABASE_URL=https://npgmcsvclcnvmonrirvj.supabase.co
SUPABASE_KEY=service key

API_KEY_NAME=key_name
API_KEY_DETAIL=api_key
```

## 2. requiremets.txt 설치

   ```bash
   pip install -r requirements.txt
   ```

## 3. streamlit run db_manage.py

<img src="https://github.com/user-attachments/assets/a16e72a3-9b47-48a4-9a93-f049e1c57e4c" style="width:50%;"/>
<img src="https://github.com/user-attachments/assets/3a9b553d-4d46-491a-81f6-6e867d20772c" style="width:50%;"/>


## 4. main4.py

PS D:\ICBM> python main4.py
>>
바코드를 입력하세요: 8801045571362
1. 제품 이름: 오뚜기 진라면 순한맛
2. 제품 번호: 19860309018680

3. 요청 url:  http://apis.data.go.kr/B553748/CertImgListServiceV3/getCertImgListServiceV3?ServiceKey=oqdC%2FqEnEV%2FuF3Vy2pVZd4qFqZQTJkEVnv4wvLJIP%2FadzKf%2FBOn5%2FzQSQ%2Fg0mEV5s53E7bSwXJ5wz0V8UNbGlw%3D%3D&prdlstReportNo=19860309018680&returnType=json&numOfRows=1
응답 데이터: {...}

5. 알레르기 정보:
 - 계란: 위험! 위험 알레르기 성분이 포함되어 있습니다.
 - 우유: 주의가 필요한 알레르기 성분이 포함되어 있습니다.


---
# DATABASE 수정을 위한 STREAMLIT 구현

<img src="https://github.com/user-attachments/assets/cb90a035-0c53-40f1-993e-90c1b051c4ef" style="width:50%;"/>

<img src="https://github.com/user-attachments/assets/6bd7fd10-9f5e-441b-90da-b6fe68593466" style="width:30%;"/>

## DB

<img src="https://github.com/kimminsu38oo/Scanfood-2024-innothink-final/blob/main/readmeref/diagram.png?raw=true" style="width:50%;"/>


## 흐름도
<img src="https://github.com/kimminsu38oo/Scanfood-2024-innothink-final/blob/main/readmeref/%EA%B5%AC%EC%84%B1%EB%8F%84.png?raw=true" style="width:60%;"/>

---
<img src="https://github.com/user-attachments/assets/ad7cd532-cd31-41fe-b93a-efea230d9bae" height="350"/>

---





