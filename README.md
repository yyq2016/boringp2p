# boringp2p
quic based iot media transport solution

基于开源quic代码实现iot音视频传输方案
功能包含:
    1. server端代码
    2. 客户端代码sdk及调用demo (linux/android/ios/windows)
    3. 三种传输模式 （p2p/relay/LAN)
    4. 传输任意数据 (短消息/音频/视频/others)

特征:
    1. 所有接入均认证和端到端传输加密 (安全是该方案最重要的基石)
    2. 最快加载体验 (quic特性)
    3. 弱网低时延 (quic特性)
    4. 基于带宽探测的拥塞控制 (quic特性)
    5. 客户端占用空间小(大概500KB左右)
    6. 客户端占用内存小(最大内存占用可由用户控制)
    7. 服务端架构提供可靠性保障(容错设计和负载均衡设计)
    8. 提供国际化支持
