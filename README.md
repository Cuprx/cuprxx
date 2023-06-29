-- Farewell infortality 
-- Revamp by ImFrostic, Version 2.8 
 
 -- Objects

local Cuprx = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local NosyliamAdmin = Instance.new("TextButton")
local ScrollingGUIV2 = Instance.new("TextButton")
local BubbleBike = Instance.new("TextButton")

-- Properties

Cuprx.Name = "Cuprx"
Cuprx.Parent = game.CoreGui

MainFrame.Name = "MainFrame"
MainFrame.Parent = Cuprx
MainFrame.Active = true
MainFrame.BackgroundColor3 = Color3.new(1, 1, 1)
MainFrame.Position = UDim2.new(2.32830644e-09, 0, 0.536674798, 0)
MainFrame.Size = UDim2.new(0, 471, 0, 379)

Frame.Parent = MainFrame
Frame.BackgroundColor3 = Color3.new(1, 1, 1)
Frame.Position = UDim2.new(0, 0, 0.124010555, 0)
Frame.Size = UDim2.new(0, 471, 0, 8)

TextLabel.Parent = MainFrame
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.Size = UDim2.new(0, 471, 0, 47)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Cuprx"
TextLabel.TextScaled = true
TextLabel.TextSize = 14
TextLabel.TextWrapped = true

NosyliamAdmin.Name = "NosyliamAdmin"
NosyliamAdmin.Parent = MainFrame
NosyliamAdmin.BackgroundColor3 = Color3.new(0.862745, 1, 0.486275)
NosyliamAdmin.Position = UDim2.new(0, 0, 0.242744058, 0)
NosyliamAdmin.Size = UDim2.new(0, 200, 0, 50)
NosyliamAdmin.Font = Enum.Font.SourceSans
NosyliamAdmin.Text = "NosyliamAdmin"
NosyliamAdmin.TextSize = 14

ScrollingGUIV2.Name = "ScrollingGUIV2"
ScrollingGUIV2.Parent = MainFrame
ScrollingGUIV2.BackgroundColor3 = Color3.new(0.862745, 1, 0.486275)
ScrollingGUIV2.Position = UDim2.new(0.549893856, 0, 0.242744058, 0)
ScrollingGUIV2.Size = UDim2.new(0, 200, 0, 50)
ScrollingGUIV2.Font = Enum.Font.SourceSans
ScrollingGUIV2.Text = "ScrollingGUIV2"
ScrollingGUIV2.TextSize = 14

BubbleBike.Name = "BubbleBike"
BubbleBike.Parent = MainFrame
BubbleBike.BackgroundColor3 = Color3.new(0.862745, 1, 0.486275)
BubbleBike.Position = UDim2.new(0.184713379, 0, 0.546174109, 0)
BubbleBike.Size = UDim2.new(0, 296, 0, 74)
BubbleBike.Font = Enum.Font.SourceSans
BubbleBike.Text = "BubbleBike"
BubbleBike.TextSize = 14

-- Scripts 

NosyliamAdmin.MouseButton1Down:connect(function() 
loadstring(game:HttpGet(('https://pastebin.com/raw/4DKTH411'),true))()
end)

ScrollingGUIV2.MouseButton1Down:connect(function() 
loadstring(game:HttpGet(('https://pastebin.com/raw/97TXnf4T'),true))()
end)

BubbleBike.MouseButton1Down:connect(function() 
loadstring(game:HttpGet(('https://pastebin.com/raw/LFFYmGzH'),true))()
end)
