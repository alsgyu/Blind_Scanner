# 2024 이노씽크 메이커톤


## 주제
인천지역 안전 및 재난 문제 해결 시제품 개발

## 개요
알권리는 누구에게나 있다.

제품의 이름을 통해 각 사용자에게 맞는 성분별 권장 섭취 비율, 알레르기 정보를 알려주는 프로그램을 만들면 어떨까
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
응답 데이터: {
  "body": {
    "items": [
      {
        "item": {
          "nutrient": "1회 제공량 1봉지 (120g) 열량 500kcal 탄수화물 79g 24% 당류 4g 단백질 12g 22% 지방 15g 29% 포화지방 8g 53% 트랜스지방 0g 콜레스테롤 0mg 0%  나트륨 1,880mg 94% 칼슘 163mg 23% *%영양성분기준치: 1일 영양성분기준치에 대한 비 율",
          "rawmtrl": "면:소맥분(밀:미국산,호주산),변성전분,팜유(말레이시아산),감 자전분(외국산:덴마크,프랑스,독일 등),글루텐,정제소금,유화유지,난각분말,육수추출농축액,마늘시즈닝,이스트엑기스,면류첨가알칼리제(산도조절제),구아검,비타민B2,녹차풍 미유 스프류:정제소금,백설탕,참맛사골양념분말,사골양념분말,참맛양지분말,조미육수분말,비프베이스분말,육수추출농축분말,맛베이스,간장양념베이스,간장분말,감칠맛베이스,진한감칠맛분,오뚜기참치간장분말,참맛볶음장분말,쇠고기육수분말,향미증진제,복합양념분말,볶음향미분말,홍고추분말,포도당,오뚜기비프시즈닝,육수맛조미분,조미야채분말,볶음마늘분,고추맛베이스,후추분말,마늘농축조미분,숙성마늘맛분,감칠맛조미분,로스팅조 미분말,유지혼합분말,옥수수전분,이스트추출물분말,참맛효모조미분말,매운고추양념분말,영양강화제,칠리혼합추출물,조미쇠고기맛후레이크,건파,건당근,건표고버섯,건청경채, 건미역",
          "prdlstNm": "오뚜기 진라면 순한맛",
          "imgurl2": "http://fresh.haccp.or.kr/prdimg/1986/19860309018680/19860309018680-2.jpg",
          "barcode": "알수없음",
          "imgurl1": "http://fresh.haccp.or.kr/prdimg/1986/19860309018680/19860309018680-1.jpg",
          "productGb": "식품",
          "seller": "알수없음",
          "prdkindstate": "알수없음",
          "rnum": "1",
          "manufacture": "오뚜기라면주식회사 ",
          "prdkind": "유탕면류",
          "capacity": "600g(120g*5)",
          "prdlstReportNo": "19860309018680",
          "allergy": "밀,대두,계란,우유,쇠고기,돼지고기,닭고기,오징어,조개류(굴, 홍합 포함) 함유"
        }
      }
    ],
    "totalCount": "1",
    "pageNo": "1",
    "numOfRows": "1"
  },
  "header": {
    "resultCode": "OK",
    "resultMessage": "success"
  }
}
Item 내용: {
  "nutrient": "1회 제공량 1봉지 (120g) 열량 500kcal 탄수화물 79g 24% 당류 4g 단백질 12g 22% 지방 15g 29% 포화지방 8g 53% 트랜스지방 0g 콜레스테롤 0mg 0% 나트륨 1,880mg 94% 칼슘 163mg 23% *%영양성분기준치: 1일 영양성분기준치에 대한 비율",      
  "rawmtrl": "면:소맥분(밀:미국산,호주산),변성전분,팜유(말레이시아산),감자전분(외국산:덴마크,프랑스,독일 등),글루텐,정제소금,유화유지,난각분말,육수추출농축액,마늘시즈닝,이스트엑기스,면류첨가알칼리제(산도조절제),구아검,비타민B2,녹차풍미유 스프 류:정제소금,백설탕,참맛사골양념분말,사골양념분말,참맛양지분말,조미육수분말,비프베이스분말,육수추출농축분말,맛베이스,간장양념베이스,간장분말,감칠맛베이스,진한감칠 맛분,오뚜기참치간장분말,참맛볶음장분말,쇠고기육수분말,향미증진제,복합양념분말,볶 음향미분말,홍고추분말,포도당,오뚜기비프시즈닝,육수맛조미분,조미야채분말,볶음마늘 분,고추맛베이스,후추분말,마늘농축조미분,숙성마늘맛분,감칠맛조미분,로스팅조미분말,유지혼합분말,옥수수전분,이스트추출물분말,참맛효모조미분말,매운고추양념분말,영양강화제,칠리혼합추출물,조미쇠고기맛후레이크,건파,건당근,건표고버섯,건청경채,건미역",
  "prdlstNm": "오뚜기 진라면 순한맛",
  "imgurl2": "http://fresh.haccp.or.kr/prdimg/1986/19860309018680/19860309018680-2.jpg",
  "barcode": "알수없음",
  "imgurl1": "http://fresh.haccp.or.kr/prdimg/1986/19860309018680/19860309018680-1.jpg",
  "productGb": "식품",
  "seller": "알수없음",
  "prdkindstate": "알수없음",
  "rnum": "1",
  "manufacture": "오뚜기라면주식회사 ",
  "prdkind": "유탕면류",
  "capacity": "600g(120g*5)",
  "prdlstReportNo": "19860309018680",
  "allergy": "밀,대두,계란,우유,쇠고기,돼지고기,닭고기,오징어,조개류(굴,홍합 포함) 함유"
}

4. 영양 정보:
   - 열량: 500kcal kcal
   - 탄수화물: 79g g
   - 단백질: 12g g
   - 지방: 15g g

5. 알레르기 정보:
 - 계란: 주의! 위험 알레르기 성분이 포함되어 있습니다.
 - 우유: 주 git init  필요한 알레르기 성분이 포함되어 있습니다.


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





