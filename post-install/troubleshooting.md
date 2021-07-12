# ❌ Troubleshooting

Did you run into a problem whilst installing HytoraCloud? Well, if yes, that's sad. If there is no fix for your problem in this guide, please consider opening a GitHub issue or joining our discord server.

### Problem: Java not found

If this error occurs, you most likely didn't install Java. 

#### Fix

Please follow [this guide](../install/installing-java.md) in order to install Java.



### Problem: Screen not found

If this error occurs, you most likely forgot to install `screen` on your system. 

#### Fix

Run the following command in your terminal:

```text
$ sudo apt-get install screen
```

### 

### Problem: NullPointerException on startup

The reason for this error is that you most likely didn't read the guide + didn't follow the instructions the setup gave you and enabled auto-updater anyway. 

#### Fix

Open `local/config.json` using the editor of your choice and set `autoUpdater` to `false`.

