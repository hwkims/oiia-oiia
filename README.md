# oiia-oiia
oiia oiia oiia oiia
![image](https://github.com/user-attachments/assets/8af7178c-75ac-4b22-9105-771b4441267e)
구글 제미나이.
3d 모델 생성 ai 등 사용
![image](https://github.com/user-attachments/assets/3ce1f1fb-33d6-4885-99da-393dd5fd4b44)
![image](https://github.com/user-attachments/assets/ce95c9a0-aff1-4507-92de-aa5b50608189)
![image](https://github.com/user-attachments/assets/ff51b923-954b-4655-af67-2f538443b387)
![image](https://github.com/user-attachments/assets/95cb34f6-d8cc-4807-b82d-4f50c9c552bd)
![image](https://github.com/user-attachments/assets/b1a732ca-b756-42e2-812e-9ab386ff8187)
![image](https://github.com/user-attachments/assets/f6f88839-39b2-462f-8785-52a9b1cab32e)
![image](https://github.com/user-attachments/assets/84e4cb99-b1ac-4559-922c-6e722a5f7002)
![image](https://github.com/user-attachments/assets/d9cf4eaa-807f-415a-8470-1efcead49f3a)
![image](https://github.com/user-attachments/assets/e0c6f137-3bdd-4af6-8827-7e5fee868186)
![image](https://github.com/user-attachments/assets/8a8a65ba-f1a7-4979-bdc4-fa54432b5211)
![image](https://github.com/user-attachments/assets/74c8f9bb-5e9f-4121-88c2-8fa6481382dd)
![image](https://github.com/user-attachments/assets/d3387595-4347-435e-baad-1d2392bd6f8f)
![image](https://github.com/user-attachments/assets/9dc4f739-a91b-4cf1-8f23-fbd90f0caee8)
![image](https://github.com/user-attachments/assets/e0490147-c67d-44ad-b97e-e5f4eba6c29a)
# 3D Model & Audio Player

이 프로젝트는 Three.js를 사용해 GLB 형식의 3D 모델을 웹에서 렌더링하고, MP3 오디오 파일을 재생할 수 있는 간단한 웹 애플리케이션입니다. 마우스/터치로 3D 모델을 회전하거나 자동 회전 기능을 사용할 수 있으며, 모바일과 데스크톱 모두에서 반응형으로 동작합니다.

## 데모
(여기에 배포된 링크나 스크린샷을 추가하세요)

## 기능
- **3D 모델 렌더링**: `oiia-oiia.glb` 파일을 로드해 3D로 표시.
- **모델 회전**: 마우스 드래그 또는 터치로 수동 회전 가능.
- **자동 회전**: 버튼으로 자동 회전 토글 가능.
- **오디오 재생**: `oiia-oiia-sound.mp3` 파일을 HTML5 오디오 플레이어로 재생.
- **반응형 디자인**: 모바일과 데스크톱에서 모두 최적화.

## 설치 방법

1. 이 저장소를 클론합니다:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
프로젝트 디렉토리로 이동합니다:
bash

Collapse

Wrap

Copy
cd your-repo-name
oiia-oiia.glb와 oiia-oiia-sound.mp3 파일을 프로젝트 루트 디렉토리에 추가합니다.
사용 방법
로컬 서버를 실행합니다 (브라우저 보안 정책 때문에 필요):
bash

Collapse

Wrap

Copy
python -m http.server 8000
브라우저에서 http://localhost:8000에 접속합니다.
3D 모델을 드래그하거나 "자동 회전" 버튼을 클릭해 조작하고, 오디오 플레이어로 음악을 재생하세요.
기술 스택
HTML/CSS/JavaScript: 기본 웹 구조 및 스타일링.
Three.js: 3D 모델 렌더링.
GLTFLoader: GLB 파일 로드.
HTML5 Audio: MP3 재생.
의존성
인터넷 연결이 필요합니다 (Three.js와 GLTFLoader를 CDN에서 로드).
로컬 테스트 시 로컬 서버 실행 필수.
문제 해결
모델/오디오가 로드되지 않음: 파일 경로(oiia-oiia.glb, oiia-oiia-sound.mp3)가 정확한지 확인하세요.
CORS 오류: 로컬 파일을 직접 브라우저에서 열지 말고, 로컬 서버를 사용하세요.
기여
버그 리포트나 개선 제안은 이슈에 남겨주세요. 풀 리퀘스트도 환영합니다!

라이선스
이 프로젝트는 MIT 라이선스에 따라 배포됩니다.

Made with ❤️
