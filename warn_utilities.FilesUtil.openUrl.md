#### ERROR: [warn] utilities.FilesUtil.openUrl 

[warn] Невозможно получить данные из https://URL
[warn] utilities.FilesUtil.openUrl
[warn] javax.net.ssl.SSLHandshakeException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target


keytool -import -alias my.avon.chain.pem -keystore "/usr/local/openjdk11/lib/security/cacerts" -file my.avon.chain.pem

( Enter keystore password:changeit ) 


