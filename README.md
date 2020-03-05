Conwayste Cross-Compiling Docker files
=================================

(making custom Docker images for cross, used by our CI)[https://github.com/rust-embedded/cross#custom-docker-images]

    $ TAG=aaronm04/cross:x86_64-unknown-linux-gnu    # change the part after the colon according to .travis.yml matrix
    $ cd linux
    $ docker build -t $TAG .
    $ docker push $TAG
