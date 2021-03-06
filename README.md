# NomadCoders TodoList Competition

TodoList 컨테스트에 참가하기 위해 시작한 Vanilla Javascript 프로젝트

* [대회 공지](https://nomadcoders.co/community/thread/182)

* [대회 결과](https://nomadcoders.co/community/thread/452)

![image](https://user-images.githubusercontent.com/67461578/110208724-386c9380-7ecc-11eb-9a20-63cf4ba3c760.png)

무려 🏆**인기상**에 당첨이 되었다! ~*(치킨 감사합니다!)*~

이 프로젝트에 투표해주신 모든 분들께 이 자리를 빌려 감사의 말씀을 드린다.

---

<br />

[프로젝트 링크](https://pshtony1.github.io/noamd-todo-competition/)

<img src="https://user-images.githubusercontent.com/67461578/110208885-00b21b80-7ecd-11eb-8eb8-958cbf04ecc7.png" width="50%" /><img src="https://user-images.githubusercontent.com/67461578/110208916-1cb5bd00-7ecd-11eb-864e-4a13cfcb4cc0.png" width="50%" />

---

<br />

## 1. 스택

**Only Vanilla Javascript + Front-end**

<img src="https://img.shields.io/badge/Javascript-1f232a?style=flat-square&logo=JavaSCript&logoColor=f0db4f" height="30px" /> 

**서드 파티는 일체 사용하지 않았다.**

<br />

## 2. 기능

이하는 현재 모두 구현된 기능들이다.

**모든 데이터는 자동으로 `LocalStorage`에 저장된다.**

### 2 - 1. 유저 🙍‍♂️

* Display name 설정(최초 1회) &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#display-name-%EC%84%A4%EC%A0%95)

* 로그아웃(데이터 초기화)

### 2 - 2. 카드 📝

* 카드 생성 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%EC%B9%B4%EB%93%9C-%EC%83%9D%EC%84%B1--%ED%83%9C%EA%B7%B8-%EC%83%9D%EC%84%B1)

* 카드 삭제 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%EC%B9%B4%EB%93%9C-%EC%82%AD%EC%A0%9C)

* 카드 수정 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%EC%B9%B4%EB%93%9C-%EC%88%98%EC%A0%95)

* 카드 검색(기준: 카드 내용)

* 카드 상태변경 ( `Todo` - `Complete` ) &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%EC%B9%B4%EB%93%9C-%EC%83%81%ED%83%9C%EB%B3%80%EA%B2%BD--todo-%EC%A7%84%EC%B2%99%EB%8F%84)

* 카운트 다운(최대 24시간)

* 카드 최상단 고정 기능 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%EC%B9%B4%EB%93%9C-%EC%B5%9C%EC%83%81%EB%8B%A8-%EA%B3%A0%EC%A0%95)

### 2 - 3. 해시태그 🏷

* 각 카드에 해시태그 부여 가능(개수 제한 X) &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%EC%B9%B4%EB%93%9C-%EC%83%9D%EC%84%B1--%ED%83%9C%EA%B7%B8-%EC%83%9D%EC%84%B1)

* 해시태그 필터링 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%ED%95%B4%EC%8B%9C%ED%83%9C%EA%B7%B8-%ED%95%84%ED%84%B0%EB%A7%81)

* 태그 색 수정 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%ED%83%9C%EA%B7%B8-%EC%83%89-%EC%88%98%EC%A0%95)

* 태그 삭제 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%ED%83%9C%EA%B7%B8-%EC%82%AD%EC%A0%9C)

### 2 - 4. 프로필 😎

* 각종 메뉴

* Todo 진척도 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%EC%B9%B4%EB%93%9C-%EC%83%81%ED%83%9C%EB%B3%80%EA%B2%BD--todo-%EC%A7%84%EC%B2%99%EB%8F%84)

* 프로필 숨기기 가능 &nbsp; [미리보기](https://github.com/pshtony1/noamd-todo-competition/#%ED%94%84%EB%A1%9C%ED%95%84-%EC%88%A8%EA%B8%B0%EA%B8%B0-%EA%B8%B0%EB%8A%A5--%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4-%EB%86%92%EC%9D%B4-%EA%B3%A0%EB%A0%A4%ED%95%B4-%EC%9E%90%EB%8F%99-%EC%88%A8%EA%B8%B0%EA%B8%B0)
  * **디바이스 높이를 고려하여 자동으로 프로필이 숨겨짐(디바이스 높이 1000px 미만 시)**

### 2 - 5. 기타 🎸

* 언어 변경 지원(한국어, 영어)

<br />

## 3. 기능 미리보기

### 유저 🙍‍♂️

#### Display name 설정

![init1](https://user-images.githubusercontent.com/67461578/110209926-871d2c00-7ed2-11eb-90fc-b4554c324bce.gif)

<br />

### 카드 📝

#### 카드 생성 & 태그 생성

![create1](https://user-images.githubusercontent.com/67461578/110210022-01e64700-7ed3-11eb-924d-cada86ea56fd.gif)

#### 카드 수정

![edit1](https://user-images.githubusercontent.com/67461578/110210067-47a30f80-7ed3-11eb-9a77-f6915f41f697.gif)

#### 카드 삭제

![delete1](https://user-images.githubusercontent.com/67461578/110210124-9c468a80-7ed3-11eb-85b6-3f58fbae9be3.gif)

#### 카드 상태변경 && Todo 진척도

![statechange1](https://user-images.githubusercontent.com/67461578/110210263-2c84cf80-7ed4-11eb-9c42-306735c6958e.gif)

#### 카드 최상단 고정

![fixcard1](https://user-images.githubusercontent.com/67461578/110210375-b92f8d80-7ed4-11eb-88a9-49d6ac13d346.gif)

<br />

### 해시태그 🏷

#### 해시태그 필터링

![filter1](https://user-images.githubusercontent.com/67461578/110210617-c8630b00-7ed5-11eb-9e7c-1350cd4a9075.gif)

#### 태그 색 수정

![coloredit1](https://user-images.githubusercontent.com/67461578/110210710-44f5e980-7ed6-11eb-9383-d8416bccafab.gif)

#### 태그 삭제

![deletetag1](https://user-images.githubusercontent.com/67461578/110210728-622ab800-7ed6-11eb-8ad3-6edf2a18c45a.gif)

<br />

### 프로필 😎

#### 프로필 숨기기 기능 + 디바이스 높이 고려해 자동 숨기기

![hide1](https://user-images.githubusercontent.com/67461578/110210845-e5e4a480-7ed6-11eb-8a6d-2ccae5d242e9.gif)



