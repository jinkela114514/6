local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {

    Title = "确认身份",

    Text = "正在验证....",

    Duration = 3, 

})

local a=tostring(game.Players.LocalPlayer.Character);

if a=="dkfkfkfjfkfjdj"then

_G.she=true

elseif a=="ljgjhfsfhcdf"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

elseif a=="用户名"then

_G.she=true

end

if _G.she==true then

    local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {

    Title = "验证结果",

    Text = a.."验证身份成功",

    Duration = 5,

})

wait(3.5)

local OrionLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/sharksharksharkshark/Hub/main/1lolll.txt"))()

local LBLG = Instance.new("ScreenGui", getParent)

local LBL = Instance.new("TextLabel", getParent)

local player = game.Players.LocalPlayer

LBLG.Name = "LBLG"

LBLG.Parent = game.CoreGui

LBLG.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

LBLG.Enabled = true

LBL.Name = "LBL"

LBL.Parent = LBLG

LBL.BackgroundColor3 = Color3.new(1, 1, 1)

LBL.BackgroundTransparency = 1

LBL.BorderColor3 = Color3.new(0, 0, 0)

LBL.Position = UDim2.new(0.75,0,0.010,0)

LBL.Size = UDim2.new(0, 133, 0, 30)

LBL.Font = Enum.Font.GothamSemibold

LBL.Text = "TextLabel"

LBL.TextColor3 = Color3.new(1, 1, 1)

LBL.TextScaled = true

LBL.TextSize = 14

LBL.TextWrapped = true

LBL.Visible = true

local FpsLabel = LBL

local Heartbeat = game:GetService("RunService").Heartbeat

local LastIteration, Start

local FrameUpdateTable = { }

local function HeartbeatUpdate()

	LastIteration = tick()	for Index = #FrameUpdateTable, 1, -1 do

		FrameUpdateTable[Index + 1] = (FrameUpdateTable[Index] >= LastIteration - 1) and FrameUpdateTable[Index] or nil

	end

	FrameUpdateTable[1] = LastIteration

	local CurrentFPS = (tick() - Start >= 1 and #FrameUpdateTable) or (#FrameUpdateTable / (tick() - Start))

	CurrentFPS = CurrentFPS - CurrentFPS % 1

	FpsLabel.Text = ("北京时间:"..os.date("%H").."时"..os.date("%M").."分"..os.date("%S"))

end

Start = tick()

Heartbeat:Connect(HeartbeatUpdate)

local Window = OrionLib:MakeWindow({Name = "选择", HidePremium = false, SaveConfig = false, IntroText = "选择菜单:注入器为："..identifyexecutor(), ConfigFolder = "选择"})

local OrionLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/shlexware/Orion/main/source"))()

local OrionLib = loadstring(game:HttpGet('https://raw.githubusercontent.com/WS857960/-/main/UI.txt'))()

local Window = OrionLib:MakeWindow({Name = "缝合中心", HidePremium = false, SaveConfig = true, ConfigFolder = "测试脚本"})

local about = Window:MakeTab({

    Name = "小天制作",

    Icon = "rbxassetid://4483345998",

    PremiumOnly = false

})

about:AddParagraph("该脚本为测试版")

about:AddParagraph("脚本为免费脚本 请勿去圈钱")

about:AddParagraph("作者:测试 ")

about:AddParagraph("帮助者:？？？？？？ ")

about:AddParagraph("帮助者QQ:无")

about:AddParagraph("作者QQ:32362798")

about:AddParagraph("禁止倒卖")

local Tab =Window:MakeTab({

	Name = "关于作者",

	Icon = "rbxassetid://4483345998",

	PremiumOnly = false

})

Tab:AddButton({

	Name = "复制作者QQ",

	Callback = function()

     setclipboard("323627983")

  	end

})

OrionLib:MakeNotification({

	Name = "小天脚本",

	Content = "欢迎使用小天脚本",

	Image = "rbxassetid://4483345998",

	Time = 2

})

local Tab =Window:MakeTab({

    Name = "通用",

	Icon = "rbxassetid://323627983",

	PremiumOnly = false

})

Tab:AddTextbox({

	Name = "移动速度",

	Default = "",

	TextDisappear = true,

	Callback = function(Value)

		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value

	end

})

Tab:AddTextbox({

	Name = "跳跃高度",

	Default = "",

	TextDisappear = true,

	Callback = function(Value)

		game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value

	end

})

Tab:AddButton({

    Name = "隐身按E",

	Callback = function()

	 loadstring(game:HttpGet('https://pastebin.com/raw/nwGEvkez'))()

	end

})

Tab:AddButton({

    Name = "飞车",

	Callback = function()

	loadstring(game:HttpGet("https://pastebin.com/raw/MHE1cbWF"))()

	end

})

Tab:AddButton({

	Name = "飞行V3（隐藏）",

	Callback = function()

    loadstring(game:HttpGet('https://pastebin.com/raw/U27yQRxS'))()

  	end    

})

Tab:AddButton({

	Name = "透视",

	Callback = function()

loadstring(game:GetObjects("rbxassetid://10092697033")[1].Source)()

	end 

})

Tab:AddToggle({

	Name = "穿墙",

	Default = false,

	Callback = function(Value)

		if Value then

		    Noclip = true

		    Stepped = game.RunService.Stepped:Connect(function()

			    if Noclip == true then

				    for a, b in pairs(game.Workspace:GetChildren()) do

                        if b.Name == game.Players.LocalPlayer.Name then

                            for i, v in pairs(game.Workspace[game.Players.LocalPlayer.Name]:GetChildren()) do

                                if v:IsA("BasePart") then

                                    v.CanCollide = false

                                end

                            end

                        
