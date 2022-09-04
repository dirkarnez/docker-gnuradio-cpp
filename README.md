docker-gnuradio-cpp
===================
using `bistromath/gnuradio`

### Notes
- gnuradio is located in `/opt/gnuradio` - build using cmake
    - ```
      cmake -G"Unix Makefiles" -DCMAKE_BUILD_TYPE=Debug -B./build 
      cmake --build .
      ```

### Other images
- [git-artes/docker-gnuradio](https://github.com/git-artes/docker-gnuradio)