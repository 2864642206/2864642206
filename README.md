local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "脚本中心", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local plrs = game:GetService("Players")
local plr = plrs.LocalPlayer
local TeleportService = game:GetService('TeleportService')
local Gui = Instance.new("ScreenGui")
local Message = game:GetService("StarterGui")
local TweenService = game:GetService('TweenService')
local CoreGui = game:GetService('CoreGui')

local Tab = Window:MakeTab({
	Name = "免费",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "林",
	Callback = function()
lin = "作者林"lin ="林QQ群 747623342"loadstring(game:HttpGet("https://raw.githubusercontent.com/linnblin/lin/main/lin"))() 
    end    
})

Tab:AddButton({
	Name = "青",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/kkaaccnnbb/money/main/fix'))()
    end    
})

Tab:AddButton({
	Name = "XSC卡密小写（a)",
	Callback = function()
getgenv().XC="作者XC"loadstring(game:HttpGet("https://pastebin.com/raw/PAFzYx0F"))()
    end    
})

local Tab = Window:MakeTab({
	Name = "要白名单",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "白脚本最新",
	Callback = function()
_G["白脚本作者修狗"]="xdjhadgdsrfcyefjhsadcctyseyr6432478rudghfvszhxcaheey"loadstring(game:HttpGet(('https://raw.githubusercontent.com/wev666666/baijiaobengV2.0beta/main/%E7%99%BD%E8%84%9A%E6%9C%ACbeta'),true))()
    end    
})

local Tab = Window:MakeTab({
	Name = "bf",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "蔚蓝(英文）",
	Callback = function()
getgenv().Team = "Pirates"
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
    end    
})

Tab:AddButton({
	Name = "菜鸟狗子(英文）",
	Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/KindIhave/ChibaHuB/main/Chiba-BF.txt'))()
    end    
})

Tab:AddButton({
	Name = "bf中文(可以用来打本）",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/XiaoYunCN/Xiao-Yun-UWU/main/%E6%B5%B7%E8%B4%BC%E7%8E%8Bbf.lua", true))()
    end    
})


OrionLib:Init()
