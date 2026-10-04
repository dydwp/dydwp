<div align="center">

![header](https://capsule-render.vercel.app/api?type=rect&color=0:6e6ef1,100:43cea2&height=120&text=Park%20Yong%20Je&fontSize=42&fontColor=ffffff&fontAlignY=45&desc=Backend%20Developer%20%C2%B7%20Java%20and%20Spring%20Boot&descAlignY=75&descSize=15&descColor=ffffff)

</div>

<br>

## 👋 About Me

- 🔭 백엔드 중심으로 학습하며, 데이터를 다루고 서비스로 완성하는 과정에 흥미를 느끼는 개발자입니다
- 🌱 Spring Boot 기반 웹 서비스 구축과 Python 기반 데이터 수집·분석을 함께 경험하고 있습니다
- 🚀 Docker, GitHub Actions, AWS를 활용해 만든 서비스를 실제로 배포하고 운영하는 과정까지 경험하고 있습니다

<br>

## 🛠 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,python,spring,mysql,hibernate,js,fastapi,tensorflow&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=docker,aws,githubactions,selenium,git,github,vscode,idea&theme=dark" />

</div>

<br>

## 🧩 Projects

<table>
  <tr>
    <td width="80" align="center" valign="middle"><span style="font-size: 40px;">🐾</span></td>
    <td>
      <b><a href="https://github.com/dydwp/meongjaguk">멍자국</a></b> — GPS 기반 반려동물 산책로 공유 & 동행 매칭 웹 서비스<br/>
      <sub>반려견과의 산책을 위해 현재 위치 기반 AI 코스 추천, GPS 산책 기록, 같이 걷기 동행 모집을 제공하는 4인 팀 프로젝트</sub><br/>
      <sub>👥 팀장 박용제 · 팀원 정석진, 최주영, 김환중</sub><br/><br/>
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
      <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
      <br/><br/>
      <ul>
        <li>Spring Security + OAuth2 기반 Google·Kakao·Naver 소셜 로그인 및 회원 자동 가입 구현</li>
        <li>GPS 경로 좌표를 포함한 산책 기록 저장 API와 카카오맵 경로 표시 구현</li>
        <li>추천 산책로 게시글 등록·수정·삭제, 메인 화면 개편 및 알림 기능 구현</li>
        <li>FastAPI AI 서버의 산책로 추천을 Spring 서버가 중계하는 구조로 변경</li>
        <li>Docker / docker-compose 구성, GitHub Actions CI, Actuator health check 및 AWS 배포 환경 구성</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="80" align="center" valign="middle"><span style="font-size: 40px;">🏭</span></td>
    <td>
      <b><a href="https://github.com/dydwp/melting-tank-kpi-mlops-serving">melting-tank-kpi-mlops</a></b> — 용해탱크 품질 예측 LSTM 모델 및 KPI 중심 MLOps<br/>
      <sub>용해탱크 시계열 센서 데이터로 다음 1분의 NG 발생 여부를 예측하고, 모델링(<a href="https://github.com/dydwp/melting-tank-kpi-mlops-modeling">modeling</a>)과 서빙(<a href="https://github.com/dydwp/melting-tank-kpi-mlops-serving">serving</a>)을 저장소별로 분리한 프로젝트</sub><br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      <br/><br/>
      <ul>
        <li>센서값 10개 시퀀스 기반 LSTM 모델 설계 및 F2-score 기준 임계값 선정</li>
        <li>Notebook 실험을 재현 가능한 Python 학습 파이프라인으로 모듈화하고 MLflow로 실험 추적</li>
        <li>KPI 승인 모델만 추론하는 FastAPI 서빙 API와 예측 대시보드 구현</li>
        <li>S3 · ECR · ECS Fargate · ALB를 CloudFormation으로 구성하고 GitHub Actions OIDC 기반 CI/CD 구축</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="80" align="center" valign="middle"><span style="font-size: 40px;">🌀</span></td>
    <td>
      <b><a href="https://github.com/dydwp/airflow-spark-data-collection-pipeline">airflow-spark-data-collection-pipeline</a></b> — Airflow · Spark 기반 데이터 수집 파이프라인<br/>
      <sub>Airflow로 웹 크롤링 워크플로를 관리하고, Spark로 전처리·집계한 데이터를 MySQL과 MinIO에 저장하는 Docker 기반 파이프라인</sub><br/><br/>
      <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <br/><br/>
      <ul>
        <li>DAG 기반 워크플로 오케스트레이션과 태스크 의존성 관리</li>
        <li>Spark Standalone Cluster로 중복 제거, Parquet 변환, 통계 집계 수행</li>
        <li>Raw–Interim–Silver–Gold 계층으로 데이터를 관리하고 batch_id로 데이터 계보 추적</li>
        <li>기본키 기반 MySQL Upsert로 재실행 안정성 확보</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="80" align="center" valign="middle"><span style="font-size: 40px;">☁️</span></td>
    <td>
      <b><a href="https://github.com/dydwp/data-collection-pipeline">data-collection-pipeline</a></b> — 로컬 · AWS Lambda 기반 데이터 수집 파이프라인<br/>
      <sub>웹 크롤링, 데이터 추출, 전처리, MySQL 적재를 로컬과 AWS 서버리스 환경에서 단계별로 수행하는 프로젝트</sub><br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white"/>
      <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      <br/><br/>
      <ul>
        <li>Crawling → Extract → Preprocess → Load 단계를 Lambda별로 분리하고 Step Functions로 순차 실행</li>
        <li>S3를 단계 간 저장소로 사용하고 Lambda 간에는 메타데이터만 전달</li>
        <li>AWS SAM으로 인프라를 코드로 정의하고 Secrets Manager로 Private RDS에 안전하게 적재</li>
        <li>pytest · Ruff · GitHub Actions 기반 CI 구성</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="80" align="center" valign="middle"><span style="font-size: 40px;">🏋️</span></td>
    <td>
      <b><a href="https://github.com/dydwp/easy-fit">EasyFit</a></b> — 개인 맞춤형 운동 관리 웹 서비스<br/>
      <sub>원하는 운동 부위를 한눈에 파악하기 어렵고 초보자는 운동 방법을 알기 어렵다는 문제에서 출발해, 캘린더와 메모로 운동 기록을 관리할 수 있게 만든 개인 프로젝트</sub><br/><br/>
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
      <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
      <br/><br/>
      <ul>
        <li>MuscleWiki 스타일 SVG 신체 부위 지도와 캘린더 기반 운동 기록·메모 기능 설계 및 구현</li>
        <li>정적 프론트엔드(HTML/CSS/Vanilla JS)를 Spring Boot REST API 기반으로 전환</li>
        <li>Entity → Repository → Service → Controller 계층형 아키텍처 적용</li>
        <li>Spring Security + OAuth2 기반 로그인 기능 구현</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="80" align="center" valign="middle"><span style="font-size: 40px;">🏟</span></td>
    <td>
      <b><a href="https://github.com/dydwp/sports-crawling-project">sports-crawling-project</a></b> — 서울시 체육시설 공공서비스예약 데이터 크롤링<br/>
      <sub>공공서비스예약 사이트를 Selenium으로 동적 크롤링하여 MySQL에 적재하는 데이터 수집 프로젝트</sub><br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <br/><br/>
      <ul>
        <li>API 대신 URL 기반 방식으로 동적 페이지 크롤링 로직 설계</li>
        <li>Selenium을 활용한 예약 데이터 수집 및 전처리</li>
        <li>수집한 데이터를 MySQL에 적재하는 파이프라인 구현</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="80" align="center" valign="middle"><span style="font-size: 40px;">🏫</span></td>
    <td>
      <b><a href="https://github.com/dydwp/school-zone-analysis">school-zone-analysis</a></b> — School Zone 지정 현황 데이터 분석<br/>
      <sub>전국 시·도별 School Zone(어린이보호구역) 지정 현황 데이터를 분석한 프로젝트</sub><br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
      <br/><br/>
      <ul>
        <li>전국 시·도별 어린이보호구역 지정 현황 데이터 수집 및 정제</li>
        <li>Jupyter Notebook을 활용한 지역별 현황 비교 분석</li>
      </ul>
    </td>
  </tr>
</table>
