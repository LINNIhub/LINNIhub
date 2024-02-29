local CoreGui = game:GetService("StarterGui") -- Variable of StarterGui

CoreGui:SetCore("SendNotification", {
    -- Customizable
    Title = "白名单认证",
    Text = "白名单验证...",
    Duration = 3, --时间
})

local CoreGui = game:GetService("StarterGui") -- Variable of StarterGui

local Whitelisted = false;

if game.Players.LocalPlayer.Name == "wuai005" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ftj520" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "powerpo311" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "binhoushangyauuni" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "cmdd123yi" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ssoo_886" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "666nb23" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "utjfjtau" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "yyj114" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ydy1234566" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "fhh6661" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "jbbhhb3" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "jbyjojo" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "CNEJRIH" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "touzi5687" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "yfhmyyffxdt" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "hdhdhuxhut" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "FBI_hmr" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "wszgr_9" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "ajiwbwiu" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "423mBK" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "cnm114514191" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "pegoms" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "N1_N2" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "13ygfhhg" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "KSLMJMMMOOODDD" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "hy159S" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "qwqjjb" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "cn_qwaoi" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end

if game.Players.LocalPlayer.Name == "用户名" then 
Whitelisted = true 
end
if Whitelisted == true then

CoreGui:SetCore("SendNotification", {
    -- Customizable
    Title = "白名单认证",
    Text = "玩家:"..game.Players.LocalPlayer.Name.."，祝你玩的开心，嘿嘿",
    Duration = 7, --时间
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
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer("霖溺-脚本", "All")
local library = loadstring(game:HttpGet("https://pastebin.com/raw/n6KRrKWP"))()
local window = library:new("『LINNI Script』『CST』")

local creds = window:Tab("使用脚本必看♥",'16060333448')

local bin = creds:section("玩家信息",true)

    bin:Label("你的用户名:"..game.Players.LocalPlayer.Character.Name)
    bin:Label("你的注入器:"..identifyexecutor())
    
    local bin = creds:section("关于的脚本和作者的信息",true)
    bin:Label("官群:493057142")
    bin:Label("主作者:霖溺『罗布乐思组织CST』")
    bin:Label("副作者：白貓『人好』")
    bin:Label("脚本永久免费")
    bin:Label("作者QQ1802952013")
    bin:Label("副作者和我的脚本会相似")
    bin:Label("后续还会添加脚本进来，不会停更")
    bin:Label("找的老外脚本有些不能用见谅")
    bin:Label("欢迎进群让我添加脚本")
    bin:Label("别好奇为啥加白名单因为仪式")
    bin:Label("支持70多个服务器")
    bin:Label("FE所有脚本添加中")
    bin:Label("阿尔宙斯部分汉化完毕")
    bin:Label("独一无二的缝合脚本，虽然缝合脚本名声不好，但没事")
    bin:Label("我永远保持初心，缝合不缝合的能用就行了")
    
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
local creds = window:Tab("通用",'16060333448')

local credits = creds:section("通用脚本",true)
    credits:Button("霖溺FPS",function()
    loadstring(game:HttpGet("https://shz.al/~FHHF"))()
end)
    credits:Button("飞行",function()
    loadstring(game:HttpGet("https://shz.al/~hhhh"))()
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
    credits:Button("踏空行走",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Float'))()
end)
    credits:Button("变玩家",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/XR4sGcgJ"))()
end)
    credits:Button("C00lgui",function()
    loadstring(game:GetObjects("rbxassetid://8127297852")[1].Source)()
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
    credits:Button("超高画质",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/jHBfJYmS"))()
end)
    credits:Button("飞车『霖溺』",function()
    loadstring(game:HttpGet("https://shz.al/~KISJS"))()
end)
    credits:Button("甩飞",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/GnvPVBEi"))()
end)
    credits:Button("人物转起来",function()
    loadstring(game:HttpGet('https://pastebin.com/raw/r97d7dS0', true))()
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
    credits:Button("Owl-Hub『嘿嘿』",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))()
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
    loadstring(game:HttpGet("https://raw.githubusercontent.com/jxdjbx/ggff/main/%E5%B8%85%E9%94%85%E4%B8%80%E6%9E%9A%E5%B0%8F%E5%8F%AF%E7%88%B1%E5%91%80%E5%8F%91%E8%B4%A7%E5%A5%BD%E7%9A%84%E5%90%83%E4%B8%8D%E5%90%83%E8%AE%B0%E5%BE%97%E8%AE%B0%E5%BE%97%E4%BD%A0%E6%96%B9%E4%BE%BF%E6%89%93%E5%BC%80%E7%94%B5%E8%84%91%E6%96%B9%E4%B8%8D%E6%96%B9%E4%BE%BF%E8%AE%B0%E5%BE%97%E9%83%BD%E8%A7%81%E4%B8%8D%E5%88%B0%E6%96%B9%E4%BE%BF%E7%9A%84%E8%AF%9D%E6%89%8B%E6%9C%BA%E6%96%B9%E4%B8%8D%E6%96%B9%E4%BE%BF%E5%B0%B1"))()
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
local credits = creds:section("脚本密钥链接https://keyrblx.com/getkey/ShifeScripts",true)
    credits:Button(" Shadow Hub V2",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Alexcirer/Alexcirer/main/V%20d"))()
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

local creds = window:Tab("力量传奇",'16060333448')

local credits = creds:section("自制为云脚本ui",true)
    credits:Button("霖溺力量传奇（来源白貓）",function()
    loadstring(game:HttpGet("https://shz.al/~baimaomeili"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("极速传奇",'16060333448')

local credits = creds:section("自制为云ui",true)
    credits:Button("霖溺自制极速传奇",function()
    loadstring(game:HttpGet("https://shz.al/~lninjj"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("监狱人生",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/mikeexc/Mike260/main/Mikeexc",true))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("自然灾害",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/9NLK7/93qjoadnlaknwldk/main/main'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("杀手于警长",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("杀手于警长（找的）",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/yadbPQUm",true))()
end)
    credits:Button("剑客脚本（通用）",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("巴掌",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("自动刷巴掌",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/ionlyusegithubformcmods/1-Line-Scripts/main/Slap%20Farm'))()
end)
    credits:Button("常用功能",function()
    loadstring(game:HttpGet("https://lkhub.net/s/loader.lua"))()
end)
    credits:Button("多功能（老外）",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/ionlyusegithubformcmods/1-Line-Scripts/main/Slap%20Battles")))()
end)

local creds = window:Tab("刀刃球",'16060333448')

local credits = creds:section("『LINNI Script』（听说的最强）",true)
    credits:Button("霖溺汉化刀刃球",function()
    loadstring(game:HttpGet("https://shz.al/75G8"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("战斗勇士",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("战斗勇士（英文电脑端，直接畅玩）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/frkfx/Combat-Warriors/main/Script"))()
end)
    credits:Button("战斗勇士英文",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/frkfx/Combat-Warriors/main/Script"))()
end)
    credits:Button("战斗勇士老外英文",function()
    loadstring(game:HttpGet("https://paste.gg/p/anonymous/697fc3cad5f743508318cb7399e89432/files/b5923e52edab4e5c91e46b74563d0ae8/raw"))()
end)
    credits:Button("战斗勇士老外",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/novahub"))()
end)
    credits:Button("战斗勇士老外KJ",function()
    loadstring(game:HttpGet("https://shz.al/~KSISI"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("p死亡球脚本",'16060333448')

local credits = creds:section("LINni脚本",true)
     credits:Button("死亡球脚本",function()
     loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/Ball1/main/Death"))()
end)
    credits:Button("死亡球脚本",function()
    loadstring(game:HttpGet("https://github.com/Hosvile/InfiniX/releases/latest/download/main.lua",true))()
end)

local creds = window:Tab("piggy脚本",'16060333448')

local credits = creds:section("piggy脚本",true)
    credits:Button("piggy脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Piggy/Loader.lua"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("彩虹朋友",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("彩虹朋友（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/XoNv04vR/raw"))()
end)
    credits:Button("彩虹朋友（推荐）",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Ihaveash0rtnamefordiscord/BorkWare/main/Scripts/' .. game.GameId .. ".lua"))(' Watermelon ? ')
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("Blox Fruit",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("BF『HOHO脚本汉化』",function()
    loadstring(game:HttpGet("https://shz.al/~xjixjx"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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

local creds = window:Tab("蜂群模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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

local creds = window:Tab("Drive World",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("Drive World脚本",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/x3fall3nangel/FallAngelHub/main/DriveWorld.lua"))()
end)

local creds = window:Tab("一路向西",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("霖溺二改『来源白』",function()
    loadstring(game:HttpGet("https://shz.al/~KSJSJ"))()
end)
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab(".,.77寻宝",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("霖溺二改『来源白』",function()
    loadstring(game:HttpGet("https://shz.al/~JISNS"))()
end)
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

local creds = window:Tab("DOORS",'16060333448')

local credits = creds:section("『LINNI Script』（最强只是听说）",true)
    credits:Button("霖溺自制Doors",function()
    loadstring(game:HttpGet("https://shz.al/yWFF"))()
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
    credits:Button("Doors（过room）",function()
    loadstring(game:HttpGet('\x68\x74\x74\x70\x73\x3A\x2F\x2F\x68\x2E\x6C\x6B\x6D\x63\x2E\x61\x73\x69\x61\x2F\x73\x63\x72\x69\x70\x74\x2F\x64\x6F\x6F\x72\x73\x72\x6F\x6F\x6D\x2E\x6C\x75\x61'))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("驾驶帝国",'16060333448')

local credits = creds:section("驾驶帝国脚本",true)
    credits:Button("驾驶帝国（英文）",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/zeuise0002/SSSWWW222/main/README.md'),true))()
end)
    credits:Button("驾驶帝国（英文）",function()
    loadstring(game:HttpGet("https://soggyhubv2.vercel.app"))()
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
    credits:Button("刺客脚本只适配FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("The rake",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("The rake电脑端",function()
    loadstring(game:HttpGet("https://realzzhub.xyz/script.lua"))()
end)

local creds = window:Tab("兵工厂",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("兵工厂1",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/RandomAdamYT/DarkHub/master/Init'), true))()
end)
    credits:Button("兵工厂Hub",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubArsenal"))("https://t.me/KrutoySuslik")
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("餐厅大亨",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("餐厅大亨（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/toosiwhip/snake-hub/main/restaurant-tycoon-2.lua"))()
end)
    credits:Button("餐厅大亨（名字相同脚本不同）",function()
    loadstring(game:HttpGet("https://pastefy.app/Ppqt0Gib/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("举重模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("举重模拟器",function()
    loadstring(game:HttpGet("https://pastefy.app/KSriAk53/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("怪兽宇宙",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("怪兽宇宙",function()
    loadstring(game:HttpGet("https://pastefy.app/oRWEIEcJ/raw"))()
end)

local creds = window:Tab("幸运方块",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("幸运方块",function()
    loadstring(game:HttpGet("https://pastefy.app/eAWNSTyw/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("寻宝模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("寻宝模拟器『霖溺汉化』",function()
    loadstring(game:HttpGet("https://shz.al/~MKS"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("最强战场",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("最强战场密钥找霖溺解",function()
    loaoostring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/SaitamaBattlegrounds.lua"))()
end)
    credits:Button("最强战场不确定能不能用",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Scripterbacon/TSBobfuscator/main/Main.Lua"))()
end)
    credits:Button("最强战场（英文）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/LOLking123456/Strongest/main/Battlegrounds77"))()
end)
    credits:Button("上面那个英文最强战场点我复制密钥",function()
    setclipboard("BestTheStrongest5412Roblox")
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("恐怖奶奶",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("恐怖奶奶",function()
    loadstring(game:HttpGet("https://pastefy.app/o688Jvmn/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("极速奔驰",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("极速奔驰",function()
    loadstring(game:HttpGet("https://pastefy.app/Y7607jwb/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("射击光束模拟器",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("射击光束模拟器",function()
    loadstring(game:HttpGet("https://pastefy.app/51yMuaCc/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("合并滴管",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("合并滴管",function()
    loadstring(game:HttpGet("https://pastefy.app/NpBrBCqM/raw"))()
end)
    credits:Button("剑客脚本",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
end)

local creds = window:Tab("活过杀手",'16060333448')

local credits = creds:section("『LINNI Script』",true)
    credits:Button("活过杀手（垃圾）",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Milan08Studio/ChairWare/main/main.lua"))()
end)
    credits:Button("剑客脚本（里面的通用）",function()
    jianke_V4 = "作者_初夏"jianke__V4 = "作者QQ1412152634"jianke___V4 = "剑客QQ群347724155"loadstring(game:HttpGet(('https://shz.al/~JianKeV4')))()
end)
    credits:Button("刺客脚本只适配忍者和FL注入器",function()
    loadstring(game:HttpGet("https://shz.al/~CikeScriptfree"))()
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
game.Players.LocalPlayer:Kick("『LINNI Script』加群493057142找管理要白名单，霖溺脚本永久免费，群友要我找脚本，我也会去")--踢人函数
   end
    
