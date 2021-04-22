while wait() do
    game.ReplicatedStorage.MainEvent:FireServer("CHECKER_1")
end
wait (0.5)
print ("Crashing!")
