---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# LOD(Level of Detail)

## 1. LOD(세부 표현식)

### 1) 정의&#x20;

* 세부 표현식 / 으로서, VLOD(View Level of Detail)라고도 한다.&#x20;

### 2) 특징&#x20;

1.  태블로는 기본적으로 나열된 숫자를 한데 모아 연산 즉, '**집계(aggregation)**'한다. \
    \
    e.g. 합계(sum), 평균(avg), 최소/최대값(min/max), 중앙값(Mdn), 분산(VAR), 표준편차(SD) 등\


    <figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>


2.  태블로의 용도는 **썰어(slicing)**보는 데에 있고, 이 표현 방식은 Business Question에 따라 다양하다.  \


    e.g. '막대 차트', '파이 차트', '버블 차트', '트리 맵'\


    <figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption><p><a href="https://vizlab.tistory.com/37">https://vizlab.tistory.com/37</a></p></figcaption></figure>
3.  태블로의  써는 방식(slicing)은 다양한데, 이를 (View) Level of Detail이라고 한다. \
    \


    <figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>
4. 차원(Dimensions)과 측정값(Measure)중 오직 차원만이 Level of Detail을 결정한다.&#x20;



