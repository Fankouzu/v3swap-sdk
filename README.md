# V3swap SDK

修改了`class Pool`,通过前端传入`FACTORY_ADDRESS`和`POOL_INIT_CODE_HASH`来计算Pool合约地址

在uniswap的前端中通过`npm remove @uniswap/v3-sdk`删除原版uniswap v3 sdk

然后在前端目录中运行`npm install v3swap-sdk`安装本项目

之后修改前端对应的`new Pool()`和`computePoolAddress()`函数