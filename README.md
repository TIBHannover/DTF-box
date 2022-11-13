# DTF-box

Perform the following steps in the terminal (Linux / macOS) or in the GitBash (Windows).

```
git clone https://github.com/TIBHannover/DTF-box.git
cd DTF-box
vagrant up
```

When the installation is complete (a few minutes, depending on the download speed), application can be opened in the browser

For Dev:

<http://192.168.56.111:4000/>


For changes - the env vars at `ansible/vars/main.yml` can be modified. Example -  

```
env: "prod" | "dev" 
```
