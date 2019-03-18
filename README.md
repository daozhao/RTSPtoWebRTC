# RTSPtoWebRTC

this sample usage Pion WebRTC https://github.com/pions/webrtc stream RTSP camera to browser

1) git clone github.com/deepch/RTSPtoWebRTC  (Don't in go path)
2) cd RTSPtoWebRTC
3) you can edit main.go url := "rtsp://admin:123456@171.25.232.42:1554/mpeg4cif" to any you stream
4) go run *.go   (if run with vendor: go run --mod=vendor *.go )
5) open browser http://127.0.0.1:8080  (Suggest change 127.0.0.1 to loacal ip,like 192.168.1.122.)

go version >=1.11
