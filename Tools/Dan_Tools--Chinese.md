
@[TOC](文章目录)

---

# 前言
在虚幻引擎工作过程中，进行项目时经常会进行重复性功能制作，或者项目越来越大不知道怎么优化。为了提升工作效率和快速优化项目，Dan--Tools开发编辑器工具应需求而生。有了它可以快速进行模型，贴图，关卡，图层，标签等功能操作。

---



# 一、Dan--Tools是什么？

Dan--Tools 是一款可以在**虚幻引擎5.3**及以上版本中使用的编辑器工具，该工具集合了工作中经常使用的操作功能。

![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/99c2c6d6d1d84b399beea111953c7d21.png)


# 二、如何运行
## 1.安装位置
将该插件放入到工程下Plugins中（没有文件就创建一个）

![请添加图片描述](https://i-blog.csdnimg.cn/direct/787640bcdda9442d8e22bb1a6656df9f.png)


## 2.引擎中位置

![请添加图片描述](https://i-blog.csdnimg.cn/direct/d265f41496b4457cb3c8a985ab4b90bb.png)
## 3.引擎中使用
右键MY_Tools点击运行编辑器工具控件
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a911d49182e94b65893e8010c1f33128.png)
点击后移动到界面框上固定
![请添加图片描述](https://i-blog.csdnimg.cn/direct/69525ae058bb497ca4a402afda2732fb.png)
# 三、界面展示
## 1.模型篇
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ce020b93c2fc488996c058536dd9022d.png)
## 2.材质篇

 ![请添加图片描述](https://i-blog.csdnimg.cn/direct/4700e742d43e4152abf8aae21b3dcf7a.png)
## 3.蓝图篇
![请添加图片描述](https://i-blog.csdnimg.cn/direct/4c867f69f60d40ca850771f6e5d1feb2.png)
## 4.文字篇
![请添加图片描述](https://i-blog.csdnimg.cn/direct/9c4133ceecd141ceb58c94f88cb8c58c.png)
## 5.优化篇
![请添加图片描述](https://i-blog.csdnimg.cn/direct/4e00d46f7622406fbfa79e7634d5fad9.png)
## 6.其它篇
![请添加图片描述](https://i-blog.csdnimg.cn/direct/0063fadd61fe46e281661c9858aad621.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/f7d9841ed1364af98207f6eb2ff06d2c.png)

# 四、使用说明
## 1.模型篇

 1.移动性
 批量选择模型选择类型，点击![请添加图片描述](https://i-blog.csdnimg.cn/direct/a8e5eafb56614951947a88060663d174.png)

 2.一键贴地
 开始位置
![请添加图片描述](https://i-blog.csdnimg.cn/direct/d533bacd28da443cb38560d723738eb3.png)
贴地后位置，模型旋转不影响贴地
![请添加图片描述](https://i-blog.csdnimg.cn/direct/0434e26ee4624a1caedc4185ef9b27ad.png)


 3.修改轴位置（**注意事项修改轴时先居中在进行其它轴位置修改**，修改是不会改变场景其它模型位置的）
 修改前
![请添加图片描述](https://i-blog.csdnimg.cn/direct/95985c6de015474bb6fa6b538990d503.png)
修改后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/50c18ce58732419eb990cd1460b9fdb5.png)


 4.法线重计算
选择模型点击法线重计算，可以解决大部分法线问题

 5.添加细分曲面（增加面数，添加细节）
 添加前
![请添加图片描述](https://i-blog.csdnimg.cn/direct/2ece3115b3ad4219b3d10e025206ba58.png)
添加后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/67d039dea3d442318fd994b5c90fce61.png)


 6.设置模型LOD组
 前
![请添加图片描述](https://i-blog.csdnimg.cn/direct/152f232191474eedad37e673ad465e49.png)
后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/b82074f4035a441e9727bc88f41e9d2e.png)

 7.模型碰撞（需模型碰撞复杂度改为项目默认才生效，Alt+c可显示碰撞）
 ![请添加图片描述](https://i-blog.csdnimg.cn/direct/8ea310d83d67453f87e0532f018bd5eb.png)

 添加碰撞
![请添加图片描述](https://i-blog.csdnimg.cn/direct/db8d5f6baf1c469f83a7427e53c50ac6.png)
移除碰撞
![请添加图片描述](https://i-blog.csdnimg.cn/direct/d78e499753424610b4be20169e90004f.png)
效果展示
![请添加图片描述](https://i-blog.csdnimg.cn/direct/5170cfb5da87453f9214f0dd9397bcfd.png)


 8.模型随机旋转
 ![请添加图片描述](https://i-blog.csdnimg.cn/direct/1f433522444748759481501650d1ffb1.png)


 9.投射阴影
 阴影开![请添加图片描述](https://i-blog.csdnimg.cn/direct/59ccb6bcf66345ff95fd8ea9115c9295.png)
阴影关
![请添加图片描述](https://i-blog.csdnimg.cn/direct/66c9ac404578403d9663c52534327b15.png)


 
 10.碰撞已启用
 开始为无碰撞![请添加图片描述](https://i-blog.csdnimg.cn/direct/74d4370841f84a1bbf6962cad6424508.png)
 修改后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/9673217da9ec445c95907f121927b1d1.png)



 11.批量模型附加
 现先选择场景中的模型作为被附加对象![请添加图片描述](https://i-blog.csdnimg.cn/direct/6121f55115d248cc9708613ac1d81c8a.png)
批量选择需附加的对象点击一键附加
![请添加图片描述](https://i-blog.csdnimg.cn/direct/116a0167f9854551947b546d0118dc95.png)


 12.一键更改模型
 先将需修改的模型和修改后的模型放入到Old Mesh和New Mesh中![请添加图片描述](https://i-blog.csdnimg.cn/direct/637de7de329144b988055809cd3194d8.png)

批量选择场景中的模型（如果场景中所选模型包含Old Mesh就都会被修改）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/0853c23f94e94842b183f9e883949157.png)

更多功能请看  https://space.bilibili.com/344860590
 
  

## 2.材质篇

 1.修改材质
 先查看模型的材质，添加需要替换的材质和新材质，批量选择模型后点击更改（仅覆层）![请添加图片描述](https://i-blog.csdnimg.cn/direct/32076d6b22204498ac2218d3b03c0f63.png)替换后源模型的材质没更改，场景中的模型材质更改了![请添加图片描述](https://i-blog.csdnimg.cn/direct/d7a4528847a442ae986ac2fd61dda463.png)
源材质修改前
![请添加图片描述](https://i-blog.csdnimg.cn/direct/30d0f2b59dc44efa8af417b98513cddb.png)
修改后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ae2e14d698904ee9b0eb3e6f4e0c1ca1.png)

 2.一键生成材质
 不选择文件夹直接点击一键生成材质（会寻找所有的贴图位置来生成材质）
 ![请添加图片描述](https://i-blog.csdnimg.cn/direct/60c9b81632cf4679bf48c8398ba04e8f.png)
选择了某个贴图的文件夹位置（会在当前选择的位置搜索贴图生成PBR材质）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/e9de287d7b434b80babf6931b56974cf.png)
生成结果展示
![请添加图片描述](https://i-blog.csdnimg.cn/direct/330af291cafc4a87ac2f337d032b9549.png)



更多功能请看  [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)
## 3.蓝图篇
1.蓝图生成替换
选择蓝图actor
![请添加图片描述](https://i-blog.csdnimg.cn/direct/24cdfb3a79de4568b3ee2b3b62a1e325.png)
蓝图替换（会删除选择的模型变成蓝图actor）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/bcc9b68aed594718b986654013c04e79.png)
蓝图生成（不会删除选择的模型）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/5543195ec47a4c389c56cb713d629d52.png)
2.蓝图生成附加（将蓝图actor生成后附加到模型上）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/267b53431b164dbb9cb8eeae69d8f56b.png)




更多功能请看  [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)
## 4.文字篇
1.批量标签操作
标签操作（展示功能）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a82b1be753114316bef0c64465949d89.png)
添加前（无标签）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/2e7848afa13b4c6e908f6bee20ad7291.png)


添加标签
![请添加图片描述](https://i-blog.csdnimg.cn/direct/8509cae544f54197aab70e3371596ae1.png)
添加后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/eb4e448759c840778de8639d7a5b2e5e.png)
标签替换
![请添加图片描述](https://i-blog.csdnimg.cn/direct/cbdc08ae19bc4382afb7dc801e2ff69a.png)
替换后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a67e8bc2d433490a814e800efb21bb9d.png)
2.浏览器类型命名
先选择浏览器中的资产

![请添加图片描述](https://i-blog.csdnimg.cn/direct/96a55046da1a46d2ac20ef75adf11ad9.png)
点击浏览器类型命名--命名后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/25670bb97a014bf8b301365c73e9332b.png)
3.编辑器内容命名（选择需要重命名actor）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/06f803c63caf4c789aa13a6c4e5e9b6f.png)
输入重命名名称
![请添加图片描述](https://i-blog.csdnimg.cn/direct/afa0bdac5e3d4a2d898fd4f73a0ebf8f.png)
重命名完成自动带序号后缀
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ff4e50fbb72a4cf39d65cb9ffb8926b4.png)




更多功能请看  [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)
## 5.优化篇
1.一键Nanite
先选择编辑器中的模型（现在该资产模型Nanite为关闭）![请添加图片描述](https://i-blog.csdnimg.cn/direct/1fc0d668cba64f7db5a992a14f4e96c7.png)
选择为启用点击按钮（现在为开启）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fc720c132eb340349f290fa9d7dcb8e4.png)
2.设置最大纹理（可批量选择贴图资产）
修改前为2048
![请添加图片描述](https://i-blog.csdnimg.cn/direct/4e71b85f1d8f4f7794208a7aa4546872.png)
修改后为512
![请添加图片描述](https://i-blog.csdnimg.cn/direct/8fabfec44ed842d0b8ee306ba8618cfb.png)
3.纹理偏移Lod（使用该功能前贴图MipMap必须为来自纹理组）

![请添加图片描述](https://i-blog.csdnimg.cn/direct/3be890cc38994c89b2289e7b2558bf50.png)
点击前
![请添加图片描述](https://i-blog.csdnimg.cn/direct/a95d9d570dfe4c7e8816625212c9825a.png)
点击后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/9e1b86b59870405d9d2b902a96aafb13.png)
4.MipMap切换
切换前
![请添加图片描述](https://i-blog.csdnimg.cn/direct/30c391b1714e45ae83fcdf9ae003a2ab.png)
切换后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/17120e8d5c5840689f8374b81fc7acf8.png)
5.一键减面
先选择需减面的模型（现在为3072面）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/0cf2331d64dc462ba3ec740340b27f47.png)
点击减面后（现在为1536）![请添加图片描述](https://i-blog.csdnimg.cn/direct/13c17dd8733843098bf1bcf56a24cb9e.png)
6.删除空文件
现在这里有路径文件111和222都是没内容的文件
![请添加图片描述](https://i-blog.csdnimg.cn/direct/8882451df2d3466ca3f5bf4c255c192a.png)
点击删除文件夹（会自动寻找项目中的空文件例如现在的111/222）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/02c25eef8ae5429e80c744a0aa0b95ba.png)
点击确定后删除后（111下的222删除了）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/7a8a211b4cc444d3b93e910bad3fb7bf.png)
7.删除未引用
先选择内容浏览器中的资产然后点击删除未引用
![请添加图片描述](https://i-blog.csdnimg.cn/direct/7e8b80824b8d45d681b4022cd9ef9950.png)
移除未引用后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/edf7d77359ae43a0ac67597c62191add.png)
未引用上锁（给资产加锁就无法删除了）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/5559a99773944fb09406b2cc678855f1.png)
8.光线通道
选择大纲里的模型（现在为通道0开）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/559769d55a7e40369d6d349026eca905.png)
点击修改后（现在为通道1开）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c862eb4e2b854c47a574bb25444fc4e0.png)
9.一键隐藏
批量选择模型（现在在游戏中隐藏为False）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/4c59879d0bbb41a2a3ebb9929f0bb03d.png)
选择功能点击后（现在为ture）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/1dbe07e363624ebeb4c12555eba21b80.png)
现在我想恢复场景中被隐藏的模型改为False（不用选择那些被隐藏的模型随意选择一个）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/562f2757feae48e4ac7b73716f029a3a.png)
点击后（模型显示出来了）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/98278afe3966461eb765c9c5008fb72e.png)
10.修复纹理压缩
选择内容浏览器中的贴图资产（比如现在的默认贴图压缩设置为灰度,SRGB为False肯定是错误的）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/0a5ef97096474696b27e1e812d955ff6.png)
点击按钮修复后（改为了默认正确选项）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/5940b2731ee7455685e97d8a691dcc8b.png)





更多功能请看  [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)
## 6.其它篇
1.独显actor
先选择需要独显的actor
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fd1f34a191384381b4f098a2b55d819b.png)
独显后（按Ctrl+H或者Ctrl+Z可以重新全部显示）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/aa44805ff6044767ba3d50d9c8ca14bf.png)
2.一键导航网格体
先选择需要添加导航网格体的模型
![请添加图片描述](https://i-blog.csdnimg.cn/direct/f5f7a84c8b1440df83bd6025b72be670.png)
添加后（然后移动下NavMeshBoundsVolume，就能正常加载了绿色部分就是导航路径需按P显示）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c91e3e66a3bc460cbeccfb9f668bb4dc.png)
3.更改当前语言（可中英切换）
中文![请添加图片描述](https://i-blog.csdnimg.cn/direct/4610e0428f2a492e94f838a70ac0366e.png)
英文
![请添加图片描述](https://i-blog.csdnimg.cn/direct/43bf69f9d1bd43bc9ad1ce81bad6cb05.png)4.创建文件夹（在内容浏览器中创建）
先选择需要创建文件夹的位置（例如现在的1中）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ab8b1f36400e448f9b2c70ebea6fffe7.png)
点击创建文件夹按钮（自动识别所选路径提示添加的文件夹，若需修改文件夹请在相关功能中修改）![请添加图片描述](https://i-blog.csdnimg.cn/direct/a03ffffd700c453f891cd6ce91f005a3.png)
添加后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fb96a57ba4524b7abc1568c226093b45.png)
5.点击移入文件夹
先选择大纲中的模型并输入文件夹名称
![请添加图片描述](https://i-blog.csdnimg.cn/direct/742266d203b2449c9e45f544983d6246.png)
移入后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/e8dfce4770ea48528ed4d1c82137d085.png)
6.图层创建与导入
先选择模型（现在无图层），输入图层名称
![请添加图片描述](https://i-blog.csdnimg.cn/direct/fc706eef16904404acbb3cf080e0bb8d.png)
创建导入后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/5ffb900fa9564b2c8616e30b0abc8c7c.png)
移除当前图层（选择模型选择图层名称点击按钮）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/df316cfef9394ca1a4857835874ae9fc.png)

7.在当前视觉位置生成
先选择需生成的类型
![请添加图片描述](https://i-blog.csdnimg.cn/direct/ab79dce0460b4f59926d0ca3f19c9ec4.png)
生成后（在之前视角位置生成了个摄像机）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/be5c3f8d85664d45815decdf0f48e0e2.png)
8.一键生成控制器（围绕选择的模型生成个视角）
将模型的位置给控制器作为中心点
![请添加图片描述](https://i-blog.csdnimg.cn/direct/b5f25603540d4c138468db54729080a8.png)
测试先将控制器的自动控制玩家改为玩家0
![请添加图片描述](https://i-blog.csdnimg.cn/direct/3f01e9375bce432397f61f0d892db4f7.png)
运行游戏可以围绕改模型进行旋转，移动，视角远近切换等操作
![请添加图片描述](https://i-blog.csdnimg.cn/direct/f6b49fd3446d4d6ca48c99d25e76e226.png)
9.一键创建时间锁
输入时间锁日期点击创建（到时间后自动关闭游戏）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/dd20b38eb23f4b57a04f038b4aafb58a.png)
10.截屏当前视图
当前视角位置
![请添加图片描述](https://i-blog.csdnimg.cn/direct/4fd218d54e044c24b9c2dd8585af697e.png)
点击截图--截图后
![请添加图片描述](https://i-blog.csdnimg.cn/direct/81c5766386c24fe8a3f02684da689956.png)
11.移入子关卡
当前子关卡（无子关卡）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/6866116a67374e41b125ea16386bc9c6.png)
创建了两个子关卡（下发没显示子关卡）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/aa23ee2e392043279eaaa2055369addc.png)
关闭编辑器工具面板重新运行后显示
![请添加图片描述](https://i-blog.csdnimg.cn/direct/203e33c56c804c798ce1f69cba8f8897.png)
批量选择模型，选择子关卡点击移入
![请添加图片描述](https://i-blog.csdnimg.cn/direct/c4592ab9883a43c9a3af6da72667044c.png)
12.模型的数据（长，宽，高，体积）
选择模型点击显示数据
![请添加图片描述](https://i-blog.csdnimg.cn/direct/e47c8775cb214fb7a3d87b360cdd149d.png)
13.取消摄像机宽高比
批量选择摄像机（当前宽高比为Ture）
![请添加图片描述](https://i-blog.csdnimg.cn/direct/2d6d9d0af00e4f5980feb158c0baedae.png)
点击后为False
![请添加图片描述](https://i-blog.csdnimg.cn/direct/b351027aa8b14adeb563462f9ea388a4.png)





更多功能请看  [https://space.bilibili.com/344860590](https://space.bilibili.com/344860590)
# 总结
以上就是虚幻编辑器工具Dan--Tools的使用说明，适用于地编，数字孪生等项目的使用。便于提升工作效率！

