# 비행기 연착 시간 예측 

## 0. Members
- 김혜수, 건축학부, 2014000191, 0228gptn@naver.com
- 박지우, 도시공학과, 2016058931, rudtlr510@naver.com
- 박진영, 건축공학과, 2016021658, verdad4824@naver.com
- 정희찬, 경영학부, 2018028322, 980519kevin@naver.com
- 최은비, 중어중문학과, 2018018313, cjo2128@naver.com

## 1. Introduction
우리는 < 2015 Flight Delays and Cancellations>에서 DOT 교통국이 수집한 3개의 Datasets를 이용하여 <Predicting flight delays Tutorial>을 바탕으로 비행기의 출발 지연을 예측하는 모델을 만들어보고자 합니다. 
먼저 데이터 정리 및 준비를 통해 Datasets에서 가장 많은 양의 데이터를 가진 7월의 데이터를 뽑아내고, EDA를 통해 데이터들을 시각화하여 비행 연착에 영향을 주는 요소들을 알아봅니다. 이를 바탕으로 선형회기분석 기법을 이용해서 1~3주차 데이터를 트레이닝데이터로 하고, 4주차를 테스트데이터로 하여 4주차 출발 지연을 예측하고, MSE (Mean Squared Error)를 이용하여 결과를 평가할 예정입니다.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/980519kevin/thebestdeeplearning.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
