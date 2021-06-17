---
title: 프로젝트 진행상황
layout: landing
description: '프로젝트 주차별 진행상황'
image: assets/images/pic07.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<section id="one">
	<div class="inner">
		<header class="major">
			<h2>금주 수행결과 및 문제점 해결방법</h2>
		</header>
	</div>
</section>

<section id="two" class="spotlights">
	<!-- Two -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw2.jpg%}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>2주차</h3>
				</header>
				<ul class="alt">
					<li>주제 아이디어를 하나 이상 제안하여 그 중 하나의 주제를 정함</li>
					<li>각자 수강했던 과목들과 하드웨어 제어의 경험을 살려 얼굴인식 기능을 새롭게 추가한 얼굴인식 기능 활용 하드웨어 제어로 주제를 정함</li>
				</ul>
			</div>
		</div>
	</section>
	 <!-- Three -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw3.jpg%}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>3주차</h3>
				</header>
				<ul class="alt">
					<li><b>홍금비 :</b> Raspberry로 웹카메라 제어 및 mqtt 환경 구축</li>
               				<li><b>강예준 :</b> Android를 통해 Firebase 관리</li>
               				<li><b>이현정 :</b> Github 홈페이지 관리, Android 카메라 제어</li>
               				<li><b>임세진 :</b> 주간 보고서 작성, 서버 컴퓨터 제어, CNN 구현</li>
				</ul>
			</div>
		</div>
	</section>
	 <!-- Four -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw4.jpg%}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>4주차</h3>
				</header>
				<ul class="alt">
					<li><b>강예준, 이현정 :</b> 안드로이드 카메라에 촬영 가이드용 윤곽선 표시 기능을 구현함.
						앱 내에서 촬영 버튼을 누를 때마다 뷰에 이미지가 뜨며 촬영되는 기능 구현. 연속 촬영 기능 구현중</li>
               				<li><b>이현정 :</b> 깃허브 홈페이지 관리</li>
               				<li><b>홍금비 :</b> 과제 제안서 작성을 완료함. 라즈베리파이로 웹캠 제어를 위한 라이브러리 설치, 파이썬 코드로 캠 제어 기능 구현중.</li>
               				<li><b>임세진 :</b> 서버컴퓨터를 비치해 둔 장소에서 무선랜으로 연결하니 속도 문제가 있어서
                  				공학관 103호로 비치 장소를 옮겨 유선랜으로 연결하여 네트워크 환경을 안정화함. 제안서 작성완료. 발표영상 제출 예정 (주말)</li>
				</ul>
			</div>
		</div>
	</section>
	 <!-- Five  -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw5.jpg%}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>5주차</h3>
				</header>
				<ul class="alt">
					<li><b>홍금비 :</b> Raspberry로 웹카메라에 사람 얼굴이 인식되면 사진을 찍어 mqtt로 전송하는 기능 구현 완료.
						Firebase에서 사진을 다운로드하는 기능 구현 완료.</li>
               				<li><b>강예준, 이현정 :</b> Android앱 내에서 연속촬영 구현중.
                  				연속촬영에 대한 자료가 많지 않아 동영상을 촬영하여 영상에서 사진을 여러장 캡처하는 방식으로 변경하여 구현중</li>
               				<li><b>이현정 :</b> Github 홈페이지 관리, 앱 내 학습 시 하단에 나오는 프로그래스바 구현 완료</li>
               				<li><b>임세진 :</b> 주간 보고서 작성, tensorflow2.4.1과 1점대 version에서 여러 문법이 변경되면서 
                  				기존에 사용하려했던 FaceNet 라이브러리가 동작하지 않는 문제가 발생하여 새로운 라이브러리를 탐색하고 있음. 
                  				가상환경을 여러개 구축하여 각각 환경에 다른 버전의 tensorflow를 설치하여 test하고 있음</li>
				</ul>
			</div>
		</div>
	</section>	
	 <!-- Six -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw6.jpg%}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>6주차</h3>
				</header>
				<ul class="alt">
					<li><b>홍금비 :</b> Firebase에서 사진 다운로드 프로토콜 정하고 구현함.
                  				폴더명을 설정하면 파이썬에서 해당 폴더를 생성하여 사진을 다운로드할 수 있게 함</li>
               				<li><b>강예준, 이현정 :</b> Android앱 내에서 동영상을 촬영하여 영상에서 사진을 여러 장 캡처하는 방식으로 구현 완료함.</li>
               				<li><b>이현정 :</b> Github 홈페이지 관리</li>
               				<li><b>임세진 :</b> 주간 보고서 작성</li>
				</ul>
			</div>
		</div>
	</section>
	 <!-- Seven & Eight -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw8.jpg%}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>7주차, 8주차</h3>
				</header>
				<ul class="alt">
					<li><b>중간고사 기간</b></li>
				</ul>
			</div>
		</div>
	</section>	
	<!-- Nine -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw9.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>9주차</h3>
            			</header>
				<ul class="alt">
					<li><b>홍금비, 임세진 :</b> 서버 컴퓨터의 GPU가 GForce RTX 3090인데
                  				해당 그래픽 카드는 tensorflow 1.X 버전을 지원하지 않는다는 사실을 알게됨.
                  				tensorflow2.X 버전으로 전체 가상환경 셋팅을 바꿔서 facenet 코드를 실행함.</li>
               				<li><b>강예준, 이현정 :</b> 안드로이드와 라즈베리파이를 mqtt로 연결하여 서로 통신할 수 있는 환경을 구축.
                  				아두이노로 도어락 제어를 할 수 있도록 구현함, 아두이노와 라즈베리파이 블루투스 연결하여 통신할 수 있도록 함</li>
               				<li><b>이현정 :</b> Github 홈페이지 관리</li>
               				<li><b>임세진 :</b> 주간 보고서 작성</li>
            			</ul>
			</div>
		</div>
	</section>
	<!-- Ten -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw10.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>10주차</h3>
				</header>
				<ul class="alt">
					<li><b>홍금비,임세진 :</b> facenet 모델을 사용할 때 얼굴인식하는 속도가 너무 느려서 원인을 찾고 있는데 아직 해결하지 못했음.
                 				다른 얼굴인식 모델을 서칭하는 중. mqtt 통신으로 firebase에서 이미지 다운로드하는 것을 완료했음.</li>
               				<li><b>강예준, 이현정 :</b> 라즈베리파이 포트포워딩을 진행하는 과정에서 어떤 포트를 열어야할지 몰라 어려움을 겪었지만 
                 				 교수님의 조언으로 외부 : 80 내부 : 1883 으로 접근하여 해결함
                  				포트포워딩을 통해 LTE환경에서도 도어락을 제어할 수 있게 함</li>
               				<li><b>이현정 :</b> Github 홈페이지 관리</li>
               				<li><b>임세진 :</b> 주간 보고서 작성</li>
            			</ul>
			</div>
		</div>
	</section>
	<!-- Eleven -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw11.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>11주차</h3>
				</header>
				<ul class="alt">
					<li><b>홍금비, 임세진 :</b> mosquitto 환경 구축, mqtt 코드 복구</li>
               				<li><b>강예준, 이현정 :</b> 포트포워딩, mqtt 연결 코드 복구</li>
               				<li><b>이현정 :</b> Github 홈페이지 관리</li>
               				<li><b>임세진 :</b> 주간 보고서 작성</li>
				</ul>
			</div>
		</div>
	</section>
	<!-- Twelve -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw12.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>12주차</h3>
				</header>
				<ul class="alt">
					<li><b>홍금비, 임세진 :</b>facenet을 새로운 방식으로 구현한 코드를 발견하여 속도를 개선하였음.
						  라즈베리파이를 유선랜과 연결하고 비디오 스트리밍 툴도 변경하여 속도를 개선.
        				          firebase와 서버 컴퓨터의 파이썬 코드를 연결함.
       				           mqtt를 통해 db에서 이미지를 다운로드 받고 한꺼번에 순서대로 학습, 분류, 카메라 동작 하도록 코드를 정리함</li>
     				          <li><b>강예준, 이현정 :</b> apmod를 사용하여 기기 인식 기능 구현중. wifi가 잡히는 것을 확인했으나,
    				              인터넷 연결은 되지 않아 다음주에 교수님께 여쭤볼 생각이다.이미지가 40장 업로드 되도록 수정하였고
    				              기존에는 이미지가 업로드 될 때마다 다이어로그가 떴는데 마지막에 다 완료한 후에 한번만 뜨도록 수정했음.
    				              서버 컴퓨터랑 통신하는 mqtt코드를 구현함</li>
   				            <li><b>이현정 :</b> Github 홈페이지 관리</li>
   				            <li><b>임세진 :</b> 주간 보고서 작성</li>
     			       </ul>
			</div>
		</div>
	</section>
	<!-- Thriteen -->
	<section>
		<a href="generic.html" class="image">
			<img src="{% link assets/images/picw13.jpg %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>13주차</h3>
				</header>
				<ul class="alt">
					<li><b>전체 팀원 :</b> 시연 </li>
				</ul>
			</div>
		</div>
	</section>
</section>

</div>
