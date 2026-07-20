# Clash-Verge自用全局拓展脚本、yaml文件、规则集

目前收录：
<br>
1、俄网playground mod网站
<br>


更新日志：
<br>
2026.7.18更新多机场自用yaml文件，可将多个订阅机场节点整合，无需全局拓展脚本（请将全局拓展改为clashverge默认配置）
<br>
2026.7.20更新AI代理组和规则组为chatgpt和gemini，方便自用（一个用美国，一个用香港）
<br>


clashverge官网全局拓展默认配置（以防万一可以备份一下）：
<br>
// 国内DNS服务器<br>
const domesticNameservers = [<br>
  "https://223.5.5.5/dns-query", // 阿里DoH<br>
  "https://doh.pub/dns-query" // 腾讯DoH<br>
];<br>
// 程序入口<br>
function main(config) {<br>
  // 默认不进行任何配置覆盖，直接返回原配置<br>
  return config;<br>
}
