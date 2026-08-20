# com.hd.zhibo 升级切片

官方超级直播 APK 分片（每片 100KB）。客户端每天拉一次仓库根目录 `update.json`，按 `base_url` 下 `chunks/<version_code>/`。

- `update.json` — 当前版本、整包 md5/size、每片 name/md5/size
- `chunks/<version_code>/part-*.png` — 该数字版本的切片（后缀 png，内容仍是 APK 字节）
