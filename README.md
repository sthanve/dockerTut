# dockerTut
> wsl --install
> 
> install docker desktop
>
> docker -v
>
> docker run hello-world
>
> Install windows terminal from microsoft 
>
> docker images
> 
> Image pull : docker pull <image name>
>
> Search images : docker search <image name>
>
> Start container : docker run <image name>
                    docker run -a <image name>
                    docker run --name <name> -d <image name>
                    docker run --name <name> -it -d <image name> #interactive and detached mode
>
> View all container : docker ps -a OR docker ps
>
> Run python in docker
> 
> docker pull <image name>
>
>E:\docker_tut>docker run --name pycontainer -it -d python
> 
>2451cc3c068a40b1b2b6b1586aba8f2be7be3ce1ba942e541024aa1790806da5
> 
> E:\docker_tut>docker ps -a
> 
>CONTAINER ID   IMAGE         COMMAND     CREATED             STATUS                         PORTS     NAMES
> 
>2451cc3c068a   python        "python3"   44 seconds ago      Up 39 seconds                            pycontainer
> 
>0ccc09b913af   python        "python3"   50 minutes ago      Exited (0) 50 minutes ago                affectionate_johnson
> 
>5d754c44e471   hello-world   "/hello"    About an hour ago   Exited (0) About an hour ago             peaceful_saha

>E:\docker_tut>docker exec -it 2451cc3c068a python
>
>Python 3.13.0 (main, Nov 12 2024, 06:05:34) [GCC 12.2.0] on linux
>
>Type "help", "copyright", "credits" or "license" for more information.
>
> >>>
>
>

