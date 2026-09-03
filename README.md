# osu!mania Skin Editor

Python 기반의 osu!mania 스킨 편집 프로그램입니다.  
GUI에서 skin.ini와 스킨 이미지를 편집하고, 변경사항을 미리보기로 확인할 수 있습니다.

⚠️ **Beta** 현재 개발 중인 베타 버전입니다. 일부 기능에 버그가 있을 수 있습니다.

---

## ✨ 주요 기능

* skin.ini 불러오기 / 저장
* 실시간 스킨 미리보기
* Key 개수 및 Column 설정
* Note / Key 이미지 변경
* Long Note Head / Body / Tail 설정
* 판정선 / 점수 / 콤보 위치 설정
* Gameplay 설정
* LightingN / LightingL 설정
* Note / Key 색상 설정
* Assets 이미지 관리
* Undo / Redo

---

## 🚀 설치 및 실행

### Windows

1. **Python 설치**
   * Python 공식 홈페이지에서 Python을 설치합니다.
   * 설치할 때 **Add python.exe to PATH**를 반드시 체크해주세요.
   * 설치 후 CMD에서 확인합니다.
     ```bash
     python --version
     ```
2. **pip 확인**
   ```bash
   python -m pip --version



pip가 없다면:

```bash
python -m ensurepip --upgrade

```

3. **프로그램 설치**
* 프로그램 ZIP을 다운로드하고 압축을 풉니다.
* 프로그램 폴더에서 터미널을 열고:
```bash
python -m pip install -r requirements.txt

```




4. **실행**
```bash
python run.py

```



---

### macOS

1. **Python 설치**
* Python 공식 홈페이지에서 Python을 설치합니다.
* 터미널에서 확인:
```bash
python3 --version

```




2. **pip 확인**
```bash
python3 -m pip --version

```


pip가 없다면:
```bash
python3 -m ensurepip --upgrade

```


3. **프로그램 설치**
* ZIP을 다운로드하고 압축을 풉니다.
* 터미널에서 프로그램 폴더로 이동한 뒤:
```bash
python3 -m pip install -r requirements.txt

```




4. **실행**
```bash
python3 run.py

```



---

## 🖼️ Assets

프로그램의 `assets/` 폴더에 사용할 이미지를 넣을 수 있습니다.

지원 형식:

* PNG
* JPG / JPEG
* GIF
* BMP
* WEBP

에디터의 Assets 메뉴 또는 파일 선택기를 통해 이미지를 적용할 수 있습니다.

---

## 🎹 Long Note

Long Note는 다음 이미지를 각각 설정할 수 있습니다.

| 항목 | 설명 |
| --- | --- |
| **Head** | LN 시작 부분 |
| **Body** | LN 본체 |
| **Tail** | LN 끝 부분 |

---

## 🐛 버그 제보

버그를 발견했다면 GitHub의 Issues에 제보해주세요.

가능하면 다음 내용을 함께 적어주세요.

* 사용 중인 OS
* Python 버전
* 프로그램 버전
* 발생한 문제
* 재현 방법
* 오류 메시지 또는 스크린샷

**예시:**

> **문제:**
> LightingN 이미지가 적용되지 않습니다.
> **재현 방법:**
> 1. Lighting 메뉴를 엽니다.
> 2. LightingN을 변경합니다.
> 3. 스킨을 저장합니다.
> 4. 다시 불러옵니다.
> 
> 
> **결과:**
> 기존 이미지가 그대로 표시됩니다.

---

## ⚠️ 현재 알려진 문제

현재 베타 버전으로 다음 문제가 발생할 수 있습니다.

* 일부 기능이 완전히 구현되지 않음
* 일부 Assets 적용 문제
* LightingN / LightingL 관련 문제
* 일부 skin.ini와의 호환성 문제
* 이미지 크기 및 위치가 실제 osu!와 다를 수 있음

---

## 🗺️ Roadmap

* ☐ UI 전체 한글화
* ☐ 메뉴 및 기능 정리
* ☐ Assets 적용 안정화
* ☐ Lighting 완전 지원
* ☐ Preview 정확도 개선
* ☐ skin.ini 호환성 개선
* ☐ Windows .exe 배포
* ☐ macOS .app 배포
* ☐ 정식 Release

---

## 📁 프로젝트 구조

```text
mania_skin_editor/
├── app/
├── assets/
├── tests/
├── run.py
├── requirements.txt
└── README.md

```

---

## 📄 License

현재 별도의 라이선스가 지정되지 않았습니다.

---

## 🙏 Credits

* osu!
* osu!mania
* osu! Skinning Community
* PySide6

```

```
