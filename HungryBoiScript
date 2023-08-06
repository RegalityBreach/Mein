local victim = "adamdine1025"
local player = game.workspace:FindFirstChild(victim)
local head = player.Head
local weld1 = Instance.new("WeldConstraint")
local fart = Instance.new("Sound")
local nom1 = Instance.new("Sound")
local nom = Instance.new("Sound")
local blood = Instance.new("Decal")
local nameB = Instance.new("Part")
local gui = Instance.new("BillboardGui")
local label = Instance.new("TextLabel")
for i,v in pairs(player:GetDescendants()) do
	if v:IsA('BasePart') then
		v.Locked = true
	end
end
blood.Texture = "rbxassetid://176678070"
blood.Transparency = 1
blood.Name = "Blood"
blood.Parent = head
blood.Face = "Front"
nameB.Position = head.Position + Vector3.new(0,4,0)
nameB.Anchored = false
nameB.CanCollide = false
nameB.Transparency = 1
nameB.Parent = head
weld1.Part0 = nameB
weld1.Part1 = head
weld1.Parent = nameB
gui.Parent = nameB
gui.Size = UDim2.new(0,200,0,50)
label.Parent = gui
label.Size = UDim2.new(0,200,0,50)
label.BackgroundTransparency = 1
label.TextScaled = true
label.TextStrokeTransparency = 0
label.TextColor = BrickColor.new("Really red")
label.Text = "HE IS HUNGRY, HE NEEDS FLESH"
fart.SoundId = "rbxassetid://1926602937"
fart.Looped = true
nom.SoundId = "rbxassetid://8900932145"
nom1.SoundId = "rbxassetid://132758217"
fart.Parent = head
nom.Parent = head
nom1.Parent = head
fart.Volume = 1
nom.Volume = 10
fart.Name = "Fart"
nom.Name = "Nom"
nom1.Name = "Nom1"

head.Size = Vector3.new(2.1,2.1,2.1)
wait(0.1)
head.Size = Vector3.new(3.1,3.1,3.1)
wait(0.1)
head.Size = Vector3.new(4.1,4.1,4.1)
wait(0.1)
head.Size = Vector3.new(5.5,5.5,5.5)
wait(0.1)
head.face.Texture = "rbxassetid://128277497"
player.Humanoid.WalkSpeed = 32
player.Humanoid.JumpPower = 80
player.Humanoid.MaxHealth = math.huge
player.Humanoid.Health = math.huge
player.Pants:Destroy()
fart:Play()

function onTouched(hit)
	player.Humanoid.Health = player.Humanoid.Health + 100000000
	local one = hit.Parent.Name
	if hit.Name == "Baseplate" then
		print("Cant eat baseplate retard")
	elseif hit.Name == "Spawnpoint" then
		print("Cant eat spawnpoint retard")
	elseif hit.Name == "RightFoot" then
		hit.Anchored = true
		print("you got a foot fetish?")
	elseif hit.Name == "LeftFoot" then
		hit.Anchored = true
		print("you got a foot fetish?")
	elseif hit.Name == "Right Leg" then
		local bPaste = blood:Clone()
		bPaste.Transparency = 0
		bPaste.Face = "Top"
		bPaste.Parent = hit
		hit.Anchored = true
		print("you got a foot fetish?")
	elseif hit.Name == "Left Leg" then
		local bPaste = blood:Clone()
		bPaste.Transparency = 0
		bPaste.Face = "Top"
		bPaste.Parent = hit
		hit.Anchored = true
		print("you got a foot fetish?")
	elseif hit.Name == "RightUpperLeg" then
		local bPaste = blood:Clone()
		bPaste.Transparency = 0
		bPaste.Face = "Top"
		bPaste.Parent = hit
		hit.Anchored = true
		print("you got a foot fetish?")
	elseif hit.Name == "LeftUpperLeg" then
		local bPaste = blood:Clone()
		bPaste.Transparency = 0
		bPaste.Face = "Top"
		bPaste.Parent = hit
		hit.Anchored = true
		print("you got a foot fetish?")
	elseif hit.Name == "RightLowerLeg" then
		hit.Anchored = true
		print("you got a foot fetish?")
	elseif game.Players:FindFirstChild(one) then
		player.Humanoid.Health = player.Humanoid.Health + 100000000
		hit:Destroy()
		nom:Play()
		label.Text = "YOU HAVE BEEN CONSUMED"
		head.face.Texture = "rbxassetid://2052678541"
		blood.Transparency = 0
		wait(1)
		label.Text = "HE IS HUNGRY, HE NEEDS FLESH"
		head.face.Texture = "rbxassetid://128277497"
		blood.Transparency = 1
	else
		hit:Destroy()
		nom1:Play()
		head.face.Texture = "rbxassetid://2052678541"
		wait(0.8)
		head.face.Texture = "rbxassetid://128277497"
	end
end
head.Touched:connect(onTouched)
