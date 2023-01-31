local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("DomTech Hub", "DarkTheme")
local remotePath = game:GetService("ReplicatedStorage").Remotes

local Tab = Window:NewTab("Races V4")
--Races V4 Teleport
local Section = Tab:NewSection("Teleport")

Section:NewButton("Temple of Time","", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28286.3555, 14896.5342, 102.624695, 0.0361683369, -7.52910712e-09, 0.99934572, 7.88635646e-08, 1, 4.67980454e-09, -0.99934572, 7.86427066e-08, 0.0361683369)
end)

Section:NewButton("Clever","", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28575.1172, 14937.8594, 72.9514847, -0.999999166, 1.95918357e-08, 0.00129557389, 1.96037959e-08, 1, 9.21894028e-09, -0.00129557389, 9.24433063e-09, -0.999999166)
end)

local Section = Tab:NewSection("Teleport 1")

Section:NewButton("Shark Gate V4","", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28725.0664, 14887.5596, -81.2946091, -0.0252211057, 4.37406982e-08, -0.99968189, -1.32500295e-08, 1, 4.40889032e-08, 0.99968189, 1.43577861e-08, -0.0252211057)
    wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28225.5449, 14890.6592, -211.407486, 0.000928392517, 1.08912467e-07, 0.999999583, 2.47758241e-08, 1, -1.08935517e-07, -0.999999583, 2.48769485e-08, 0.000928392517)
end)

Section:NewButton("Cybord Gate V4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28725.0664, 14887.5596, -81.2946091, -0.0252211057, 4.37406982e-08, -0.99968189, -1.32500295e-08, 1, 4.40889032e-08, 0.99968189, 1.43577861e-08, -0.0252211057)
    wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28495.7734, 14895.6582, -422.757965, 0.00911685731, 1.84143278e-08, 0.999958456, 1.8354628e-08, 1, -1.85824369e-08, -0.999958456, 1.85232789e-08, 0.00911685731)
end)

Section:NewButton("Rabbit Gate V4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28725.0664, 14887.5596, -81.2946091, -0.0252211057, 4.37406982e-08, -0.99968189, -1.32500295e-08, 1, 4.40889032e-08, 0.99968189, 1.43577861e-08, -0.0252211057)
    wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(29018.6016, 14890.6582, -379.476959, -0.0136231221, -2.2180151e-08, -0.999907196, -1.05748285e-07, 1, -2.0741453e-08, 0.999907196, 1.05455911e-07, -0.0136231221)
end)

Section:NewButton("Human Gate V4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28725.0664, 14887.5596, -81.2946091, -0.0252211057, 4.37406982e-08, -0.99968189, -1.32500295e-08, 1, 4.40889032e-08, 0.99968189, 1.43577861e-08, -0.0252211057)
    wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(29232.3945, 14890.6582, -206.106796, 0.00881271344, 3.61804919e-09, -0.999961138, -2.05697699e-08, 1, 3.4369072e-09, 0.999961138, 2.05386819e-08, 0.00881271344)
end)

Section:NewButton("Ghoul Gate V4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28725.0664, 14887.5596, -81.2946091, -0.0252211057, 4.37406982e-08, -0.99968189, -1.32500295e-08, 1, 4.40889032e-08, 0.99968189, 1.43577861e-08, -0.0252211057)
    wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28672.9688, 14890.3613, 451.107788, -0.99994266, -7.93182142e-09, -0.0107079614, -7.77457121e-09, 1, -1.47270018e-08, 0.0107079614, -1.46429082e-08, -0.99994266)
end)

Section:NewButton("Sky Gate V4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28725.0664, 14887.5596, -81.2946091, -0.0252211057, 4.37406982e-08, -0.99968189, -1.32500295e-08, 1, 4.40889032e-08, 0.99968189, 1.43577861e-08, -0.0252211057)
    wait()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28964.4375, 14919.3066, 234.451019, 0.0190088041, -2.2531963e-09, -0.999819338, -4.91191798e-08, 1, -3.18746896e-09, 0.999819338, 4.91708931e-08, 0.0190088041)
end)
--Complete
local Section = Tab:NewSection("Complete Trials")

Section:NewButton("Rabbit V4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3333, 11000, 16000, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

Section:NewButton("Angel V4", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(12000, 17000, 5555, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

Section:NewButton("Cybord Safe (Test)", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-20010.7637, 10009.4004, -25.7639999, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

local Section = Tab:NewSection("Ancient One")

Section:NewButton("Teleport","",function ()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(28977.5195, 14889.6582, -119.156143, -0.00927338935, 7.81460017e-08, 0.999957025, -7.37632604e-08, 1, -7.88334305e-08, -0.999957025, -7.44911404e-08, -0.00927338935)
end)

Section:NewButton("Complete Train Seasons","",function ()
    local args = {
        [1] = "Ancient One"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

--Teleport
local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("Teleport")

Section:NewButton("Masion", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-12550.3789, 337.194061, -7467.9707, 0.999997795, 4.86966556e-08, -0.00209881202, -4.86113834e-08, 1, 4.0678696e-08, 0.00209881202, -4.05765803e-08, 0.999997795)
end)

Section:NewButton("Castle on the sea", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4990.60596, 314.54129, -3014.92944, -0.361172259, 3.58336045e-08, 0.932499111, 5.48476038e-08, 1, -1.71841137e-08, -0.932499111, 4.49389184e-08, -0.361172259)
end)

Section:NewButton("TurTle Centre", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-11993.5801, 331.833496, -8844.18262, 1, -8.28384472e-08, -4.21672869e-13, 8.28384472e-08, 1, 4.91729288e-08, 4.17599467e-13, -4.91729288e-08, 1)
end)
--Melee
local Tab = Window:NewTab("Melee")
local Section = Tab:NewSection("Melee V1")

Section:NewButton("Black Leg", "", function()
    local args = {
        [1] = "BuyBlackLeg"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Electro", "", function()
    local args = {
        [1] = "BuyElectro"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Electro", "", function()
    local args = {
        [1] = "BuyFishmanKarate"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Dragon Breath", "", function()
    local args = {
        [1] = "BlackbeardReward",
        [2] = "DragonClaw",
        [3] = "2"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("SuperHuman", "", function()
    local args = {
        [1] = "BuySuperhuman"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

local Section = Tab:NewSection("Melee V2")

Section:NewButton("Death Step", "", function()
    local args = {
        [1] = "BuyDeathStep"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("SharkmanKarate", "", function()
    local args = {
        [1] = "BuySharkmanKarate"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Electric Claw", "", function()
    local args = {
        [1] = "BuyElectricClaw"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Dragon Talon", "", function()
    local args = {
        [1] = "BuyDragonTalon"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Godhuman", "", function()
    local args = {
        [1] = "BuyGodhuman"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

--Setting
local Tab = Window:NewTab("Setting")
local Section = Tab:NewSection("GUI")

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.RightControl, function()
	Library:ToggleUI()
end)

--Shop
local Tab = Window:NewTab("Shop")
local Section = Tab:NewSection("Shop")

Section:NewButton("Races Roll (3,000 Fragments)", "", function()
    local args = {
        [1] = "BlackbeardReward",
        [2] = "Reroll",
        [3] = "2"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Ghoul", "", function()
    local args = {
        [1] = "Ectoplasm",
        [2] = "BuyCheck",
        [3] = 4
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Cybord (2,500 Fragments)", "", function()
    local args = {
        [1] = "CyborgTrainer",
        [2] = "Buy"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Random Fruit","",function ()
    local args = {
        [1] = "Cousin",
        [2] = "Buy"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

Section:NewButton("Player Hunter Quest","",function ()
    local args = {
        [1] = "PlayerHunter"
    }
    remotePath.CommF_:InvokeServer(unpack(args))
end)

local Section = Tab:NewSection("Server")

Section:NewButton("Copy Id Server","",function ()
    setclipboard(game.JobId)
end)


Section:NewButton("FastAttack Off","",function ()
    (getgenv()).Config = {
        ["FastAttack"] = false,
        ["ClickAttack"] = false
       } 
       coroutine.wrap(function()
       local StopCamera = require(game.ReplicatedStorage.Util.CameraShaker)StopCamera:Stop()
           for v,v in pairs(getreg()) do
               if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework then
                    for v,v in pairs(debug.getupvalues(v)) do
                       if typeof(v) == "table" then
                           spawn(function()
                               game:GetService("RunService").RenderStepped:Connect(function()
                                   if getgenv().Config['FastAttack'] then
                                        pcall(function()
                                            v.activeController.timeToNextAttack = -(math.huge^math.huge^math.huge)
                                            v.activeController.attacking = false
                                            v.activeController.increment = 4
                                            v.activeController.blocking = false   
                                            v.activeController.hitboxMagnitude = 150
                                            v.activeController.humanoid.AutoRotate = true
                                              v.activeController.focusStart = 0
                                              v.activeController.currentAttackTrack = 0
                                            sethiddenproperty(game:GetService("Players").LocalPlayer, "SimulationRaxNerous", math.huge)
                                        end)
                                    end
                                end)
                           end)
                       end
                   end
               end
           end
       end)();
       
       spawn(function()
           game:GetService("RunService").RenderStepped:Connect(function()
               if getgenv().Config['ClickAttack'] then
                    pcall(function()
                       game:GetService'VirtualUser':CaptureController()
                       game:GetService'VirtualUser':Button1Down(Vector2.new(0,1,0,1))
                   end)
               end
           end)
       end)
 end)

 Section:NewButton("FastAttack On","",function ()
    (getgenv()).Config = {
        ["FastAttack"] = true,
        ["ClickAttack"] = true
       } 
       coroutine.wrap(function()
       local StopCamera = require(game.ReplicatedStorage.Util.CameraShaker)StopCamera:Stop()
           for v,v in pairs(getreg()) do
               if typeof(v) == "function" and getfenv(v).script == game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework then
                    for v,v in pairs(debug.getupvalues(v)) do
                       if typeof(v) == "table" then
                           spawn(function()
                               game:GetService("RunService").RenderStepped:Connect(function()
                                   if getgenv().Config['FastAttack'] then
                                        pcall(function()
                                            v.activeController.timeToNextAttack = -(math.huge^math.huge^math.huge)
                                            v.activeController.attacking = false
                                            v.activeController.increment = 4
                                            v.activeController.blocking = false   
                                            v.activeController.hitboxMagnitude = 150
                                            v.activeController.humanoid.AutoRotate = true
                                              v.activeController.focusStart = 0
                                              v.activeController.currentAttackTrack = 0
                                            sethiddenproperty(game:GetService("Players").LocalPlayer, "SimulationRaxNerous", math.huge)
                                        end)
                                    end
                                end)
                           end)
                       end
                   end
               end
           end
       end)();
       
       spawn(function()
           game:GetService("RunService").RenderStepped:Connect(function()
               if getgenv().Config['ClickAttack'] then
                    pcall(function()
                       game:GetService'VirtualUser':CaptureController()
                       game:GetService'VirtualUser':Button1Down(Vector2.new(0,1,0,1))
                   end)
               end
           end)
       end)
 end)
