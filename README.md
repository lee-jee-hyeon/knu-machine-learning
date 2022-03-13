# knu-machine-learning - 서울시 공공자전거(따릉이) 고장율 예측


![Kayak][logo]

[logo]: https://play-lh.googleusercontent.com/qxPKLrBi-zwgDqsYf9FtbrHuxbkT_VVS1thV6F5bDw-WJvFiD_9LvTz0VejNFtMnmnE "To go kayaking."

# 서울시 공공 자전거 (따릉이) 고장 데이터 셋 

- 최종 데이터프레임 컬럼

| columns name | mean | datatype | count | non-null | 
|---|:---:|---:|---:|---:|
| `자전거번호` | 각 자전거 고유 번호 | `object` |  **20571** |**non-null** |
| `등록일시` | 고장신고 등록날짜 | `datetime64` |  **20571** |**non-null** |
| `등록일시2` | 대여이력 등록날짜 | `object`  |  **20571** |**non-null** |
| `고장구분` | 고장상태 구분 | `object` | **20571** |**non-null** |
| `총이용시간` | 대여일 이후 고장신고 날까지의 이용시간 | `float64` | **20571** |**non-null** |
| `총이용거리` | 대여일 이후 고장신고 날까지의 이용거리 | `float64` | **20571** |**non-null** |
| `날짜차이` | 고장신고 이후 재고장까지의 일수 |`int64`  | **20571** |**non-null** |
| `고장구분별_고장횟수` | 자전거, 고장부분 별 고장 횟수 | `int64` | **20571** |**non-null** |


