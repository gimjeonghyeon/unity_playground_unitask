# UniTask란?

---

- UniRx를 만든 개발자가 CEO로 있는 Cysharp에서 제공하는 유니티에서 비동기 작업을 처리하기 위한 도구로 설계된 오픈소스 라이브러리입니다.

# Task와 비교했을 때 이점은?

---

- Class로 작성된 Task와 달리 UniRx는 Struct로 설계되어 더욱 가볍고 메모리 관리적인 측면에서 효율적입니다.
- 또한 Unity의 코루틴과 통하밯여 사용될 수 있도록 설계되어 유니티 개발자에게 익숙한 코드 작성을 지원합니다.

# UniRx와 비교

---

- UniTask의 경우 전체적으로 콜백 없이 선형적으로 실행되기 때문에 코드의 가독성이 좋습니다.
- 버튼의 입력처리와 같은 특정 시퀀스를 여러번 반복하게 되는경우, 한 번에 여러 이벤트를 처리하려 하는 경우에는 UniRx를 사용하는 것이 좋습니다. (이벤트 중심으로 처리, UI처리시 사용)
- 초기화를 기다리거나 서버통신을 기다리는 등 단순하게 한 번만 실행되는 경우 또는 절차적으로 처리를 작성하고 ㅅ피은 경우에는 UniTask를 상요하는 것이 좋습니다. (비동기 처리시 사용)
