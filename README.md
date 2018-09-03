
# F5 VPN client

## Setup

* Install Docker. **Important:** Do **not** use the packages provided by your
  distribution packages sources.
  Use the officical resources from docker: https://docs.docker.com/engine/installation/.
* Install required python packages:
  ```
  pip install -r requirements.txt
  ```

### Mac

* For automatic route setup on Mac you need to install ```iproute2mac``` via homebrew.


## Start F5 VPN client

There's a wrapper script (```f5fpy-client.py```) which helps to set up
the docker container, the VPN connection and the desired network routes.

Simple run:
```
./f5fpc-client.py <VPN_HOST> <USER>
```

For more information and options see
```
./f5fpc-client.py -h
```
