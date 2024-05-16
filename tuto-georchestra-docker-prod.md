# Tuto : deploy georchestra with docker, on production

Here, we are going to explain how to adapt the dockercomposition offered byt the georchestra community, to run it on production.
This is probably still not really a production-ready deployment, but will work on a remote server, with a custom domain and SSL certificate.

## Step 1: Clone the official repo

```bash
git clone --recurse-submodules https://github.com/georchestra/docker.git
cd docker
git checkout 23.0 && git submodule update
```

# Step 2: