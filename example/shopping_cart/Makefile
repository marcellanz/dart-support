image=sleipnir/cloudstate-dart-shoppingcart:0.5.5

.PHONY: all clean

all: build install

run:

	dart bin/main.dart

build:

	docker build -t ${image} . 

install:

	docker push ${image}

	
