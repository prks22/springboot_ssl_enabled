# springboot_ssl_enabled

This project describes how to enable http and https both togather in springboot application.
1.Config.java provides the basic configuration for http with https which enabled http request for you
2. by providing certian entry in application.properties open https for you.
3.To generate certificate do following step.
      1.Generate certificate
      keytool -genkey -alias tomcat -storetype PKCS12 -keyalg RSA -keysize 2048 -keystore C:\Users\keystore.p12 -validity 3650

      2. Verify your certificate
      keytool -list -v -keystore C:\Users\keystore.p12 -storetype PKCS12
      
4. Now for adding the certificate in crom browser follow below step.
       1 Chrome Settings > Show advanced settings > HTTPS/SSL >Intermidiate certificate Authurity tab.
       2. import your certificate.
       
       
 5. Start the browsing your sit..
 
 
