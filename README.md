local args = {
    [1] = "bayad"
}

while true do
    game:GetService("ReplicatedStorage").ValentinesEvent.RemoteEvent:FireServer(unpack(args))
    wait(0)
end
