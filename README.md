local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
library:CreateWatermark("DEKNOI hub No.1")
local CenterHubNo1 = library:CreateWindow("Deknoi X Hub ",Enum.KeyCode.RightControl)
local Tab = CenterHubNo1:CreateTab("Main")
local Sector1 = Tab:CreateSector("Auto Farm","left")
Old_World = false
New_World = false
Three_World = false
local placeId = game.PlaceId
if placeId == 2753915549 then
    Old_World = true
elseif placeId == 4442272183 then
    New_World = true
elseif placeId == 7449423635 then
    Three_World = true
end
Sector1:AddToggle("Auto Farm",false,function(t)
local Tab = CenterHubNo1:CreateTab("Teleport")
local Sector2 = Tab:CreateSector("Teleport","left")
Sector2:AddToggle("Ctrl + Click = TP",false,function(vu)
    CTRL = vu
    end)
    local Plr = game:GetService("Players").LocalPlayer
    local Mouse = Plr:GetMouse()
    Mouse.Button1Down:connect(
    function()
      if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
        return
      end
      if not Mouse.Target then
        return
      end
      if CTRL then
        Plr.Character:MoveTo(Mouse.Hit.p)
      end
    end)
Sector2:AddButton("Port town",function()
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(60, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-243.04154968262, 6.7557435035706, 5347.5927734375)})
    tween:Play()
    v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Mansion",function()
    tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(60, Enum.EasingStyle.Linear)
    tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-12552.8066, 337.194061, -7470.02637, -0.000724825368, 0, -0.999999762, 0, 1, 0, 0.999999762, 0, -0.000724825368)})
    tween:Play()
    v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Sea Castle",function()
        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(60, Enum.EasingStyle.Linear)
        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-5074.2280273438, 314.5412902832, -2980.3911132812)})
        tween:Play()
        v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Hauted Castle",function()
        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(60, Enum.EasingStyle.Linear)
        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-9504.3232421875, 142.13061523438, 5520.9326171875)})
        tween:Play()
        v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Hydra Island",function()
        tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(60, Enum.EasingStyle.Linear)
        tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(5274.4873046875, 602.0693359375, 321.09646606445)})
        tween:Play()
        v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Save",function()
       tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(30, Enum.EasingStyle.Linear)
       tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-5327.1157226562, 1878.9854736328, -2504.9079589844)})
       tween:Play()
       v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Beautiful Pirate",function()
       tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(60, Enum.EasingStyle.Linear)
       tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(5307.3549804688, 22.56223487854, -37.132148742676)})
       tween:Play()
       v.Humanoid:ChangeState(11)
    end)
       Sector2:AddButton("Do Tushita Beta",function()
          tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(60, Enum.EasingStyle.Linear)
          tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(5154.9096679688, 141.81224060059, 916.3544921875)})
          tween:Play()
          v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Do Tushita Beta 1",function()
       tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(20, Enum.EasingStyle.Linear)
       tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-10753.6875, 412.22952270508, -9366.4111328125)})
       tween:Play()
       v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Do Tushita Beta 2",function()
       tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(20, Enum.EasingStyle.Linear)
       tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-12133.139648438, 519.47521972656, -10655.107421875)})
       tween:Play()
       v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Do Tushita Beta 3",function()
       tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(15, Enum.EasingStyle.Linear)
       tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-13337.799804688, 485.94622802734, -6984.4028320312)})
       tween:Play()
       v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("Do Tushita Beta 4",function()
       tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(15, Enum.EasingStyle.Linear)
       tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-13486.76953125, 332.40393066406, -7924.84765625)})
       tween:Play()
       v.Humanoid:ChangeState(11)
    end)
    Sector2:AddButton("By pass Mansion",function()

local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(-12462.883789062, 374.94024658203, -7549.2065429688)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector2:AddButton("By pass Hydra",function()
local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(5750.0512695312, 610.44982910156, -248.16889953613)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector2:AddButton("By pass Castle Island",function()
local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(-5064.8447265625, 314.5412902832, -3155.0434570312)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector2:AddButton("By pass Beatiful inside",function()
local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(5314.58203125, 25.419387817383, -125.94227600098)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector2:AddButton("By pass Beatiful Out Side",function()
local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(-11993.580078125, 334.78128051758, -8844.1826171875)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector2:AddButton("By pass Water Under City",function()
local args = {
    [1] = "requestEntrance",
    [2] = Vector3.new(61163.8515625, 11.6796875, 1819.7841796875)
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
    local Tab = CenterHubNo1:CreateTab("Misc")
    local Sector4 = Tab:CreateSector("Misc","left")
    Sector4:AddToggle("Fly",false,function(a)
        Fly = Value
        activatefly()
        end)
        Sector4:AddToggle("No Clip",false,function(value)
        v.Humanoid:ChangeState(11)
        end)
        Sector4:AddToggle("Auto Haki",true,function(value)
        local args = {
            [1] = "Buso"
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end)
        Sector4:AddButton("SharkMan Karate",function(value)
           -- Script generated by SimpleSpy - credits to exx#9394
        
        local args = {
           [1] = "BuySharkmanKarate"
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end)
        
        -- Script generated by SimpleSpy - credits to exx#9394
        Sector4:AddButton("Death Step",function(value)
        local args = {
           [1] = "BuyDeathStep"
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end)
        Sector4:AddButton("SuperHuman",function(value)
        -- Script generated by SimpleSpy - credits to exx#9394
        
        local args = {
           [1] = "BuySuperhuman"
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end)
        
        Sector4:AddButton("Electci claw",function(Value)
           -- Script generated by SimpleSpy - credits to exx#9394
        
           local args = {
               [1] = "BuyElectricClaw"
           }
           
           game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end)
        Sector4:AddButton("Black leg",function(Value)
local args = {
    [1] = "BuyBlackLeg"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector4:AddButton("Electric",function(Value)
-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "BuyElectro"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector4:AddButton("Water Kung Fu",function(Value)
-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "BuyFishmanKarate"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector4:AddButton("Dragon Breath",function(Value)
-- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "BlackbeardReward",
    [2] = "DragonClaw",
    [3] = "2"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector4:AddButton("Dragon Talon",function(Value)
    -- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "BuyDragonTalon"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
        Sector4:AddToggle("Auto Random Fruit",false,function(value)
        -- Script generated by SimpleSpy - credits to exx#9394
        
        local args = {
            [1] = "Cousin",
            [2] = "Buy"
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        end)
        Sector4:AddButton("Random Race",false,function(value)
        -- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "BlackbeardReward",
    [2] = "Reroll",
    [3] = "1"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Sector4:AddButton("Restats",false,function(value)
    -- Script generated by SimpleSpy - credits to exx#9394

local args = {
    [1] = "BlackbeardReward",
    [2] = "Refund",
    [3] = "1"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
            Sector4:AddButton("Marine Join",function(value)
                local args = {
                    [1] = "SetTeam",
                    [2] = "Marines"
                  }
                  game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
                end)
        Sector4:AddButton("Pirate Join",function(value)
            local args = {
                [1] = "SetTeam",
                [2] = "Pirates"
              }
              game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end)
        Sector4:AddButton("FPS Boost",function()
           local decalsyeeted = true -- Leaving this on makes games look shitty but the fps goes up by at least 20.
           local g = game
           local w = g.Workspace
           local l = g.Lighting
           local t = w.Terrain
           t.WaterWaveSize = 0
           t.WaterWaveSpeed = 0
           t.WaterReflectance = 0
           t.WaterTransparency = 0
           l.GlobalShadows = false
           l.FogEnd = 9e9
           l.Brightness = 0
           settings().Rendering.QualityLevel = "Level01"
           for i, v in pairs(g:GetDescendants()) do
             if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then
               v.Material = "Plastic"
               v.Reflectance = 0
             elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
               v.Transparency = 1
             elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
               v.Lifetime = NumberRange.new(0)
             elseif v:IsA("Explosion") then
               v.BlastPressure = 1
               v.BlastRadius = 1
             elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
               v.Enabled = false
             elseif v:IsA("MeshPart") then
               v.Material = "Plastic"
               v.Reflectance = 0
               v.TextureID = 10385902758728957
             end
           end
           for i, e in pairs(l:GetChildren()) do
             if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
               e.Enabled = false
             end
           end
           end)
    local Sector4 = Tab:CreateSector("Misc","right")
        end)
        local Sector5 = CenterHubNo1:CreateTab("Game")
        local Sector5 = Sector5:CreateSector("Game","left")
    Sector5:AddToggle("Music Shark X",false,function()
        _G.Music = "rbxassetid://7184554636"

Instance.new("Sound", game:GetService("Workspace")).Name = "MUSIC_FUNCTION"

    game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = false
    game:GetService("Workspace")["MUSIC_FUNCTION"].Volume = 1
    game.workspace["MUSIC_FUNCTION"].SoundId = _G.Music 
    game.workspace["MUSIC_FUNCTION"].Playing = true
    end)
    Sector5:AddToggle("Music Shark X Close",false,function()
        _G.Music = "rbxassetid://7184554636"

Instance.new("Sound", game:GetService("Workspace")).Name = "MUSIC_FUNCTION"

    game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = false
    game:GetService("Workspace")["MUSIC_FUNCTION"].Volume = 1
    game.workspace["MUSIC_FUNCTION"].SoundId = _G.Music 
    game.workspace["MUSIC_FUNCTION"].Playing = false
    end)
    Sector5:AddToggle("Music Saran",false,function()
        _G.Music = "rbxassetid://6781122747"

        Instance.new("Sound", game:GetService("Workspace")).Name = "MUSIC_FUNCTION"

    game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = false
    game:GetService("Workspace")["MUSIC_FUNCTION"].Volume = 1
    game.workspace["MUSIC_FUNCTION"].SoundId = _G.Music 
    game.workspace["MUSIC_FUNCTION"].Playing = true
    end)
    Sector5:AddToggle("Music Saran Close",false,function()
        _G.Music = "rbxassetid://6781122747"

        Instance.new("Sound", game:GetService("Workspace")).Name = "MUSIC_FUNCTION"

    game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = false
    game:GetService("Workspace")["MUSIC_FUNCTION"].Volume = 1
    game.workspace["MUSIC_FUNCTION"].SoundId = _G.Music 
    game.workspace["MUSIC_FUNCTION"].Playing = false
    end)
    Sector5:AddToggle("Music Saran Gologoso",false,function()
        _G.Music = "rbxassetid://7663351238"

        Instance.new("Sound", game:GetService("Workspace")).Name = "MUSIC_FUNCTION"

    game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = false
    game:GetService("Workspace")["MUSIC_FUNCTION"].Volume = 1
    game.workspace["MUSIC_FUNCTION"].SoundId = _G.Music 
    game.workspace["MUSIC_FUNCTION"].Playing = true
    end)
    Sector5:AddToggle("Music Saran Gologoso Close",false,function()
        _G.Music = "rbxassetid://7663351238"

        Instance.new("Sound", game:GetService("Workspace")).Name = "MUSIC_FUNCTION"

    game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = false
    game:GetService("Workspace")["MUSIC_FUNCTION"].Volume = 1
    game.workspace["MUSIC_FUNCTION"].SoundId = _G.Music 
    game.workspace["MUSIC_FUNCTION"].Playing = false
    end)
    Sector5:AddToggle("Loop",false,function()
        game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = true
    end)
    Sector5:AddToggle("Loop Close",false,function()
        game:GetService("Workspace")["MUSIC_FUNCTION"].Looped = false
    end)
    Sector5:AddToggle("Auto Enble PvP",false,function()
        _G.EnablePvp = true
        while _G.EnablePvp do wait(2)
        local args = {
            [1] = "EnablePvp"
        }
        
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end
    end)     
    local Sector6 = CenterHubNo1:CreateTab("Players")
    local Sector6 = Sector6:CreateSector("Players","left")   
    local Players = serv:Channel("Players","http://www.roblox.com/asset/?id=7252023075")
SelectKillWeapon = ""

Player = ""
local SelectPlayer = Sector6:AddDropdown("Selected Player", PlayerName, function(vu)
    SelectedKillPlayer = vu
end)

Sector6:AddButton("Refresh Player", function()
    PlayerName = {}
    SelectPlayer:Clear()
    for i,v in pairs(game.Players:GetChildren()) do
		if v.Name ~= game.Players.LocalPlayer.Name then
	        SelectPlayer:Add(v.Name)
		end
    end
end)

Sector6:AddToggle("Spectate Player", false, function(vu)
    Spectate = vu
    repeat game:GetService("RunService").Heartbeat:wait()
        game.Workspace.Camera.CameraSubject = game.Players:FindFirstChild(SelectedKillPlayer).Character.Humanoid
    until Spectate == false
    game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
end)

Sector6:AddToggle("Kill All Player + Hop [Defense 1 only]", _G.AutoBounty, function()
	_G.AutoBounty = vu
end)

Sector6:AddToggle("Safe Mode", false, function(vu)
    SafeMode = vu
	TP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
end)

local SelectWeapon = Sector6:AddDropdown("Select Weapon",Wapon,function(Value)
    SelectKillWeapon = Value
end)

Sector6:AddButton("Refresh Weapon", function()
    SelectWeapon:Clear()
	for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		if v:IsA("Tool") then
			SelectWeapon:Add(v.Name)
		end
	end
	for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
		if v:IsA("Tool") then
			SelectWeapon:Add(v.Name)
		end
	end
end)

Sector6:AddToggle("Kill Player", false, function(vu)
    KillPlayer = vu
	TP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
end)

Sector6:AddToggle("Aimbot Gun", false, function(vu)
	Aimbot = vu
end)

Sector6:AddToggle("Aimbot Skill Nearest", false, function(vu)
	AimSkillNearest = vu
end)

spawn(function()
	while wait(.1) do
		pcall(function()
			local MaxDistance = math.huge
			for i,v in pairs(game:GetService("Players"):GetPlayers()) do
				if v.Name ~= game.Players.LocalPlayer.Name then
					local Distance = v:DistanceFromCharacter(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
					if Distance < MaxDistance then
						MaxDistance = Distance
						TargetPlayerAim = v.Name
					end
				end
			end
		end)
	end
end)

spawn(function()
	pcall(function()
		game:GetService("RunService").RenderStepped:connect(function()
			if AimSkillNearest and TargetPlayerAim ~= nil and game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool") and game.Players.LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name]:FindFirstChild("MousePos") then
				local args = {
					[1] = game:GetService("Players"):FindFirstChild(TargetPlayerAim).Character.HumanoidRootPart.Position
				}
				game:GetService("Players").LocalPlayer.Character[game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name].RemoteEvent:FireServer(unpack(args))
			end
		end)
	end)
end)

Sector6:AddSlider("WalkSpeed", 0,1000,16, function(t)
    game:GetService("Players").LocalPlayer.Character.Humanoid.WalkSpeed = t
    while t do wait(1)
        game:GetService("Players").LocalPlayer.Character.Movement.Disabled = true
    end
end)

Sector6:AddSlider("Jump Power", 0,1000,50, function(t)
    game:GetService("Players").LocalPlayer.Character.Humanoid.JumpPower = t
end)

Sector6:AddSlider("Gravity", 0,500,196, function(t)
    workspace.Gravity = t
end)
