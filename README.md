local CoreGui = game:GetService("StarterGui") -- Variable of StarterGui

CoreGui:SetCore("SendNotification", {
    -- Customizable
    Title = "白名单认证",
    Text = "白名单验证...",
    Duration = 6, --时间
})

local CoreGui = game:GetService("StarterGui") -- Variable of StarterGui

local Whitelisted = false;

if game.Players.LocalPlayer.Name == "wuai005" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "iwqqqqqqqqqs" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "iwqqqqqqqqs" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "AK_xjs978" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "hdykhj666" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "FBI_hmr" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "wszgr_9" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "okkokkplok" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "udxcgrdx" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "THQngedqx" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "sueii74" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "udhehuxh" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "miaomiao_233" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "miamia_1234567891011" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "cmdd123yi" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "123dgd3" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "GN46661" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "AYHngedGx" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "binhoushangyauun" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "qw118118" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "cn_qwaoi" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "bajidashe" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ydy1234566" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "Infinitejade404" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "HFO_DR" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "EVOKINGJFC2" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "cnmrnm12345" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "nbbcscydw" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "123654abcf" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "Awing707" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "yfhmyyffxdt" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "CN_xiaozhe" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ifw215n" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ifw215" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "zbsswl" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ajiwbwiu" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "wkert2" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "IIWZBII" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "xu6123liang55" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "Ehhsbsuj" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "hdhdhuxhut" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "Retention_Star" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "tgydggg" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "plm123plm123123" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ginghoayo" then 
Whitelisted = true 
end
if Whitelisted == true then

CoreGui:SetCore("SendNotification", {
    -- Customizable
    Title = "白名单认证",
    Text = "玩家:"..game.Players.LocalPlayer.Name.."，祝你玩的开心，嘿嘿",
    Duration = 10, --时间
})

   
   repeat task.wait() until game:IsLoaded()
local library = {}
local ToggleUI = false
library.currentTab = nil
library.flags = {}

local services = setmetatable({}, {
  __index = function(t, k)
    return game.GetService(game, k)
  end
})
local library = loadstring(game:HttpGet("https://pastebin.com/raw/Wh7Wa8Tb"))()
local window = library:new("『LINNI Script』高级付费版本")

local creds = window:Tab("使用脚本必看♥",'16060333448')

local bin = creds:section("玩家信息",true)

    bin:Label("你的用户名:"..game.Players.LocalPlayer.Character.Name)
    bin:Label("你的注入器:"..identifyexecutor())
    
    local bin = creds:section("关于的脚本和作者的信息😖",true)
    bin:Label("大群:932613422😀")
    bin:Label("副群:493057142🤨")
    bin:Label("主作者:霖溺，作者QQ1802952013😁合作清岩")
    bin:Label("副作者：白貓，钢筋，无xia🤓")
    bin:Label("本脚本在俄亥俄州可能不能开启，忍者注入器也不支持开启😍另外有些脚本是小天自制的")
    bin:Label("后续还会添加脚本进来，不会停更，找的一些老外脚本可能不能用见谅😘")
    bin:Label("欢迎进群让我添加脚本😄")
    bin:Label("付费模式脚本😚")
    bin:Label("支持70多个服务器😋")
    bin:Label("FE所有脚本添加中😰")
    bin:Label("脚本很好😦")
    bin:Label("脚本疯狂优化中😡")
    
local credits = creds:section("关闭",true)

credits:Toggle("脚本框架变小一点", "", false, function(state)
        if state then
        game:GetService("CoreGui")["frosty"].Main.Style = "DropShadow"
        else
            game:GetService("CoreGui")["frosty"].Main.Style = "Custom"
        end
    end)
    credits:Button("关闭脚本",function()
        game:GetService("CoreGui")["frosty"]:Destroy()
    end)
local credits = creds:section("彩虹ui",true)
credits:Toggle("彩虹UI", "", false, function(state)
        if state then
        game:GetService("CoreGui")["frosty"].Main.Style = "DropShadow"
        else
            game:GetService("CoreGui")["frosty"].Main.Style = "Custom"
        end
    end)
    
local creds = window:Tab("复制大群小群系列",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("点我复制大群",function()
    setclipboard("932613422")
end)
    credits:Button("点我复制副群",function()
    setclipboard("493057142")
end)
    credits:Button("点我复制作者QQ",function()
    setclipboard("1802952013")
end)

local creds = window:Tab("娱乐脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("非常娱乐",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KingHaxxor/King-Hax-Gui/main/Arab-Gui%E2%98%85"))();
end)

local creds = window:Tab("通用",'16060333448')

local credits = creds:section("通用脚本",true)
    credits:Button("聊天气泡美化这个自制",function()
    loadstring(game:HttpGet("https://shz.al/~lniNimeihua"))()
end)
    credits:Button("霖溺FPS",function()
    loadstring(game:HttpGet("https://shz.al/~FHHF"))()
end)
    credits:Button("穿墙",function()
    loadstring(game:HttpGet("https://github.com/DXuwu/OK/raw/main/clip"))()
end)
    credits:Button("人物体积……汉化",function()
    loadstring(game:HttpGet("https://shz.al/~KSJXBC62"))()
end)
    credits:Button("飞行",function()
    loadstring(game:HttpGet("https://shz.al/~hhhh"))()
end)
    credits:Button("夜视仪",function()
    _G.OnShop = trueloadstring(game:HttpGet('https://raw.githubusercontent.com/DeividComSono/Scripts/main/Scanner.lua'))()
end)
    credits:Button("正常范围",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/jiNwDbCN"))()
end)
    credits:Button("中等范围",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/x13bwrFb"))()
end)
    credits:Button("高级范围",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/KKY9EpZU"))()
end)
    credits:Button("反挂机",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/9fFu43FF"))()
end)
    credits:Button("无限跳",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/V5PQy3y0", true))()
end)
    credits:Button("吸人脚本",function()
    loadstring(game:HttpGet("https://shz.al/~HHAKS"))()
end)
    credits:Button("人物无敌",function()
    loadstring(game:HttpGet("https://shz.al/~HHHSNNNKIA"))()
end)
    credits:Button("飞檐走壁",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
end)
    credits:Button("踏空行走",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Float'))()
end)
    credits:Button("黑洞脚本",function()
    loadstring(game:HttpGet("https://shz.al/~KAKAKKKKSS"))()
end)
    credits:Button("死亡笔记",function()
    loadstring(game:HttpGet("https://shz.al/~KKKSS"))()
end)
    credits:Button("想杀谁就杀谁",function()
    loadstring(game:HttpGet("https://shz.al/~HHHS"))()
end)
    credits:Button("变玩家",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/XR4sGcgJ"))()
end)
    credits:Button("C00lgui",function()
    loadstring(game:GetObjects("rbxassetid://8127297852")[1].Source)()
end)
    credits:Button("声音播放器",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/GEianeKX"))()
end)
    credits:Button("物理枪",function()
    loadstring(game:HttpGet("https://shz.al/~KJANNKSKKS"))()
end)
    credits:Button("1x1x1x1",function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/JipYNCht'),true))()
end)
local credits = creds:section("『LINNI』跟踪脚本系列",true)
    credits:Button("老外跟踪1『不用自己打字搜索旁边有可以选择玩家』",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Infinity2346/Tect-Menu/main/Teleport%20Gui.lua'))()
end)
    credits:Button("霖溺的跟踪玩家『需要自己搜索，每次跟踪都要点击』",function()
    loadstring(game:HttpGet("https://shz.al/xtQP"))()
end)
    credits:Button("老外跟踪脚本2『需要自己搜索，但是点击后就不用点击了，只不过不能移动，需要变小建议找霖溺』",function()
    loadstring(game:HttpGet("https://shz.al/~LDSLS66"))()
end)
local credits = creds:section("通用脚本",true)
    credits:Button("工具包",function()
    loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/BTools.txt"))()
end)
    credits:Button("绘制『小天』",function()
    loadstring(game:HttpGet(('https://shz.al/~Xiaotian/ESPScript')))()
end)
    credits:Button("骂人无违规",function()
    loadstring(game:GetObjects("rbxassetid://1262435912")[1].Source)()
end)
    credits:Button("超高画质",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/jHBfJYmS"))()
end)
    credits:Button("工具挂",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Bebo-Mods/BeboScripts/main/StandAwekening.lua"))()
end)
    credits:Button("飞车『霖溺』",function()
    loadstring(game:HttpGet("https://shz.al/~KISJS"))()
end)
    credits:Button("霖溺甩飞",function()
    loadstring(game:HttpGet("https://shz.al/~linNI"))()
end)
    credits:Button("电脑键盘",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)
    credits:Button("宙斯飞行V3『未汉化』",function()
    loadstring(game:HttpGet("https://shz.al/~ArceusXFlyV3"))()
end)
    credits:Button("KRNL",function()
    loadstring(game:HttpGet("https://shz.al/~KRNLRobloxScirpt"))()
end)
    credits:Button("宙斯自瞄『未汉化』",function()
    loadstring(game:HttpGet("https://shz.al/~ArceusXAimbot"))()
end)
    credits:Button("Sonic",function()
    loadstring(game:HttpGet("https://shz.al/~SonicRobloxScirpt"))()
end)
    credits:Button("Tiger",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/balintTheDevX/TigerX-V2/main/Back"))()
end)
    credits:Button("Alysse",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/NathTheDev/AlysseAndroid/main/loader.lua"))()
end)
    credits:Button("宙斯V3",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/chillz-workshop/main/Arceus%20X%20V3"))()
end)
    credits:Button("acrylix",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/3dsonsuce/acrylix/main/Acrylix'))()
end)
    credits:Button("透视",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Lucasfin000/SpaceHub/main/UESP'))()
end)
    credits:Button("Synapse",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/tWGxhNq0"))()
end)

local creds = window:Tab("霖溺汉化阿尔宙斯脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("霖溺汉化阿尔宙斯瞄准",function()
    loadstring(game:HttpGet("https://shz.al/~KKA"))()
end)
    credits:Button("霖溺汉化阿尔宙斯飞行『推荐用这个飞行』",function()
    loadstring(game:HttpGet("https://shz.al/~KKDKS"))()
end)
    credits:Button("霖溺电脑端ESP『找不到阿尔宙斯ESP所以用这个绘制替代』",function()
    loadstring(game:HttpGet("https://shz.al/~MMSJS"))()
end)
    credits:Button("这个源太长了霖溺无能为力『DEX-Explorer』",function()
    loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Dex%20Explorer.txt"))()
end)
    credits:Button("另一种esp『霖溺找的』",function()
    loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/WRD%20ESP.txt"))()
end)
    credits:Button("infinite-Yield『懒得汉化了』",function()
    loadstring(game:HttpGet("https://shz.al/~DCFF"))()
end)

local creds = window:Tab("老外脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("老外通用",function()
    loadstring(game:HttpGet("https://shz.al/~jdjsjs"))()
end)

local creds = window:Tab("帮助者脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("白貓『美』",function()
    loadstring(game:HttpGet("https://shz.al/~lihhh"))()
end)

local creds = window:Tab("各位脚本作者脚本",'16060333448')
    
local credits = creds:section("作者脚本",true)
    credits:Button("林脚本",function()
    lin = "作者林"lin ="林QQ群 747623342"loadstring(game:HttpGet("https://raw.githubusercontent.com/linnblin/lin/main/lin"))()
end)
    credits:Button("鸭hub",function()
    loadstring(game:HttpGet(utf8.char((function() return table.unpack({104,116,116,112,115,58,47,47,112,97,115,116,101,98,105,110,46,99,111,109,47,114,97,119,47,81,89,49,113,112,99,115,106})end)())))()
end)
    credits:Button("龙脚本",function()
    getgenv().long = "龙脚本，加载时间长请耐心"loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\108\121\121\97\105\110\105\47\108\111\110\47\109\97\105\110\47\108\105\115\119\109\34\41\41\40\41")()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
local credits = creds:section("霖溺电脑端脚本",true)
    credits:Button("霖溺脚本电脑端的",function()
    loadstring(game:HttpGet("https://shz.al/~jxjzj"))()
end)
    credits:Button("霖溺另一个手机端脚本（二改的）",function()
    loadstring(game:HttpGet("https://shz.al/~GHBBJJ"))()
end)
    credits:Button("霖溺超多脚本",function()
    loadstring(game:HttpGet("https://shz.al/~KJANN"))()
end)
local credits = creds:section("作者脚本",true)
    credits:Button("听说最新云脚本",function()
    _G.CloudScript = "云脚本主群号526684389"
loadstring(game:HttpGet("https://raw.githubusercontent.com/XiaoYunCN/LOL/main/%E4%BA%91%E8%84%9A%E6%9C%ACCloud%20script.lua", true))()
end)
    credits:Button("云脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XiaoYunCN/Xiao-Yun-UWU/main/%E6%B5%B7%E8%B4%BC%E7%8E%8Bbf.lua", true))()
end)
    credits:Button("山脚本",function()
    loadstring(game:HttpGet("https://h.lkmc.asia/script/ssfb.lua"))()
end)
    credits:Button("青脚本",function()
    loadstring(game:HttpGet('https://rentry.co/ct293/raw'))()
end)
    credits:Button("陈脚本",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/QxDD9SpW"))()
end)
    credits:Button("杯脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/zuohongjian/bjb/main/llcq"))()
end)
    credits:Button("北极脚本『中心』",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/KwARpDxV",true))()
end)
    credits:Button("地岩脚本",function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\98\98\97\109\120\98\98\97\109\120\98\98\97\109\120\47\99\111\100\101\115\112\97\99\101\115\45\98\108\97\110\107\47\109\97\105\110\47\37\69\55\37\57\57\37\66\68\34\41\41\40\41")()
end)
    credits:Button("导管中心",function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\117\115\101\114\97\110\101\119\114\102\102\47\114\111\98\108\111\120\45\47\109\97\105\110\47\37\69\54\37\57\68\37\65\49\37\69\54\37\65\67\37\66\69\37\69\53\37\56\68\37\56\70\37\69\56\37\65\69\37\65\69\34\41\41\40\41\10")()
end)
    credits:Button("脚本中心1.5版本",function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\103\101\109\120\72\119\65\49"))()
end)
    credits:Button("玖恶脚本",function()
    loadstring(game:HttpGet('https://ayangwp.cn/api/v3/file/get/8508/%E7%8E%96%E6%81%B6%E4%B8%AD%E5%BF%83.lua?sign=wt54yWf_f0LDB3gXXyQu0SFQ0oUDUXZBOaWQShwCFGg%3D%3A0'))()
end)
    credits:Button("老大脚本",function()
    loadstring(game:HttpGet("https://ayangwp.cn/api/v3/file/get/8401/%E8%80%81%E5%A4%A7%E8%84%9A%E6%9C%AC1.0%E7%89%88.txt?sign=XHxQ1ja8djAnEjVEG-eEZFPeZKFHJ0FHeybHpSbtBW4%3D%3A0"))()
end)
    credits:Button("乌云脚本",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/dT4ZGge8"))()
end)
    credits:Button("皇脚本",function()
    loadstring(game:HttpGet("https://ayangwp.cn/api/v3/file/get/8577/%E7%9A%87v5.txt?sign=ToDT3Udyh4r3WwDu_yVblRL849qC2GJjjjQ7FTidF_w%3D%3A0"))()
end)
    credits:Button("冰红茶脚本",function()
    loadstring(game:HttpGet("https://ayangwp.cn/api/v3/file/get/8582/Protected_9297682332119129.lua?sign=jP-h1AGooC90C0A0O5eDboOCoaQTZpOzLoWzg_oz1eE%3D%3A0"))()
end)
    credits:Button("静新脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/jxdjbx/MOQ/main/%E6%9C%88%E5%90%97"))()
end)
    credits:Button("小魔脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/xiaomoNB666/xiaomoNB666/main/%E6%9E%81.lua"))()
end)
    credits:Button("鲨新ui脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/fvvhhh/sturdy-octo-engine/main/Protected_1221338743706560.lua.txt"))()
end)
    credits:Button("雷脚本",function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/tPB47inG')))()
end)
    credits:Button("秋脚本",function()
    _G[".秋·自制脚本 遗存抢救"]="2024dncxddtsnchzxtb0112"loadstring(game:HttpGet(utf8.char((function() return table.unpack({104,116,116,112,115,58,47,47,114,97,119,46,103,105,116,104,117,98,117,115,101,114,99,111,110,116,101,110,116,46,99,111,109,47,87,83,98,117,113,47,45,47,109,97,105,110,47,37,69,55,37,65,55,37,56,66,37,67,50,37,66,55,37,69,56,37,56,55,37,65,65,37,69,53,37,56,56,37,66,54,37,69,56,37,56,52,37,57,65,37,69,54,37,57,67,37,65,67})end)())))()
end)
    credits:Button("鱼脚本",function()
    getgenv().FISH = "鱼脚本群:851686462"loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\101\108\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\72\119\81\77\82\90\68\69\34\41\41\40\41")("鱼脚本")
end)
    credits:Button("火脚本",function()
    loadstring(game:HttpGet("https://shz.al/~FireCatV2RobloxScript"))()
end)

local creds = window:Tab("HUB",'16060333448')

local credits = creds:section("HUB脚本",true)
    credits:Button("EZ-HUB",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/debug42O/Ez-Industries-Launcher-Data/master/Launcher.lua'),true))()
end)
    credits:Button("unfair hub",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/rblxscriptsnet/unfair/main/rblxhub.lua'),true))()
end)
local credits = creds:section("脚本密钥链接https://keyrblx.com/getkey/ShifeScripts",true)
    credits:Button(" Shadow Hub V2",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Alexcirer/Alexcirer/main/V%20d"))()
end)
local credits = creds:section("HUB脚本",true)
    credits:Button("PlaybackX Hub",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/NeaPchX2/Playback-X-HUB/main/Protected.lua.txt'))()
end)
    credits:Button("Tianhe's script hub",function()
    loadstring(game:HttpGet('https://pastebin.com/raw/xdQVhQdm'))()
end)
    credits:Button("Mango hub",function()
    loadstring(game:HttpGet('https://gitlab.com/L1ZOT/mango-hub/-/raw/main/Mango-Bloxf-Fruits-Beta'))()
end)
    credits:Button("SOG hub",function()
    loadstring(game:HttpGet("https://shz.al/~JAJSNN233"))()
end)
    credits:Button("VG hub",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)
    credits:Button("Owl-Hub『嘿嘿』",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))()
end)
    credits:Button("HOHO_hub",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
end)

local creds = window:Tab("FE脚本『这几天将全部添加』",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("C00lgui",function()
    loadstring(game:GetObjects("rbxassetid://8127297852")[1].Source)()
end)
    credits:Button("1x1x1x1",function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/JipYNCht'),true))()
end)
    credits:Button("Abyssal sword",function()
    loadstring(game:HttpGet("https://shz.al/~KHHG"))()
end)
    credits:Button("FE传送",function()
    mouse = game.Players.LocalPlayer:GetMouse() tool = Instance.new("Tool") tool.RequiresHandle = false tool.Name = "[FE] TELEPORT TOOL" tool.Activated:connect(function() local pos = mouse.Hit+Vector3.new(0,2.5,0) pos = CFrame.new(pos.X,pos.Y,pos.Z) game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos end) tool.Parent = game.Players.LocalPlayer.Backpack
end)
    credits:Button("AKV",function()
    loadstring(game:HttpGet("https://shz.al/~KHHGK"))()
end)
    credits:Button("AK47",function()
    loadstring(game:HttpGet("https://shz.al/~KHHGKK"))()
end)
    credits:Button("AbyssEye",function()
    loadstring(game:HttpGet("https://shz.al/~KHJJ"))()
end)
    credits:Button("Animation ID Player",function()
    loadstring(game:HttpGet("https://shz.al/~KHJJK"))()
end)
    credits:Button("Angel wing master",function()
    loadstring(game:HttpGet("https://shz.al/~HHA"))()
end)
    credits:Button("Amythest Sword",function()
    loadstring(game:HttpGet("https://shz.al/~HHAJ"))()
end)
    credits:Button("Amythest Ninja",function()
    loadstring(game:HttpGet("https://shz.al/~HHAJK"))()
end)
    credits:Button("Baldi FE",function()
    loadstring(game:HttpGet("https://shz.al/~KKHHAJK"))()
end)
    credits:Button("Backup",function()
    loadstring(game:HttpGet("https://shz.al/~KKHHAJKKK"))()
end)
    credits:Button("Aureate",function()
    loadstring(game:HttpGet("https://shz.al/~KKHHAJKK"))()
end)
    credits:Button("Anti Furry lol",function()
    loadstring(game:HttpGet("https://shz.al/~KMH"))()
end)
    credits:Button("Bumper Car",function()
    loadstring(game:HttpGet("https://shz.al/~KMHK"))()
end)
    credits:Button("Bizzaro",function()
    loadstring(game:HttpGet("https://shz.al/~KMHKM"))()
end)
    credits:Button("Billie",function()
    loadstring(game:HttpGet("https://shz.al/~KMHKMM"))()
end)
    credits:Button("Big Daddy",function()
    loadstring(game:HttpGet("https://shz.al/~LBN"))()
end)
    credits:Button("Ban Sword",function()
    loadstring(game:HttpGet("https://shz.al/~LBNK"))()
end)
    credits:Button("cadacus",function()
    loadstring(game:HttpGet("https://shz.al/~LBNKj"))()
end)
    credits:Button("Cop",function()
    loadstring(game:HttpGet("https://shz.al/~LBNKjk"))()
end)
    credits:Button("CLOVR",function()
    loadstring(game:HttpGet("https://shz.al/~kansjs"))()
end)
    credits:Button("Chips",function()
    loadstring(game:HttpGet("https://shz.al/~kkkansjs"))()
end)
    credits:Button("Chara",function()
    loadstring(game:HttpGet("https://shz.al/~97373"))()
end)
    credits:Button("Carnage",function()
    loadstring(game:HttpGet("https://shz.al/~k97373"))()
end)
    credits:Button("Pendulum Hub V5",function()
    loadstring(game:HttpGet("https://shz.al/~k97373k"))()
end)
    credits:Button("PUBG Pan",function()
    loadstring(game:HttpGet("https://shz.al/~k97373kK"))()
end)
    credits:Button("SCP-106",function()
    loadstring(game:HttpGet("https://shz.al/~LDS"))()
end)
    credits:Button("KillbotV2",function()
    loadstring(game:HttpGet("https://shz.al/~LDSLS"))()
end)

local creds = window:Tab("Vehicle Legends CARS!脚本",'16060333448')

local credits = creds:section("『卡密模式』",true)
    credits:Button("Vehicle Legends CARS!",function()
    loadstring(game:HttpGet('https://scripts.luawl.com/hosted/2399/18728/FiberHubFree.lua'))()
end)
    credits:Button("点击我复制dc链接自己弄",function()
    setclipboard("https://discord.gg/NZYMVZvT2H")
end)
local credits = creds:section("『不需要卡密模式』",true)
    credits:Button("Vehicle Legends CARS!",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/houjk2/Boosthub/main/main.lua"))()
end)
    credits:Button("Vehicle Legends CARS!",function()
    loadstring(game:HttpGet("https://shz.al/~CNCJJFD882"))()
end)

local creds = window:Tab("Sol's RNG脚本",'16060333448')

local credits = creds:section("『卡密模式』",true)
    credits:Button("Sol's RNG",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Alan0947383/Demonic-HUB-V2/main/S-C-R-I-P-T.lua",true))()
end)
    credits:Button("点击我复制密钥链接",function()
    setclipboard("https://pandadevelopment.net/startkey.html?service=demonichubv2")
end)
local credits = creds:section("『免费模式』",true)
    credits:Button("Sol's RNG",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Looser3itx/Hmmmmmmmmmmmmmmmmmmmmmmmmmmmm/main/loader.lua"))()
end)
    credits:Button("hub",function()
    loadstring(game:HttpGet("https://shz.al/~JAJSNN233"))()
end)

local creds = window:Tab("力量传奇",'16060333448')

local credits = creds:section("自制为云脚本ui",true)
    credits:Button("新力量传奇修复版",function()
    loadstring(game:HttpGet("https://shz.al/~ANJSJS"))()
end)
    credits:Button("霖溺力量传奇（来源白貓）",function()
    loadstring(game:HttpGet("https://shz.al/~baimaomeili"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("极速传奇",'16060333448')

local credits = creds:section("自制为云ui",true)
    credits:Button("霖溺自制极速传奇",function()
    loadstring(game:HttpGet("https://shz.al/~lninjj"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("忍者传奇",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("霖溺忍者传奇（来源白貓）",function()
    loadstring(game:HttpGet("https://shz.al/~baimaomeilihh"))()
end)
    credits:Button("忍者传奇",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Zyb150933/zyb/main/123'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("忍者（老外1）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/zerpqe/script/main/NinjaLegends.lua"))()
end)
    credits:Button("忍者（老外2）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ThatBlueDevil/Bleus/main/Ninja%20Legends/Source.lua"))()
end)

local creds = window:Tab("监狱人生",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("油管找的管理员脚本",function()
    loadstring(game:HttpGet("https://shz.al/~ggghhhh"))()
end)
    credits:Button("汉化后的moonhub",function()
    loadstring(game:HttpGet("https://shz.al/~MoonHub"))()
end)
local credits = creds:section("Tiger无敌了",true)
    credits:Button("tiger",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/dalloc2/Roblox/main/TigerAdmin.lua"))()
end)
local credits = creds:section("霖溺嘿",true)
    credits:Button("听说吊打一切",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))()
end)
    credits:Button("请使用青脚本里的管理员脚本（推荐）",function()
    loadstring(game:HttpGet('https://rentry.co/ct293/raw'))()
end)
    credits:Button("剑客脚本（通用）",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("死亡球",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("死亡球（1）",function()
    loadstring(game:HttpGet("https://github.com/Hosvile/InfiniX/releases/latest/download/main.lua",true))()
end)
    credits:Button("死亡球（2）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/Ball1/main/Death"))()
end)

local creds = window:Tab("自然灾害",'16060333448')

local credits = creds:section("自制为云ui",true)
    credits:Button("霖溺自制自然灾害",function()
    loadstring(game:HttpGet("https://shz.al/D8Kn"))()
end)
    credits:Button("自然灾害1",function()
    loadstring(game:HttpGet("https://gist.githubusercontent.com/TurkOyuncu99/7c75386107937fa006304efd24543ad4/raw/8d759dfcd95d39949c692735cfdf62baec0bf835/cafwetweg", true))()
end)
    credits:Button("自然灾害2",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/LoadstringUjHI6RQpz2o8", true))()
end)
    credits:Button("自然灾害3",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/9NLK7/93qjoadnlaknwldk/main/main'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("杀手于警长",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("杀手于警长（找的）",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/yadbPQUm",true))()
end)
    credits:Button("剑客脚本（通用）",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("巴掌模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("自动刷巴掌",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/ionlyusegithubformcmods/1-Line-Scripts/main/Slap%20Farm'))()
end)
    credits:Button("巴掌模拟器yyds",function()
    loadstring(game:HttpGet("https://shz.al/~HHAKKSSKSOOS"))()
end)
    credits:Button("巴掌模拟器",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)
    credits:Button("常用功能",function()
    loadstring(game:HttpGet("https://lkhub.net/s/loader.lua"))()
end)
    credits:Button("多功能（老外）",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/ionlyusegithubformcmods/1-Line-Scripts/main/Slap%20Battles")))()
end)

local creds = window:Tab("内脏与黑火药脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("加入https://discord.gg/RjqwhMY7DU获取密钥",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/FnfCheatbotsonroblox/kitten.cc-lua/main/kitten-obfuscated%20(1).lua"))()
end)
    credits:Button("点击我复制dc",function()
    setclipboard("https://discord.gg/RjqwhMY7DU")
end)
local credits = creds:section("『LINNI Script』",true)
    credits:Button("内脏与黑火药",function()
    loadstring(game:HttpGet("https://shz.al/~KSKKS"))()
end)

local creds = window:Tab("51区脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("51区",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Saktk-In-Area51/main/Area51", true))()
end)

local creds = window:Tab("短信模拟器脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("短信模拟器",function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/9hxkxUZ5'),true))()
end)

local creds = window:Tab("克隆大亨脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("克隆大亨",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/HELLLO1073/RobloxStuff/main/CT-Destroyer"))()
end)

local creds = window:Tab("刀刃球",'16060333448')

local credits = creds:section("『LINNI Script』（听说的战场）",true)
    credits:Button("霖溺汉化刀刃球",function()
    loadstring(game:HttpGet("https://shz.al/75G8"))()
end)
    credits:Button("Seeds-Next刀刃球不会的自己研究『强，作者推荐』",function()
    loadstring(game:HttpGet(('https://shz.al/~Seeds-Next/Ditto-so-tried/HAGOU-and-Qumuuuuu')))()
end)
    credits:Button("刀刃球（强1）",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/Unknownkellymc1/Unknownscripts/main/slap-battles')))()
end)
    credits:Button("刀刃球（强2）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/HKLua/Balls/main/DawnLoader.lua"))()
end)
    credits:Button("刀刃球（强3）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BladeBall/main/redz9999"))()
end)
    credits:Button("刀刃球（强4）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Neoncat765/Neon.C-Hub-X/main/UnknownVersion"))()
end)
    credits:Button("刀刃球（强5）",function()
    local a,b,c,d=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,"https://shz.al/~NeoV4"c(a and b, "Your Executor does not support.")a(b({Url=d,Method="GET"}).Body)()
end)
    credits:Button("刀刃球（强6）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/HKLua/Balls/main/DawnLoader.lua"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("模仿者",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("模仿者（1有自动赢）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ttjy9808/obfloadstringmainmimic/main/README.md", true))()
end)
    credits:Button("模仿者（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ttjy9808/obfloadstringmainmimic/main/README.md", true))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("出租车司机脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("自动抽蛋开启",function()
    loadstring(game:HttpGet("https://shz.al/~KAKSKSK"))()
end)
    credits:Button("自动抽蛋关闭",function()
    loadstring(game:HttpGet("https://shz.al/~KA28272"))()
end)

local creds = window:Tab("战斗勇士",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("战斗勇士（英文电脑端，直接畅玩）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/frkfx/Combat-Warriors/main/Script"))()
end)
    credits:Button("战斗勇士老外英文",function()
    loadstring(game:HttpGet("https://paste.gg/p/anonymous/697fc3cad5f743508318cb7399e89432/files/b5923e52edab4e5c91e46b74563d0ae8/raw"))()
end)
    credits:Button("战斗勇士无限体力",function()
    loadstring(game:HttpGet("https://shz.al/~KSK"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("piggy脚本",'16060333448')

local credits = creds:section("piggy脚本",true)
    credits:Button("piggy脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Piggy/Loader.lua"))()
end)
    credits:Button("piggy英文",function()
    loadstring(game:HttpGet("https://encurtador.com.br/fiyFJ"))()
end)

local creds = window:Tab("SharkBite 2[TRADING]脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("SharkBite 2[TRADING]",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JerrymiahPM/SharkRipper/main/main.lua"))()
end)
    credits:Button("SharkBite 2[TRADING]",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/PikachuHack/SharkBite2-Instant-Kill-Main-Shark/main/Instant%20Kill%20Main%20Shark"))()
end)
local credits = creds:section("『卡密模式』",true)
    credits:Button("SharkBite 2[TRADING]",function()
    loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/62ac508ae22ac9d4d5485af7a4531b0b.lua"))() 
end)
    credits:Button("点击我复制密钥链接",function()
    setclipboard("https://keyrblx.com/getkey/StellarHub")
end)
    credits:Button("SharkBite 2[TRADING]",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/FlmesCoding/CandyHubGames/main/Protected_1799613766569471.lua"))()
end)
    credits:Button("点击复制dc",function()
    setclipboard("https://discord.gg/NZU9zq5gMu")
end)
    credits:Button("SharkBite 2[TRADING]",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IsThisMe01/Project-L/main/Main.lua"))()
end)
    credits:Button("点击我复制dc",function()
    setclipboard("https://discord.gg/FWhdk92nYj")
end)

local creds = window:Tab("火箭发射模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("火箭发射模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://ayangwp.cn/api/v3/file/get/9245/%E7%8C%AB%E9%80%9A%E7%94%A8.txt?sign=hrWROZdVfK2mtJcIFa3Tvbl-TojP1C86_Zd3q03qttc%3D%3A0"))()
end)
    credits:Button("火箭发射模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/dizyhvh/rbx_scripts/main/321_blast_off_simulator')))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("只因剑",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("只因剑（名字相同脚本不同）",function()
    loadstring(game:HttpGet(('https://gist.githubusercontent.com/blox-hub-roblox/021bad62bbc6a0adc4ba4e625f9ad7df/raw/c89af6e1acf587d09e4ce4bc7510e7100e0c0065/swordWarrior.lua'),true))()
end)
    credits:Button("只因剑（2召唤小黑子）",function()
    loadstring(game:HttpGet(('https://gist.githubusercontent.com/blox-hub-roblox/021bad62bbc6a0adc4ba4e625f9ad7df/raw/c89af6e1acf587d09e4ce4bc7510e7100e0c0065/swordWarrior.lua'),true))()
end)
    credits:Button("只因剑（3巨剑战士）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0SwordWarriors"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("战争大亨脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("战争大亨",function()
    loadstring(game:HttpGet'https://raw.githubusercontent.com/Macintosh1983/ChillHubMain/main/ChillHubOilWarfareTycoon.lua')()
end)
    credits:Button("狼脚本",function()
    loadstring(game:HttpGet("https://shz.al/~WarTycoon"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("彩虹朋友",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("彩虹朋友（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/XoNv04vR/raw"))()
end)
    credits:Button("彩虹朋友自动获胜",function()
    loadstring(game:HttpGet("https://shz.al/~zkzkzisKAKAKKKKSS"))()
end)
    credits:Button("彩虹朋友（推荐）",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Ihaveash0rtnamefordiscord/BorkWare/main/Scripts/' .. game.GameId .. ".lua"))(' Watermelon ? ')
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("河北唐县",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("河北唐县（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Sw1ndlerScripts/RobloxScripts/main/Tang%20Country.lua"))()
end)
    credits:Button("河北唐县（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/s20nni0h/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("Blox Fruit",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("霖溺BF",function()
    loadstring(game:HttpGet("https://shz.al/~KAKKKS"))()
end)
    credits:Button("BF『HOHO脚本』链接不一样",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HohoV2/Free/BloxFruitFreeV3.lua"))()
end)
    credits:Button("BF『HOHIO脚本』链接不一样",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
end)
    credits:Button("BF（听说第二强）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Augustzyzx/UraniumMobile/main/UraniumKak.lua"))()
end)
    credits:Button("BF（霖溺找的）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RobloxScriptsExploit/Blox-Fruits/main/Ripper%20M"))()
end)
    credits:Button("BF（自动箱子）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
end)
    credits:Button("BF（汉化）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XiaoYunCN/Xiao-Yun-UWU/main/%E6%B5%B7%E8%B4%BC%E7%8E%8Bbf.lua", true))()
end)
    credits:Button("BF（听说最屌）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AkiraNus/UniquehubKak/main/FreeCr.Xenonhub"))()
end)
    credits:Button("BF（刷怪）",function()
    loadstring(game:HttpGet('https://rawscripts.net/raw/UPDATE-16-Blox-Fruits-Nub-V1-Hub-4583'))()
end)
    credits:Button("BF脚本w-azure无密钥",function()
    getgenv().Team = "Pirates"loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
end)
    credits:Button("BF（自动升级）",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xDepressionx/Free-Script/main/AllScript.lua")()
end)
    credits:Button("BF",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("进击的僵尸脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("进击的僵尸",function()
    loadstring(game:HttpGet("https://shz.al/~KSKSKSK"))()
end)

local creds = window:Tab("破坏者谜团2",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("破坏者谜团2（多功能）",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/Ethanoj1/EclipseMM2/master/Script"),true))()
end)
    credits:Button("霖溺非常推荐（破坏者谜团2）",function()
    loadstring(game:HttpGet("https://shz.al/~GHD"))()
end)
    credits:Button("破坏者谜团2（老外的）",function()
    loadstring(game:HttpGet("https://shz.al/~GHDJJ"))()
end)
    credits:Button("破坏者谜团2",function()
    loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)
    credits:Button("破坏者谜团（透视谁是警长）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Ihaveash0rtnamefordiscord/Releases/main/MurderMystery2HighlightESP"))(' Watermelon ?')
end)

local creds = window:Tab("nico下一个机器人脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("nico下一个机器人",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/elonof/nicosbots-script/main/main.lua",true))()
end)
    credits:Button("nico下一个机器人",function()
    loadstring(game:HttpGet("https://fern.wtf/scripts/nico_bot.lua", true))()
end)
    credits:Button("nico下一个机器人",function()
    local hrp = game.Players.LocalPlayer.Character:FindFirstChild("Humanoid")
hrp.Parent = nil
hrp:Clone()
hrp.Parent = game.Players.LocalPlayer.Character
hrp.Name = "Humanoid"
game.StarterGui:SetCore("SendNotification", {Title="God Mode"; Text="God Mode Activated"; Duration=5;})
end)
    credits:Button("nico下一个机器人",function()
    loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/fartbutt69/Nico-s-Nextbot-Killer/main/script.lua", true))()
end)
    credits:Button("nico下一个机器人",function()
    local Player = game:GetService("Players").LocalPlayer

while true do 
wait(0.5)
Player.Character.HumanoidRootPart.Position = Vector3.new(0, -50, 0)
wait(0.5)
Player.Character.HumanoidRootPart.Position = Vector3.new(0, -80, 0)
end
end)

local creds = window:Tab("蜂群模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("霖溺简易汉化",function()
    loadstring(game:HttpGet("https://shz.al/~HHAKKJA"))()
end)
    credits:Button("蜂群模拟器",function()
    loadstring(game:HttpGet("https://shz.al/~HHAKKSS"))()
end)
    credits:Button("蜂群模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/3A61hnGA", true))()
end)
    credits:Button("蜂群模拟器bee swarm",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Historia00012/HISTORIAHUB/main/BSS%20FREE"))()
end)
    credits:Button("蜂群模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/QtYmKaQ1/raw"))()
end)
    credits:Button("蜂群模拟器（自动收集）",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/max0mind/lua/main/loader.lua'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("小偷模拟器脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("小偷模拟器",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/adrician/Thief-Simulator---GUI/main/Thief%20sim.lua"),true))()
end)

local creds = window:Tab("evade大逃脱",'16060333448')

local credits = creds:section("evade脚本",true)
    credits:Button("evade脚本1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/PepesGH1/stuff/main/evadeloader.lua"))()
end)
    credits:Button("evade大逃脱",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XiaoYunCN/UWU/main/%E4%BA%91%E8%84%9A%E6%9C%ACEvade.lua"))()
end)
    credits:Button("老外脚本",function()
    loadstring(game:HttpGet("https://shz.al/~jdjsjsKK"))()
end)

local creds = window:Tab("Fling Things and People脚本",'16060333448')

local credits = creds:section("Fling Things and People脚本",true)
    credits:Button("Fling Things and People1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/BlizTBr/scripts/main/FTAP.lua"))()
end)

local creds = window:Tab("国王遗产脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("『1』",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/sannin9000/scripts/main/kinglegacy.lua"))()
end)
    credits:Button("『2』",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/legacy"))()
end)
    credits:Button("『3』",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/King%20Leagacy"))()
end)
    credits:Button("『4』",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Strikehubv2z/StormSKz/main/All_in_one"))()
end)

local creds = window:Tab("披萨店脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("披萨点自动工作",function()
    loadstring(game:HttpGet("https://shz.al/~HHHSUSU"))()
end)

local creds = window:Tab("Drive World",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("Drive World脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/x3fall3nangel/FallAngelHub/main/DriveWorld.lua"))()
end)

local creds = window:Tab("一路向西",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("一路向西（无后坐力超级射速无限子弹）",function()
    loadstring(game:GetObjects("rbxassetid://10040701935")[1].Source)()
end)
    credits:Button("一路向西（名字相同脚本不同）",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/Drifter0507/scripts/main/westbound"),true))()
end)
    credits:Button("一路向西（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/q08owYGG/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab(".,.77寻宝",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("造船寻宝（名字相同脚本不同）",function()
    loadstring(game:HttpGet("http://dirtgui.xyz/BuildABoat.lua",true))()
end)
    credits:Button("造船寻宝（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/hvV1c4nO/raw"))()
end)
    credits:Button("造船寻宝（复制别人船）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/max2007killer/auto-build-not-limit/main/autobuild.txt"))()
end)
    credits:Button("造船寻宝（刷钱）",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/urmomjklol69/GoldFarmBabft/main/GoldFarm.lua'),true))()
end)

local creds = window:Tab("鲨口求生脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("鲨口求生有一些功能慎用",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/YYVLbzVg", true))()
end)

local creds = window:Tab("DOORS",'16060333448')

local credits = creds:section("『LINNI Script』（最强只是听说）",true)
    credits:Button("霖溺自制Doors",function()
    loadstring(game:HttpGet("https://shz.al/yWFF"))()
end)
    credits:Button("新doors脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing-obf/main/Doors%20Blackking%20And%20BobHub"))()
end)
    credits:Button("最强汉化DOORS",function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\54\53\84\119\84\56\106\97"))()
end)
    credits:Button("DX汉化加二改",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/DXuwu/replicator-lol/main/dor.lua"))()
end)
    credits:Button("多功能DOORS",function()
    loadstring(game:HttpGet("https://shz.al/~SJZJJSISI"))()
end)
    credits:Button("微山DOORS",function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\119\101\105\115\104\97\110\116\101\97\109\47\83\99\114\105\112\116\47\109\97\105\110\47\100\111\111\114\115\47\87\101\105\83\104\97\110\95\76\111\97\100\101\114\46\108\117\97\10"))()
end)
    credits:Button("Doors（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/Su9RsViT/raw"))()
end)
    credits:Button("Doors（最强1）",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/mstudio45/poopdoors_edited/main/poopdoors_edited.lua"),true))()
end)
    credits:Button("Doors（最强2）",function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\54\53\84\119\84\56\106\97"))()
end)
    credits:Button("Doors（最强3）",function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/R8QMbhzv')))()
end)
    credits:Button("DOORS听说是好用脚本",function()
    loadstring("\112\114\105\110\116\40\34\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\75\73\78\71\72\85\66\48\49\47\66\108\97\99\107\75\105\110\103\47\109\97\105\110\47\66\108\97\99\107\75\105\110\103\37\50\48\68\111\111\114\115\37\50\48\77\111\98\105\108\101\34\41\41\40\41\32\34\41\10")()
end)
    credits:Button("Doors（过room）",function()
    loadstring(game:HttpGet('\x68\x74\x74\x70\x73\x3A\x2F\x2F\x68\x2E\x6C\x6B\x6D\x63\x2E\x61\x73\x69\x61\x2F\x73\x63\x72\x69\x70\x74\x2F\x64\x6F\x6F\x72\x73\x72\x6F\x6F\x6D\x2E\x6C\x75\x61'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("破坏模拟器脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("破坏模拟器",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/AquaModz/DestructionSIMModded/main/DestructionSimAqua.lua'))()
end)

local creds = window:Tab("驾驶帝国",'16060333448')

local credits = creds:section("驾驶帝国脚本",true)
    credits:Button("驾驶帝国（英文）",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/zeuise0002/SSSWWW222/main/README.md'),true))()
end)
    credits:Button("驾驶帝国（英文）",function()
    loadstring(game:HttpGet("https://soggyhubv2.vercel.app"))()
end)

local creds = window:Tab("动物进化脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("动物进化1",function()
    game:GetService("ReplicatedStorage").Events.UpdateStatEvent:FireServer("Lv", 999999999)
end)
    credits:Button("动物进化2",function()
    game:GetService("ReplicatedStorage").Events.UpdateStatEvent:FireServer("Xp", 999999999)
end)
    credits:Button("动物进化3",function()
    game:GetService("ReplicatedStorage").Events.UpdateStatEvent:FireServer("DmgLvl", 999999999)
end)
    credits:Button("动物进化4",function()
    game:GetService("ReplicatedStorage").Events.UpdateStatEvent:FireServer("CritDmgLvl", 999999999)
end)
    credits:Button("动物进化",function()
    local player = game.Players.LocalPlayer

for _, child in ipairs(player:GetChildren()) do
    if child:IsA("BoolValue") then
        child.Value = true
    end
end
end)

local creds = window:Tab("浴缸战争脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("（升级演习）浴缸战争",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Alan0947383/Boom/main/Protected_1198219713372149.lua.txt",true))()
end)
    credits:Button("点我复制解密钥链接",function()
    setclipboard("https://pandadevelopment.net/startkey.html?service=demonichubv2")
end)

local creds = window:Tab("飞行比赛脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("飞行比赛",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/NightCoded/script/main/fly-race.lua"))()
end)

local creds = window:Tab("俄亥俄州",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("俄亥俄州（老外1）",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/0MqfXpvY", true))()
end)
    credits:Button("俄亥俄州（老外2）",function()
    loadstring(game:HttpGet('https://pastebin.com/raw/MyfCUnGK'))()
end)
    credits:Button("俄亥俄州（自动工作＋传送工作地点）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/ohio/main/Roblox232"))()
end)
    credits:Button("俄亥俄州1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/rxn-xyz/Ohio./main/Ohio.lua",true))()
end)
    credits:Button("俄亥俄州2",function()
    loadstring(game:HttpGet("https://pastefy.app/QbXPfsgC/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("The rake",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("The rake电脑端",function()
    loadstring(game:HttpGet("https://realzzhub.xyz/script.lua"))()
end)
    credits:Button("the rake",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/3EloHIyChay123123/The-rake-noob-edition-gui/main/.GUI"))()
end)

local creds = window:Tab("兵工厂",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("霖溺出品必属精品",function()
    loadstring(game:HttpGet("https://shz.al/~KKAKSKKS"))()
end)
    credits:Button("最强更新绕过反作弊启动即可奔放",function()
    loadstring(game:HttpGet("https://shz.al/~FGD"))()
end)
    credits:Button("兵工厂1",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/RandomAdamYT/DarkHub/master/Init'), true))()
end)
    credits:Button("兵工厂无敌子追",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubArsenal"))()
end)
    credits:Button("兵工厂",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Arsenal/MainFile"))()
end)
    credits:Button("兵工厂（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/2YdrWHxV/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("餐厅大亨",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("餐厅大亨无限钱",function()
    loadstring(game:HttpGet("https://shz.al/~zkzkzisKAKAKK"))()
end)
    credits:Button("餐厅大亨（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/toosiwhip/snake-hub/main/restaurant-tycoon-2.lua"))()
end)
    credits:Button("餐厅大亨（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/Ppqt0Gib/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("超级大力士模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("超级大力士模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe2/ToraIsMe2/main/0strongman", true))()
end)
    credits:Button("超级大力士模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/aO18ZEB9/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("举重模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("举重模拟器祝你玩的开心",function()
    loadstring(game:HttpGet("https://shz.al/~HHHSUSUKSKS"))()
end)
    credits:Button("举重模拟器",function()
    loadstring(game:HttpGet("https://pastefy.app/KSriAk53/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("怪兽宇宙",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("怪兽宇宙",function()
    loadstring(game:HttpGet("https://pastefy.app/oRWEIEcJ/raw"))()
end)

local creds = window:Tab("铲雪模拟器脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("铲雪模拟器",function()
    loadstring(game:HttpGet("https://shz.al/~KJAKAKSKKS"))()
end)

local creds = window:Tab("幸运方块",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("汽车经销大亨",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("汽车经销大亨（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/5o594Q0i/raw"))()
end)
    credits:Button("汽车经销大亨（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/03sAlt/BlueLockSeason2/main/README.md"))()
end)
    credits:Button("汽车经销大亨（收集所有砖头）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IExpIoit/Script/main/Car%20Dealership%20Tycoon.lua"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("寻宝模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("寻宝模拟器『霖溺汉化』",function()
    loadstring(game:HttpGet("https://shz.al/~MKS"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("拳击模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("拳击模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/T4O1SA3q/raw"))()
end)
    credits:Button("拳击模拟器（名字相同脚本不同）",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Solx69/Shit-Boy-Hub-Main/main/Master.lua'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("伐木大亨",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("伐木大亨（听说最强）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/frencaliber/LuaWareLoader.lw/main/luawareloader.wtf",true))()
end)
    credits:Button("想白的老外脚本",function()
    loadstring(game:HttpGet('https://getexploits.com/key-system/',true))('https://da.com/936657404291084298/1006220505583460352/Script.txt')
end)
    credits:Button("白脚本（不知道能不能用）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CloudX-ScriptsWane/ScriptsDache/main/%E4%BC%90%E6%9C%A8%E5%A4%A7%E4%BA%A822.lua", true))()
end)
    credits:Button("伐木大亨",function()
    loadstring(game:HttpGet("https://shz.al/~/dkfkfkfjfkfjdj/longshu/main/lllllkllllllll"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("绵羊大亨脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("绵羊大亨『小天』",function()
    loadstring(game:HttpGet(('https://shz.al/PHep')))()
end)

local creds = window:Tab("最强战场",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("最强战场能用",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Scripterbacon/TSBobfuscator/main/Main.Lua"))()
end)
local credits = creds:section("『需要密钥脚本』",true)
    credits:Button("需要密钥自己加dc",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/DrakainnnDL/Script/main/TheStrongestBattle'))()
end)
    credits:Button("点击我复制dc",function()
    setclipboard("https://discord.gg/Mbh9NRd8")
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("奎尔湖",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("奎尔湖",function()
    loadstring(game:HttpGet("https://pastefy.app/ZwaXa3ZR/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("格林维尔",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("格林维尔",function()
    loadstring(game:HttpGet("https://pastefy.app/WBYAsWJm/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("恐怖奶奶",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("恐怖奶奶",function()
    loadstring(game:HttpGet("https://pastefy.app/o688Jvmn/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("奶酪逃亡",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("奶酪逃亡",function()
    loadstring(game:HttpGet("https://pastefy.app/IIpzN8f5/raw"))()
end)

local creds = window:Tab("我的餐厅",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("我的餐厅（不确定是手机端）",function()
    loadstring(game:HttpGet("http://void-scripts.com/Scripts/myRest.lua"))()
end)
    credits:Button("我的餐厅",function()
    loadstring(game:HttpGet("https://pastefy.app/5R1Ch6kk/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("钓鱼模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("钓鱼模拟器（1英文）",function()
    loadstring(game:HttpGet("https://shz.al/~LNINIGGDHH"))()
end)
    credits:Button("钓鱼模拟器（2英文）",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/reddythedev/Reddy-Hub/main/_Loader'))()
end)
    credits:Button("钓鱼模拟器（3英文）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/bebedi15/SRM-Scripts/main/Bebedi9960/SRMHub"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("旗帜战争",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("旗帜战争（名字相同脚本不同）",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Infinity2346/Tect-Menu/main/Flag%20Wars.txt'))()
end)
    credits:Button("旗帜战争（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/otEg6PJV/raw"))()
end)

local creds = window:Tab("法宝模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("法宝模拟器",function()
    loadstring(game:HttpGet("https://pastefy.app/9bGpv4H3/raw"))()
end)
    credits:Button("法宝模拟器（汉化）",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/zhanghuihuihuil/Script/main/%E6%B3%95%E5%AE%9D%E6%A8%A1%E6%8B%9F%E5%99%A8%E6%B1%89%E5%8C%96'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("极速奔驰",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("极速奔驰",function()
    loadstring(game:HttpGet("https://pastefy.app/Y7607jwb/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("射击光束模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("射击光束模拟器",function()
    loadstring(game:HttpGet("https://pastefy.app/51yMuaCc/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("合并滴管",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("合并滴管",function()
    loadstring(game:HttpGet("https://pastefy.app/NpBrBCqM/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("成为跑酷忍者脚本",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("成为跑酷忍者",function()
    loadstring(game:HttpGet(('https://shz.al/~XiaoTian/Script/yyds')))()
end)

local creds = window:Tab("动感星期五",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("动感星期五（Auto Click）",function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/XMAS-Event-or-Funky-Friday-Auto-Player-Mobile-6721"))()
end)
    credits:Button("动感星期五（自动PK）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/wally-rblx/funky-friday-autoplay/main/main.lua",true))()
end)
    credits:Button("动感星期五",function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/XMAS-Event-or-Funky-Friday-Auto-Player-Mobile-6721"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("活过杀手",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("活过杀手（垃圾）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Milan08Studio/ChairWare/main/main.lua"))()
end)
    credits:Button("剑客脚本（里面的通用）",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)

local creds = window:Tab("起床战争",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("起床vape",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))()
end)

local creds = window:Tab("RELEASE + EVENT The Heroes Simulator",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("Demonic HUB V2脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Alan0947383/Demonic-HUB-V2/main/S-C-R-I-P-T.lua",true))()
end)

local creds = window:Tab("ZapHub The Best PS99 Script (Fast Version) ",'16060333448')

local credits = creds:section("密钥链接https://linkvertise.com/608384/zaphub-key-system",true)
    credits:Button("ZapHub The Best PS99 Script (Fast Version) ",function()
    loadstring(game:HttpGet('https://www.zaphub.xyz/ExecPS99FV'))()
end)

local creds = window:Tab("超级联赛足球",'16060333448')

local credits = creds:section("踢足球",true)
    credits:Button("菜单一",function()
    loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/8fdf7c482d3b3d108ccdb282a7fc35e2.lua"))()
end)
    credits:Button("菜单二",function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xtrey10x/xtrey10x-hub/main/neo")()
end)
else
game.Players.LocalPlayer:Kick("『LINNI Script』要白名单，霖溺脚本持续更新，脚本良心三元，进群932613422找霖溺买，群主和管理『名称为霖溺的』都是我")--踢人函数
   end
   
