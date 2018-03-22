# envoy-binaries
Binaries for envoy

## Example in Ansible

```
- name: Download binary
  get_url:
    url: https://github.com/shaicoleman/envoy-binaries/raw/master/envoy-1.6.0-xenial-amd64
    dest: /usr/local/bin/envoy
    mode: 0755
    owner: root
    group: root
    checksum: sha256:d3d3326072c4ee894c60aaf64cf0a3b80d13d7ef7a07f50be542b696cc526471
```
