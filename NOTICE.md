# 데이터와 에셋 출처

- 따공의 온기 지도는 [krmap의 실제 시도 경계 SVG](https://github.com/worlyung/krmap/blob/8d6b1df4628ed01fa44ab03ff052dd6d5b9e0d02/svg/01_%EC%A0%84%EA%B5%AD/%EC%A0%84%EA%B5%AD_%EC%8B%9C%EB%8F%84.svg)를 사용합니다. 원본 경로를 유지하고 여백, 지명 표시, 개나리색 포인트와 지역별 탐색을 추가했습니다. 경계 출처는 통계청 SGIS 행정구역 경계(2026.10.01, 공공누리 제1유형)와 vuski/admdongkor 가공본(CC BY 4.0)입니다. [krmap 출처 및 라이선스](https://github.com/worlyung/krmap/blob/8d6b1df4628ed01fa44ab03ff052dd6d5b9e0d02/NOTICE.md)
- `python3 scripts/krmap-tiles.py`는 [krmap의 16개 시도 타일 SVG 원본](https://github.com/worlyung/krmap/blob/8d6b1df4628ed01fa44ab03ff052dd6d5b9e0d02/svg/06_%ED%83%80%EC%9D%BC/%EC%A0%84%EA%B5%AD_%EC%8B%9C%EB%8F%84_%EB%84%A4%EB%AA%A8.svg)에서 지역 목록의 축약명과 표시 순서에 쓰는 데이터를 가져옵니다.
- 지역 이름, 행정기관코드와 인구는 행정안전부 주민등록 인구통계의 2026년 10월 말 전국 시도 CSV에서 가져왔습니다. 등록구분 ‘전체’의 총인구수는 거주자, 거주불명자 및 주민등록 재외국민을 포함하고 외국인은 제외합니다. [행정안전부 월간 통계표](https://jumin.mois.go.kr/statMonth.do) · [2026년 10월 CSV](https://jumin.mois.go.kr/downloadCsv.do?searchYearMonth=month&xlsStats=1&sltOrgType=1&sltOrgLvl1=A&searchYearStart=2026&searchMonthStart=10&searchYearEnd=2026&searchMonthEnd=10&sltOrderType=1&sltOrderValue=ASC&category=month&state=1)
- 홈의 책방 사진과 시연 카드용 사진 소재는 ImageGen으로 제작한 가상 장면입니다.
- 시연 프로필 사진에는 사용자가 제공한 이미지를 사용합니다.
- 화면의 사진과 타이포그래피 배치를 기획할 때 HomeCraft를 참고했습니다. [HomeCraft 디자인 레퍼런스](https://pin.it/6H5xK0CFN)
- Pretendard Variable 1.3.9 웹폰트를 수정 없이 포함합니다. Copyright (c) 2021, Kil Hyung-jin. [배포처](https://github.com/orioncactus/pretendard/tree/v1.3.9) · [SIL Open Font License 1.1](public/fonts/OFL-Pretendard.txt)
