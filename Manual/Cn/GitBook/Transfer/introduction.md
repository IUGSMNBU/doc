EasySwoole 是一款基于Swoole Server 开发的常驻内存型PHP框架，专为API而生，摆脱传统PHP运行模式在进程唤起和文件加载上带来的性能损失。EasySwoole 高度封装了Swoole Server 而依旧维持Swoole Server 原有特性，支持同时混合监听HTTP、自定义TCP、UDP协议，让开发者以最低的学习成本和精力编写出多进程，可异步，高可用的应用服务。

虽然说easySwoole是专为API而生的框架，但这并不妨碍我们将他作为一个全站框架，提供像ThinkPHP和Laravel一样的只需要专注业务的开发体验，本手记篇幅较长，详细的介绍了如何将其他框架的一些业务组件移植到easySwoole，在保持原有开发习惯不做太大改变的情况下享受到easySwoole提供的超高效率HTTP服务