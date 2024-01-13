local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()

local window = DrRayLibrary:Load("Thai Hub Meme Adventure", "Default")

local tab = DrRayLibrary.newTab("Op Stat", "ImageIdHere")


tab.newToggle("op Stat", "(ใช้ไม่ได้แปลว่าเเอดมินเเก้เเล้ว)", false, function(lol)
 _G.ez = lol
while _G.ez do wait ()
   local args = {
    [1] = "The World Head",
    [2] = "Armor"
}

game:GetService("ReplicatedStorage").OtherThing.Tools:FireServer(unpack(args))

local args = {
    [1] = "Cosmic Orb",
    [2] = "Armor"
}

game:GetService("ReplicatedStorage").OtherThing.Tools:FireServer(unpack(args))

local args = {
    [1] = "Skull Bike",
    [2] = "Armor"
}

game:GetService("ReplicatedStorage").OtherThing.Tools:FireServer(unpack(args))
end
end)
