# convertor

    docker build -t convertor

## to run the container
    docker run -v $PWD/images:/app/images -v $PWD/output:/app/output -e PDF_NAME=yael convertor images
