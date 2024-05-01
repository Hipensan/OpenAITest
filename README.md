# OpenAITest
한글 음성 받아서 파파고로 영어 변환 후 OpenAI API 써서 답안 도출 후 다시 파파고로 한글 변환 후 TTS 로 읽게 해 보는 프로젝트

https://www.youtube.com/watch?v=Xujt_rFf9Us 

대충 이거 참고

# .gitignore lists
recorded*
speech*
audio_recording*


# 주의 사항
API KEY는 private 하게 사용할 것


# 참고 사항
### OpenAI RateLimitError 발생 시
이전에 혹시 API Key를 한 번이라도 사용하는 계정으로 발급받은 적이 있다면 
Free trial 불가능, 5$ 결제하고 사용하도록 하자
gpt-3.5-turbo 사용시 꽤나 써도 크레딧 소모를 많이 하지 않는 편
다른 버전은 공식 문서의 Billing 참고<br>

### Chatbot.Speak() 부분 
파일이 늘어나지 않는 것 같음 
그래서 그냥 정말 대충 index 하나 더 올려주는 코드 작성
칸이 좀 늘어났다면 지워주자