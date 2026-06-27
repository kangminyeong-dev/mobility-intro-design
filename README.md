# Mobility Intro Design

모빌리티 입문설계 과목에서 진행한 LIMO 기반 자율주행 과제와 프로젝트를 정리한 저장소입니다.

카메라 영상 처리와 LiDAR 데이터를 활용해 차선 인식, 횡단보도 감지, 장애물 정지, 통합 주행 제어를 구현했습니다. 원본 제출물 중 보고서류와 압축 파일은 제외하고, 공개용으로 보기 좋은 코드, 파라미터, 시각화 자료 중심으로 구성했습니다.

## Project Structure

```text
assignments/
  crosswalk/   횡단보도 인식 과제
  e-stop/      장애물 정지 과제

midterm/       중간 프로젝트: 차선 인식 및 주행 제어
final/         기말 프로젝트: 차선, 횡단보도, LiDAR 정지, 주행 제어 통합

visualization/ 과제 및 프로젝트 시연 영상
```

## Contents

| Category | Description | Main Files |
| --- | --- | --- |
| Crosswalk Assignment | 횡단보도 인식 과제 | `assignments/crosswalk/code/` |
| E-Stop Assignment | 장애물 감지 및 정지 과제 | `assignments/e-stop/`, `visualization/02_e_stop.mp4` |
| Midterm Project | 차선 인식 기반 주행 제어 | `midterm/code/`, `midterm/params/` |
| Final Project | 차선, 횡단보도, LiDAR 정지 통합 주행 | `final/code/`, `final/params/` |

## Visualizations

### 1. Crosswalk Detection

[Watch video](visualization/01_crosswalk_detection.mp4)

### 2. E-Stop

[Watch video](visualization/02_e_stop.mp4)

### 3. Midterm Project

[Watch video](visualization/03_midterm_project.mp4)

### 4. Final Project

[Watch video](visualization/04_final_project.mp4)


## Tech Stack

- Python
- ROS
- OpenCV
- LiDAR
- WeGo LIMO Pro
