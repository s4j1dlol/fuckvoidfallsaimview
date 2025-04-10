local weshuasaimviewer = Instance.new("ScreenGui")
local UI = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local ScrollingFrame = Instance.new("ScrollingFrame")
local aimviewer = Instance.new("Frame")
local UIListLayout = Instance.new("UIListLayout")
local TargetUser = Instance.new("TextBox")
local Reset = Instance.new("TextButton")
local UIPadding = Instance.new("UIPadding")
local View = Instance.new("TextButton")
local UIPadding_2 = Instance.new("UIPadding")
local UICorner_2 = Instance.new("UICorner")
local UIListLayout_2 = Instance.new("UIListLayout")
local Background = Instance.new("ImageLabel")
local UICorner_3 = Instance.new("UICorner")
local TopFrame = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local TitleLabel = Instance.new("TextLabel")
local Background_2 = Instance.new("ImageLabel")
local UICorner_5 = Instance.new("UICorner")
local OppText = Instance.new("TextLabel")

weshuasaimviewer.Name = "weshuas aimviewer"
weshuasaimviewer.Parent = game:GetService("CoreGui")
weshuasaimviewer.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

UI.Name = "UI"
UI.Parent = weshuasaimviewer
UI.AnchorPoint = Vector2.new(0.5, 0.5)
UI.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
UI.BackgroundTransparency = 0.500
UI.BorderColor3 = Color3.fromRGB(27, 42, 53)
UI.Position = UDim2.new(0.5, 0, 0.5, 0)
UI.Size = UDim2.new(0, 250, 0, 300)
UI.Active = true
UI.Draggable = true

UICorner.Parent = UI

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(75, 75, 75)), ColorSequenceKeypoint.new(0.46, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(75, 75, 75))}
UIGradient.Rotation = 90
UIGradient.Parent = UI

ScrollingFrame.Parent = UI
ScrollingFrame.Active = true
ScrollingFrame.AnchorPoint = Vector2.new(0.5, 0.5)
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BackgroundTransparency = 0.300
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.5, 0, 0.5719558, 0)
ScrollingFrame.Size = UDim2.new(0, 238, 0, 246)
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 1.58000004, 0)
ScrollingFrame.ScrollBarThickness = 0

aimviewer.Name = "aimviewer"
aimviewer.Parent = ScrollingFrame
aimviewer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aimviewer.BackgroundTransparency = 1.000
aimviewer.BorderColor3 = Color3.fromRGB(27, 42, 53)
aimviewer.Size = UDim2.new(0, 237, 0, 43)

UIListLayout.Parent = aimviewer
UIListLayout.FillDirection = Enum.FillDirection.Horizontal
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder

TargetUser.Name = "TargetUser"
TargetUser.Parent = aimviewer
TargetUser.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TargetUser.BackgroundTransparency = 1.000
TargetUser.BorderColor3 = Color3.fromRGB(27, 42, 53)
TargetUser.Size = UDim2.new(0, 137, 0, 50)
TargetUser.Font = Enum.Font.SourceSans

TargetUser.Text = ""
TargetUser.TextColor3 = Color3.fromRGB(255, 255, 255)
TargetUser.TextSize = 28.000
TargetUser.PlaceholderText = "Target"

Reset.Name = "Reset"
Reset.Parent = aimviewer
Reset.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Reset.BackgroundTransparency = 1.000
Reset.BorderColor3 = Color3.fromRGB(27, 42, 53)
Reset.Size = UDim2.new(0, 50, 0, 50)
Reset.Font = Enum.Font.GothamBold
Reset.Text = "RESET"
Reset.TextColor3 = Color3.fromRGB(255, 0, 0)
Reset.TextScaled = true
Reset.TextSize = 32.000
Reset.TextWrapped = true

UIPadding.Parent = Reset
UIPadding.PaddingBottom = UDim.new(0.100000001, 0)
UIPadding.PaddingLeft = UDim.new(0.100000001, 0)
UIPadding.PaddingRight = UDim.new(0.100000001, 0)
UIPadding.PaddingTop = UDim.new(0.100000001, 0)

View.Name = "View"
View.Parent = aimviewer
View.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
View.BackgroundTransparency = 1.000
View.BorderColor3 = Color3.fromRGB(27, 42, 53)
View.Size = UDim2.new(0, 50, 0, 50)
View.Font = Enum.Font.GothamBold
View.Text = "VIEW"
View.TextColor3 = Color3.fromRGB(255, 255, 255)
View.TextScaled = true
View.TextSize = 32.000
View.TextWrapped = true

UIPadding_2.Parent = View
UIPadding_2.PaddingBottom = UDim.new(0.100000001, 0)
UIPadding_2.PaddingLeft = UDim.new(0.100000001, 0)
UIPadding_2.PaddingRight = UDim.new(0.100000001, 0)
UIPadding_2.PaddingTop = UDim.new(0.100000001, 0)

UICorner_2.Parent = ScrollingFrame

UIListLayout_2.Parent = ScrollingFrame

Background.Name = "Background"
Background.Parent = UI
Background.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Background.BackgroundTransparency = 1.000
Background.BorderColor3 = Color3.fromRGB(0, 0, 0)
Background.BorderSizePixel = 0
Background.Size = UDim2.new(0, 250, 0, 300)
Background.ZIndex = 0
Background.Image = "rbxassetid://2151741365"

UICorner_3.Parent = Background

TopFrame.Name = "TopFrame"
TopFrame.Parent = UI
TopFrame.AnchorPoint = Vector2.new(0.5, 0.5)
TopFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TopFrame.BackgroundTransparency = 0.300
TopFrame.BorderColor3 = Color3.fromRGB(27, 42, 53)
TopFrame.BorderSizePixel = 0
TopFrame.Position = UDim2.new(0.500999987, 0, 0.0844526142, 0)
TopFrame.Size = UDim2.new(0, 237, 0, 37)

UICorner_4.Parent = TopFrame

TitleLabel.Name = "TitleLabel"
TitleLabel.Parent = TopFrame
TitleLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TitleLabel.BackgroundTransparency = 1.000
TitleLabel.BorderColor3 = Color3.fromRGB(27, 42, 53)
TitleLabel.Size = UDim2.new(0, 237, 0, 35)
TitleLabel.Font = Enum.Font.SourceSans
TitleLabel.Text = "Void Falls Aimviewer"
TitleLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TitleLabel.TextSize = 32.000

Background_2.Name = "Background"
Background_2.Parent = UI
Background_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Background_2.BackgroundTransparency = 1.000
Background_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Background_2.BorderSizePixel = 0
Background_2.Size = UDim2.new(0, 250, 0, 300)
Background_2.ZIndex = 0
Background_2.Image = "rbxassetid://2151741365"

UICorner_5.Parent = Background_2

OppText.Name = "OppText"
OppText.Parent = UI
OppText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OppText.BackgroundTransparency = 1.000
OppText.BorderColor3 = Color3.fromRGB(0, 0, 0)
OppText.BorderSizePixel = 0
OppText.Position = UDim2.new(0.100000001, 0, 0.326666653, 0)
OppText.Size = UDim2.new(0, 204, 0, 171)
OppText.Font = Enum.Font.SourceSans
OppText.Text = "vf aimviewer brought back by <u><i>IDKKK</i></u> :p <i>fuck my opps!</i>"
OppText.TextColor3 = Color3.fromRGB(178, 178, 178)
OppText.TextScaled = true
OppText.TextSize = 32.000
OppText.TextWrapped = true
OppText.RichText = true

-- scripts

local TargetPlayer = nil
local beamAttachment = nil
local aimPart = nil
local beam = nil
local attachment = nil
local spawnBeam = nil
local runService = game:GetService("RunService")

-- Function to create and show notifications
local function makeNotification(title, text, idArg)
    local imageArg = (idArg == "good") and "375691700" or "132769506"
    game:GetService("StarterGui"):SetCore("SendNotification", {
        Title = title,
        Text = text,
        Icon = "rbxassetid://" .. imageArg
    })
end

-- Function to retrieve a player by partial username/display name
local function getPlayerByPartialName(partialName)
    local target = nil

    for _, player in pairs(game.Players:GetPlayers()) do
        if string.sub(string.lower(player.Name), 1, #partialName) == string.lower(partialName) then
            target = player
        end
    end

    if not target then
        for _, player in pairs(game.Players:GetPlayers()) do
            if string.sub(string.lower(player.DisplayName), 1, #partialName) == string.lower(partialName) then
                target = player
            end
        end
    end

    if target then
        if target.Name == game.Players.LocalPlayer.Name then
            makeNotification("LOL", "Nice try", "not good")
            return nil
        else
            return target
        end
    else
        return nil
    end
end

-- View Player Button Logic
View.MouseButton1Click:Connect(function()
    local playerName = TargetUser.Text
    local player = getPlayerByPartialName(playerName)

    if not player then
        makeNotification("Failed", "Failed to get username", "not good")
        return
    end

    if TargetPlayer then
        -- Reset previous target view
        if beam then
            beam:Destroy()
        end
        if beamAttachment then
            beamAttachment:Destroy()
        end
        if aimPart then
            aimPart:Destroy()
        end
        makeNotification("Worked", "Now viewing " .. player.Name, "good")
    else
        TargetPlayer = player
        makeNotification("Worked", "Now viewing " .. player.Name, "good")
    end

    -- Create new parts and attachments for the beam
    aimPart = Instance.new("Part", workspace)
    aimPart.Size = Vector3.new(1, 0.5, 1)
    aimPart.Name = "AimPart"
    aimPart.CanQuery = false
    aimPart.CanCollide = false
    aimPart.Anchored = true

    beamAttachment = Instance.new("Attachment", TargetPlayer.Character.Head)
    beamAttachment.Name = "BeamAttachment"

    attachment = Instance.new("Attachment", aimPart)

    beam = Instance.new("Beam", workspace)
    beam.Name = "Beam"
    beam.Enabled = true

    beam.Color = ColorSequence.new({
        ColorSequenceKeypoint.new(0, Color3.fromRGB(255, 0, 0)),
        ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 0, 0))
    })
    beam.LightEmission = 1
    beam.LightInfluence = 0
    beam.Width0 = 0.2
    beam.Width1 = 0.2
    beam.FaceCamera = true
    beam.Attachment0 = beamAttachment
    beam.Attachment1 = attachment

    -- Handle player re-joining (character added)
    spawnBeam = TargetPlayer.CharacterAdded:Connect(function(newCharacter)
        repeat wait() until TargetPlayer.Character
        beamAttachment = Instance.new("Attachment", newCharacter.Head)
        beam.Attachment0 = beamAttachment
    end)

    -- Update the beam position during the game loop
    runService.Stepped:Connect(function()
        if not TargetPlayer then
            return
        end

        -- Handle tool and ammo
        local tool = TargetPlayer.Character:FindFirstChildOfClass("Tool")
        if tool and tool:FindFirstChild("AMMO") then
            beam.Enabled = true
            aimPart.Transparency = 0
            beamAttachment.Parent = tool.Handle.Flare

            if TargetPlayer.Backpack:GetAttribute("AimPosition") then
                local aimPosition = TargetPlayer.Backpack:GetAttribute("AimPosition")
                local direction = (aimPosition - tool.Handle.Flare.WorldPosition).Unit * 300
                local raycastParams = RaycastParams.new()
                raycastParams.FilterDescendantsInstances = tool.Parent:GetDescendants()
                raycastParams.FilterType = Enum.RaycastFilterType.Exclude

                local hit = workspace:Raycast(tool.Handle.Flare.WorldPosition, direction, raycastParams)
                if hit then
                    aimPart.Position = hit.Position
                    local hitModel = hit.Instance:FindFirstAncestorOfClass("Model", true)
                    if hitModel and hitModel:FindFirstChild("Humanoid") then
                        beam.Color = ColorSequence.new({
                            ColorSequenceKeypoint.new(0, Color3.fromRGB(255, 255, 0)),
                            ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 0))
                        })
                    else
                        beam.Color = ColorSequence.new({
                            ColorSequenceKeypoint.new(0, Color3.fromRGB(255, 0, 0)),
                            ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 0, 0))
                        })
                    end
                else
                    aimPart.Position = tool.Handle.Flare.WorldPosition + direction
                    beam.Color = ColorSequence.new({
                        ColorSequenceKeypoint.new(0, Color3.fromRGB(255, 0, 0)),
                        ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 0, 0))
                    })
                end
            end
        else
            beam.Enabled = false
            aimPart.Transparency = 1
            beamAttachment.Parent = TargetPlayer.Character.Head
        end
    end)
end)

-- Reset Button Logic
Reset.MouseButton1Click:Connect(function()
    -- Disconnect and destroy existing objects if needed
    if beam then
        beam:Destroy()
    end
    if beamAttachment then
        beamAttachment:Destroy()
    end
    if aimPart then
        aimPart:Destroy()
    end
    if TargetPlayer then
        makeNotification("Stopped", "Stopped viewing " .. TargetPlayer.Name, "not good")
        TargetPlayer = nil
    else
        makeNotification("Nope", "Wasn't viewing anyone", "not good")
    end
end)
