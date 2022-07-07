# Keystore-for-jd2018

修补lenovoz5 在android12及以上在keystore的bug，此Bug会导致锁定屏幕密码无法使用/重启UI闪退等问题

# 注意：

请勿在其他系统刷入此补丁，可能会出奇奇怪怪的问题，请了解风险后使用

# 密码库源

\system\vendor 

Keystore Copyright by lenovo

# Ways to use

1.使用Recovery（如Twrp）刷入vendor分区

2.使用文件管理器将补丁目录下文件复制到手机system\vendor下相应位置即可

# 此补丁刷入后，不更换vendor镜像，将不会失效，如果android12启动后发生问题（如无sim卡，卡顿等）请清除data数据再试一次即可


