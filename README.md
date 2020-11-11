# y2util
golang常用封装
###配置相关叙述
```text
 使用聚合数据库（建议使用,准确率高）
         * ip相关db库更新地址
         * 库地址 https://github.com/lionsoul2014/ip2region
         * ip2region的数据聚合自以下服务商的开放API或者数据(升级程序每秒请求次数2到4次):
         * 01, >80%, 淘宝IP地址库, http://ip.taobao.com/
         * 02, ≈10%, GeoIP, https://geoip.com/
         * 03, ≈2%, 纯真IP库, http://www.cz88.net/
 * 查询ip 使用纯真IP库
          * jsdelivr    https://cdn.jsdelivr.net/npm/qqwry.ipdb/qqwry.ipdb
          * unpkg    https://unpkg.com/qqwry.ipdb/qqwry.ipdb
```