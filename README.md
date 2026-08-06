# Numpad-Triggered Smart Key Mapper

A lightweight Windows productivity utility built with **AutoHotkey (v2)**.

When **NumLock is ON**, this utility automatically rebinds the top row number keys to their primary shift symbols (`!`, `@`, `#`, etc.) and remaps `F1`–`F3` keys to essential editing shortcuts (`Copy`, `Cut`, `Paste`). When **NumLock is OFF**, all keys immediately revert to their default behavior.

> **한국어 사용자 안내:** 아래로 스크롤하시면 한국어 상세 설명을 확인하실 수 있습니다.

---

## 💡 Key Features

- **Context-Aware Mapping:** Activated **only** when `NumLock` is turned `ON`.
- **Top Row Symbol Converter:** Type symbols instantly without pressing the `Shift` key (since numbers are typed using the Numpad).
- **Productivity F-Keys:** Quick access to `Copy`, `Cut`, and `Paste` right at your fingertips (`F1`–`F3`).
- **Instant Toggle:** Switching `NumLock` `OFF` instantly restores original key functions without restarting the app.
- **Lightweight & Fast:** Runs quietly in the background with minimal resource usage.

---

## ⌨️ Key Mappings

### 1. Function Keys (`F1` – `F3`)

| Key | When NumLock is ON | When NumLock is OFF |
| :--- | :--- | :--- |
| **`F1`** | **Copy** (`Ctrl + C`) | 
| **`F2`** | **Cut** (`Ctrl + X`) | Original `F2` (e.g., Rename) |
| **`F3`** | **Paste** (`Ctrl + V`) | Original `F3` (e.g., Search) |

### 2. Top-Row Number Keys (`1` – `0`)

| Key | When NumLock is ON | When NumLock is OFF |
| :---: | :---: | :---: |
| **`1`** | **`!`** | `1` |
| **`2`** | **`@`** | `2` |
| **`3`** | **`#`** | `3` |
| **`4`** | **`$`** | `4` |
| **`5`** | **`%`** | `5` |
| **`6`** | **`^`** | `6` |
| **`7`** | **`&`** | `7` |
| **`8`** | **`*`** | `8` |
| **`9`** | **`(`** | `9` |
| **`0`** | **`)`** | `0` |

---

## 🚀 How to Use

### Option A: Running from Source (`.ahk`)
1. Download and install [AutoHotkey v2](https://www.autohotkey.com/).
2. Clone or download this repository.
3. Double-click `numberlock.ahk` to run.

### Option B: Auto-start with Windows
1. Press `Win + R`, type `shell:startup`, and press **Enter**.
2. Create a shortcut to `numberlock.ahk` inside the Startup folder.

---

## 🛡️ Note on Anti-Virus Warnings (False Positives)

Because this script intercepts low-level keyboard inputs (Keyboard Hooking) to remap keys, some Antivirus software (or Windows Defender) may flag the compiled `.exe` version as a false positive (e.g., Keylogger). 

Rest assured, **this utility is completely safe and open-source**. You can inspect the full source code directly in `numberlock.ahk`.

---
---

# 🇰🇷 한국어 설명 (Korean Guide)

AutoHotkey(v2) 기반의 **NumLock 연동 스마트 키 매핑 윈도우 유틸리티**입니다.

**NumLock이 켜져(ON) 있을 때**, 상단 숫자행 키(`1`~`0`)를 누르면 `Shift` 조합 특수문자(`!`, `@`, `#` 등)가 즉시 입력되며, `F2`~`F4` 키는 편집 단축키(`복사`, `잘라내기`, `붙여넣기`)로 작동합니다. **NumLock을 끄면(OFF)** 시스템 기본 동작으로 즉시 복원됩니다.

---

## 💡 주요 기능

- **NumLock 연동 동작:** `NumLock`이 켜진 상태에서만 매핑이 활성화됩니다.
- **상단 숫자행 특수문자 변환:** 숫자 패드(Numpad)로 숫자를 입력하므로, 상단 숫자키는 `Shift` 키 없이 바로 특수문자를 입력하도록 변환합니다.
- **F키 생산성 향상:** 손이 닿기 쉬운 `F1`~`F3` 키를 `복사`, `잘라내기`, `붙여넣기` 단축키로 활용합니다.
- **실시간 토글:** 프로그램 재시작 없이 `NumLock` 온/오프만으로 원래 키 기능과 매핑 기능을 오갈 수 있습니다.
- **초경량 백그라운드 실행:** 시스템 리소스를 거의 차지하지 않고 시계 옆 트레이에서 조용히 동작합니다.

---

## ⌨️ 키 매핑표

### 1. 기능 키 (`F1` – `F3`)

| 키 | NumLock ON 상태 | NumLock OFF 상태 |
| :--- | :--- | :--- |
| **`F1`** | **복사** (`Ctrl + C`) |
| **`F2`** | **잘라내기** (`Ctrl + X`) | 원래 `F2`(예: 이름 바꾸기) |
| **`F3`** | **붙여넣기** (`Ctrl + V`) | 원래 `F3` (예: 찾기/검색) |

### 2. 상단 숫자 키 (`1` – `0`)

| 키 | NumLock ON 상태 | NumLock OFF 상태 |
| :---: | :---: | :---: |
| **`1`** | **`!`** | `1` |
| **`2`** | **`@`** | `2` |
| **`3`** | **`#`** | `3` |
| **`4`** | **`$`** | `4` |
| **`5`** | **`%`** | `5` |
| **`6`** | **`^`** | `6` |
| **`7`** | **`&`** | `7` |
| **`8`** | **`*`** | `8` |
| **`9`** | **`(`** | `9` |
| **`0`** | **`)`** | `0` |

---

## 🚀 사용 방법

### 소스 코드 파일(`.ahk`)로 실행하기
1. [AutoHotkey v2](https://www.autohotkey.com/) 공식 홈페이지에서 프로그램 설치.
2. 이 저장소의 `numberlock.ahk` 파일 다운로드.
3. `numberlock.ahk` 파일을 더블 클릭하여 실행.

### 윈도우 부팅 시 자동 실행 설정
1. 단축키 `Win + R`을 누르고 `shell:startup` 입력 후 엔터.
2. 열린 시작프로그램 폴더 안에 `numberlock.ahk` 파일의 **바로 가기**를 생성.

---

## 🛡️ 백신 오탐지(False Positive) 관련 안내

키보드 신호를 중간에서 가로채는 방식(Keyboard Hooking) 특성상, 일부 백신 프로그램이나 Windows Defender에서 실행 파일(.exe)을 키로거 형태의 위험 요소로 잘못 감지(오탐지)할 수 있습니다.

본 유틸리티는 **100% 안전한 오픈소스 프로젝트**입니다. 모든 동작 로직은 `numberlock.ahk` 소스 코드로 직접 검증하실 수 있습니다.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

MIT License

Copyright (c) [2026] [ereschris@gmail.com]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom Supplemental Software
is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
