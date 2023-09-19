              precision    recall  f1-score   support

      class1       0.85      0.92      0.88        75
      class2       0.73      0.83      0.78       206
      class3       0.60      0.43      0.50       100
      class4       0.84      0.79      0.81        75

    accuracy                           0.75       456
   macro avg       0.76      0.74      0.74       456
weighted avg       0.74      0.75      0.74       456

class4 750EA, class3 1000EA, class1 750EA로 이미지 증식결괏값으로
class3의 결과가 조금 아쉬운 점이 있음..
model4의 전체 데이터가 다른 model보다 작은편이라서 그런지 원본형태의 데이터 형식을 유지 못하고
데이터 왜곡현상이 우려되어서 class3의 f1-score가 다른 class보다 낮지만 그래도 사용은 가능한 수준으로 사려됨