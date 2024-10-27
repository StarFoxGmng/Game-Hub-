--Server Side / Internal By Server Side Script!

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local Frame_2 = Instance.new("Frame")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(63, 8, 8)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.282012194, 0, 0.260122687, 0)
Frame.Size = UDim2.new(0, 572, 0, 390)

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0297202803, 0, 0.0435897447, 0)
TextBox.Size = UDim2.new(0, 537, 0, 276)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 20.000
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0297202803, 0, 0.807692289, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Execute"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 28.000
TextButton.TextWrapped = true

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.618881166, 0, 0.807692289, 0)
TextButton_2.Size = UDim2.new(0, 200, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Server Side Execute"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 28.000
TextButton_2.TextWrapped = true

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.41083914, 0, 0.807692289, 0)
TextButton_3.Size = UDim2.new(0, 102, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Clear"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextSize = 28.000
TextButton_3.TextWrapped = true

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(43, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(1, 0, 0, 0)
Frame_2.Size = UDim2.new(0, 93, 0, 390)

TextButton_4.Parent = Frame_2
TextButton_4.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.0752688199, 0, 0.146153852, 0)
TextButton_4.Size = UDim2.new(0, 78, 0, 76)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Btools"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextSize = 29.000

TextButton_5.Parent = Frame_2
TextButton_5.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.0752688199, 0, 0.402564108, 0)
TextButton_5.Size = UDim2.new(0, 78, 0, 76)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Fast"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextSize = 29.000

TextButton_6.Parent = Frame_2
TextButton_6.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.0752688199, 0, 0.658974409, 0)
TextButton_6.Size = UDim2.new(0, 78, 0, 76)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "Close"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextSize = 29.000


local function ZIUYTVS_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		assert(loadstring(script.Parent.Parent.TextBox.Text))()
	end)
end
coroutine.wrap(ZIUYTVS_fake_script)()
local function HASJH_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		game.ReplicatedStorage.RemoteEvent:FireServer(script.Parent.Parent.TextBox.Text)
	end)
end
coroutine.wrap(HASJH_fake_script)()
local function UAZSPPI_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.TextBox.Text = "Cleared!"
		wait(.1)
		script.Parent.Parent.TextBox.Text = ""
	end)
end
coroutine.wrap(UAZSPPI_fake_script)()
local function ACWZSQI_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		Instance.new("HopperBin", game.Players.LocalPlayer.Backpack).BinType = 2
		Instance.new("HopperBin", game.Players.LocalPlayer.Backpack).BinType = 3
		Instance.new("HopperBin", game.Players.LocalPlayer.Backpack).BinType = 4
	end)
end
coroutine.wrap(ACWZSQI_fake_script)()
local function YRAT_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
	end)
end
coroutine.wrap(YRAT_fake_script)()
local function RTRPEIN_fake_script() -- TextButton_6.Script 
	local script = Instance.new('Script', TextButton_6)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent:Destroy()
	end)
end
coroutine.wrap(RTRPEIN_fake_script)()
local function ANEL_fake_script() -- Frame.Dragable 
	local script = Instance.new('LocalScript', Frame)

	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(ANEL_fake_script)()
