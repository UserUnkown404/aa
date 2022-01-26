-- Notify


-- Instances:

local NotifyShitHub = Instance.new("ScreenGui")
local NotifyBackground = Instance.new("ScrollingFrame")
local Notify = Instance.new("Frame")
local AdminstratorRank = Instance.new("TextLabel")
local AccesText = Instance.new("TextLabel")
local Frame = Instance.new("Frame")

--Properties:

NotifyShitHub.Name = "NotifyShitHub"
NotifyShitHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
NotifyShitHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

NotifyBackground.Name = "NotifyBackground"
NotifyBackground.Parent = NotifyShitHub
NotifyBackground.Active = true
NotifyBackground.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NotifyBackground.BackgroundTransparency = 1.000
NotifyBackground.Position = UDim2.new(0.5, -156, 0.5, -76)
NotifyBackground.Size = UDim2.new(0, 312, 0, 152)
NotifyBackground.BottomImage = ""
NotifyBackground.MidImage = ""
NotifyBackground.ScrollBarThickness = 0
NotifyBackground.ScrollingEnabled = false
NotifyBackground.TopImage = ""

Notify.Name = "Notify"
Notify.Parent = NotifyBackground
Notify.BackgroundColor3 = Color3.fromRGB(118, 118, 118)
Notify.Position = UDim2.new(-0.685000002, 0, -0.0743021816, 0)
Notify.Size = UDim2.new(0, 776, 0, 66)

AdminstratorRank.Name = "AdminstratorRank"
AdminstratorRank.Parent = Notify
AdminstratorRank.BackgroundColor3 = Color3.fromRGB(136, 136, 136)
AdminstratorRank.Position = UDim2.new(0.350515485, 0, 0, 0)
AdminstratorRank.Size = UDim2.new(0, 182, 0, 28)
AdminstratorRank.Font = Enum.Font.Fantasy
AdminstratorRank.Text = "Administrator Rank"
AdminstratorRank.TextColor3 = Color3.fromRGB(66, 66, 66)
AdminstratorRank.TextScaled = true
AdminstratorRank.TextSize = 14.000
AdminstratorRank.TextWrapped = true

AccesText.Name = "AccesText"
AccesText.Parent = Notify
AccesText.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AccesText.BorderColor3 = Color3.fromRGB(0, 0, 0)
AccesText.Position = UDim2.new(0.282216549, 0, 0.409091145, 0)
AccesText.Size = UDim2.new(0, 301, 0, 21)
AccesText.Font = Enum.Font.SciFi
AccesText.Text = "You now Have Acces to Shit Hub."
AccesText.TextColor3 = Color3.fromRGB(207, 207, 207)
AccesText.TextScaled = true
AccesText.TextSize = 14.000
AccesText.TextWrapped = true

Frame.Parent = Notify
Frame.BackgroundColor3 = Color3.fromRGB(0, 144, 216)
Frame.BorderColor3 = Color3.fromRGB(0, 144, 216)
Frame.Position = UDim2.new(0.228092819, 0, 0.818182051, 0)
Frame.Size = UDim2.new(0, 378, 0, 12)

-- Scripts:

local function QUIF_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	wait(2)
	script.Parent.Parent.Frame:TweenPosition(UDim2.new(0.688, 0,0.818, 0))
	
	
end
coroutine.wrap(QUIF_fake_script)()
local function HADRUXL_fake_script() -- Notify.LocalScript 
	local script = Instance.new('LocalScript', Notify)

	local object = script.Parent
	
	wait(0)
	
	object:TweenPosition(UDim2.new(-0.685, 0,0.042, 0))
	
	wait(3.0)
	
	object:TweenPosition(UDim2.new(-0.685, 0,0.198, 0))
end
coroutine.wrap(HADRUXL_fake_script)()

wait(6)

--MainScript

-- Instances:

local AdminUniversal = Instance.new("ScreenGui")
local Main = Instance.new("ImageLabel")
local Frame = Instance.new("ImageLabel")
local ImageLabel = Instance.new("ImageLabel")
local UserProfile = Instance.new("ImageLabel")
local GetUsername = Instance.new("TextLabel")
local GetUsername_2 = Instance.new("TextLabel")
local Playercount = Instance.new("TextLabel")
local ServerStatus = Instance.new("TextLabel")
local Barline1 = Instance.new("Frame")
local AdministratorsIngame = Instance.new("TextLabel")
local Display = Instance.new("TextLabel")
local Barlineshort2 = Instance.new("Frame")
local AdministratorsIngame_2 = Instance.new("TextLabel")
local Selecttab = Instance.new("Frame")
local Exit = Instance.new("TextButton")
local OpenSelections = Instance.new("ScrollingFrame")
local openselecttab = Instance.new("TextButton")
local TeleportTab = Instance.new("ImageLabel")
local TeleportTabUp = Instance.new("Frame")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Lava = Instance.new("TextButton")
local SafeBeachHut = Instance.new("TextButton")
local SafeVolcanoPlace = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local VolcanoIsland = Instance.new("TextButton")
local Camp = Instance.new("TextButton")
local Ocean = Instance.new("TextButton")
local Tittle = Instance.new("TextLabel")
local Beach = Instance.new("TextButton")
local Frame_2 = Instance.new("Frame")
local Frame_3 = Instance.new("Frame")
local Frame_4 = Instance.new("Frame")
local Frame_5 = Instance.new("Frame")
local Frame_6 = Instance.new("Frame")
local Frame_7 = Instance.new("Frame")
local Frame_8 = Instance.new("Frame")
local Frame_9 = Instance.new("Frame")
local Frame_10 = Instance.new("Frame")
local Frame_11 = Instance.new("Frame")
local Frame_12 = Instance.new("Frame")
local Frame_13 = Instance.new("Frame")
local Frame_14 = Instance.new("Frame")
local Frame_15 = Instance.new("Frame")
local Frame_16 = Instance.new("Frame")
local Frame_17 = Instance.new("Frame")
local Frame_18 = Instance.new("Frame")
local Frame_19 = Instance.new("Frame")
local Frame_20 = Instance.new("Frame")
local Frame_21 = Instance.new("Frame")
local Frame_22 = Instance.new("Frame")
local GameTab = Instance.new("ImageLabel")
local GameTabUp = Instance.new("Frame")
local ScrollingFrame_2 = Instance.new("ScrollingFrame")
local Unburn = Instance.new("TextButton")
local Tittle_2 = Instance.new("TextLabel")
local ObtainLava = Instance.new("TextButton")
local Frame_23 = Instance.new("Frame")
local ExtraTab = Instance.new("ImageLabel")
local ExtraTabUp = Instance.new("Frame")
local ScrollingFrame_3 = Instance.new("ScrollingFrame")
local Tittle_3 = Instance.new("TextLabel")
local InfYeild = Instance.new("TextButton")
local Frame_24 = Instance.new("Frame")
local SelectFrame = Instance.new("ImageLabel")
local SelectionUpFrame = Instance.new("Frame")
local SelectionDownFrame = Instance.new("Frame")
local Home = Instance.new("TextButton")
local Teleport = Instance.new("TextButton")
local Game = Instance.new("TextButton")
local Extra = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")

--Properties:
AdminUniversal.Name = "AdminUniversal"
AdminUniversal.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
AdminUniversal.ResetOnSpawn = false

AdminUniversal.Name = "AdminUniversal"
AdminUniversal.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Main.Name = "Main"
Main.Parent = AdminUniversal
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BackgroundTransparency = 1.000
Main.Position = UDim2.new(0.5, -225, 0.5, -141)
Main.Size = UDim2.new(0, 451, 0, 282)
Main.Image = "rbxassetid://3570695787"
Main.ImageColor3 = Color3.fromRGB(58, 58, 58)
Main.ScaleType = Enum.ScaleType.Slice
Main.SliceCenter = Rect.new(100, 100, 100, 100)
Main.SliceScale = 0.120

Frame.Name = "Frame"
Frame.Parent = Main
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Size = UDim2.new(0, 451, 0, 41)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(58, 58, 58)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120

ImageLabel.Parent = Main
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(0.017738359, 0, 0.145390064, 0)
ImageLabel.Size = UDim2.new(0, 437, 0, 120)
ImageLabel.Image = "http://www.roblox.com/asset/?id=5107147421"

UserProfile.Name = "UserProfile"
UserProfile.Parent = ImageLabel
UserProfile.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
UserProfile.Position = UDim2.new(0.434782594, 0, 0.166666672, 0)
UserProfile.Size = UDim2.new(0, 50, 0, 50)
UserProfile.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

GetUsername.Name = "GetUsername"
GetUsername.Parent = ImageLabel
GetUsername.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GetUsername.BackgroundTransparency = 1.000
GetUsername.Position = UDim2.new(0.267734557, 0, 0.583333313, 0)
GetUsername.Size = UDim2.new(0.482582211, 0, 0.201516524, 0)
GetUsername.Font = Enum.Font.Ubuntu
GetUsername.Text = "Loading Username..."
GetUsername.TextColor3 = Color3.fromRGB(244, 244, 244)
GetUsername.TextScaled = true
GetUsername.TextSize = 14.000
GetUsername.TextWrapped = true

GetUsername_2.Name = "GetUsername"
GetUsername_2.Parent = ImageLabel
GetUsername_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GetUsername_2.BackgroundTransparency = 1.000
GetUsername_2.Position = UDim2.new(0.267734557, 0, 0.784849823, 0)
GetUsername_2.Size = UDim2.new(0.482582211, 0, 0.215150252, 0)
GetUsername_2.Font = Enum.Font.Ubuntu
GetUsername_2.Text = "Administrator"
GetUsername_2.TextColor3 = Color3.fromRGB(244, 244, 244)
GetUsername_2.TextScaled = true
GetUsername_2.TextSize = 14.000
GetUsername_2.TextWrapped = true

Playercount.Name = "Playercount"
Playercount.Parent = Main
Playercount.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Playercount.BackgroundTransparency = 1.000
Playercount.BorderColor3 = Color3.fromRGB(0, 0, 0)
Playercount.Position = UDim2.new(0.0199556537, 0, 0.666666687, 0)
Playercount.Size = UDim2.new(0.968957901, 0, 0.0957446918, 0)
Playercount.Font = Enum.Font.Ubuntu
Playercount.Text = "Player count"
Playercount.TextColor3 = Color3.fromRGB(255, 255, 255)
Playercount.TextSize = 21.000
Playercount.TextXAlignment = Enum.TextXAlignment.Left

ServerStatus.Name = "ServerStatus"
ServerStatus.Parent = Main
ServerStatus.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerStatus.BackgroundTransparency = 1.000
ServerStatus.Position = UDim2.new(0.017738359, 0, 0.595744669, 0)
ServerStatus.Size = UDim2.new(0, 423, 0, 20)
ServerStatus.Font = Enum.Font.SourceSans
ServerStatus.Text = "Server Status"
ServerStatus.TextColor3 = Color3.fromRGB(255, 255, 255)
ServerStatus.TextSize = 33.000
ServerStatus.TextTransparency = 0.630
ServerStatus.TextWrapped = true
ServerStatus.TextXAlignment = Enum.TextXAlignment.Left

Barline1.Name = "Barline1"
Barline1.Parent = Main
Barline1.BackgroundColor3 = Color3.fromRGB(213, 213, 213)
Barline1.BorderColor3 = Color3.fromRGB(113, 113, 113)
Barline1.Position = UDim2.new(0.024390243, 0, 0.762411356, 0)
Barline1.Size = UDim2.new(0, 434, 0, 0)

AdministratorsIngame.Name = "AdministratorsIngame"
AdministratorsIngame.Parent = Main
AdministratorsIngame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AdministratorsIngame.BackgroundTransparency = 1.000
AdministratorsIngame.BorderColor3 = Color3.fromRGB(0, 0, 0)
AdministratorsIngame.Position = UDim2.new(0.0199556537, 0, 0.762411356, 0)
AdministratorsIngame.Size = UDim2.new(0.968957901, 0, 0.0815602913, 0)
AdministratorsIngame.Font = Enum.Font.Ubuntu
AdministratorsIngame.Text = "Administrators Ingame                                             1"
AdministratorsIngame.TextColor3 = Color3.fromRGB(255, 255, 255)
AdministratorsIngame.TextSize = 21.000
AdministratorsIngame.TextXAlignment = Enum.TextXAlignment.Left

Display.Name = "Display"
Display.Parent = Main
Display.BackgroundTransparency = 1.000
Display.Position = UDim2.new(0.711751699, -100, 0.842198551, 0)
Display.Size = UDim2.new(0.796961904, 0, 0.0921985805, 0)
Display.SizeConstraint = Enum.SizeConstraint.RelativeYY
Display.Text = "000 Hours, 00 Minutes, 00 Seconds"
Display.TextColor3 = Color3.fromRGB(255, 255, 255)
Display.TextScaled = true
Display.TextSize = 9.000
Display.TextWrapped = true

Barlineshort2.Name = "Barlineshort2"
Barlineshort2.Parent = Main
Barlineshort2.BackgroundColor3 = Color3.fromRGB(213, 213, 213)
Barlineshort2.BorderColor3 = Color3.fromRGB(113, 113, 113)
Barlineshort2.Position = UDim2.new(0.024390243, 0, 0.84397161, 0)
Barlineshort2.Size = UDim2.new(0, 260, 0, 0)

AdministratorsIngame_2.Name = "AdministratorsIngame"
AdministratorsIngame_2.Parent = Main
AdministratorsIngame_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AdministratorsIngame_2.BackgroundTransparency = 1.000
AdministratorsIngame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
AdministratorsIngame_2.Position = UDim2.new(0.0199556462, 0, 0.840425611, 0)
AdministratorsIngame_2.Size = UDim2.new(0.968957901, 0, 0.0815602913, 0)
AdministratorsIngame_2.Font = Enum.Font.Ubuntu
AdministratorsIngame_2.Text = "Server uptime"
AdministratorsIngame_2.TextColor3 = Color3.fromRGB(255, 255, 255)
AdministratorsIngame_2.TextSize = 21.000
AdministratorsIngame_2.TextXAlignment = Enum.TextXAlignment.Left

Selecttab.Name = "Selecttab"
Selecttab.Parent = Main
Selecttab.BackgroundColor3 = Color3.fromRGB(58, 58, 58)
Selecttab.BorderColor3 = Color3.fromRGB(58, 58, 58)
Selecttab.Position = UDim2.new(0.00665188488, 0, 0.145390064, 0)
Selecttab.Size = UDim2.new(0, 5, 0, 233)

Exit.Name = "Exit"
Exit.Parent = Main
Exit.BackgroundColor3 = Color3.fromRGB(58, 58, 58)
Exit.BorderColor3 = Color3.fromRGB(58, 58, 58)
Exit.Position = UDim2.new(0.89578712, 0, 0.0212765951, 0)
Exit.Size = UDim2.new(0, 41, 0, 24)
Exit.Font = Enum.Font.SourceSans
Exit.Text = "X"
Exit.TextColor3 = Color3.fromRGB(240, 240, 240)
Exit.TextSize = 23.000

OpenSelections.Name = "OpenSelections"
OpenSelections.Parent = Main
OpenSelections.Active = true
OpenSelections.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OpenSelections.BackgroundTransparency = 1.000
OpenSelections.Size = UDim2.new(0, 464, 0, 281)
OpenSelections.MidImage = ""
OpenSelections.ScrollBarThickness = 0
OpenSelections.ScrollingEnabled = false
OpenSelections.TopImage = ""

openselecttab.Name = "openselecttab"
openselecttab.Parent = OpenSelections
openselecttab.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
openselecttab.BackgroundTransparency = 1.000
openselecttab.Position = UDim2.new(0.0224104971, 0, 0.00758771086, 0)
openselecttab.Size = UDim2.new(0, 34, 0, 32)
openselecttab.Font = Enum.Font.SourceSans
openselecttab.Text = "="
openselecttab.TextColor3 = Color3.fromRGB(255, 255, 255)
openselecttab.TextScaled = true
openselecttab.TextSize = 14.000
openselecttab.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
openselecttab.TextStrokeTransparency = 0.930
openselecttab.TextWrapped = true

TeleportTab.Name = "TeleportTab"
TeleportTab.Parent = OpenSelections
TeleportTab.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TeleportTab.BackgroundTransparency = 1.000
TeleportTab.Position = UDim2.new(0.00215517241, 0, 0.0722814798, 0)
TeleportTab.Size = UDim2.new(0, 453, 0, 241)
TeleportTab.Visible = false
TeleportTab.Image = "rbxassetid://3570695787"
TeleportTab.ImageColor3 = Color3.fromRGB(26, 26, 26)
TeleportTab.ScaleType = Enum.ScaleType.Slice
TeleportTab.SliceCenter = Rect.new(100, 100, 100, 100)
TeleportTab.SliceScale = 0.120

TeleportTabUp.Name = "TeleportTabUp"
TeleportTabUp.Parent = TeleportTab
TeleportTabUp.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
TeleportTabUp.BorderColor3 = Color3.fromRGB(26, 26, 26)
TeleportTabUp.Position = UDim2.new(0, 0, 0.000967825123, 0)
TeleportTabUp.Size = UDim2.new(0, 450, 0, 19)

ScrollingFrame.Parent = TeleportTab
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
ScrollingFrame.BorderColor3 = Color3.fromRGB(26, 26, 26)
ScrollingFrame.Position = UDim2.new(0.0406342559, 0, 0.0881047547, 0)
ScrollingFrame.Size = UDim2.new(0, 431, 0, 220)
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 3, 0)

Lava.Name = "Lava"
Lava.Parent = ScrollingFrame
Lava.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Lava.BorderColor3 = Color3.fromRGB(26, 26, 26)
Lava.Position = UDim2.new(0.00239907205, 0, 0.478340268, 0)
Lava.Size = UDim2.new(0, 427, 0, 53)
Lava.Font = Enum.Font.SourceSans
Lava.Text = " Lava                                                                                                                     Teleport to Lava"
Lava.TextColor3 = Color3.fromRGB(171, 171, 171)
Lava.TextScaled = true
Lava.TextSize = 14.000
Lava.TextWrapped = true
Lava.TextXAlignment = Enum.TextXAlignment.Left

SafeBeachHut.Name = "Safe Beach Hut"
SafeBeachHut.Parent = ScrollingFrame
SafeBeachHut.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
SafeBeachHut.BorderColor3 = Color3.fromRGB(26, 26, 26)
SafeBeachHut.Position = UDim2.new(-0.00228074146, 0, 0.692878306, 0)
SafeBeachHut.Size = UDim2.new(0, 427, 0, 53)
SafeBeachHut.Font = Enum.Font.SourceSans
SafeBeachHut.Text = " Safe Beach Hut                                                                                                                     Teleport to Safe"
SafeBeachHut.TextColor3 = Color3.fromRGB(171, 171, 171)
SafeBeachHut.TextScaled = true
SafeBeachHut.TextSize = 14.000
SafeBeachHut.TextWrapped = true
SafeBeachHut.TextXAlignment = Enum.TextXAlignment.Left

SafeVolcanoPlace.Name = "SafeVolcanoPlace"
SafeVolcanoPlace.Parent = ScrollingFrame
SafeVolcanoPlace.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
SafeVolcanoPlace.BorderColor3 = Color3.fromRGB(26, 26, 26)
SafeVolcanoPlace.Position = UDim2.new(-0.00424129888, 0, 0.583273888, 0)
SafeVolcanoPlace.Size = UDim2.new(0, 427, 0, 53)
SafeVolcanoPlace.Font = Enum.Font.SourceSans
SafeVolcanoPlace.Text = " Safe Volcano Place                                                                                                                     Teleport to Safe"
SafeVolcanoPlace.TextColor3 = Color3.fromRGB(171, 171, 171)
SafeVolcanoPlace.TextScaled = true
SafeVolcanoPlace.TextSize = 14.000
SafeVolcanoPlace.TextWrapped = true
SafeVolcanoPlace.TextXAlignment = Enum.TextXAlignment.Left

Volcano.Name = "Volcano"
Volcano.Parent = ScrollingFrame
Volcano.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Volcano.BorderColor3 = Color3.fromRGB(26, 26, 26)
Volcano.Position = UDim2.new(0.00235962309, 0, 0.378505617, 0)
Volcano.Size = UDim2.new(0, 427, 0, 53)
Volcano.Font = Enum.Font.SourceSans
Volcano.Text = " Volcano                                                                                                                      Teleport to the side of the volcano          "
Volcano.TextColor3 = Color3.fromRGB(171, 171, 171)
Volcano.TextScaled = true
Volcano.TextSize = 14.000
Volcano.TextWrapped = true
Volcano.TextXAlignment = Enum.TextXAlignment.Left

VolcanoIsland.Name = "VolcanoIsland"
VolcanoIsland.Parent = ScrollingFrame
VolcanoIsland.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
VolcanoIsland.BorderColor3 = Color3.fromRGB(26, 26, 26)
VolcanoIsland.Position = UDim2.new(-0.00228074542, 0, 0.275028288, 0)
VolcanoIsland.Size = UDim2.new(0, 427, 0, 53)
VolcanoIsland.Font = Enum.Font.SourceSans
VolcanoIsland.Text = " Volcano Island                                                                                                                     Teleport to an Island"
VolcanoIsland.TextColor3 = Color3.fromRGB(171, 171, 171)
VolcanoIsland.TextScaled = true
VolcanoIsland.TextSize = 14.000
VolcanoIsland.TextWrapped = true
VolcanoIsland.TextXAlignment = Enum.TextXAlignment.Left

Camp.Name = "Camp"
Camp.Parent = ScrollingFrame
Camp.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Camp.BorderColor3 = Color3.fromRGB(26, 26, 26)
Camp.Position = UDim2.new(-0.00196055998, 0, 0.895486236, 0)
Camp.Size = UDim2.new(0, 427, 0, 53)
Camp.Font = Enum.Font.SourceSans
Camp.Text = " Camp                                                                                                                     Teleport to Camp"
Camp.TextColor3 = Color3.fromRGB(171, 171, 171)
Camp.TextScaled = true
Camp.TextSize = 14.000
Camp.TextWrapped = true
Camp.TextXAlignment = Enum.TextXAlignment.Left

Ocean.Name = "Ocean"
Ocean.Parent = ScrollingFrame
Ocean.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Ocean.BorderColor3 = Color3.fromRGB(26, 26, 26)
Ocean.Position = UDim2.new(-0.00220185611, 0, 0.796038747, 0)
Ocean.Size = UDim2.new(0, 427, 0, 53)
Ocean.Font = Enum.Font.SourceSans
Ocean.Text = " Ocean                                                                                                                     Teleport to the empty Ocean"
Ocean.TextColor3 = Color3.fromRGB(171, 171, 171)
Ocean.TextScaled = true
Ocean.TextSize = 14.000
Ocean.TextWrapped = true
Ocean.TextXAlignment = Enum.TextXAlignment.Left

Tittle.Name = "Tittle"
Tittle.Parent = ScrollingFrame
Tittle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Tittle.BackgroundTransparency = 1.000
Tittle.Position = UDim2.new(0.00470700022, 0, 0.0481409468, 0)
Tittle.Size = UDim2.new(0, 200, 0, 51)
Tittle.Font = Enum.Font.SourceSans
Tittle.Text = "Teleport"
Tittle.TextColor3 = Color3.fromRGB(102, 102, 102)
Tittle.TextScaled = true
Tittle.TextSize = 14.000
Tittle.TextWrapped = true
Tittle.TextXAlignment = Enum.TextXAlignment.Left

Beach.Name = "Beach"
Beach.Parent = ScrollingFrame
Beach.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Beach.BorderColor3 = Color3.fromRGB(26, 26, 26)
Beach.Position = UDim2.new(0.00238676975, 0, 0.170954362, 0)
Beach.Size = UDim2.new(0, 427, 0, 53)
Beach.Font = Enum.Font.SourceSans
Beach.Text = " Beach                                                                                                                     Teleport to Lobby"
Beach.TextColor3 = Color3.fromRGB(171, 171, 171)
Beach.TextScaled = true
Beach.TextSize = 14.000
Beach.TextWrapped = true
Beach.TextXAlignment = Enum.TextXAlignment.Left

Frame_2.Parent = ScrollingFrame
Frame_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_2.Position = UDim2.new(-0.0277633481, 0, 0.882262588, 0)
Frame_2.Size = UDim2.new(0, 406, 0, 0)

Frame_3.Parent = ScrollingFrame
Frame_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_3.Position = UDim2.new(0.0620147064, 0, NAN, 0)
Frame_3.Size = UDim2.new(0, 406, 0, 0)

Frame_4.Parent = ScrollingFrame
Frame_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_4.Position = UDim2.new(0.106807411, 0, 0.882262588, 0)
Frame_4.Size = UDim2.new(0, 406, 0, 0)

Frame_5.Parent = ScrollingFrame
Frame_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_5.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_5.Position = UDim2.new(0.0205127615, 0, 0.779441237, 0)
Frame_5.Size = UDim2.new(0, 406, 0, 0)

Frame_6.Parent = ScrollingFrame
Frame_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_6.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_6.Position = UDim2.new(-0.00268909545, 0, 0.779441237, 0)
Frame_6.Size = UDim2.new(0, 406, 0, 0)

Frame_7.Parent = ScrollingFrame
Frame_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_7.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_7.Position = UDim2.new(0.0645962879, 0, 0.779441237, 0)
Frame_7.Size = UDim2.new(0, 406, 0, 0)

Frame_8.Parent = ScrollingFrame
Frame_8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_8.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_8.Position = UDim2.new(0.00659164693, 0, 0.675706804, 0)
Frame_8.Size = UDim2.new(0, 406, 0, 0)

Frame_9.Parent = ScrollingFrame
Frame_9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_9.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_9.Position = UDim2.new(0.0738770291, 0, 0.675706804, 0)
Frame_9.Size = UDim2.new(0, 406, 0, 0)

Frame_10.Parent = ScrollingFrame
Frame_10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_10.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_10.Position = UDim2.new(0.0297935046, 0, 0.675706804, 0)
Frame_10.Size = UDim2.new(0, 406, 0, 0)

Frame_11.Parent = ScrollingFrame
Frame_11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_11.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_11.Position = UDim2.new(0.0692366585, 0, 0.566439867, 0)
Frame_11.Size = UDim2.new(0, 406, 0, 0)

Frame_12.Parent = ScrollingFrame
Frame_12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_12.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_12.Position = UDim2.new(0.00195127586, 0, 0.566439867, 0)
Frame_12.Size = UDim2.new(0, 406, 0, 0)

Frame_13.Parent = ScrollingFrame
Frame_13.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_13.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_13.Position = UDim2.new(0.025153134, 0, 0.566439867, 0)
Frame_13.Size = UDim2.new(0, 406, 0, 0)

Frame_14.Parent = ScrollingFrame
Frame_14.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_14.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_14.Position = UDim2.new(-0.00268909521, 0, 0.468237936, 0)
Frame_14.Size = UDim2.new(0, 406, 0, 0)

Frame_15.Parent = ScrollingFrame
Frame_15.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_15.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_15.Position = UDim2.new(0.0205127634, 0, 0.468237936, 0)
Frame_15.Size = UDim2.new(0, 406, 0, 0)

Frame_16.Parent = ScrollingFrame
Frame_16.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_16.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_16.Position = UDim2.new(0.0645962879, 0, 0.468237936, 0)
Frame_16.Size = UDim2.new(0, 406, 0, 0)

Frame_17.Parent = ScrollingFrame
Frame_17.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_17.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_17.Position = UDim2.new(-0.000368909677, 0, 0.364503503, 0)
Frame_17.Size = UDim2.new(0, 406, 0, 0)

Frame_18.Parent = ScrollingFrame
Frame_18.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_18.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_18.Position = UDim2.new(0.0669164732, 0, 0.364503503, 0)
Frame_18.Size = UDim2.new(0, 406, 0, 0)

Frame_19.Parent = ScrollingFrame
Frame_19.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_19.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_19.Position = UDim2.new(0.0228329487, 0, 0.364503503, 0)
Frame_19.Size = UDim2.new(0, 406, 0, 0)

Frame_20.Parent = ScrollingFrame
Frame_20.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_20.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_20.Position = UDim2.new(0.0669164732, 0, 0.260769069, 0)
Frame_20.Size = UDim2.new(0, 406, 0, 0)

Frame_21.Parent = ScrollingFrame
Frame_21.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_21.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_21.Position = UDim2.new(0.0228329487, 0, 0.260769069, 0)
Frame_21.Size = UDim2.new(0, 406, 0, 0)

Frame_22.Parent = ScrollingFrame
Frame_22.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_22.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_22.Position = UDim2.new(-0.000368909677, 0, 0.260769069, 0)
Frame_22.Size = UDim2.new(0, 406, 0, 0)

GameTab.Name = "GameTab"
GameTab.Parent = OpenSelections
GameTab.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GameTab.BackgroundTransparency = 1.000
GameTab.Position = UDim2.new(0.00215517241, 0, 0.0722814798, 0)
GameTab.Size = UDim2.new(0, 453, 0, 241)
GameTab.Visible = false
GameTab.Image = "rbxassetid://3570695787"
GameTab.ImageColor3 = Color3.fromRGB(26, 26, 26)
GameTab.ScaleType = Enum.ScaleType.Slice
GameTab.SliceCenter = Rect.new(100, 100, 100, 100)
GameTab.SliceScale = 0.120

GameTabUp.Name = "GameTabUp"
GameTabUp.Parent = GameTab
GameTabUp.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
GameTabUp.BorderColor3 = Color3.fromRGB(26, 26, 26)
GameTabUp.Position = UDim2.new(0, 0, 0.000967825123, 0)
GameTabUp.Size = UDim2.new(0, 450, 0, 19)

ScrollingFrame_2.Parent = GameTab
ScrollingFrame_2.Active = true
ScrollingFrame_2.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
ScrollingFrame_2.BorderColor3 = Color3.fromRGB(26, 26, 26)
ScrollingFrame_2.Position = UDim2.new(0.0406342559, 0, 0.0881047547, 0)
ScrollingFrame_2.Size = UDim2.new(0, 431, 0, 220)
ScrollingFrame_2.CanvasSize = UDim2.new(0, 0, 1.10000002, 0)

Unburn.Name = "Unburn"
Unburn.Parent = ScrollingFrame_2
Unburn.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Unburn.BorderColor3 = Color3.fromRGB(26, 26, 26)
Unburn.Position = UDim2.new(-0.00228074542, 0, 0.689966083, 0)
Unburn.Size = UDim2.new(0, 427, 0, 53)
Unburn.Font = Enum.Font.SourceSans
Unburn.Text = " Un Burn                                                                                                                     Remove Burning Effect"
Unburn.TextColor3 = Color3.fromRGB(171, 171, 171)
Unburn.TextScaled = true
Unburn.TextSize = 14.000
Unburn.TextWrapped = true
Unburn.TextXAlignment = Enum.TextXAlignment.Left

Tittle_2.Name = "Tittle"
Tittle_2.Parent = ScrollingFrame_2
Tittle_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Tittle_2.BackgroundTransparency = 1.000
Tittle_2.Position = UDim2.new(0.00934737176, 0, 0.0820904002, 0)
Tittle_2.Size = UDim2.new(0, 200, 0, 51)
Tittle_2.Font = Enum.Font.SourceSans
Tittle_2.Text = "Game"
Tittle_2.TextColor3 = Color3.fromRGB(102, 102, 102)
Tittle_2.TextScaled = true
Tittle_2.TextSize = 14.000
Tittle_2.TextWrapped = true
Tittle_2.TextXAlignment = Enum.TextXAlignment.Left

ObtainLava.Name = "ObtainLava"
ObtainLava.Parent = ScrollingFrame_2
ObtainLava.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
ObtainLava.BorderColor3 = Color3.fromRGB(26, 26, 26)
ObtainLava.Position = UDim2.new(0.00238676998, 0, 0.352018088, 0)
ObtainLava.Size = UDim2.new(0, 427, 0, 53)
ObtainLava.Font = Enum.Font.SourceSans
ObtainLava.Text = " Obtain Lava                                                                                                                     Obtain The lava"
ObtainLava.TextColor3 = Color3.fromRGB(171, 171, 171)
ObtainLava.TextScaled = true
ObtainLava.TextSize = 14.000
ObtainLava.TextWrapped = true
ObtainLava.TextXAlignment = Enum.TextXAlignment.Left

Frame_23.Parent = ScrollingFrame_2
Frame_23.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_23.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_23.Position = UDim2.new(0.0112320203, 0, 0.604035735, 0)
Frame_23.Size = UDim2.new(0, 406, 0, 0)

ExtraTab.Name = "ExtraTab"
ExtraTab.Parent = OpenSelections
ExtraTab.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ExtraTab.BackgroundTransparency = 1.000
ExtraTab.Position = UDim2.new(0.00215517241, 0, 0.0722814798, 0)
ExtraTab.Size = UDim2.new(0, 453, 0, 241)
ExtraTab.Visible = false
ExtraTab.Image = "rbxassetid://3570695787"
ExtraTab.ImageColor3 = Color3.fromRGB(26, 26, 26)
ExtraTab.ScaleType = Enum.ScaleType.Slice
ExtraTab.SliceCenter = Rect.new(100, 100, 100, 100)
ExtraTab.SliceScale = 0.120

ExtraTabUp.Name = "ExtraTabUp"
ExtraTabUp.Parent = ExtraTab
ExtraTabUp.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
ExtraTabUp.BorderColor3 = Color3.fromRGB(26, 26, 26)
ExtraTabUp.Position = UDim2.new(0, 0, 0.000967825123, 0)
ExtraTabUp.Size = UDim2.new(0, 450, 0, 19)

ScrollingFrame_3.Parent = ExtraTab
ScrollingFrame_3.Active = true
ScrollingFrame_3.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
ScrollingFrame_3.BorderColor3 = Color3.fromRGB(26, 26, 26)
ScrollingFrame_3.Position = UDim2.new(0.0406342559, 0, 0.0881047547, 0)
ScrollingFrame_3.Size = UDim2.new(0, 431, 0, 220)
ScrollingFrame_3.CanvasSize = UDim2.new(0, 0, 1.10000002, 0)

Tittle_3.Name = "Tittle"
Tittle_3.Parent = ScrollingFrame_3
Tittle_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Tittle_3.BackgroundTransparency = 1.000
Tittle_3.Position = UDim2.new(0.00934737176, 0, 0.0820904002, 0)
Tittle_3.Size = UDim2.new(0, 200, 0, 51)
Tittle_3.Font = Enum.Font.SourceSans
Tittle_3.Text = "Extra"
Tittle_3.TextColor3 = Color3.fromRGB(102, 102, 102)
Tittle_3.TextScaled = true
Tittle_3.TextSize = 14.000
Tittle_3.TextWrapped = true
Tittle_3.TextXAlignment = Enum.TextXAlignment.Left

InfYeild.Name = "InfYeild"
InfYeild.Parent = ScrollingFrame_3
InfYeild.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
InfYeild.BorderColor3 = Color3.fromRGB(26, 26, 26)
InfYeild.Position = UDim2.new(0.00238676998, 0, 0.352018088, 0)
InfYeild.Size = UDim2.new(0, 427, 0, 53)
InfYeild.Font = Enum.Font.SourceSans
InfYeild.Text = " Infinite Yeild                                                                                                                     Execute Infinite yeild"
InfYeild.TextColor3 = Color3.fromRGB(171, 171, 171)
InfYeild.TextScaled = true
InfYeild.TextSize = 14.000
InfYeild.TextWrapped = true
InfYeild.TextXAlignment = Enum.TextXAlignment.Left

Frame_24.Parent = ScrollingFrame_3
Frame_24.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_24.BorderColor3 = Color3.fromRGB(152, 152, 152)
Frame_24.Position = UDim2.new(0.0112320203, 0, 0.604035735, 0)
Frame_24.Size = UDim2.new(0, 406, 0, 0)

SelectFrame.Name = "SelectFrame"
SelectFrame.Parent = OpenSelections
SelectFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SelectFrame.BackgroundTransparency = 1.000
SelectFrame.Position = UDim2.new(-0.282327592, 0, 0.0719999969, 0)
SelectFrame.Size = UDim2.new(0, 125, 0, 241)
SelectFrame.Image = "rbxassetid://3570695787"
SelectFrame.ImageColor3 = Color3.fromRGB(44, 44, 44)
SelectFrame.ScaleType = Enum.ScaleType.Slice
SelectFrame.SliceCenter = Rect.new(100, 100, 100, 100)
SelectFrame.SliceScale = 0.120

SelectionUpFrame.Name = "SelectionUpFrame"
SelectionUpFrame.Parent = SelectFrame
SelectionUpFrame.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
SelectionUpFrame.BorderColor3 = Color3.fromRGB(44, 44, 44)
SelectionUpFrame.Size = UDim2.new(0, 125, 0, 20)

SelectionDownFrame.Name = "SelectionDownFrame"
SelectionDownFrame.Parent = SelectFrame
SelectionDownFrame.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
SelectionDownFrame.BorderColor3 = Color3.fromRGB(44, 44, 44)
SelectionDownFrame.Position = UDim2.new(0.824000001, 0, 0, 0)
SelectionDownFrame.Size = UDim2.new(0, 22, 0, 241)

Home.Name = "Home"
Home.Parent = SelectFrame
Home.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
Home.Position = UDim2.new(0, 0, 0.0456431545, 0)
Home.Size = UDim2.new(0, 119, 0, 31)
Home.Font = Enum.Font.SciFi
Home.Text = "Home"
Home.TextColor3 = Color3.fromRGB(0, 0, 0)
Home.TextScaled = true
Home.TextSize = 14.000
Home.TextWrapped = true

Teleport.Name = "Teleport"
Teleport.Parent = SelectFrame
Teleport.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
Teleport.Position = UDim2.new(0, 0, 0.215767637, 0)
Teleport.Size = UDim2.new(0, 119, 0, 31)
Teleport.Font = Enum.Font.SciFi
Teleport.Text = "Teleport"
Teleport.TextColor3 = Color3.fromRGB(0, 0, 0)
Teleport.TextScaled = true
Teleport.TextSize = 14.000
Teleport.TextWrapped = true

Game.Name = "Game"
Game.Parent = SelectFrame
Game.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
Game.Position = UDim2.new(0, 0, 0.3900415, 0)
Game.Size = UDim2.new(0, 119, 0, 31)
Game.Font = Enum.Font.SciFi
Game.Text = "Game"
Game.TextColor3 = Color3.fromRGB(0, 0, 0)
Game.TextScaled = true
Game.TextSize = 14.000
Game.TextWrapped = true

Extra.Name = "Extra"
Extra.Parent = SelectFrame
Extra.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
Extra.Position = UDim2.new(0, 0, 0.59336102, 0)
Extra.Size = UDim2.new(0, 119, 0, 31)
Extra.Font = Enum.Font.SciFi
Extra.Text = "Extra"
Extra.TextColor3 = Color3.fromRGB(0, 0, 0)
Extra.TextScaled = true
Extra.TextSize = 14.000
Extra.TextWrapped = true

Close.Name = "Close"
Close.Parent = SelectFrame
Close.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
Close.Position = UDim2.new(0, 0, 0.780083001, 0)
Close.Size = UDim2.new(0, 119, 0, 31)
Close.Font = Enum.Font.SciFi
Close.Text = "Close Select"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.26385808, 0, 0.0141843967, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 32)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Shit Hub"
TextLabel.TextColor3 = Color3.fromRGB(213, 213, 213)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

-- Scripts:

local function BNTYE_fake_script() -- UserProfile.GetProfile 
	local script = Instance.new('LocalScript', UserProfile)

	local Players = game:GetService("Players")
	
	local player = Players.LocalPlayer
	
	
	local userId = player.UserId
	local thumbType = Enum.ThumbnailType.HeadShot
	local thumbSize = Enum.ThumbnailSize.Size420x420
	local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
	
	
	local imageLabel = script.Parent
	imageLabel.Image = content
end
coroutine.wrap(BNTYE_fake_script)()
local function IFFVVG_fake_script() -- GetUsername.LocalScript 
	local script = Instance.new('LocalScript', GetUsername)

	script.Parent.Text = ""..game.Players.LocalPlayer.Name
	
	
	
	
end
coroutine.wrap(IFFVVG_fake_script)()
local function EDNEWKK_fake_script() -- Playercount.Script 
	local script = Instance.new('Script', Playercount)

	txt = script.Parent
	function updateGUI()
		local maxplayers = game.Players.MaxPlayers
		local players = game.Players:getPlayers()
		if #players == 1 then
			txt.Text = "Players count                                                             ".. #players ..""
		end
	end
	
	updateGUI()
	game.Players.ChildAdded:connect(updateGUI)
	game.Players.ChildRemoved:connect(updateGUI)
end
coroutine.wrap(EDNEWKK_fake_script)()
local function VMEZ_fake_script() -- Display.Script 
	local script = Instance.new('Script', Display)

	while true do
		wait()
		local seconds = math.floor(game.Workspace.DistributedGameTime)
		local minutes = math.floor(game.Workspace.DistributedGameTime / 60)
		local hours = math.floor(game.Workspace.DistributedGameTime / 60 / 60)
		local seconds = seconds - (minutes * 60)
		local minutes = minutes - (hours * 60)
		if hours < 1 then
			if minutes < 1 then
				script.Parent.Text = seconds.." second(s)"
			else
				script.Parent.Text = minutes.." minute(s), "..seconds.." second(s)"
			end
		else
			script.Parent.Text = hours.." hour(s), "..minutes.." minute(s), "..seconds.." second(s)"
		end
	end
	
end
coroutine.wrap(VMEZ_fake_script)()
local function TEIHS_fake_script() -- Exit.Exit 
	local script = Instance.new('Script', Exit)

	Button = script.Parent.Parent.Parent.Main
	
	function onClick()
	if Button.Visible == true then
	Button.Visible = false
	else Button.Visible = true
	end
	end
	
	script.Parent.MouseButton1Click:connect(onClick)
end
coroutine.wrap(TEIHS_fake_script)()
local function ZXCYWWU_fake_script() -- openselecttab.LocalScript 
	local script = Instance.new('LocalScript', openselecttab)

	script.Parent.MouseButton1Click:Connect(function(clicked)
		script.Parent.Parent.SelectFrame:TweenPosition(UDim2.new(0, 0,0.072, 0))
	end)
end
coroutine.wrap(ZXCYWWU_fake_script)()
local function VHQQL_fake_script() -- Home.LocalScript 
	local script = Instance.new('LocalScript', Home)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Parent.TeleportTab.Visible = false
		script.Parent.Parent.Parent.GameTab.Visible = false
		script.Parent.Parent.Parent.ExtraTab.Visible = false
	end)
end
coroutine.wrap(VHQQL_fake_script)()
local function KVMZVES_fake_script() -- Teleport.LocalScript 
	local script = Instance.new('LocalScript', Teleport)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Parent.TeleportTab.Visible = true
		script.Parent.Parent.Parent.GameTab.Visible = false
		script.Parent.Parent.Parent.ExtraTab.Visible = false
	end)
end
coroutine.wrap(KVMZVES_fake_script)()
local function IPOA_fake_script() -- Game.LocalScript 
	local script = Instance.new('LocalScript', Game)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Parent.TeleportTab.Visible = false
		script.Parent.Parent.Parent.GameTab.Visible = true
		script.Parent.Parent.Parent.ExtraTab.Visible = false
	end)
end
coroutine.wrap(IPOA_fake_script)()
local function BGHNEY_fake_script() -- Extra.LocalScript 
	local script = Instance.new('LocalScript', Extra)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Parent.TeleportTab.Visible = false
		script.Parent.Parent.Parent.GameTab.Visible = false
		script.Parent.Parent.Parent.ExtraTab.Visible = true
	end)
end
coroutine.wrap(BGHNEY_fake_script)()
local function BFRVDR_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Click:Connect(function(clicked)
		script.Parent.Parent:TweenPosition(UDim2.new(-0.282, 0,0.072, 0))
	end)
end
coroutine.wrap(BFRVDR_fake_script)()
local function SIVAEKR_fake_script() -- Main.SmoothDrag 
	local script = Instance.new('LocalScript', Main)

	local Drag = script.Parent.Parent.Main
	gsCoreGui = game:GetService("CoreGui")
	gsTween = game:GetService("TweenService")
	local UserInputService = game:GetService("UserInputService")
		local dragging
		local dragInput
		local dragStart
		local startPos
		local function update(input)
			local delta = input.Position - dragStart
			local dragTime = 0.09
			local SmoothDrag = {}
			SmoothDrag.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
			local dragSmoothFunction = gsTween:Create(Drag, TweenInfo.new(dragTime, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), SmoothDrag)
			dragSmoothFunction:Play()
		end
		Drag.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				dragging = true
				dragStart = input.Position
				startPos = Drag.Position
				input.Changed:Connect(function()
					if input.UserInputState == Enum.UserInputState.End then
						dragging = false
					end
				end)
			end
		end)
		Drag.InputChanged:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end)
		UserInputService.InputChanged:Connect(function(input)
			if input == dragInput and dragging and Drag.Size then
				update(input)
			end
		end)
	
end
coroutine.wrap(SIVAEKR_fake_script)()


Beach.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(229.3734588623, 5.9383950233459, -270.6960144043)
end)

Lava.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(468.94436645508, 70.55696105957, 349.2587890625)
end)

SafeBeachHut.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(152.74566650391, -1.7399846315384, -382.58245849609)
end)

SafeVolcanoPlace.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-459.62045288086, 15.453666687012, 342.03817749023)
end)

Volcano.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-445.74166870117, 76.13452911377, 339.92861938477)
end)

VolcanoIsland.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-338.27276611328, -7.0000653266907, 278.10394287109)
end)

Camp.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(334.93655395508, -0.39183175563812, -260.06802368164)
end)

Ocean.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
end)

ObtainLava.MouseButton1Down:connect(function()
	LPos = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
	wait()



	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-469.60775756836, 70.556915283203, 353.97024536133)

	wait(0)

	for _, tool in ipairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
		if tool:IsA("Tool") then
			tool.Parent = game:GetService("Players").LocalPlayer.Character
		end
	end

	wait(1)
	mouse1click()
	wait(0)
	mouse1click()
	wait(0)
	mouse1click()
	wait(0)
	mouse1click()
	wait(0)
	mouse1click()
	wait(0)

	wait(1)
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()


	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = LPos
end)

Unburn.MouseButton1Down:connect(function()
	LPos = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-93.580825805664, -27.618032455444, -59.705154418945)
	wait()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = LPos
end)

InfYeild.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
