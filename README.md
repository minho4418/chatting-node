# chatting-node
### Node.js 기반의 실시간 그룹채팅 예제연습

# Chapter 3 - 정적 파일 제공

```javascript
/* 서버 image 폴더의 파일들을 제공(액세스 가능) */
/* 클라이언트는 http://서버주소/test 로 액세스 */
app.use('/test', express.static('./image/'))
```
