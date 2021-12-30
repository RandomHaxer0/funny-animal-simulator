if game:GetService("CoreGui"):FindFirstChild("GASFucker") then
    game:GetService("CoreGui"):FindFirstChild("GASFucker"):Destroy()
    	game.StarterGui:SetCore("SendNotification", {
    Title = "This Script";
    Text = "Executed Script Again";
    Icon = "rbxassetid://4452245157";
    Duration = 5;
    })
end

for i,v in pairs(game.Players:GetPlayers()) do
if string.match(v.UserId, "694352102") then
game.Players.LocalPlayer:Kick("amogus no life spotted!!!11!!1!")
end
end

local MainGui = Instance.new("ScreenGui", game:GetService("CoreGui"))
MainGui.Name = "GASFucker"
MainGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
local Stepped
local Stepped2
local Stepped3
local Stepped4

function notification(text)
	game.StarterGui:SetCore("SendNotification", {
    Title = "This Script";
    Text = text;
    Icon = "rbxassetid://4452245157";
    Duration = 6;
    })
end

notification("Prefix To Open Command Bar Is ; (Semicolon)")

game:GetService("RunService").RenderStepped:Connect(function()
    
if game.Players.LocalPlayer.PlayerGui:FindFirstChild("anticheat1") then
    

local AntiExploit = game.Players.LocalPlayer.PlayerGui.anticheat1

local AntiExploit2 = game.Players.LocalPlayer.PlayerGui.Weapons

for i,v in pairs(getconnections(AntiExploit.Changed)) do
    v:Disable()
end

for i,v in pairs(getconnections(AntiExploit2.Changed)) do
    v:Disable()
end    

elseif not game.Players.LocalPlayer.PlayerGui:FindFirstChild("anticheat1") then
    --- nothing
end
    
    
    
end)

local CBar = Instance.new("TextBox", MainGui)
CBar.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CBar.BorderColor3 = Color3.fromRGB(255, 255, 255)
CBar.BorderSizePixel = 3
CBar.Position = UDim2.new(0, 0, 0.633333333333, 0)
CBar.Size = UDim2.new(0, 0, 0, 20)
CBar.Visible = false
CBar.Font = Enum.Font.GothamBlack
CBar.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
CBar.Text = ""
CBar.TextColor3 = Color3.fromRGB(255, 255, 255)
CBar.TextSize = 15
CBar.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)

local Frame = Instance.new("Frame", MainGui)
Frame.BackgroundTransparency = 1
Frame.Position = UDim2.new(0.005, 0, 0, 0)
Frame.Size = UDim2.new(0, 91, 0, 100)

local UIListLayout = Instance.new("UIListLayout", Frame)
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder

local Uis = game:GetService("UserInputService")
local Ctrl = false
Uis.InputBegan:Connect(function(Key, Typing)
   if Typing then return end
       if Key.KeyCode.Name == "Semicolon" then -- change this to what you like
       CBar.Visible = true
       CBar.Text = "Type cmds Into Here To View All Commands"
       wait()
       CBar:CaptureFocus()
       CBar:TweenSize(UDim2.new(0, 419, 0, 20), "Out", "Quad", 0.1, true)
   end
end)
CBar.FocusLost:Connect(function(Foc)
   if Foc == true then
       CBar:TweenSize(UDim2.new(0, 0, 0, 20), "Out", "Quad", 0.1, true)
       wait()
       CBar.Visible = false
       if CBar.Text == "cmds" then
           notification("Press F9 To View All Commands")
           print("sledge - Grabs A Sledge Hammer")
           print("cleaver - Grabs A Cleaver")
           print("fireaxe - Grabs A Fire Axe")
           print("glassknife - Grabs A Glass Knife")
           print("leadpipe - Grabs A Lead Pipe")
           print("infstamina - Infinite Stamina.")
           print("noinfstamina - Stops Infinite Stamina.")
           print("infyield - Executes Inf Yield.")
           print("profov - Makes Your Fov 150.")
           print("noprofov - Makes Your Fov Normal.")
           print("nocamshake - Removes Camera Shake.")
           print("yescamshake - Enables Camera Shake (Re Equip Weapon).")
           print("nocrystal - Removes Every Crystal.")
           print("nocrystalpath - Removes Every Crystal Path.")
           print("nocrystalzone - Removes Crystal Zone.")
           print("fullbright - Full Bright (Do This Cmd Again To Enable/Disable).")
           print("antifurry - Anti Furry.")
           print("unantifurry - Disables Anti Furry.")
           print("nowater - Makes It So That You Can't Be Affected By Water.")
           print("fpsboost - Boosts Your Fps.")
           print("nospawnarea - Removes Spawn Area.")
       elseif not CBar.Text == "cmds" then
          --- nothing
       end      
              if CBar.Text == "sledge" then
               if game.Players.LocalPlayer.Character:FindFirstChild("Sledgehammer") or game.Players.LocalPlayer.Backpack:FindFirstChild("Sledgehammer") then
    notification("u allready have a sledgehammer idiot")
elseif not game.Players.LocalPlayer.Character:FindFirstChild("Sledgehammer") or game.Players.LocalPlayer.Backpack:FindFirstChild("Sledgehammer") then     

for i,v in pairs(game.Workspace.map:GetDescendants()) do
    if v.ClassName == "Model" and v.Name == "Sledgehammer" then
        if v:FindFirstChild("Hitbox") then
            local sledge = v:FindFirstChild("Hitbox")
            local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(sledge.Position)
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
        end
    end
end
end
elseif not CBar.Text == "sledge" then
    --- nothing
end
if CBar.Text == "cleaver" then
        if game.Players.LocalPlayer.Character:FindFirstChild("Cleaver") or game.Players.LocalPlayer.Backpack:FindFirstChild("Cleaver") then
    notification("you allready have a cleaver idiot")
elseif not game.Players.LocalPlayer.Character:FindFirstChild("Cleaver") or game.Players.LocalPlayer.Backpack:FindFirstChild("Cleaver") then     

for i,v in pairs(game.Workspace.map:GetDescendants()) do
    if v.ClassName == "Model" and v.Name == "Cleaver" then
        if v:FindFirstChild("Hitbox") then
            local sledge = v:FindFirstChild("Hitbox")
            local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(sledge.Position)
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
        end
    end
end
end
end
end
if CBar.Text == "infstamina" then
    Stepped = game:GetService("RunService").RenderStepped:Connect(function()
        game.Players.LocalPlayer.Character.RunScript.Stamina.Value = 99999
        game.Players.LocalPlayer.Character.RunScript.CanGain.Value = true
    end)
elseif not CBar.Text == "infstamina" then
    --- nothing
end
if CBar.Text == "noinfstamina" then
    Stepped:Disconnect()
    task.wait()
    game.Players.LocalPlayer.Character.RunScript.Stamina.Value = 100
elseif not CBar.Text == "noinfstamina" then
    --- nothing
end    
if CBar.Text == "fireaxe" then
            if game.Players.LocalPlayer.Character:FindFirstChild("Fireaxe") or game.Players.LocalPlayer.Backpack:FindFirstChild("Fireaxe") then
    notification("you allready have a fireaxe idiot")
elseif not game.Players.LocalPlayer.Character:FindFirstChild("Fireaxe") or game.Players.LocalPlayer.Backpack:FindFirstChild("Fireaxe") then     

for i,v in pairs(game.Workspace.map:GetDescendants()) do
    if v.ClassName == "Model" and v.Name == "Fireaxe" then
        if v:FindFirstChild("Hitbox") then
            local sledge = v:FindFirstChild("Hitbox")
            local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(sledge.Position)
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
        end
    end
end
end
elseif not CBar.Text == "fireaxe" then
    --- nothing
end

if CBar.Text == "machete" then

            if game.Players.LocalPlayer.Character:FindFirstChild("Machete") or game.Players.LocalPlayer.Backpack:FindFirstChild("Machete") then
    notification("you allready have a machete idiot")
elseif not game.Players.LocalPlayer.Character:FindFirstChild("Machete") or game.Players.LocalPlayer.Backpack:FindFirstChild("Machete") then     

for i,v in pairs(game.Workspace.map:GetDescendants()) do
    if v.ClassName == "Model" and v.Name == "Machete" then
        if v:FindFirstChild("Hitbox") then
            local sledge = v:FindFirstChild("Hitbox")
            local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(sledge.Position)
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
        end
    end
end
end
elseif not CBar.Text == "machete" then
    --- nothing
end
if CBar.Text == "glassknife" then
                if game.Players.LocalPlayer.Character:FindFirstChild("Glass knife") or game.Players.LocalPlayer.Backpack:FindFirstChild("Glass knife") then
    notification("you allready have a machete idiot")
elseif not game.Players.LocalPlayer.Character:FindFirstChild("Glass knife") or game.Players.LocalPlayer.Backpack:FindFirstChild("Glass knife") then     

for i,v in pairs(game.Workspace.map:GetDescendants()) do
    if v.ClassName == "Model" and v.Name == "Glass knife" then
        if v:FindFirstChild("Hitbox") then
            local sledge = v:FindFirstChild("Hitbox")
            local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(sledge.Position)
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
        end
    end
end
end
elseif not CBar.Text == "glassknife" then
    --- nothing
end
if CBar.Text == "leadpipe" then
                    if game.Players.LocalPlayer.Character:FindFirstChild("Lead pipe") or game.Players.LocalPlayer.Backpack:FindFirstChild("Lead pipe") then
    notification("you allready have a machete idiot")
elseif not game.Players.LocalPlayer.Character:FindFirstChild("Lead pipe") or game.Players.LocalPlayer.Backpack:FindFirstChild("Lead pipe") then     

for i,v in pairs(game.Workspace.map:GetDescendants()) do
    if v.ClassName == "Model" and v.Name == "Lead pipe" then
        if v:FindFirstChild("Hitbox") then
            local sledge = v:FindFirstChild("Hitbox")
            local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(sledge.Position)
            wait()
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(pos)
        end
    end
end
end
elseif not CBar.Text == "leadpipe" then
    --- nothing
end 
if CBar.Text == "infyield" then
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
elseif not CBar.Text == "infyield" then
    --- nothing
end
if CBar.Text == "profov" then
if game.Players.LocalPlayer.PlayerGui.Weapons:FindFirstChild("Value") then
    if game.Players.LocalPlayer.PlayerGui.Weapons:FindFirstChild("Value") then
        if game.Players.LocalPlayer.PlayerGui.Weapons:FindFirstChild("Value") then
            if game.Players.LocalPlayer.PlayerGui.Weapons:FindFirstChild("Value") then
game.Players.LocalPlayer.PlayerGui.Weapons.Value.Name = "fuck"
game.Players.LocalPlayer.PlayerGui.Weapons.Value.Name = "shit"
game.Players.LocalPlayer.PlayerGui.Weapons.Value.Name = "ass"
game.Players.LocalPlayer.PlayerGui.Weapons.Value.Name = "dick"
end
end
end
end

Stepped2 = game:GetService("RunService").RenderStepped:Connect(function()
game.Players.LocalPlayer.PlayerGui.Weapons.dick.Value = Vector3.new(0, 150, 0)
end)
elseif not CBar.Text == "profov" then
    --- nothing
end
if CBar.Text == "noprofov" then
    Stepped2:Disconnect()
elseif not CBar.Text == "noprofov" then
    --- nothing
end
if CBar.Text == "nocamshake" then
    Stepped3 = game:GetService("RunService").RenderStepped:Connect(function()
    if game:GetService("Workspace").Camera:FindFirstChild("Viewmodel") then
        if game:GetService("Workspace").Camera:FindFirstChild("Viewmodel"):FindFirstChild("rotation") then
            game:GetService("Workspace").Camera:FindFirstChild("Viewmodel"):FindFirstChild("rotation"):Destroy()
        end
    end
end)
elseif not CBar.Text == "nocamshake" then
    --- nothing
end
if CBar.Text == "yescamshake" then
    Stepped3:Disconnect()
    task.wait()
    notification("Re Equip Your Weapon!")
elseif not CBar.Text == "yescamshake" then
    --- nothing
end    
if CBar.Text == "nocrystal" then
    if game.Workspace:FindFirstChild("Crystal zone").Crystals.redcrystal then
        for i,v in pairs(game.Workspace:FindFirstChild("Crystal zone").Crystals:GetDescendants()) do
            if v.ClassName == "Model" then
                v:Destroy()
            end
        end
    elseif not game.Workspace:FindFirstChild("Crystal zone").Crystals.redcrystal then
        notification("they are allready removed idiot")
    end
elseif not CBar.Text == "nocrystal" then
    --- nothing
end 
if CBar.Text == "nocrystalpath" then
    if game.Workspace:FindFirstChild("Crystal zone").Path.ispath then
        for i,v in pairs(game.Workspace:FindFirstChild("Crystal zone").Path:GetDescendants()) do
            if v.ClassName == "Part" then
                v:Destroy()
            end
        end
    elseif not game.Workspace:FindFirstChild("Crystal zone").Path.ispath then
        notification("they are allready removed idiot")
    end
elseif not CBar.Text == "nocrystalpath" then
    --- nothing
end
if CBar.Text == "nocrystalzone" then
    if game.Workspace:FindFirstChild("Crystal zone") then
        game.Workspace:FindFirstChild("Crystal zone"):Destroy()
    elseif not game.Workspace:FindFirstChild("Crystal zone") then
        notification("its allready removed idiot")
    end
elseif not CBar.Text == "nocrystalzone" then
    --- nothing
end
if CBar.Text == "fullbright" then
    notification("Do This Cmd Again To Enable/Disable.")
    if not _G.FullBrightExecuted then

    _G.FullBrightEnabled = false

    _G.NormalLightingSettings = {
        Brightness = game:GetService("Lighting").Brightness,
        ClockTime = game:GetService("Lighting").ClockTime,
        FogEnd = game:GetService("Lighting").FogEnd,
        GlobalShadows = game:GetService("Lighting").GlobalShadows,
        Ambient = game:GetService("Lighting").Ambient
    }

    game:GetService("Lighting"):GetPropertyChangedSignal("Brightness"):Connect(function()
        if game:GetService("Lighting").Brightness ~= 1 and game:GetService("Lighting").Brightness ~= _G.NormalLightingSettings.Brightness then
            _G.NormalLightingSettings.Brightness = game:GetService("Lighting").Brightness
            if not _G.FullBrightEnabled then
                repeat
                    wait()
                until _G.FullBrightEnabled
            end
            game:GetService("Lighting").Brightness = 1
        end
    end)

    game:GetService("Lighting"):GetPropertyChangedSignal("ClockTime"):Connect(function()
        if game:GetService("Lighting").ClockTime ~= 12 and game:GetService("Lighting").ClockTime ~= _G.NormalLightingSettings.ClockTime then
            _G.NormalLightingSettings.ClockTime = game:GetService("Lighting").ClockTime
            if not _G.FullBrightEnabled then
                repeat
                    wait()
                until _G.FullBrightEnabled
            end
            game:GetService("Lighting").ClockTime = 12
        end
    end)

    game:GetService("Lighting"):GetPropertyChangedSignal("FogEnd"):Connect(function()
        if game:GetService("Lighting").FogEnd ~= 786543 and game:GetService("Lighting").FogEnd ~= _G.NormalLightingSettings.FogEnd then
            _G.NormalLightingSettings.FogEnd = game:GetService("Lighting").FogEnd
            if not _G.FullBrightEnabled then
                repeat
                    wait()
                until _G.FullBrightEnabled
            end
            game:GetService("Lighting").FogEnd = 786543
        end
    end)

    game:GetService("Lighting"):GetPropertyChangedSignal("GlobalShadows"):Connect(function()
        if game:GetService("Lighting").GlobalShadows ~= false and game:GetService("Lighting").GlobalShadows ~= _G.NormalLightingSettings.GlobalShadows then
            _G.NormalLightingSettings.GlobalShadows = game:GetService("Lighting").GlobalShadows
            if not _G.FullBrightEnabled then
                repeat
                    wait()
                until _G.FullBrightEnabled
            end
            game:GetService("Lighting").GlobalShadows = false
        end
    end)

    game:GetService("Lighting"):GetPropertyChangedSignal("Ambient"):Connect(function()
        if game:GetService("Lighting").Ambient ~= Color3.fromRGB(178, 178, 178) and game:GetService("Lighting").Ambient ~= _G.NormalLightingSettings.Ambient then
            _G.NormalLightingSettings.Ambient = game:GetService("Lighting").Ambient
            if not _G.FullBrightEnabled then
                repeat
                    wait()
                until _G.FullBrightEnabled
            end
            game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
        end
    end)

    game:GetService("Lighting").Brightness = 1
    game:GetService("Lighting").ClockTime = 12
    game:GetService("Lighting").FogEnd = 786543
    game:GetService("Lighting").GlobalShadows = false
    game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)

    local LatestValue = true
    spawn(function()
        repeat
            wait()
        until _G.FullBrightEnabled
        while wait() do
            if _G.FullBrightEnabled ~= LatestValue then
                if not _G.FullBrightEnabled then
                    game:GetService("Lighting").Brightness = _G.NormalLightingSettings.Brightness
                    game:GetService("Lighting").ClockTime = _G.NormalLightingSettings.ClockTime
                    game:GetService("Lighting").FogEnd = _G.NormalLightingSettings.FogEnd
                    game:GetService("Lighting").GlobalShadows = _G.NormalLightingSettings.GlobalShadows
                    game:GetService("Lighting").Ambient = _G.NormalLightingSettings.Ambient
                else
                    game:GetService("Lighting").Brightness = 1
                    game:GetService("Lighting").ClockTime = 12
                    game:GetService("Lighting").FogEnd = 786543
                    game:GetService("Lighting").GlobalShadows = false
                    game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
                end
                LatestValue = not LatestValue
            end
        end
    end)
end

_G.FullBrightExecuted = true
_G.FullBrightEnabled = not _G.FullBrightEnabled
elseif not CBar.Text == "fullbright" then
    --- nothing
end   
if CBar.Text == "antifurry" then

    Stepped4 = game:GetService("RunService").RenderStepped:Connect(function()
        
        if game:GetService("Players").LocalPlayer.Character:FindFirstChild("GooHead") then

LP = game:GetService('Players').LocalPlayer

prev = LP.Character:WaitForChild('HumanoidRootPart').CFrame --holds old CFrame string
LP.Character.Parent = workspace.Terrain --removes character from workspace lol

LP.Character:BreakJoints()
 --breaks character joints
game:GetService('Workspace'):WaitForChild(LP.Name) --waits for character to be re-added to workspace
wait(3)
LP.Character:WaitForChild('HumanoidRootPart').CFrame = prev -- returns back to previous spot

end
end)
elseif not CBar.Text == "antifurry" then
    --- nothing
end
if CBar.Text == "unantifurry" then
    Stepped4:Disconnect()
elseif not CBar.Text == "unantifurry" then
    --- nothing
end
if CBar.Text == "nowater" then
if game.Workspace.map:FindFirstChild("watercube") or game.Workspace:FindFirstChild("water1") then
    game.Workspace.map:FindFirstChild("watercube"):Destroy()
    game.Workspace:FindFirstChild("water1"):Destroy()
elseif not game.Workspace.map:FindFirstChild("watercube") or game.Workspace:FindFirstChild("water1") then
    --- nothing
end

local waterfake = Instance.new("Part", game.Workspace)
waterfake.Position = Vector3.new(366.417999, -1.50000024, 284.200012, -1, 0, 0, 0, 1, 0, 0, 0, -1) + Vector3.new(0,-2.5,0)
waterfake.Orientation = Vector3.new(0,0,0)
waterfake.Anchored = true
waterfake.Size = Vector3.new(9999999999999999999999999999999999,1,9999999999999999999999999999999999)
waterfake.Name = "fuck off water"

task.wait()

game.Workspace.map:FindFirstChild("waterpart"):Destroy() 
elseif not CBar.Text == "nowater" then
    --- nothing
end    
if CBar.Text == "fpsboost" then
loadstring(game:HttpGet"https://pastebinp.com/raw/VekKpUuz")()
elseif not CBar.Text == "fpsboost" then
    --- nothing
end
if CBar.Text == "nospawnarea" then
    if game.Workspace.map:FindFirstChild("lasers") then
        game.Workspace.map:FindFirstChild("lasers"):Destroy()
    elseif not game.Workspace.map:FindFirstChild("lasers") then
        notification("allready deleted bro")
    end
elseif not CBar.Text == "nospawnarea" then
    --- nothing
end    
end)
Uis.InputEnded:Connect(function(Key)
   if Key.KeyCode.Name == "LeftAlt" then
       Ctrl = false
       CBar.Visible = false -- Dont mind this
   end
end)
