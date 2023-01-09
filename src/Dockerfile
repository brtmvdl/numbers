FROM tmvdl/android:cordova

WORKDIR /app

RUN cordova create numbers com.brtmvdl.numbers numbers

WORKDIR /app/numbers

COPY app www

RUN cordova platform add android

RUN cordova build android
