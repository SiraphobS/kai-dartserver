FROM dart:stable

COPY . /dart-server

WORKDIR /dart-server

RUN dart compile exe ./bin/dart_server.dart -o ./build/dartserve

CMD ["./build/dartserve"]
