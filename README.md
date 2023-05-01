# URDF Example with ROS2


이 문서에는 URDF 파일의 예와 이를 실행하기 위한 실행 스크립트가 포함되어 있습니다. (ROS 2)
이것은 URDF 파일 생성에 대한 튜토리얼의 일부이며 아래 링크에서 확인할 수 있습니다:



유튜브:
[![예를 들어 동영상 참조](https://img.youtube.com/vi/CwdbsvcpOHM/0.jpg) )(https://youtu.be/CwdbsvcpOHM) )

블로그 게시물:
[http://culatedrobotics.xyz/ready-for-ros-7-urdf/](http://culatedrobotics.xyz/ready-for-ros-7-urdf/)




## 실행 방법
1. 콜콘으로 패키지를 만듭니다.
2. robot_state_launch 파일을 ros2 launch urdf_launch rsp.launch.py 로 실행합니다.
3. 'ros2 run joint_state_publisher_gui joint_state_publisher_gui'와 함께 'joint_state_publisher_gui'를 실행합니다. 아직 설치하지 않은 경우 설치해야 할 수도 있습니다.
4. 'rviz2'로 RViz 출시

비디오에 표시된 RViz 디스플레이를 복제하려면 다음과 같이 하십시오
- 고정 프레임을 "world"로 설정합니다
- 주제를 '/robot_description'으로 설정하고 알파를 0.8로 설정한 'Robot Model' 디스플레이를 추가합니다
- 이름이 활성화된 'TF' 표시를 추가합니다.
