

# 配置防护包策略

购买完防护包后，需要到安全策略管理标签页里去配置防护包的各项安全策略，具体步骤：在左上角下拉框中选中防护包—>在需要配置机房的那一列右边点击编辑按钮:
![](/images/uanycastclean/配置防护包策略.png)

## 策略编辑
进入编辑策略页面后，需要对会有不同的阈值根据业务进行针对性的配置，如果对自身业务不是很确认，建议保留默认阈值：
![](/images/uanycastclean/策略编辑.png)

- **机房**：当前编辑策略的机房。
- **IP封堵**：是否需要直接封堵所有流量，默认为不封堵。
- **IP封堵阈值（Mbps）**：指该机房提供的防护能力。
- **UDP封堵**：是否需要直接封堵UDP流量，默认为不封堵。
- **UDP清洗阈值（pps）**：指UDP包量超过阈值会被自动拉入清洗，默认是3wpps。
- **ICMP封堵**：是否需要直接封堵ICMP流量，默认为不封堵。
- **ICMP清洗阈值（pps）**：指ICMP包量超过阈值会被自动拉入清洗，默认是1wpps。
- **TCP Ack清洗阈值（pps）**：指Ack包量超过阈值会被自动拉入清洗，默认是3wpps。
- **TCP Syn清洗阈值（pps）**：指Syn包量超过阈值会被自动拉入清洗，默认是1.5wpps。

## 策略模板管理
对于已经固定的策略模板，可以将当前防护包的策略一键同步至其他防护包，具体操作步骤：点击同步策略策略至其他防护包按钮—>勾选需要同步的防护包—>点击确认。
![](/images/uanycastclean/策略模板管理.png)






