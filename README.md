#Application properties
    spring.application.name=ecommerce
    #Server Properties
    server.port=443
    #Database Configuration Properties
    spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_springboot?createDatabaseIfNotExist=true
    spring.datasource.username=root
    spring.datasource.password=root
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.show-sql=true
    spring.jpa.properties.hibernate.format_sql=true
    #Email Properties
    spring.mail.host=smtp.gmail.com
    spring.mail.port=587
    spring.mail.username=<Email>
    spring.mail.password=<App password>
    spring.mail.properties.mail.smtp.auth=true
    spring.mail.properties.mail.smtp.starttls.enable=true
    #Cloudinary Properties
    cloudinary.cloud_name=<cloudinary name>
    cloudinary.key=<key>
    cloudinary.secret=<secrect>
    #Razorpay Properties
    razorpay.key=rzp_test_f4vcAPoh0RDZfi
    razorpay.secret=jjblWSJ6F7NJuPUOtNmDjg4i
    #Admin Credentials
    admin.email=admin
    admin.password=admin
    #For redirect to work 
    server.forward-headers-strategy=FRAMEWORK
    #For not checking while saving in DB
    spring.jpa.properties.javax.persistence.validation.mode=none
    # HTTPS
    server.ssl.key-store-type=PKCS12
    server.ssl.key-store=classpath:/security.p12
    server.ssl.key-store-password=saish123
    server.ssl.key-alias=saish
    server.ssl.enabled=true
    spring.servlet.multipart.max-file-size=50MB
    spring.servlet.multipart.max-request-size=50MB
