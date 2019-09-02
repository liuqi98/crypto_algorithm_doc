# crypto_algorithm_doc
本仓库存放了一些已经发布的密码算法说明文档，主要包括Hash函数、随机数发生器、消息认证码、分组密码、流密码、数字签名、公钥加密、密钥协商等。
# 目录结构
crypto_algorithm_doc
├── README.md                                     
├── Hash                                    
|   ├── MD2                                      
|   ├── MD4                              
|   ├── MD5                                        
│   └── SM3                              
├── RNG
└── END


├── build                                       // webpack配置文件
├── config                                      // 项目打包路径
├── elm                                         // 上线项目文件，放在服务器即可正常访问
├── screenshots                                 // 项目截图
├── src                                         // 源码目录
│   ├── components                              // 组件
│   │   ├── common                              // 公共组件
│   │   │   ├── alertTip.vue                    // 弹出框组件
│   │   │   ├── buyCart.vue                     // 购物车组件
│   │   │   ├── computeTime.vue                 // 倒计时组件
│   │   │   ├── loading.vue                     // 页面初始化加载数据的动画组件
│   │   │   ├── mixin.js                        // 组件混合(包括：指令-下拉加载更多，处理图片地址)
│   │   │   ├── ratingStar.vue                  // 评论的五颗星组件
│   │   │   └── shoplist.vue                    // msite和shop页面的餐馆列表公共组件
│   │   ├── footer
│   │   │   └── footGuide.vue                   // 底部公共组件
│   │   └── header
│   │       └── head.vue                        // 头部公共组件