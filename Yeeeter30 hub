local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Yeeeter30's Hub v4", "DarkTheme")
local Tab = Window:NewTab("universal")
--MAIN
local Section = Tab:NewSection("Universal")
Section:NewButton("infinite yield", "infinite yield", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
Section:NewButton("Moon Ui", "Moon Ui", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()
end)
Section:NewButton("Infinite Store", "infinite storr", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Infinite-Store/Infinite-Store/main/main.lua"))()
end)
--TOGGLE
Section:NewToggle("Super Human", "Super Fast", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
game.Players.LocalPlayer.Character.Humanoid.Jumppower = 100
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
game.Players.LocalPlayer.Character.Humanoid.Jumppower = 50
end
end)
Section:NewButton("VHub", "VHub Simple Edition", function()

loadstring(game:HttpGet(('https://raw.githubusercontent.com/Veincx5315/Created/VHub/Simple'),true))()
end)
Section:NewButton("Keyboard Gui", "Keyboard Gui", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)
Section:NewButton("Linkvertise Bypass", "Linkvertise bypass", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Woutt/Lua-Scripts/main/bypass.lua"))()
end)
local Section = Tab:NewSection("Prison Life")
Section:NewButton("Prison Life Admin", "Admin", function()
loadstring(game:HttpGet('https://pastebin.com/raw/iZ64yzjE'))();
end)
Section:NewButton("prison life m9", "m9 mod", function() local player = game:GetService("Players").LocalPlayer
local gun = player.Backpack:FindFirstChild("M9")
local sM = require(gun:FindFirstChild("GunStates"))
sM["Damage"] = 999
sM["MaxAmmo"] = 9999991
sM["StoredAmmo"] = 9999991
sM["FireRate"] = 0.05
sM["AmmoPerClip"] = 9999991
sM["Range"] = 5000
sM["ReloadTime"] = 0.05
sM["Bullets"] = 10
sM["AutoFire"] = true
end)

Section:NewButton("prison life GUI", "Prison Life GUI", function()
loadstring(game:HttpGet("https://pastebin.com/raw/VZxFg1wK"))()
end)
local Tab = Window:NewTab("Player")
local Section = Tab:NewSection("Player")

Section:NewSlider("Speed", "SPEED!!", 500, 16, function(s)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

Section:NewSlider("Jumppower", "Jump High", 350, 50, function(s)
    game.Players.LocalPlayer.Character.Humanoid.Jumppower = s
end)

local Tab = Window:NewTab("Extra")
local Section = Tab:NewSection("Credits")
--CREDITS
Section:NewButton("yeeeter30", "Made by Yeeeter30 and special thaaks to TheEGod for the Prison life gui", function()
print("SUB TO YEEETER30")
end)
local Section = Tab:NewSection("Printer")
Section:NewTextBox("Print What You type", "type", function(Printer)
	print(Printer)
end)
--TOGGLE
Section:NewLabel("Toggle Gui")
Section:NewKeybind("Toggle GUI By F", "toggle the GUI from F", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)
