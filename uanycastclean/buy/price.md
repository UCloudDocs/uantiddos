

# 产品定价

全球清洗为预付费模式。

### AnycastEIP地址费用

AnycastEIP的计费模式为预付费保底+弹性按小时后付费，计费周期为按小时,保底带宽与弹性带宽的价格均为0.21元/小时/Mbps。弹性带宽峰值最大为保底带宽的5倍，若实际业务流量超过弹性带宽峰值则会做限速处理。AnycastEIP默认支持全球2Gbps的防护能力。

### Anycast防护包

#### 企业版

每个防护包可以防护1小时的攻击。EIP被攻击，则开始消耗防护包时间，按秒计算。防护包消耗完后，支持自动续包。防护包的售价为5000元/个。防护包将在购买后一个月自动到期，如果没开启自动续费anycastEIP将被黑洞。

#### 免费版

免费版防护包可以[可防护Region](https://docs.ucloud.cn/uantiddos/uanycastclean/intro/limit)创建ULB、Uhost资源时选择开启DDoS攻击防护获取。使用方式和功能与企业版没有区别，<u>主要区别如下：</u>


***免费版全球清洗作为体验性产品提供，每账号仅可创建一个免费的防护包***

***免费版防护包不支持续费，防护时长使用完毕、或者到期后anycastEIP将被黑洞且强制解绑回收***

***免费版仅提供50G防护，攻击流量超过50G anycastEIP将被黑洞***




### 计费示例

购买一个全球清洗防护包，AnycastEIP带宽设置为1Mbps，则AnycastEIP月单价为1Mbps\*0.21元／Mbps\*30\*24=151.2元。防护包价格为5000元，合计5151.2元。

