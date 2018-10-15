功能说明:

泰内布利斯城堡 [上/下级] 1-2-3王 攻击提示

------------------------------

在 /8 频道中输入

ccg	(默认开启提示状态)

------------------------------

模仿[AA-Guide] [RK9-Guide] 两个模块制作的攻击提示

------------------------------

config.json 中添加一行参数可改变提示文字颜色 如:

{

	"enabled": true,
	
	"sendToParty": false,
	
	"streamenabled": false,
	
	"msgcolour" : "FF00DC"
	
}

------------------------------

config.json 参数说明:

enabled 模块初始 [启动]

sendToParty 发送提示文字到[真实组队] [关闭]

streamenabled 发送提示文字到[代理频道] [关闭]

msgcolour 提示文字颜色为[粉色](FF00DC) 不添加则为默认颜色
