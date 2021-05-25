-- Gui to Lua
-- Version: 3.2

-- Instances:

local FoodMagnet = Instance.new("ScreenGui")
local DestroyFolder = Instance.new("Folder")
local Frame = Instance.new("Frame")
local SuperRebirth = Instance.new("TextButton")
local GemFarm = Instance.new("TextButton")
local FoodFarm = Instance.new("TextButton")
local CashFarm = Instance.new("TextButton")
local GemFarmToggle = Instance.new("Frame")
local SuperRebirthFarmToggle = Instance.new("Frame")
local FoodFarmToggle = Instance.new("Frame")
local CashFarmToggle = Instance.new("Frame")
local Frame2 = Instance.new("Frame")
local AntiAFK = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local RebirthFarm = Instance.new("TextButton")
local RebirthFarmToggle = Instance.new("Frame")
local Frame3 = Instance.new("Frame")
local AutoUpgradeToken = Instance.new("TextButton")
local AutoSuperExchange = Instance.new("TextButton")
local SuperExchangeToggle = Instance.new("Frame")
local TokenUpgradeToggle = Instance.new("Frame")

--Properties:

FoodMagnet.Name = "FoodMagnet"
FoodMagnet.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
FoodMagnet.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
FoodMagnet.ResetOnSpawn = false

DestroyFolder.Name = "DestroyFolder"
DestroyFolder.Parent = FoodMagnet

Frame.Parent = DestroyFolder
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.Position = UDim2.new(0.277083308, 0, 0, 0)
Frame.Size = UDim2.new(0, 856, 0, 53)

SuperRebirth.Name = "SuperRebirth"
SuperRebirth.Parent = Frame
SuperRebirth.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SuperRebirth.BackgroundTransparency = 1.000
SuperRebirth.Position = UDim2.new(0.207028821, 0, 0.0562077276, 0)
SuperRebirth.Size = UDim2.new(0, 267, 0, 50)
SuperRebirth.Font = Enum.Font.SourceSans
SuperRebirth.Text = "Super Rebirth Farm"
SuperRebirth.TextColor3 = Color3.fromRGB(0, 0, 0)
SuperRebirth.TextSize = 40.000

GemFarm.Name = "GemFarm"
GemFarm.Parent = Frame
GemFarm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GemFarm.BackgroundTransparency = 1.000
GemFarm.Position = UDim2.new(0.0142718162, 0, 0.0184718799, 0)
GemFarm.Size = UDim2.new(0, 143, 0, 50)
GemFarm.Font = Enum.Font.SourceSans
GemFarm.Text = "Gem Farm"
GemFarm.TextColor3 = Color3.fromRGB(0, 0, 0)
GemFarm.TextSize = 40.000

FoodFarm.Name = "FoodFarm"
FoodFarm.Parent = Frame
FoodFarm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FoodFarm.BackgroundTransparency = 1.000
FoodFarm.Position = UDim2.new(0.549318552, 0, 0.0184718799, 0)
FoodFarm.Size = UDim2.new(0, 161, 0, 50)
FoodFarm.Font = Enum.Font.SourceSans
FoodFarm.Text = "Food Farm"
FoodFarm.TextColor3 = Color3.fromRGB(0, 0, 0)
FoodFarm.TextSize = 40.000

CashFarm.Name = "CashFarm"
CashFarm.Parent = Frame
CashFarm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CashFarm.BackgroundTransparency = 1.000
CashFarm.Position = UDim2.new(0.779458761, 0, -0.000396044925, 0)
CashFarm.Size = UDim2.new(0, 161, 0, 50)
CashFarm.Font = Enum.Font.SourceSans
CashFarm.Text = "Cash Farm"
CashFarm.TextColor3 = Color3.fromRGB(0, 0, 0)
CashFarm.TextSize = 40.000

GemFarmToggle.Name = "GemFarmToggle"
GemFarmToggle.Parent = Frame
GemFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
GemFarmToggle.Position = UDim2.new(0, 0, -0.0188679248, 0)
GemFarmToggle.Size = UDim2.new(0, 12, 0, 54)

SuperRebirthFarmToggle.Name = "SuperRebirthFarmToggle"
SuperRebirthFarmToggle.Parent = Frame
SuperRebirthFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
SuperRebirthFarmToggle.Position = UDim2.new(0.19275701, 0, 0.0562077276, 0)
SuperRebirthFarmToggle.Size = UDim2.new(0, 12, 0, 54)

FoodFarmToggle.Name = "FoodFarmToggle"
FoodFarmToggle.Parent = Frame
FoodFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
FoodFarmToggle.Position = UDim2.new(0.539719582, 0, 0.0562077276, 0)
FoodFarmToggle.Size = UDim2.new(0, 15, 0, 46)

CashFarmToggle.Name = "CashFarmToggle"
CashFarmToggle.Parent = Frame
CashFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
CashFarmToggle.Position = UDim2.new(0.761682332, 0, 0, 0)
CashFarmToggle.Size = UDim2.new(0, 15, 0, 50)

Frame2.Name = "Frame2"
Frame2.Parent = DestroyFolder
Frame2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame2.BorderSizePixel = 0
Frame2.Position = UDim2.new(0.331770808, 0, 0.0539053902, 0)
Frame2.Size = UDim2.new(0, 646, 0, 49)

AntiAFK.Name = "AntiAFK"
AntiAFK.Parent = Frame2
AntiAFK.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AntiAFK.BackgroundTransparency = 1.000
AntiAFK.BorderSizePixel = 0
AntiAFK.Position = UDim2.new(0.65781194, 0, -0.0204081628, 0)
AntiAFK.Size = UDim2.new(0, 200, 0, 50)
AntiAFK.Font = Enum.Font.SourceSans
AntiAFK.Text = "AntiAFK"
AntiAFK.TextColor3 = Color3.fromRGB(0, 0, 0)
AntiAFK.TextSize = 40.000

Close.Name = "Close"
Close.Parent = Frame2
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.346749216, 0, 0, 0)
Close.Size = UDim2.new(0, 200, 0, 50)
Close.Font = Enum.Font.SourceSans
Close.Text = "Close"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 40.000

RebirthFarm.Name = "RebirthFarm"
RebirthFarm.Parent = Frame2
RebirthFarm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RebirthFarm.BackgroundTransparency = 1.000
RebirthFarm.BorderSizePixel = 0
RebirthFarm.Position = UDim2.new(0.0191459451, 0, 2.98023224e-08, 0)
RebirthFarm.Size = UDim2.new(0, 200, 0, 50)
RebirthFarm.Font = Enum.Font.SourceSans
RebirthFarm.Text = "Rebirth Farm"
RebirthFarm.TextColor3 = Color3.fromRGB(0, 0, 0)
RebirthFarm.TextSize = 40.000

RebirthFarmToggle.Name = "RebirthFarmToggle"
RebirthFarmToggle.Parent = Frame2
RebirthFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
RebirthFarmToggle.Position = UDim2.new(-0.0030236023, 0, 0.0816326514, 0)
RebirthFarmToggle.Size = UDim2.new(0, 15, 0, 45)

Frame3.Name = "Frame3"
Frame3.Parent = DestroyFolder
Frame3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame3.BorderSizePixel = 0
Frame3.Position = UDim2.new(0.331770808, 0, 0.108910888, 0)
Frame3.Size = UDim2.new(0, 646, 0, 49)

AutoUpgradeToken.Name = "AutoUpgradeToken"
AutoUpgradeToken.Parent = Frame3
AutoUpgradeToken.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoUpgradeToken.BackgroundTransparency = 1.000
AutoUpgradeToken.BorderSizePixel = 0
AutoUpgradeToken.Position = UDim2.new(0.563384652, 0, -0.0204081628, 0)
AutoUpgradeToken.Size = UDim2.new(0, 282, 0, 50)
AutoUpgradeToken.Font = Enum.Font.SourceSans
AutoUpgradeToken.Text = "AutoUpgradeToken"
AutoUpgradeToken.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoUpgradeToken.TextSize = 40.000

AutoSuperExchange.Name = "AutoSuperExchange"
AutoSuperExchange.Parent = Frame3
AutoSuperExchange.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoSuperExchange.BackgroundTransparency = 1.000
AutoSuperExchange.Position = UDim2.new(0.0201238394, 0, 0, 0)
AutoSuperExchange.Size = UDim2.new(0, 279, 0, 50)
AutoSuperExchange.Font = Enum.Font.SourceSans
AutoSuperExchange.Text = "AutoSuperExchange"
AutoSuperExchange.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoSuperExchange.TextSize = 40.000

SuperExchangeToggle.Name = "SuperExchangeToggle"
SuperExchangeToggle.Parent = Frame3
SuperExchangeToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
SuperExchangeToggle.Position = UDim2.new(-0.00457159011, 0, 0.0109112794, 0)
SuperExchangeToggle.Size = UDim2.new(0, 15, 0, 48)

TokenUpgradeToggle.Name = "TokenUpgradeToggle"
TokenUpgradeToggle.Parent = Frame3
TokenUpgradeToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
TokenUpgradeToggle.Position = UDim2.new(0.551155925, 0, 0.0313194431, 0)
TokenUpgradeToggle.Size = UDim2.new(0, 15, 0, 48)

-- Scripts:

local function XLYTZEU_fake_script() -- DestroyFolder.LocalScript 
	local script = Instance.new('LocalScript', DestroyFolder)

	local toggle = false -- false is Off; true is On
	
	
	function onKeyPress(actionName, userInputState, inputObject)
		if userInputState == Enum.UserInputState.Begin then
			Frame.Visible = false
			Frame2.Visible = false
			Frame3.Visible = false
			if toggle == false then
				toggle = true
			else
				toggle = false
				Frame.Visible = true
				Frame2.Visible = true
				Frame3.Visible = true
			end
		end
	end
	
	game.ContextActionService:BindAction("keyPress", onKeyPress, false, Enum.KeyCode.P)
end
coroutine.wrap(XLYTZEU_fake_script)()
local function OLVR_fake_script() -- DestroyFolder.LocalScript 
	local script = Instance.new('LocalScript', DestroyFolder)

	while wait(1) do
		game:GetService("Players").LocalPlayer["Player_Stats"]["Tool_Delay"].Value = nil
		game:GetService("Players").LocalPlayer["Player_Stats"]["Tool_Delay"].Value = 0
	end
end
coroutine.wrap(OLVR_fake_script)()
local function PTBYIND_fake_script() -- SuperRebirth.LocalScript 
	local script = Instance.new('LocalScript', SuperRebirth)

	local char = game.Players.LocalPlayer.Character
	local cPos = char.HumanoidRootPart.Position
	local fPos = cPos.Z + 10
	
	getfenv().SuperRebirthToggle = true
	
	SuperRebirth.MouseButton1Down:connect(function()
		if getfenv().SuperRebirthToggle == true then
			SuperRebirthFarmToggle.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-672.110107, 10.0386496, 206.300644)
			wait(0.1)
			getfenv().SuperRebirthFarm = true
			getfenv().SuperRebirthToggle = false
		else
			if getfenv().SuperRebirthToggle == false then
				SuperRebirthFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
				getfenv().SuperRebirthFarm = false
				getfenv().SuperRebirthToggle = true
			end
		end
	end)
	
	
	
	while wait() do
		if getfenv().SuperRebirthFarm == true then
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.1)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Super_Rebirth:FireServer()
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Super_Rebirth:FireServer()
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-643.972595, 10.0386467, 234.600739)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Super_Rebirth:FireServer()
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-647.190247, 10.0386467, 194.058533)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Super_Rebirth:FireServer()
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-720.033325, 10.0386467, 189.805679)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Super_Rebirth:FireServer()
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-716.561279, 10.03862, 233.449615)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
		end
	end
end
coroutine.wrap(PTBYIND_fake_script)()
local function JTKLVSM_fake_script() -- SuperRebirth.LocalScript 
	local script = Instance.new('LocalScript', SuperRebirth)

	getfenv().SuperRebirthToggle2 = true
	
	SuperRebirth.MouseButton1Down:connect(function()
			if getfenv().SuperRebirthToggle2 == true then
				getfenv().SuperRebirthFarm2 = true
				getfenv().SuperRebirthToggle2 = false
			else
				if getfenv().SuperRebirthToggle2 == false then
					getfenv().SuperRebirthFarm2 = false
					getfenv().SuperRebirthToggle2 = true
				end
			end
	end)
	
	while wait() do
	if getfenv().SuperRebirthFarm2 == true then
	wait(0.9)
	game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"].Exchange:FireServer()
		end
	end
end
coroutine.wrap(JTKLVSM_fake_script)()
local function XTUL_fake_script() -- GemFarm.LocalScript 
	local script = Instance.new('LocalScript', GemFarm)

	local char = game.Players.LocalPlayer.Character
	local cPos = char.HumanoidRootPart.Position
	local fPos = cPos.Z + 10
	
	getfenv().GemFarmToggle = true
	
	GemFarm.MouseButton1Down:connect(function()
		if getfenv().GemFarmToggle == true then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-672.110107, 10.0386496, 206.300644)
			wait(0.1)
			GemFarmToggle.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
			getfenv().GemFarm = true
			getfenv().GemFarmToggle = false
		else
			if getfenv().GemFarmToggle == false then
				GemFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
				getfenv().GemFarm = false
				getfenv().GemFarmToggle = true
			end
		end
	end)
	
	
	
	while wait() do
		if getfenv().GemFarm == true then
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.1)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"].Exchange:FireServer()
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"].Exchange:FireServer()
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-643.972595, 10.0386467, 234.600739)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"].Exchange:FireServer()
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-647.190247, 10.0386467, 194.058533)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"].Exchange:FireServer()
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-720.033325, 10.0386467, 189.805679)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.01)
			game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"].Exchange:FireServer()
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-716.561279, 10.03862, 233.449615)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
		end
	end
end
coroutine.wrap(XTUL_fake_script)()
local function VXEK_fake_script() -- FoodFarm.LocalScript 
	local script = Instance.new('LocalScript', FoodFarm)

	local char = game.Players.LocalPlayer.Character
	local cPos = char.HumanoidRootPart.Position
	local dPos = cPos.Z + 2
	
	getfenv().FoodFarmToggle = true
	
	FoodFarm.MouseButton1Down:connect(function()
		if getfenv().FoodFarmToggle == true then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-672.110107, 10.0386496, 206.300644)
			wait(0.1)
			getfenv().FoodFarm = true
			FoodFarmToggle.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
			getfenv().FoodFarmToggle = false
		else
			if getfenv().FoodFarmToggle == false then
				FoodFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
				getfenv().FoodFarm = false
				getfenv().FoodFarmToggle = true
			end
		end
	end)
	
	
	
	while wait() do
		if getfenv().FoodFarm == true then
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-643.972595, 10.0386467, 234.600739)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,dPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-647.190247, 10.0386467, 194.058533)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,dPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-720.033325, 10.0386467, 189.805679)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,dPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-716.561279, 10.03862, 233.449615)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,dPos))
		end
	end
end
coroutine.wrap(VXEK_fake_script)()
local function XFQC_fake_script() -- CashFarm.LocalScript 
	local script = Instance.new('LocalScript', CashFarm)

	local char = game.Players.LocalPlayer.Character
	local cPos = char.HumanoidRootPart.Position
	local fPos = cPos.Z + 10
	
	getfenv().CashFarmToggle = true
	
	CashFarm.MouseButton1Down:connect(function()
		if getfenv().CashFarmToggle == true then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-672.110107, 10.0386496, 206.300644)
			wait(0.1)
			CashFarmToggle.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
			getfenv().CashFarm = true
			getfenv().CashFarmToggle = false
		else
			if getfenv().CashFarmToggle == false then
				CashFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
				getfenv().CashFarm = false
				getfenv().CashFarmToggle = true
			end
		end
	end)
	
	
	
	while wait() do
		if getfenv().CashFarm == true then
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-643.972595, 10.0386467, 234.600739)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-647.190247, 10.0386467, 194.058533)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-720.033325, 10.0386467, 189.805679)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-716.561279, 10.03862, 233.449615)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
		end
	end
end
coroutine.wrap(XFQC_fake_script)()
local function OKOHWS_fake_script() -- AntiAFK.LocalScript 
	local script = Instance.new('LocalScript', AntiAFK)

	AntiAFK.MouseButton1Click:Connect(function()
	wait(0.5)local ba=Instance.new("ScreenGui")
	local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
	local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
	ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
	ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
	ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,304,0,52)
	ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti AFK"ca.TextColor3=Color3.new(0,1,1)
	ca.TextSize=22;da.Parent=ca
	da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
	da.Size=UDim2.new(0,304,0,107)_b.Parent=da
	_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
	_b.Size=UDim2.new(0,304,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made By IDK"
	_b.TextColor3=Color3.new(1,1,1)_b.TextSize=20;ab.Parent=da
	ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377379,0)
	ab.Size=UDim2.new(0,304,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status : ONLINE"
	ab.TextColor3=Color3.new(1,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
	game:service'Players'.LocalPlayer.Idled:connect(function()
		bb:CaptureController()bb:ClickButton2(Vector2.new())
			ab.Text="EASY DESTROYED AFK KICK"wait(2)ab.Text="SCRIPT RELOAD"end)
	end)
end
coroutine.wrap(OKOHWS_fake_script)()
local function KZIA_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	Close.MouseButton1Click:Connect(function()
		DestroyFolder:Destroy()
	end)
end
coroutine.wrap(KZIA_fake_script)()
local function ZQLWMI_fake_script() -- RebirthFarm.LocalScript 
	local script = Instance.new('LocalScript', RebirthFarm)

	local char = game.Players.LocalPlayer.Character
	local cPos = char.HumanoidRootPart.Position
	local fPos = cPos.Z + 10
	
	getfenv().RebirthFarmToggle = true
	
	RebirthFarm.MouseButton1Down:connect(function()
		if getfenv().RebirthFarmToggle == true then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-672.110107, 10.0386496, 206.300644)
			wait(0.1)
			RebirthFarmToggle.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
			getfenv().RebirthFarm = true
			getfenv().RebirthFarmToggle = false
		else
			if getfenv().RebirthFarmToggle == false then
				RebirthFarmToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
				getfenv().RebirthFarm = false
				getfenv().RebirthFarmToggle = true
			end
		end
	end)
	
	
	
	while wait() do
		if getfenv().RebirthFarm == true then
			wait(0.2)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.4)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-643.972595, 10.0386467, 234.600739)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-647.190247, 10.0386467, 194.058533)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-720.033325, 10.0386467, 189.805679)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			wait(0.2)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.0001)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace")["Client_Services"]["Point_Areas"].Sell3.CFrame.Position + Vector3.new(0,0,0))
			wait(0.01)
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
			wait(0.4)
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-716.561279, 10.03862, 233.449615)
			char.Humanoid:MoveTo(Vector3.new(cPos.X,cPos.Y,fPos))
			game:GetService("ReplicatedStorage").Game_Service.Remotes_Event.Rebirth:FireServer()
		end
	end
end
coroutine.wrap(ZQLWMI_fake_script)()
local function KRTSKXA_fake_script() -- AutoUpgradeToken.LocalScript 
	local script = Instance.new('LocalScript', AutoUpgradeToken)

	getfenv().AutoTokenUpgrade = true
	
	AutoUpgradeToken.MouseButton1Down:connect(function()
		if getfenv().AutoTokenUpgrade == true then
			TokenUpgradeToggle.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
			getfenv().TokenUpgrade = true
			getfenv().AutoTokenUpgrade = false
		else
			if getfenv().AutoTokenUpgrade == false then
				TokenUpgradeToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
				getfenv().TokenUpgrade = false
				getfenv().AutoTokenUpgrade = true
			end
		end
	end)
	
	
	
	while wait() do
		if getfenv().TokenUpgrade == true then
			wait()
			local Event = game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"].Tokens
			Event:FireServer()
		end
	end
end
coroutine.wrap(KRTSKXA_fake_script)()
local function LPCXAG_fake_script() -- AutoSuperExchange.LocalScript 
	local script = Instance.new('LocalScript', AutoSuperExchange)

	getfenv().AutoSuperExchange = true
	
	AutoSuperExchange.MouseButton1Down:connect(function()
		if getfenv().AutoSuperExchange == true then
			SuperExchangeToggle.BackgroundColor3 = Color3.fromRGB(0, 170, 0)
			getfenv().SuperExchange = true
			getfenv().AutoSuperExchange = false
		else
			if getfenv().AutoSuperExchange == false then
				SuperExchangeToggle.BackgroundColor3 = Color3.fromRGB(170, 0, 0)
				getfenv().SuperExchange = false
				getfenv().AutoSuperExchange = true
			end
		end
	end)
	
	
	
	while wait() do
		if getfenv().SuperExchange == true then
			wait()
			local Event = game:GetService("ReplicatedStorage")["Game_Service"]["Remotes_Event"]["Super_Exchange"]
			Event:FireServer()
		end
	end
end
coroutine.wrap(LPCXAG_fake_script)()
local function GCIPPSS_fake_script() -- DestroyFolder.LocalScript 
	local script = Instance.new('LocalScript', DestroyFolder)

	-- THIS MAKE UR RANGE BIG AND NO TOOL COOLDOWN U NO NEED ANYMORE BUY A TOOL FOR RANKE 
	-- CREDITS : Maxi
	-- DONT MAKE HIGHER RANGE THEN 150
	while wait(0.01) do
		game:GetService("Players").LocalPlayer["Player_Stats"]["Tool_Delay"].Value = -1110
	end
end
coroutine.wrap(GCIPPSS_fake_script)()
