# 🚗 C Language

## 📅 학습 페이지 바로가기

- [DAY 01 - C Programming Lab](https://khj930629.github.io/hyundai-hint-mobility-sw-academy/hint-c-language/hint_c_programming_lab.html)
- [DAY 02 - C Programming Lab 02](https://khj930629.github.io/hyundai-hint-mobility-sw-academy/hint-c-language/hint_c_programming_lab_02.html)

---

## 🚘 Introduction

현대 HINT 모빌리티 SW 아카데미에서 학습하는 C언어의 기초 및 응용 내용을 정리하는 공간입니다.

C언어의 기본 문법부터 메모리 구조, 포인터, 구조체 등 핵심 개념을 학습하고, 실습 코드를 직접 작성하며 프로그래밍 역량을 향상시키는 것을 목표로 합니다.

또한 학습한 내용을 자동차 임베디드 SW 및 ECU 개발과 연계하여 이해하고, 실제 모빌리티 소프트웨어 개발에 필요한 기초 역량을 쌓고자 합니다.

## 🎯 Learning Objectives

- C언어 기본 문법 및 프로그래밍 구조 이해
- 변수, 자료형, 연산자 등 핵심 개념 학습
- 조건문과 반복문을 활용한 프로그램 구현
- 배열, 포인터, 함수 및 구조체 활용
- 문자열 처리 및 메모리 관리 원리 이해
- 자동차 임베디드 SW 및 ECU 개발과의 연관성 파악

## 📚 Learning Contents

| No. | Category | Learning Contents |
|---|---|---|
| 01 | C Basics | C언어 기초 및 프로그램 구조 |
| 02 | Variables & Data Types | 변수, 상수 및 자료형 |
| 03 | Input & Output | `printf()`, `scanf()` |
| 04 | Operators | 산술, 대입, 관계, 논리 및 비트 연산자 |
| 05 | Control Flow | 조건문 및 분기문 |
| 06 | Loops | 반복문 및 반복 제어 |
| 07 | Arrays | 배열 및 다차원 배열 |
| 08 | Strings | 문자열 처리 및 문자열 함수 |
| 09 | Functions | 함수 정의, 호출 및 매개변수 |
| 10 | Pointers | 포인터 및 메모리 주소 |
| 11 | Structures | 구조체 및 사용자 정의 자료형 |
| 12 | Memory Management | 메모리 관리 |
| 13 | Embedded C | 임베디드 C 기초 및 응용 |
| 14 | Projects | 실습 및 응용 프로젝트 |

---

## 📅 Daily Learning Records

### DAY 01 - C Programming Basics

**학습 주제: C언어 기초 및 프로그램 구조**

- 프로그래밍 언어의 종류와 특징
- 기계어, 어셈블리어 및 고급언어 이해
- 컴파일러와 Visual Studio 개발 환경
- C언어 프로그램의 작성 및 실행 과정
- `#include` 전처리기 지시어
- `main()` 함수와 프로그램의 기본 구조
- 주석 및 들여쓰기 작성 방법
- 변수와 자료형의 기초
- `printf()`를 이용한 출력
- `scanf()`를 이용한 입력

**주요 실습**

| 실습 | 학습 내용 |
|---|---|
| Hello World | C언어 프로그램 작성 및 실행 |
| 덧셈 프로그램 | 변수와 산술 연산 활용 |
| 데이터 입력 및 출력 | `scanf()`, `printf()` 활용 |
| 기본 문법 실습 | 전처리기, 함수, 주석 및 코드 구조 |

### DAY 02 - C Programming Lab 02

**학습 주제: C언어 응용 문법 및 데이터 처리**

- 변수와 자료형을 활용한 데이터 처리
- 연산자 및 연산식 활용
- 조건문과 반복문을 활용한 프로그램 구현
- 배열을 이용한 데이터 관리
- 함수 정의 및 함수 호출
- 함수 매개변수와 반환값 이해
- 문자열 및 문자열 처리 함수
- `strtok()`을 활용한 문자열 토큰 분리
- `time()` 등 시간 관련 함수 활용 및 오류 확인

**주요 실습**

| 실습 | 학습 내용 |
|---|---|
| 학생 성적 관리 프로그램 | 학생별 국어, 영어, 수학 점수 입력 |
| 총점 및 평균 계산 | 배열과 반복문을 활용한 데이터 처리 |
| 성적 등급 판별 | 조건문을 활용한 A/B/C/D 등급 분류 |
| 함수 활용 | 점수 계산 및 등급 판별 기능 분리 |
| 문자열 토큰 분리 | `strtok()`을 활용한 문자열 분리 |
| 오류 해결 | 함수 사용 시 발생하는 오류 및 컴파일 경고 확인 |

**실습 결과 예시 - 학생 성적 관리 프로그램**

| 학생 | 총점 | 평균 | 등급 |
|---|---:|---:|---|
| 1번 | 240 | 80.00 | B |
| 2번 | 285 | 95.00 | A |
| 3번 | 195 | 65.00 | D |

**오류 분석 및 해결**

- 시간 관련 함수 사용 과정에서 발생한 오류 원인 확인
- `strtok()` 사용 시 Visual Studio의 C4996 보안 관련 경고 확인
- `strtok()`과 `strtok_s()`의 차이 및 사용 방법 학습
- 함수 사용 시 반환값과 매개변수의 역할 확인

---

## 🔧 Practice & Implementation

학습한 이론을 바탕으로 직접 코드를 작성하고 실행 결과를 확인합니다.

- 실습 코드 작성 및 실행
- 코드 분석 및 주석 정리
- 오류 발생 원인 및 해결 과정 기록
- 코드 개선 및 리팩토링
- 학습 내용을 활용한 응용 프로그램 구현
- 실습 결과 및 테스트 과정 기록

## 🚘 Automotive Software Connection

C언어 학습 내용을 자동차 임베디드 소프트웨어 개발 관점에서 확장합니다.

| C Language | Automotive SW Application |
|---|---|
| Variables & Data Types | 센서 데이터 및 상태값 관리 |
| Input & Output | ECU 데이터 입력 및 출력 |
| Conditional Statements | ECU 입력값 정상·비정상 판별 |
| Loops | 센서 데이터 반복 처리 |
| Arrays | 다중 센서 데이터 관리 |
| Strings | 진단 메시지 및 오류 코드 처리 |
| Functions | 기능별 소프트웨어 모듈 구현 |
| Pointers | 메모리 및 데이터 주소 관리 |
| Structures | 센서 및 ECU 데이터 구조화 |
| Bitwise Operators | 레지스터 및 상태 플래그 제어 |

## 📁 Repository Structure

```text
C_Language/
├── README.md
├── 01_Basics/
├── 02_Operators/
├── 03_Control_Flow/
├── 04_Loops/
├── 05_Arrays/
├── 06_Strings/
├── 07_Functions/
├── 08_Pointers/
├── 09_Structures/
├── 10_Memory/
├── 11_Embedded_C/
└── Projects/
```

## 📈 Learning Progress

- [x] C언어 기초 및 프로그램 구조
- [x] 변수와 자료형 기초
- [x] 기본 입출력 함수
- [x] 연산자 기초
- [x] 조건문 및 반복문 기초
- [x] 배열을 활용한 데이터 처리 기초
- [x] 함수 활용 기초
- [x] 문자열 처리 기초
- [ ] 포인터
- [ ] 구조체
- [ ] 메모리 관리
- [ ] 임베디드 C
- [ ] 응용 프로젝트

## 📝 Learning Record

각 학습 주제는 다음 기준으로 기록합니다.

1. 학습 목표 및 핵심 이론
2. 주요 문법 및 개념 정리
3. 실습 코드 및 실행 결과
4. 오류 및 해결 과정
5. 자동차 임베디드 SW 연계 내용
6. 학습 후기 및 추가 학습 사항

---

**Goal:** C언어의 기초를 탄탄하게 다지고, 자동차 임베디드 SW 및 ECU 개발에 필요한 프로그래밍 역량을 갖추는 것을 목표로 합니다.