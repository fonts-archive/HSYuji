# HS유지체

[배포처 바로가기](https://blog.naver.com/hp0/221803810393)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `HSYuji`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/HSYuji.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/HSYuji.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'HSYuji';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/HSYuji.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/HSYuji.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/HSYuji.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/HSYuji.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/subsets/HSYuji-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HSYuji/subsets/HSYuji-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "HSYuji", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
- 개인용, 상업용 전면 무료 사용 가능 
개인 및 기업 사용자를 포함한 모든 사용자에게 
무료로 제공되며 자유롭게 수정하고 재배포하실 수 있습니다. 
단, 글꼴 자체를 유료로 판매하는 것은 금지합니다. 
 
사용범위: 
문서제작(비영리 교재 시험지, 무료배포 공익 홍보문서, 광고 등 마케팅용 배포문서, 단체 내부 문서, 사내 배포용 프리젠테이션, 영리 목적의 교재) 
서식(증서, 원서, 신고서, 무료배포공문서식, 마케팅용 배포 문서, 단체 내부 문서및 서식) 
배포용(브로슈어, 포스터, 자료작성, 보고서, 리포터, 뉴스레터, 벽면장식, 서적) 
잡지/신문(일반잡지, 전문지, 중앙지(일간,스포츠,시사지), 대학지, 학술지, 학회지, 사보, 지방지, 무가지, 대학신문) 
판매용 인쇄/출판물(제품포장패키지, 포장지, 티켓(영화, 연극, 공연, 스포츠), CD/DVD 커버, 자켓, 문구, 엽서, 카드) 
인쇄출판(브로슈어, 소식지, 카달로그, 팜플렛, 리플렛, 현수막, 쿠폰, 명함, 전단지, 매장 내 POP물, 봉투, 메뉴판, 사용설명서, 연하장, 초대장, 카드, 엽서, 자료집, 사보, 간행물, 단행본) 
도서류(참고서, 학습지, 교과서, 백과사전, 잡지, 만화책, 신문기사) 
웹사이트(이메일, 웹툰, 웹페이지 이미지 제작, 이미지배너, 배너광고) 
영상물(영상 광고(CF, 극장, 가상광고, 온라인 등), 영화 자막(예고편, 본편, 오프닝 엔딩 등), 공중파 및 케이블 자막, 일반 동영상) 
모바일 APP(각종 스마트폰 어플리케이션 적용 (UI디자인, 임베딩) 
2차 제작물(직접 판매 목적의 이미지 제작(PT템플릿, 콘텐츠 상품, 이모티콘 등), 폰트 형태를 직접적으로 이용한 상품 제작(의류, 머그컵, 물병, 수건, 에코백, 네임스티커 등) 
e-Learning(교육용 온라인 동영상 강좌, 플래시 강좌 등) 
e-Book(도서, 문서, 잡지 등을 e-Book 형식으로 제작 및 변환하여 온라인상에 배포 및 게시) 
CI, BI(사명, 로고, 마크, 슬로건, 캐치프레이즈 등, 브랜드명, 상품명, 각종 패키지 디자인 등) 
옥내외광고물(일단 단독간판, 옥내외 간판, 옥상간판, 선전탑, 전기 이용 간판, 공공시설물 이용 광고물, 교통시설 이용 광고물, 교통수단 이용 광고물) 
임베딩(각종 디바이스, 서버, 프로그램, 게임 등에 폰트파일 탑재) 
 
상기 기재된 범위 내에서 사용할 경우 청구되는 라이센스 비용은 없으며 사용 범위에 대한 문의가 있을 경우 메일(hp0@naver.com) 부탁드립니다. 
무단으로 폰트를 유료로 판매하는 행위는 저작권법, 계약법 및 기타 해당법률에 의해 민형사상의 책임이 있습니다.
```
