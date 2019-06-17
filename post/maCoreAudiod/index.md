## Mac今天插入耳机后没有声音，但是还能调节音量与播放暂停

### 各种尝试后无果，Google了下，找到了如下命令：

```bash
sudo killall coreaudiod
```

### 完美解决。

