VS Code의 User Snippets 기능을 이용하면
자주 쓰는 코드를 단축어로 지정해놓을 수 있다!

방법
1. 왼쪽 하단의 톱니바퀴 모양 클릭 > User Snippets 클릭
2. html.json 파일 열기
3. 주석처리 되어있는 Example 파일에 맞춰 코드 작성

```json
	"Print to console": {
		"prefix": "log", // 단축어 이름
		"body": [ // 포함할 코드
			"console.log('$1');", // $1: 처음 포커스 위치
			"$2" // $2: tab 누르면 포커싱되는 위치
		],
		"description": "Log output to console"
	}
```

같은 방식으로 javascript.json에서
console.log() 등의 코드도 단축어로 설정할 수 있다!
