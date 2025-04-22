# Coach Connect
직접 운동 목적, 운동 강도, 운동 횟수를 설정하여 트레이너에게 제공하여 개인 트레이너를 매칭해주는 애플리케이션

## 프로젝트 배경
최근 운동을 취미로 하는 사람들이 증가하였는데, 정작 자신 운동 스타일과 맞는 트레이너를 찾기는 쉽지 않은 상황임

그래서 CoachConnect 앱을 통해 자신의 목표와 부합하는 트레이너와 연결할 수 있도록 하고자 함


## 화면 구성 및 기능
<details>
  <summary><b>스플래시 화면</b></summary>
  로그인창으로 넘어가기 전 잠깐 나오는 시작화면
  <br/><br/>
<img width="274" alt="image" src="https://github.com/user-attachments/assets/4812a61a-5a9c-46a3-81e0-6abca30c4d40" />
</details>
<details>
  <summary><b>로그인 화면</b></summary>
    <img width="273" alt="image" src="https://github.com/user-attachments/assets/e5c14e3d-2156-4107-b144-d16eed59678f" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>회원가입을 했다면 이메일과 비밀번호를 입력 → 메인화면창(예약내역창)으로 넘어감</li>   
      <li>잘못된 로그인 정보 기입 시 “로그인 정보가 일치하지 않습니다.”라는 문구가 등장</li>
      <li>아직 가입을 안 했다면 회원가입 텍스트 누르기</li>    
    </ul>
  </div>
  </details>
<details>
  <summary><b>회원가입 화면</b></summary>
  <img width="285" alt="image" src="https://github.com/user-attachments/assets/c39dda86-f00a-40aa-ba2b-85bb1b6344d6" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>이메일과 비밀번호를 입력 후  NEXT 버튼 누르면 “회원가입이 완료되었습니다” 라는 문구 3.5초 표시 후 로그인으로 돌아감</li>   
    </ul>
  </div>
  </details>
  <details>
  <summary><b>하단바 기능</b></summary>
    <img width="516" alt="image" src="https://github.com/user-attachments/assets/e4c6e994-73b9-4125-8b7f-2bc4123db732" />
  <br/> 
    모든 화면에 동일하게 적용
    <div markdown="1">
    <ul>
      <li>집 모양 버튼 : 메인 화면</li>
      <li>검색 모양 버튼 : 트레이너 리스트 화면</li>
      <li>웃는 얼굴 버튼 : 목표 설정 화면</li>
      <li>사람 모양 버튼 : 프로필 설정 화면</li>   
    </ul>
  </div>
  </details>

  <details>
  <summary><b>메안 화면 (예약현황창)</b></summary>
    <img width="719" alt="image" src="https://github.com/user-attachments/assets/cf00ed83-a558-4f97-a849-70ea9c0d9127" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>로그인 진행 후 가장 처음 뜨는 화면</li>
      <li>메인화면은 예약현황창으로 예약이 되어있는지 확인 가능 (추후에 예약 완료시)</li>
    </ul>
  </div>
  </details>

  <details>
  <summary><b>프로필 설정 화면</b></summary>
    하단바의 사람 모양 버튼 클릭
        <img width="254" alt="image" src="https://github.com/user-attachments/assets/c9ae2051-e9a9-4dc8-894e-2d63b3cd49bc" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>이름/ 성별 / 닉네임 / 생일 / 키 / 현재 체중 / 목표체중을 입력하고 확인 버튼을 누르면 저장됨</li>
      <li>해당 성별을 클릭하면 색깔이 바뀜 (남→ 파랑 , 여 → 빨강) 성별은 중복 선택 불가</li>
      <li>생일 날짜를 선택 → 캘린더로 넘어가 날짜 선택할 수 있음</li>
    </ul>
  </div>
  </details>

  <details>
  <summary><b>목표 설정 화면</b></summary>
    
하단바의 웃는 모양 버튼 클릭
<img width="266" alt="image" src="https://github.com/user-attachments/assets/7ccc94e8-03a6-47d8-8248-8da56e1a791c" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>체크박스 형태로 진행</li>
      <li>운동목적 : 다이어트 / 바디프로필 / 벌크업 / 기타 (복수선택가능)</li>
      <li>운동강도: 상/중/하</li>
      <li>운동계획: 주 1회부터 주 7회까지</li>
      <li>목표 설정 완료 버튼 클릭시 목표설정 저장</li>
    </ul>
  </div>
  </details>

  <details>
  <summary><b>트레이너 리스트 화면</b></summary>
하단바의 돋보기 모양 버튼 클릭
    <img width="280" alt="image" src="https://github.com/user-attachments/assets/b5168a90-b4ef-444c-93e5-58c17c253674" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>내부 데이터베이스를 사용하여 트레이너 리스트를 만듦</li>
      <li>리스트 화면에는 트레이너 이름, 해시태그, 센터 위치가 보임</li>
      <li>트레이너를 선택하면 트레이너 info 화면으로 넘어감</li>
    </ul>
  </div>
  </details>

  <details>
  <summary><b>트레이너 info 화면</b></summary>
    <img width="281" alt="image" src="https://github.com/user-attachments/assets/923e130d-2be7-4035-bb9f-fdcfbcee142b" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>학력과 자격이 포함된 세부사항이 들어가있음</li>
      <li>예약하기 버튼을 클릭하면 예약 화면으로 넘어감</li>
    </ul>
  </div>
  </details>

  <details>
  <summary><b>시간 예약 화면</b></summary>
    <img width="271" alt="image" src="https://github.com/user-attachments/assets/07d6f2f3-d5c1-4174-a576-68663d1e97e6" />
  <br/> 
    <div markdown="1">
    <ul>
      <li>날짜는 캘린더 형식으로 선택 가능</li>
      <li>시간은 최대 두개 버튼만 선택 가능</li>
      <li>예약하기 버튼을 누르면 메인 화면으로 넘어가 예약한 내역을 확인 가능</li>
    </ul>
  </div>
  </details>

## 애플리케이션 구현영상 (유튜브)
[Connect Coach 애플리케이션](https://m.youtube.com/watch?v=6cWg86FURpk)
