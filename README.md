# 3proxy
You can use 3proxy docker to donate new endpoint to [https://redirectinspector.com](https://redirectinspector.com)

We apreciate yours support.

Current servers donated by 
- [MailCheck](https://mailcheck.co/) - email verification service that protects you from bounces
- [NodeArt](https://nodeart.io) - nodejs developers company, company that builds quality products for customers. And we passionate about JS.

## Usage

```
$ docker run -d --name 3proxy -v ./3proxy.cfg:/etc/3proxy.cfg -p 8080:8080 nailgun/3proxy
or
start.sh
```
