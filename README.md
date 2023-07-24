# ✍️ JAVASCRIPT : SEARCH EFFECT

![search01](https://github.com/YeoDaSeul4355/SearchEffect/assets/125419623/e217ab1a-d83d-44e8-81e9-c95875198a11)

<br><br>

> View Site : https://yeodaseul4355.github.io/web2023/javascirpt/search/searchEffect01.html

<br><br>

## 👋 소개
웹페이지는 사용자들이 원하는 키워드로 빠르고 쉽게 검색할 수 있는 CSS 속성 검색 이펙트를 제공합니다. 키워드를 입력하면 입력한 내용과 일치하는 검색 결과를 즉시 확인할 수 있습니다.
이 프로젝트를 통해 javascript 메서드를 학습하였습니다.

<br><br>

## 🔧 사용 스택과 메서드
* HTML: HTML 언어를 사용하여 웹 페이지의 구조와 콘텐츠를 정의합니다.
* CSS: CSS(Cascading Style Sheets)를 사용하여 웹 페이지의 스타일을 지정합니다.
* javascript :
  * document.querySelector(): HTML 요소를 선택하는 메서드입니다.
  * querySelectorAll(): 주어진 CSS 선택자와 일치하는 모든 HTML 요소를 선택하는 메서드입니다. 여기서는 .search__list li를 선택하여 모든 목록 리스트 요소들을 가져옵니다.
  * event.target.value: 이벤트 객체를 통해 사용자가 입력한 검색어를 가져옵니다.
  * addEventListener(): 이벤트를 등록하여 해당 이벤트가 발생했을 때 특정 동작을 실행하는 메서드입니다. 여기서는 searchBox 요소에 "keyup" 이벤트를 등록하고, 사용자가 키를 누를 때마다 입력값을 가져와서 검색 기능을 실행합니다.
  * classList.add(): HTML 요소의 클래스 목록에 새로운 클래스를 추가하는 메서드입니다. 여기서는 검색 결과가 없을 때, 해당 요소에 "hide" 클래스를 추가하여 화면에서 해당 요소를 숨깁니다.
  * classList.remove(): HTML 요소의 클래스 목록에서 클래스를 제거하는 메서드입니다. 여기서는 검색 결과가 있을 때, 해당 요소에서 "hide" 클래스를 제거하여 숨겨진 요소를 다시 화면에 표시합니다.
  * dataset: HTML 요소의 data-* 속성들을 가져오거나 설정하는 속성입니다. 여기서는 dataset.name을 사용하여 data-name 속성에 접근합니다. el.dataset.name은 el.getAttribute("data-name")과 동일한 결과를 제공합니다.

<br><br>

## 📚 구현 내역

*서치 기능 구현

<br><br>
## 📸 상세
![search02](https://github.com/YeoDaSeul4355/SearchEffect/assets/125419623/0e3e9bad-1a4a-4630-9fee-15de2956e57b)
