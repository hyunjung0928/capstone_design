---
layout: post
title: 프로젝트 소개 
description: 프로젝트 소개 
image: assets/images/pic11.jpg
nav-menu: true
---
<h2>프로젝트 수행 목적</h2>

<h3>프로젝트 정의</h3>
<blockquote>Deep Learning 기반의 얼굴인식 및 기기인증을 활용한 보안 원격 제어 시스템</blockquote>
<p>본 프로젝트의 목적은 비밀번호를 통한 도어락과 같은 잠금장치의 취약성을 보완하여 얼굴과 모 바일 기기 인식을 통해 검증하는 방식으로 보안성을 강화하는 것이다.</p>

<h3>프로젝트 배경</h3>
<blockquote>현재 대부분의 도어락 잠금장치는 비밀번호를 통해 제어된다.
하지만 비밀번호로 잠금해제를 하는 도어락의 경우 비밀번호가 유출될 수 있는 가능성이 있어 보 안에 취약하다. 따라서 우리는 이러한 취약점을 보안하기 위해서 얼굴인식과 기기인식을 통하여 도어락을 제어하고자 한다.</blockquote>

<h3>프로젝트 목표</h3>
<dl>
	<dt>얼굴 인식</dt>
	<dd>
		<p>CNN을 이용한 얼굴인식 구현 </p>
	</dd>
	<dt>기기 인증</dt>
	<dd>
		<p>블루투스 이용한 기기인증</p>
	</dd>
	<dt>도어락 제어</dt>
	<dd>
		<p>나의 인증이 성공하면 도어락을 열 수 있다.</p>
	</dd>
</dl>
<hr />
<h2>프로젝트 개요</h2>

<h3>프로젝트 구조</h3>
<section>
	<img src="{% link assets/images/structure.jpg %}" alt="" data-position="center center" />
	<div class="content">
		<div class="inner">
			<p>본 시스템은 아래의 그림처럼 라즈베리파이, 서버 PC, 아두이노, 사용자 어플리케이션으로 구성된 다. 각각의 시스템은 MQTT(MessageQueuingTelemetryTransport) 프로토콜을 통해 데이터를 주고 받는다. MQTT Broker는 라즈베리파이에 탑재하였으며, 사용자의 얼굴인식을 위한 웹카메라도 라 즈베리파이에 연결하여 제어한다. 모바일 기기를 통해 입력받은 사용자 이미지와 데이터는 Firebase에 업로드 된다. 서버 PC는 얼굴인식 프로그램과 기기인증 프로그램이 실행되고 있으며 Firebase에서 데이터를 다운받아 얼굴 인식을 모델을 학습시킨다. 얼굴 인식과 기기 인증에 성공 하면 MQTT 프로토콜을 통해 아두이노에게 성공을 알려 도어락을 제어한다.</p>
		</div>
		</div>
	</section>
