# go-messenger

A messenger application written in GO with two components. A RESTful user component for registering and tracking users and a real-time chat component.
# go-messenger
# go-messenger

Run steps:

cd build/1.8/
docker build -t go-messenger .
docker run --rm -it -v $PWD:/go/src/github.com/leoncaiau912/go-messenger -e SOURCE_PATH=github.com/kardianos/govendor go-messenger
