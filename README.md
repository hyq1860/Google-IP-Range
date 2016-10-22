# Google-IP-Range
一个超大的 Google 全球 IP 扫描范围库

## 来源 

>- [XX-net/XX-Net](https://github.com/XX-net/XX-Net/blob/master/code/default/gae_proxy/local/ip_range.txt)
>- [PeerXu/google-ip-explorer](https://github.com/PeerXu/google-ip-explorer/blob/master/input.txt)
>- [out0fmemory/GoAgent-Always-Available/local/gscan/my.conf](https://github.com/out0fmemory/GoAgent-Always-Available/blob/master/local/gscan/my.conf)
>- [out0fmemory/GoAgent-Always-Available/googleip.txt](https://github.com/out0fmemory/GoAgent-Always-Available/blob/master/googleip.txt)
>- [peqing/GoogleIPRange](https://github.com/peqing/GoogleIPRange/blob/master/googleip.txt)
>- [CNMan/GoogleIPRange](https://github.com/CNMan/GoogleIPRange/blob/master/nogoogleip.txt)
>- [红领巾](http://honglingjin.ga/)(此网站取得的 IP 全部补全为 /24 )


*(来源统计不完全)*

使用 [xyuanmu/checkiptools](https://github.com/xyuanmu/checkiptools/) 进行简单整合，极少部分 IP 人工处理 (太多了……)。 

## 详情
- ip_range_big.txt 共有205W个IP，**不再更新**。  
- ip_range_large.txt 共有332W个IP，包括 ip_range_big.txt 的所有IP段，**随着时间推移可能改变所有者的IP段可能较多**。会抽时间更新。    

不会补充更多类型的 IP 库。

## 效果
*(因人而异)*
- 可用 IP 数量增加
- 延迟减小
- 抗封锁能力增强
- 速度改善

以上效果仅限低调使用时生效。  
**请务必低调使用。**

## 使用方法
### XX-Net
1. 
  + 在 [XX-Net 的高级设置](http://127.0.0.1:8085/?module=gae_proxy&menu=advanced)中替换 IP 段列表并保存  

	或者

 + 重命名为 ip_range.txt ，放到 data/gaeproxy/ 
2. 
 + 重启  XX-Net 
3. 
 + XX-Net 会自动开始扫描新的列表 
4. 
 + *(可选)初次使用扫描线程可以设为 200 左右扫描 12 - 24 小时* 
 + 日常使用可以设为 50 左右或更低  

### 其他
#### 扫描工具
1. 
 - 导入到扫描列表 
2. 
 - *(可选)设置最大延时为 800ms 以保证质量；或 2000ms 以保证数量* 
 - 扫描，耐心等待结束 

#### 带扫描功能的翻墙工具
1. 
 - 导入到扫描列表，而不是可用的 IP 列表，保存。  
2. 
 - 重启翻墙工具  
3. 
 - *(可选)设置最大延时为 800ms 以保证质量；或 2000ms 以保证数量*  
 - 自动开始扫描，或手动开始  
4. 
 - *(可选)初次使用可以设置扫描线程为 200 左右扫描 12 - 24 小时*  
 - 日常使用可以设为 50 左右或更低  

## 注意事项
1. **请低调使用。**
2. **请低调使用。**
3. **请低调使用。**
4. 此**并非现成的可用 IP** ，而是由 Google *现在/曾经/可能* 所拥有的 IP 的集合，需要配合扫描使用。
5. **扫描及翻墙时关闭国产杀毒软件/安全软件**，特别是 360 全系软件，此类软件可能会自动上报 IP 地址到 GFW，导致可用 IP 减少。
6. **不要使用国产浏览器翻墙**，理由同上，否则再大的 IP 库都救不了你。╭(╯^╰)╮
7. 关闭杀毒软件就担心中毒的话，可以**换用国外的杀毒软件**。
8. 无论如何，最好**不要用国产杀毒软件**。
9. 因内含 IP 非常多，使用效果可能需要较长时间显现。
