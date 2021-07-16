		local LocalPlayer = game:GetService("Players").LocalPlayer
		local char = LocalPlayer.Character
		char.ChildAdded:Connect(function(sock)
			if sock:IsA("MeshPart") then do
					wait(0.1)
					sock:Destroy()
				end
			end
		end)
