# Clash-Verge自用全局拓展脚本、yaml文件、规则集
目前收录：
1、俄网playground mod网站

更新日志：
2026.7.18更新多机场自用yaml文件，可将多个订阅机场节点整合，无需全局拓展脚本（请将全局拓展改为clashverge默认配置）

clashverge官网全局拓展默认配置（以防万一可以备份一下）：

// 国内DNS服务器
const domesticNameservers = [

  "https://223.5.5.5/dns-query", // 阿里DoH

  "https://doh.pub/dns-query" // 腾讯DoH
];

// 程序入口
function main(config) {

  // 默认不进行任何配置覆盖，直接返回原配置
  
  return config;

}
