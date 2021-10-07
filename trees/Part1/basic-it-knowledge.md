# Part1 
## Part 1-1. basic-it-knowledge
> 학습 목표 : 우리가 사용하는 인터넷이 어떻게 동작하고 있는 지 이해합니다.
<br/>

## 📑 Table Of Index
- [How Does The Internet Work?](#How-Does-The-Internet-Work)
- [What Is HTTP?](#What-Is-HTTP)
- [Browsers And How They Work?](#Browsers-And-How-They-Work)
- [DNS And How It Works? & What Is Domain Name?](#DNS-And-How-It-Works)
- [What-Is-Hosting?](#What-Is-Hosting)
<br/>

## 💑 Special Thanks (Reference)
- https://developer.mozilla.org/ko/docs/Learn/Common_questions/How_does_the_Internet_work
<br/>


## How Does The Internet Work
### 1. 인터넷의 작동 원리

#### 1-1. 인터넷의 정의

인터넷(Internet)이란 International Network, 즉 국제적인 네트워크입니다.   
이는 전 세계적으로 연결되어 있는 큰 네트워크 망을 말합니다.  
<br/>

#### 1-2. 인터넷의 작동 원리

컴퓨터 간의 통신이 필요할 때는 물리적 케이블 또는 무선 주파수를 통해 연결 되어야 합니다.   
인터넷도 마찬가지 입니다. 그렇다면 우리는 인터넷을 어떤 방식으로 연결하고 있을까요?  

오직 컴퓨터만을 이용하여 네트워크를 연결한다고 가정해 봅시다.  
아래와 같이 컴퓨터마다 각각 케이블을 연결하는 방법이 있습니다.   

![image](https://user-images.githubusercontent.com/79235021/136170632-07d75dd2-ba81-40f4-8eaf-5c2c5458ed06.png)

얼핏 보면 좋아보이지만, 컴퓨터 수가 증가하는 경우 케이블의 수도 함께 기하급수적으로 증가합니다.

![image](https://user-images.githubusercontent.com/79235021/136170701-88fcceff-1c29-4088-ac56-876dc998fd4e.png)

우리는 이 문제를 해결하기 위해 '라우터' 라고 하는 특수 목적의 디바이스에 연결합니다.

라우터는 A 컴퓨터에서 보낸 요청을 B 컴퓨터에 도달할 때까지의 길잡이 역할을 수행합니다.

라우터 덕분에 기하급수적으로 늘던 케이블의 문제는 사라집니다.

![image](https://user-images.githubusercontent.com/79235021/136170882-294319e1-a1d4-4909-8624-0ed064eae8de.png)

그러나 라우터도 결국은 하나의 디바이스입니다. 

즉 하나의 라우터에 모든 컴퓨터를 연결하는 것은 불가능하다는 것입니다.

그래서 우리는 아래와 같이 라우터와 라우터를 연결하기로 했습니다. 

![image](https://user-images.githubusercontent.com/79235021/136170929-d4495cee-5c31-4868-8dfb-5f5f5a543285.png)

PC 보급률이 높아지며 네트워크 망은 점차 커지게 되고, 
아래와 같이 *라우터와 라우터와 라우터와 라우터와 라우터와 ...* 가 이어집니다.

![image](https://user-images.githubusercontent.com/79235021/136170972-e2305290-3935-4d4a-aa34-0532626250f2.png)

그러나 위와 같은 방식으로 국제적으로 연결하기에는 무리가 있어보입니다.

즉 많은 사용자를 연결할 수는 있겠지만, 먼 거리의 사용자를 연결하기에는 무리가 있다는 것입니다.

고민하던 찰나 이미 구축되어 있는 전화 망을 이용하기로 합니다.

다만 전화에 사용되는 데이터와 인터넷을 연결하는 데 사용되는 데이터는 엄연히 다른 구조로 이루어져 있기 때문에 특수한 기기를 이용해야 합니다.

**'모뎀'** 입니다. 

이 모뎀을 ISP에 연결합니다. 

> **ISP(Internet Service Provider)**
다른 네트워크의 라우터와 연결을 도와주는 서비스입니다.   
예시) 국가 ↔ 국가, 도시 ↔ 도시 등
> 

![image](https://user-images.githubusercontent.com/79235021/136171012-0b48abba-b29b-4615-9187-f448428afc5e.png)

ISP를 통해 모뎀과 모뎀이 연결되고 모뎀의 라우터가 연결되어 아래와 같은 구조를 형성합니다.

드디어 먼 거리의 사용자끼리 통신할 수 있게 되었습니다.

![image](https://user-images.githubusercontent.com/79235021/136171034-e46ddb1a-ace6-48cf-8fd0-482fc2430fde.png)
<br/>

## What Is HTTP
<br/>

## Browsers And How They Work
<br/>

## DNS And How It Works
<br/>

## What Is Hosting
<br/>
