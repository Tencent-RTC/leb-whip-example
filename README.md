# leb-whip-example

腾讯快直播  WebRTC WHIP 推流  

## WHIP URL

POST URL：` https://webrtcpush.myqcloud.com/webrtc/v1/whippushstream`


URL Parms: `streamurl=urlencode(webrtc://xxxxdomain/live/xxxxstreamname?txSecret=xxxxx&txTime=xxxxx)

So the push URL should be 

`
https://webrtcpush.myqcloud.com/webrtc/v1/whippushstream?streamurl=webrtc%3a%2f%2f5000.livepush.myqcloud.com%2flive%2ftest_1614592477%3ftxSecret%3d495e61f4bee542af2fb3e8befe6420a6%26txTime%3d61F958FF
`


## 关于测试

测试账号是个人账号，仅供测试使用，


## 如果测试

安装完node后执行 `npx http-server`

浏览器打开： http://localhost:8080