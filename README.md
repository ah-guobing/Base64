# Base64
.NET与JAVA、PHP对Base64的实现

### JAVA
String str="yunzhang123";<br/>
String encode=Base64.getEncoder().encodeToString(str.getBytes("UTF-8"));<br/>
String decode=new String(Base64.getDecoder().decode(encode.getBytes("UTF-8")));<br/>
System.out.println(encode+"\r\n"+decode);

### PHP
$str='yunzhang123';<br />
$encode=base64_encode($str);<br />
$decode=base64_decode($encode);<br />
