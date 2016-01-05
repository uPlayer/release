
## Release steps
1. change excuable bundle identity `version` and `build`
2. zip the excualbe
3. sign it with dsa private key  
`	~/Sparkle/bin/sign_update Smine.zip ~/快盘/dsa/dsa_priv.pem`
4. ls the zip file size
5. update the cast xml

##To test update
Use `python -m SimpleHTTPServer 8080`  

