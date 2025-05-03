-- YuKi GUI with Orion-style design and loading screen

local player = game.Players.LocalPlayer
local playerGui = player:WaitForChild("PlayerGui")

-- Loading Screen
local loadingGui = Instance.new("ScreenGui", playerGui)
loadingGui.Name = "LoadingScreen"
loadingGui.ResetOnSpawn = false

local loadingLabel = Instance.new("TextLabel", loadingGui)
loadingLabel.Size = UDim2.new(0, 200, 0, 50)
loadingLabel.Position = UDim2.new(0.5, -100, 0.5, -25)
loadingLabel.BackgroundTransparency = 1
loadingLabel.Text = "YuKi"
loadingLabel.TextColor3 = Color3.fromRGB(0, 255, 0)
loadingLabel.TextSize = 32
loadingLabel.Font = Enum.Font.SourceSansBold

wait(3)
loadingGui:Destroy()

-- Main GUI
local gui = Instance.new("ScreenGui", playerGui)
gui.Name = "YuKiGUI"
gui.ResetOnSpawn = false

-- Main Frame
local mainFrame = Instance.new("Frame", gui)
mainFrame.Name = "MainFrame"
mainFrame.Size = UDim2.new(0, 500, 0, 300)
mainFrame.Position = UDim2.new(0.5, -250, 0.5, -150)
mainFrame.BackgroundColor3 = Color3.fromRGB(240, 228, 200)
mainFrame.Draggable = true
mainFrame.Active = true
mainFrame.BorderSizePixel = 0
local mainCorner = Instance.new("UICorner", mainFrame)
mainCorner.CornerRadius = UDim.new(0, 8)

-- Title Bar
local titleBar = Instance.new("TextLabel", mainFrame)
titleBar.Size = UDim2.new(1, 0, 0, 30)
titleBar.Position = UDim2.new(0, 0, 0, 0)
titleBar.Text = "YuKi"
titleBar.TextColor3 = Color3.fromRGB(255, 255, 255)
titleBar.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
titleBar.Font = Enum.Font.GothamBold
titleBar.TextSize = 14
titleBar.TextXAlignment = Enum.TextXAlignment.Center
local barCorner = Instance.new("UICorner", titleBar)
barCorner.CornerRadius = UDim.new(0, 4)

-- Tab List (left side)
local tabList = Instance.new("Frame", mainFrame)
tabList.Size = UDim2.new(0, 100, 1, -30)
tabList.Position = UDim2.new(0, 0, 0, 30)
tabList.BackgroundColor3 = Color3.fromRGB(220, 220, 220)
local tabCorner = Instance.new("UICorner", tabList)
tabCorner.CornerRadius = UDim.new(0, 4)

-- Settings Button
local settingsBtn = Instance.new("TextButton", tabList)
settingsBtn.Size = UDim2.new(1, 0, 0, 40)
settingsBtn.Position = UDim2.new(0, 0, 0, 10)
settingsBtn.Text = "Settings"
settingsBtn.Font = Enum.Font.Gotham
settingsBtn.TextSize = 12
settingsBtn.BackgroundColor3 = Color3.fromRGB(180, 180, 180)
local btnCorner = Instance.new("UICorner", settingsBtn)
btnCorner.CornerRadius = UDim.new(0, 4)

-- Content Area
local contentFrame = Instance.new("Frame", mainFrame)
contentFrame.Size = UDim2.new(1, -110, 1, -40)
contentFrame.Position = UDim2.new(0, 110, 0, 35)
contentFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
local contentCorner = Instance.new("UICorner", contentFrame)
contentCorner.CornerRadius = UDim.new(0, 6)

-- Ready for future content inside contentFrame
