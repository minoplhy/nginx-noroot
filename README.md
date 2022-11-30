# NGINX without Root
This is a mini project that I'll find any workaround for building NGINX without relies on Root Required Dependencies as much as possible

The main point of the project is to configure Nginx to just work without root. So many modules are missing, but you can add them yourself.

# Setup Script

### using Curl
```
curl https://raw.githubusercontent.com/minoplhy/nginx-noroot/main/build.sh | bash
```

### using Wget
```
wget https://raw.githubusercontent.com/minoplhy/nginx-noroot/main/build.sh
chmod +x build.sh && ./build.sh
```