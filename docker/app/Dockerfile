from node

RUN apt-get update && apt-get install -y default-jdk-headless

USER node

RUN mkdir /home/node/app
WORKDIR /home/node/app

ENV ANDROID_HOME=/home/node/Android/Sdk
ENV PATH=$ANDROID_HOME/emulator:$ANDROID_HOME/tools:$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH
