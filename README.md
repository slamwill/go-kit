# go-kit
# Study Reference
  * https://kaichu.io/posts/gokit-engineering-operation/
  * https://www.youtube.com/watch?v=tcfVgusbqy0&t=1s
  * https://github.com/cage1016/gokit-workshop
# 分三層 service, endpoint, transport
  1. service: 運算邏輯
  2. endpoint
  3. transport: http, gPRC, etc…
* 其中
     * endpoint 經由 encode 傳送到 transport
     * transport 經由 decode 傳送到 endpoint 
# Source Code reference
  * https://dev.to/eminetto/microservices-in-go-using-the-go-kit-jjf
  * https://github.com/eminetto/talk-microservices-gokit
