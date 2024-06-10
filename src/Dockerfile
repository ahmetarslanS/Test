# Image olarak Java runtime kullanma

FROM openjdk:11

# Containerin icinde working directory tanimlama

WORKDIR /usr/src/myapp

# Current directory icerigini olusturdugumuz directorye kopyalama

COPY . /usr/src/myapp

# Compile etme

RUN javac Main.java

# Container basladiginda .java dosyasini calistirma

CMD ["java", "Main"]
