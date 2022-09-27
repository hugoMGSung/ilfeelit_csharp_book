---
description: C에서부터 시작합시다
---

# 🎢 C#이 나오기 까지

C는 대단한 언어입니다. 하지만, 단점이 있습니다.\
무지막지하게 어렵다는 것입니다. 그리고, 절차적인 언어 체계를 담고 있습니다.

### C++

그래서 AT\&T 벨 연구소에 있던 덴마크 개발자 비야 스트롭스트룹(Bjarne Stroustrup)이 이러한 C의 단점을 보완한 객체지 프로그래밍이 가능한 C+1의 의미인 C++를 1979년 부터 연구하기 시작하여, 1985년 출시하게 되면서 객체지향 프로그래밍이 시작되었습니다.

<figure><img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Bjarne-stroustrup_(cropped).jpg" alt=""><figcaption><p>출처 - 위키피디아</p></figcaption></figure>

이 C와 C++의 영향을 받고 거의 대부분의 언어들이 만들어졌습니다. Java, Python, JavaScript 등이 C, C++를 참조하여 개발된 언어들이며, C#과 Java는 C++에 지대한 영향을 받았다고 해도 과언이 아닙니다. C, C++의 영향을 받지 않은 언어는 Visual Basic, Delphi 정도라고 보면 되겠습니다.

### C# --> C++++

Java(1995)가 전세계 프로그래밍 생태계를 장악해가기 시작하자, 다급해진 마이크로소프트사는 델파이를 개발했던 덴마크 개발자 아네르스 하일스베르를 주축으로 C#(2000)을 개발 발표하기에 이릅니다.&#x20;

이때부터 마이크로소프트사는 자신들의 개발 환경을 대표하는 닷넷(.NET) 프레임워크를을 동시에 발표하며 Java의 대항마가 되고자 경쟁하기 시작합니다.

만... 안타깝게도 아직 상대가 안되고 있습니다.

2002년말 C# 1.0을 시작했지만 2010년 C# 4.0(.NET Framework 4.0) 부터 그나마 쓸만한 언어로 거듭나왔고, 2022년 현재 C# 10.0이 최신이며, C# 11.0이 연구 개발 중입니다.

### C# 생태계의 변화

<figure><img src="https://learn.microsoft.com/ko-kr/dotnet/standard/library-guidance/media/cross-platform-targeting/platforms-netstandard.png" alt=""><figcaption><p>출처 - 마이크로소프트</p></figcaption></figure>

긴 이야기를 해야 하지만 간단하게 정리하자면, .NET Framework는 MS Windows 상에서만 동작했습니다. 이것이 바로 Java를 이기지 못한 큰 문제였습니다.

그래서 MS는 기존의 Windows에서 사용하던 .NET Framework 외에 OS 독립적으로 사용할 수 있는 .NET Core를 발표했습니다. 그리고, 이를 통해 모바일을 개발할 수 있는 Xamarin도 발표했습니다. 이 모든 프레임워크가 .Net Standard라는 라이브러리 위에서 운용되고 있습니다.

.NET Framework와 .NET Core는 소스의 소소한 차이가 있지만 거의 대부분이 비슷하여 쉽게 전환할 수 있습니다. 하지만, 아직 .NET Framework에는 존재하지만 .NET Core에는 없는 라이브러리들이 존재합니다. 이는 점점 MS에서 추가 개발해 나갈 것으로 보입니다.

이외에도 Unity라는 3D 그래픽 엔진에서 그래픽 오브젝트에 명령을 할 수 있는 표준 스크립트 언어로 C#이 지정되고, 스마트팩토리 솔루션 개발에 개발 생산성을 목적으로 하여 C#이 주목을 받으면서 다시 대한민국에서 급부상하고 있는 언어입니다.
