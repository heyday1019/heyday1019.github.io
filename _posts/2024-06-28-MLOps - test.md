## BEST  SELLER 문제

- 미국 고객의 Retention Rate 가 제일 높음 확인
- 미국에 집중 
- 미국의 TOP5 차량 모델 추출을 부탁
- 차량모델별로 매출이 가장 잘 나온 것 Top5
- 차량모델별로 매출액 구하기

```sql
SELECT * 
FROM orders A
LEFT JOIN customers B
ON A.customerNumber = B.customerNumber
LEFT JOIN orderDetails C
ON A.orderNumber = C.orderNumber
LEFT JOIN products D
ON C.productCode = D.productCode
-- WHERE B.country = 'USA'
;
```

## WHERE B.country = 'USA'



