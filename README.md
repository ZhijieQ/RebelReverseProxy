# ReverseProxy
ReverseProxy in golang

## Use:

	./ReverseProxy_[OS]_[ARCH] -h
	
	Usage of ReverseProxy_[OS]_[ARCH]:
	  -l string
	        listen on ip:port (default "0.0.0.0:8888")
	  -r string
	        reverse proxy addr (default "http://idea.lanyus.com:80")


	./ReverseProxy_windows_amd64.exe -l "0.0.0.0:8081" -r "https://www.baidu.com"

	Listening on 0.0.0.0:8081, forwarding to https://www.baidu.com

### Important
After download the package, give chmod 777 and write a script to run it
start.sh
```sh
nohup ./ReverseProxy &
```

After that, open your 8888 port and use that IP.
http://{yourIP}/1F1A44B7-76D4-4650-A831-B530E59DDD50

One step more, go to help -> JRebel -> Config -> WorkOffline
