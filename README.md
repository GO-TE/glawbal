# Glawbal worker
> 전세계 어디에서나 일하고 싶은 당신을 위한, 글로-발 워커!

<img src="docs/thumbnail.jpg" width=200/>

* 전세계 외국인 근로자를 위한 RAG 기반 AI 법률 탐색 서비스
* RAG-based AI legal recommendation service for foreign workers around the world

## 1. Introduction
* 이 Repository는 KT AIVLE SCHOOL 5기 AI트랙 19조의 빅프로젝트 코드를 포함하고 있습니다.
* FE는 React.js 기반으로 작성되었습니다.
* BE는 django 기반으로 작성되었습니다.



<img src="docs/preview-home.png" width=40%/> <img src="docs/preview-login.png" width=40%/>
<img src="docs/preview-faq.png" width=40%/> <img src="docs/preview-community.png" width=40%/>

### AX
<img src="docs/preview-chat1.png" width=30%/> <img src="docs/preview-chat2.png" width=30%/> <img src="docs/preview-ocr.png" width=30%/>

### Service Flow
![service_flow.png](..%2Fdocs%2Fservice_flow.png)

### ERD
![erd.png](..%2Fdocs%2Ferd.png)


## 2. How to use?

### FE
1. **Node.js 설치**
    * 이 레포는 React.js framework를 사용하였으며, Node.js 설치가 선행되어야 실행할 수 있습니다.
2. **터미널에서 `npm start` 실행**
    * 해당 Repository를 Clone 한 후, 터미널에서 해당 명령어를 실행하면 현재 진행된 프로젝트 결과물을 로컬에서 확인할 수 있습니다.

### BE
1. **Django 설치**
   * 이 레포는 Django Framework를 사용하였으며, python이 설치가 선행되어야 실행할 수 있습니다.
2. **mysql 설치**
   * DB로 mysql이 설치되어 있어야 합니다.`8.0.37`버전을 사용합니다.
3. **터미널에서 `python manage.py runserver` 실행**
   * 실제 프로젝트는 `gunicorn`과 `nginx`를 사용했습니다. 로컬에서 실행할 경우 현재 진행된 프로젝트 결과물을 로컬에서 확인할 수 있습니다. 

### 공통
1. **Package**
   * 각 프레임워크에 설치된 패키지는 최하단 Appendix의 '설치한 패키지 목록'을 참고해주세요.


## Appendix
1. **FE 설치한 패키지 목록**
    ```
    big-project-fe@0.1.0
    ├── @emotion/react@11.11.4
    ├── @emotion/styled@11.11.5
    ├── @fortawesome/fontawesome-svg-core@6.5.2
    ├── @fortawesome/free-brands-svg-icons@6.5.2
    ├── @fortawesome/free-regular-svg-icons@6.5.2
    ├── @fortawesome/free-solid-svg-icons@6.5.2
    ├── @fortawesome/react-fontawesome@0.2.2
    ├── @mui/icons-material@5.15.21
    ├── @mui/material@5.15.21
    ├── @testing-library/jest-dom@5.17.0
    ├── @testing-library/react@13.4.0
    ├── @testing-library/user-event@13.5.0
    ├── material-icons@1.13.12
    ├── react-dom@18.3.1
    ├── react-router-dom@6.24.0
    ├── react-scripts@5.0.1
    ├── react-textarea-autosize@8.5.3
    ├── react@18.3.1
    ├── sass@1.77.6
    ├── scss@0.2.4
    └── web-vitals@2.1.4
    ```

2. **BE 설치한 패키지 목록**
   ```
   pip install
   openai
   langchain
   django
   djangorestframework
   chromadb
   langchain_community
   langchain-openai
   requests
   deep-translator
   pytest
   Pillow
   opencv-python-headless
   django-cors-header
   django-cron
   django-redis
   mysqlclient
   mysql-connector-python
   scikit-learn
   faiss-cpu
   djangorestframework-simplejwt
   ```
   `pip install -r requirements.txt`로 설치가 가능합니다.