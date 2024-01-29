# DTunnelProxyServerRelease
### DTunnelProxy C++
```sh
{
    rm -f /usr/bin/main /usr/bin/proxy
    curl -s -L -o /usr/bin/main https://github.com/DTunnel0/DTunnelProxyServerRelease/raw/main/$(uname -i)/main
    curl -s -L -o /usr/bin/proxy https://github.com/DTunnel0/DTunnelProxyServerRelease/raw/main/$(uname -i)/proxy
    chmod +x /usr/bin/main /usr/bin/proxy
    clear && echo -e "\033[1;31mExecute: \033[1;32mmain\033[0m"
}
```
### DTunnelProxy GO
```sh
{
    rm -f /usr/bin/main /usr/bin/proxy
    curl -s -L -o /usr/bin/main https://github.com/DTunnel0/DTunnelProxyServerRelease/raw/main/$(uname -i)/main
    curl -s -L -o /usr/bin/proxy https://github.com/DTunnel0/DTunnelProxyServerRelease/raw/main/build/proxy
    chmod +x /usr/bin/main /usr/bin/proxy
    clear && echo -e "\033[1;31mExecute: \033[1;32mmain\033[0m"
}
```
