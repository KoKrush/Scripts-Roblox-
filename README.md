# Scripts-Roblox-
A few scripts for beginners to learn off of!

--Menu Gui--

Script Button "Play":

Menu = script.Parent.Parent.Parent



script.Parent.MouseButton1Click:connect(function()
	Menu:remove()
end)


Script MenuGui:


Menu = script.Menu


game.Players.PlayerAdded:connect(function(player)
	local MenuClone = Menu:Clone()
	MenuClone.Parent = player.PlayerGui
end)

*The menu goes into the MenuGui Script*
