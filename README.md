local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/AikaV3rm/UiLib/master/Lib.lua')))()

local w = library:CreateWindow("Low Tier God Hub")

local b = w:CreateFolder("By Butter_Cat#0139")
    
b:Button("Reset Character",function()
local args = {
    [1] = "Your life is nothing!",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(3)
local args = {
    [1] = "You Serve Zero Purpose!",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(3)
local args = {
    [1] = "You should Reset Character now!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end)

b:Button("Go Outside",function()
local args = {
    [1] = "Your life is nothing!",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(3)
local args = {
    [1] = "You Serve Zero Purpose!",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(3)
local args = {
    [1] = "You should go outside now!",
    [2] = "All"

}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end)

b:Button("Father Figure",function()
    local args = {
    [1] = "Your life is nothing!",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(3)
local args = {
    [1] = "You Serve Zero Purpose!",
    [2] = "All"
}
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
wait(3)
local args = {
    [1] = "You should find your father figure now!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end)
b:DestroyGui()
