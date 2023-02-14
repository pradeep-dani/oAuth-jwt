https://www.cryptool.org/en/cto/openssl

 _ _ _     _      _____             _____ _____ __    
| | | |___| |_   |     |___ ___ ___|   __|   __|  |   
| | | | -_| . |  |  |  | . | -_|   |__   |__   |  |__ 
|_____|___|___|  |_____|  _|___|_|_|_____|_____|_____|
                       |_|                            
                
OpenSSL 3.0.7 1 Nov 2022 (Library: OpenSSL 3.0.7 1 Nov 2022)
Compiled to WebAssembly with Emscripten. Running in WebWorker.

Usage: openssl [command] [params]

$ openssl genrsa -des3 -passout pass:x -out server.pass.key 2048
$ cat server.pass.key

-----BEGIN ENCRYPTED PRIVATE KEY-----
MIIFHDBOBgkqhkiG9w0BBQ0wQTApBgkqhkiG9w0BBQwwHAQIbpgSI7z2a/YCAggA
MAwGCCqGSIb3DQIJBQAwFAYIKoZIhvcNAwcECDAsVDhTpzjKBIIEyJctmZ5CTV8d
lpTHdprCswakl4zuEvZnFbV7/eOeKKe3oYXbWB/GfPl9iNqUnvi84BPuN4vxkBGe
nmVyR+AxuCPzD3Fca7nuBviHOC5rVUqwDbnJesrM07N7ujwTWNfIGTuKhjFIZAGs
Nove9twmZ+zW3ZP75rrtHZV4TMPQPmV6FCpQ2BV37gMThwA5M1eXDMKsZSkDq1Bm
SNlYzLN3F+abMJbAw3eOxmhVY8yGPan6xWEpZ4UIvc3imnB6Zzz5QKRm8/bJCOM+
hA+PRIVR8ULXV7u0aZd8Ojgt/xgw8guRlcoQ8h6tbUDibIVXcT+UzokoBdM05iyQ
5TH2KI5L4/pyE+1cntDJG5+WHEWPRj7hETjbM1oPYAB/TSGtmQvtPWAep287f4wr
6zJ+1dC+OLJ6kmFcwk5mksjthj3FGOoDxjy/F9Mr8oc8Pcv0TqkBNggj8F/Zd4PW
wInnNcwN6O1Tavb8JNGG4VUmTvzQONWrVUeX8KUrhMkmrHLkkAQ+zAp82c2zG0qq
411loVuJGunPItrXj6oFGI+Rub9DrGNk0e3t44WLDW2Cawrv4AO0ccizgpwULPrM
j9xIUsGiqVrGl+0S4+jx5ns0q7SZeZT3k2zSDFOoWFIl2daE9b6xd8Hl4TuMQDKA
0xnxs59dXWcyhUhYBJ4y1ktLkfIF6qXKJ0udZAaj4WYihxJY822YaXREHlQBQGs7
V3s8WVHELHZQu6Chfh6QT+dkHT9TNXYP/RXaLLZjzzqgy/U+Sx3GFxxlLZUp15KF
iYXPU37rHaSN+6nREjJkkfsKEn7cFR7IbdPzow5G7dz3Q1uuAZBLl6ahpTTgM/wb
L5xsZ6yJpmB/hx4My8BPZlTJMXLvzlvGYbmtOyBDJ1HuI2sM6kshO1xGiLs7DGIh
1Umipy8iFcA+563J56LWmR9cAiZrte7ATAsfX5IivQv0jipIN8cDJNv5uyupUkNs
CBk4Y5hyTAFO8Kqyr6l2zWfQjt1lylUVEhmwwQHlFRkckqm9NJ3tlBeq0lBxSc2Y
yF0VFhqRNfaq1rJXHkz3y2GkwhHMsjl+ifv/bEL2ZvI7tya2VVz0tJPBzrqf6+9u
FiMXrCU+JhYju8rDe2emyfV3SR/swsIQTDcst0yj9gamCcl2/+x9JxEhFx/kD/u8
NcD9qoMUpQKi6+HGurBkpbBgYX8R3zQmUwmfh2xJZKOFi9jqbjyDuocUjkMuyu3/
hkQpFJlsCKKCHk7kdGqQTfASuRxFU0DzcOF10v6CnWbNiASDnmkGtHgRq2E1RdrW
vuCuRpZmjbSpSnQGyvVtM3UChn3ZhCpymJqo/H96zlrqzudfiVhuHK8rOuxMF6xf
sHh5zaNP4FhtGVJCX298/uokDx2Wy4obxcZDmoM6R4p3X8RrPkFHwmmx3v2DKPvp
cC7JpT6Qvel3jbME4bpOCaY0eC7L4bUTeeGuF8Lf0gnahmPEl4+ZSTU2wSxLf0NY
2zSNozM/Bah/rbFY8kGuD9wRmJuLm3eTb8LdrU8PUOt0p4G+zclVo+zRYGGCHrsh
mtgsa6wbSrWFgdHrDYtGrt1NOFrYLPM/Cry6QVyH9R9la5JlRK2fOjRfCOCCISH5
IBGCBsewA3rEfmVFvNGLYQ==
-----END ENCRYPTED PRIVATE KEY-----

$ openssl rsa -passin pass:x -in server.pass.key -out server.key
writing RSA key
$echo "copy all the content and keep it in a file."
$ cat server.key

-----BEGIN PRIVATE KEY-----
MIIEvgIBADANBgkqhkiG9w0BAQEFAASCBKgwggSkAgEAAoIBAQCYUQ7Mfw2ZR/a6
pY0pGrcWKvH/IjuiX+fUuWMS+Sp+rsTjVlfp0dF/ldEmJKHxSuUVY9T7E4XFV42v
jpZ2183OFQc6VHFJ0u/DlNzf5b5Wu6+cad5oz3uIziJaeLpSoWE7QdXGfgDroUpB
ERYUndNyCTAr1q90ie2/6PpsDjTl7ihj6yXTlkOXU0CEjZEJUBIHCUx0FC5/Fmhp
Ze1zo9+fLH8oUVW4hhSNzZhr1Hl3r7dkiblXkUXuWJbusJ1+GO4xU4TvHZozzV42
2yODunAE1nCPlVFTC/P3BsomRDQ9r1jjJoGGhGiGteCyDMoB7llBU3T0NQqsoxBX
2O+kXtjrAgMBAAECggEAMHf2vBcgBisytZERusdABINU72l+zXw0QupdPv/fyGEn
0Om8XvC/+Bf97mPQzn4VKLnUX7MGKdZjBT7b3WRtnortel+9jw7a8gMwR+UNLP9b
cev0dKi1eEKUBvMM41dsH9Wix593/oMcJFliC9xvGQYYeJK/0VdEuwFRksnwhkvF
NAH4WyZotIL1uz4nyszufK4jM0i0PI5nUl6YcVO6BE9hdBfyHlxTRobHLO5BIzZQ
AlopxPjCtq6lVEm9TImw5JbmiFGQmhq2p2io38dhicUcCRorgMpxM+EuK1U3h0yQ
uXisZlLT3pcJqie0a63Pwu5WylxvVswn3fMHvuKltQKBgQDUuQpmnl84SKUnTG03
aqw0wm/NE+Bl3t6E4/gZqODqInQGR3XJvI09u5up/m3OEZTahjKnASVTwWfwvyMc
JGLcM33oEnmcvkku50YYMoE3S2K3T4ciRU+gzaWCQvif7wuO0cJigT4ujy2WURTd
TXGCkGDhmXlYdNT+GJkju8lz1wKBgQC3TfZaf3qMkEEAvth1QKAOLa3+NrGZ+cQ+
FJ/CpOIiciPtzZYVSEPfI7p7Wp7PkbCXPu8jrmZmvRAGeDw9fnn+pFFS8r9j2N7f
jJNQ5uCjMcGs9bZYT+t5qO4pChAQKTLDGeMThkyzDC/lwQBjPr57ldxBh4k9xPxi
g/Tji8zhDQKBgEt462vFPNtnStFKmGVU/4wogCoupyr9i81yZJAWDtaDKs8fg3bz
4tjIO05w6tx1+G4fttDx4yB4Ojx8VCSj9D9UNZOlGmi2SpjNjV0AbkAECx4mpTdP
iBTxYYt532Q/F8awPVtdp4Y1XmM6mUB7PY6pUvY30YnEydztNUgsVCk5AoGBALBK
LZTJp13KWonSAbF6rrQUIJMtnM8eFCs0gJWdJ9LC/WT2ZNIhBw1yeiWqeLPeRPyg
zTL+xoMmb2QZfK4TllZdR81DoufvKiHLO98BvKeW8dJbGbyDWE9QNYSIpfw08xoK
KoabkeZc4S/Q14ObU2zeKs9m/4nFiolgqUOyLx99AoGBALFKXBpq6HL8RhcmZcyv
lRxRFZbs7p4vsInthXsHp3JPN+mqaGQhHB1JyRnpZ4bBu22sq5QW7wlKwNH/GAz8
AXbghw0HvktjwJISY3fljnuLSdrpYFq7lR5R+dxUxwu7FYLJgsgDebexXjFI4jSU
fmRt+CvNaojWAldVFdxQx/fP
-----END PRIVATE KEY-----

$ openssl req -new -key server.key -out server.csr

You are about to be asked to enter information that will be incorporated
into your certificate request.
What you are about to enter is what is called a Distinguished Name or a DN.
There are quite a few fields but you can leave some blank
For some fields there will be a default value,
If you enter '.', the field will be left blank.
-----
Country Name (2 letter code) [AU]:US
State or Province Name (full name) [Some-State]:Georgia
Locality Name (eg, city) []:Alpharetta
Organization Name (eg, company) [Internet Widgits Pty Ltd]:PD_ORG
Organizational Unit Name (eg, section) []:AH
Common Name (e.g. server FQDN or YOUR name) []:PD_COMMON_NAME
Email Address []:pradeep.jdani@gmail.com


$echo "copy all the content and keep it in a file."
$ cat server.csr

-----BEGIN CERTIFICATE REQUEST-----
MIIC2TCCAcECAQAwgZMxCzAJBgNVBAYTAlVTMRAwDgYDVQQIDAdHZW9yZ2lhMRMw
EQYDVQQHDApBbHBoYXJldHRhMQ8wDQYDVQQKDAZQRF9PUkcxCzAJBgNVBAsMAkFI
MRcwFQYDVQQDDA5QRF9DT01NT05fTkFNRTEmMCQGCSqGSIb3DQEJARYXcHJhZGVl
cC5qZGFuaUBnbWFpbC5jb20wggEiMA0GCSqGSIb3DQEBAQUAA4IBDwAwggEKAoIB
AQCYUQ7Mfw2ZR/a6pY0pGrcWKvH/IjuiX+fUuWMS+Sp+rsTjVlfp0dF/ldEmJKHx
SuUVY9T7E4XFV42vjpZ2183OFQc6VHFJ0u/DlNzf5b5Wu6+cad5oz3uIziJaeLpS
oWE7QdXGfgDroUpBERYUndNyCTAr1q90ie2/6PpsDjTl7ihj6yXTlkOXU0CEjZEJ
UBIHCUx0FC5/FmhpZe1zo9+fLH8oUVW4hhSNzZhr1Hl3r7dkiblXkUXuWJbusJ1+
GO4xU4TvHZozzV422yODunAE1nCPlVFTC/P3BsomRDQ9r1jjJoGGhGiGteCyDMoB
7llBU3T0NQqsoxBX2O+kXtjrAgMBAAGgADANBgkqhkiG9w0BAQsFAAOCAQEACAR3
HQtSXXy/tg51fc2oENPGNAINVB8ROzPZUL0l4NuHFlDVzGwjVUctiEZX3i10Wmco
kTUVbTUbq8kYkFLXwWiKxlcSlPLH88jk8NndVQWXWlmV/3tV0uddi2yWvPu1cV5U
hrx5FC+D5H7XLGMXOSJbWgrPzQ1KqWfN9Hw7zxCK0FWGGGv4Gq/rnRaWqaFS/Hh3
MZw7HxUvRUt4xJ9PLXPS3XyUE0Zu48sKNK6ZYbi6qxO22spnqXh58KegIOlOl+D5
Sa7I5CgsEqkiUAYXzc/uDEW9ku4NiUOD7/qKhhmXBtdBBrmtrrfJO1DLey28jz7f
O5o10n+8io+gKZR4EQ==
-----END CERTIFICATE REQUEST-----

$ openssl x509 -req -sha256 -days 365 -in server.csr -signkey server.key -out server.crt

Certificate request self-signature ok
subject=C = US, ST = Georgia, L = Alpharetta, O = PD_ORG, OU = AH, CN = PD_COMMON_NAME, emailAddress = pradeep.jdani@gmail.com


$echo "copy all the content and keep it in a file."
$ cat server.crt

-----BEGIN CERTIFICATE-----
MIIDrzCCApcCFCi0Kw0Hj6sIknOLQ04/gRsQNuyNMA0GCSqGSIb3DQEBCwUAMIGT
MQswCQYDVQQGEwJVUzEQMA4GA1UECAwHR2VvcmdpYTETMBEGA1UEBwwKQWxwaGFy
ZXR0YTEPMA0GA1UECgwGUERfT1JHMQswCQYDVQQLDAJBSDEXMBUGA1UEAwwOUERf
Q09NTU9OX05BTUUxJjAkBgkqhkiG9w0BCQEWF3ByYWRlZXAuamRhbmlAZ21haWwu
Y29tMB4XDTIzMDIxNDA3NDMyMVoXDTI0MDIxNDA3NDMyMVowgZMxCzAJBgNVBAYT
AlVTMRAwDgYDVQQIDAdHZW9yZ2lhMRMwEQYDVQQHDApBbHBoYXJldHRhMQ8wDQYD
VQQKDAZQRF9PUkcxCzAJBgNVBAsMAkFIMRcwFQYDVQQDDA5QRF9DT01NT05fTkFN
RTEmMCQGCSqGSIb3DQEJARYXcHJhZGVlcC5qZGFuaUBnbWFpbC5jb20wggEiMA0G
CSqGSIb3DQEBAQUAA4IBDwAwggEKAoIBAQCYUQ7Mfw2ZR/a6pY0pGrcWKvH/Ijui
X+fUuWMS+Sp+rsTjVlfp0dF/ldEmJKHxSuUVY9T7E4XFV42vjpZ2183OFQc6VHFJ
0u/DlNzf5b5Wu6+cad5oz3uIziJaeLpSoWE7QdXGfgDroUpBERYUndNyCTAr1q90
ie2/6PpsDjTl7ihj6yXTlkOXU0CEjZEJUBIHCUx0FC5/FmhpZe1zo9+fLH8oUVW4
hhSNzZhr1Hl3r7dkiblXkUXuWJbusJ1+GO4xU4TvHZozzV422yODunAE1nCPlVFT
C/P3BsomRDQ9r1jjJoGGhGiGteCyDMoB7llBU3T0NQqsoxBX2O+kXtjrAgMBAAEw
DQYJKoZIhvcNAQELBQADggEBAIB29TQ5KCH8U+QV8B8mPMVufA4AYUrL3xShgtsf
XdIC3YLLbJszoyIpmk0UhKctsvUm/kC9yCiuioGG7fiMRWuhWtosvqjnzEp0WWyb
JNVUhZ3B2f4bDpKvbBwRYWsxq+zX+wSYH/iY8qO/wiaYuMPrIZDRiS3uDEgMP2b6
HzhVFN2xLpN3Vz+VWcGbQin5h2N9+zzwIxMx3kszq3uR5ncJduXe/0HwDVatKHXW
/xJSu9colMRs4HUkLUvuENvj5ihQanKBkxuL3Duq5b1vdzObU86MRoufqcuztEy/
t9V6znH4FBKJvaHr/pOu16pK2ETP45tne7hSHTYHsEIg0ko=
-----END CERTIFICATE-----


Following are the next steps:
	create connected app
		Enbale oAuth Setting
		Callaback url - keep dummy
		Select api & refresh token
		Save
		Click on Manage
		Got to policies & edit
		Select pre-authorised
		Generate Consumer KEY & use it for issuer while generating the JWT.
		
	Now generate JWT by using https://jwt.io, below is sample
		HEADER:ALGORITHM & TOKEN TYPE
			{
			  "alg": "RS256"
			}
			
		PAYLOAD:DATA
			{
			  "iss": "Consumer Key",
			  "sub": "User Id",
			  "aud": "https://test.salesforce.com",
			  "exp": "1703980800"
			}
		VERIFY SIGNATURE -- select RSA256 at the top if it is not selected already.
			RSASHA256(
			  base64UrlEncode(header) + "." +
			  base64UrlEncode(payload),
				[Private Key in PKCS #8, PKCS #1, or JWK string format]
				## copy the contents of private key file.
			)
	https://jwt.io/#debugger-io?token=eyJhbGciOiJSUzI1NiJ9.eyJpc3MiOiIzTVZHOW9adEZDVld1U3dPSkhPaXFjWk9aVGk0YXo4cF9mc2lJVUtSUTZ3UWpQMHlMVThVdEFqWVJ0THVubVFxVkVMX21tem1wcWhVZGtWZ3phTlA4Iiwic3ViIjoicHJhZGVla3VtYXJAZGVsb2l0dGUuY29tLmRldmh1Yi5qd3R0YXJnZXQiLCJhdWQiOiJodHRwczovL3Rlc3Quc2FsZXNmb3JjZS5jb20iLCJleHAiOiIxNzAzOTgwODAwIn0.gOOmT2dbrZqBhqjCEzOu4C-lL6vC8Mibb13Rcj20ZsKxT28XWhS9u2Wc4rlxi2h4DisfMiowFqx3ofuikaYUcWjocWGx2LCbm1QjMkKNUyDvLAgwaYf8VbdChR5JKu0tiJIdy4gkOUPMkLBmIPiw-ok1GZh-KSyCxsCbD-TFmZZwhwHU6C2I7HTREei19pQbCuGM8HGNQ9COaxjq5n-v-I7wCL5SpA99-G8UCk4ZmV-9_47prekBt0SbhNX7pw7k_UEMF_vS-xWwW7rcNdsfUXfat1g7XSn9Y4Ws99VrTyBTLFbkmC9ThgU9RrySLYf2cXSV4wUF72VtI2CvpxTFTw
	
	Ready to go, following is the request(assertion as the JWT) you can use in postman collection
	File name: collection.json
	----------------------------------------------------------------------------------------------------
	{
		"info": {
			"_postman_id": "975739c7-1061-480a-b9c1-5f866e05984a",
			"name": "JWT",
			"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
			"_exporter_id": "1870481"
		},
		"item": [
			{
				"name": "https://d-dev-hub--jwttarget.sandbox.my.salesforce.com/services/oauth2/token",
				"request": {
					"method": "POST",
					"header": [],
					"body": {
						"mode": "urlencoded",
						"urlencoded": [
							{
								"key": "grant_type",
								"value": "urn:ietf:params:oauth:grant-type:jwt-bearer",
								"type": "text"
							},
							{
								"key": "assertion",
								"value": "eyJhbGciOiJSUzI1NiJ9.eyJpc3MiOiIzTVZHOW9adEZDVld1U3dPSkhPaXFjWk9aVGk0YXo4cF9mc2lJVUtSUTZ3UWpQMHlMVThVdEFqWVJ0THVubVFxVkVMX21tem1wcWhVZGtWZ3phTlA4Iiwic3ViIjoicHJhZGVla3VtYXJAZGVsb2l0dGUuY29tLmRldmh1Yi5qd3R0YXJnZXQiLCJhdWQiOiJodHRwczovL3Rlc3Quc2FsZXNmb3JjZS5jb20iLCJleHAiOiIxNzAzOTgwODAwIn0.gOOmT2dbrZqBhqjCEzOu4C-lL6vC8Mibb13Rcj20ZsKxT28XWhS9u2Wc4rlxi2h4DisfMiowFqx3ofuikaYUcWjocWGx2LCbm1QjMkKNUyDvLAgwaYf8VbdChR5JKu0tiJIdy4gkOUPMkLBmIPiw-ok1GZh-KSyCxsCbD-TFmZZwhwHU6C2I7HTREei19pQbCuGM8HGNQ9COaxjq5n-v-I7wCL5SpA99-G8UCk4ZmV-9_47prekBt0SbhNX7pw7k_UEMF_vS-xWwW7rcNdsfUXfat1g7XSn9Y4Ws99VrTyBTLFbkmC9ThgU9RrySLYf2cXSV4wUF72VtI2CvpxTFTw",
								"type": "text"
							}
						]
					},
					"url": {
						"raw": "https://d-dev-hub--jwttarget.sandbox.my.salesforce.com/services/oauth2/token",
						"protocol": "https",
						"host": [
							"d-dev-hub--jwttarget",
							"sandbox",
							"my",
							"salesforce",
							"com"
						],
						"path": [
							"services",
							"oauth2",
							"token"
						]
					}
				},
				"response": []
			}
		]
	}
	----------------------------------------------------------------------------------------------------
	
