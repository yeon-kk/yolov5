# yolov5

C:\windows_v1.8.1\data
해당 경로에서 predefined_classes 파일 수정해주기.

관리자 권한으로 labelImg.exe 실행 후 반드시 YOLO로 바꿔주기!!  
YOLO로 바꾸어 주어야함! ..  

데이터 수집할때는 파일명을 카테고리별로 지정해주는게 편한데, 같은 카테고리폴더에 다 넣어놓은 뒤에 파이썬 코딩으로 '파일명 + 인덱스(enumerate)' 해주면 YOLO로 라벨링 작업할 때 편하다.  

라벨링 할 때 정말 중요한건 어느 부분까지 인식할지를 정하는 것.  
예를들어 치킨을 한다면 한 조각만 할지, 한 접시에 있는것을 전부할지 . 내가 분석하는것에 맞게 영역정해야 한다.  
