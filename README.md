      --  carregando script

      local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

      --window

local Window = Library.CreateLib("Infinity Hub v2", "BloodTheme")

      --arsenal
local Tab = Window:NewTab("Arsenal")

local arsenal = Tab:NewSection("Unkeyless")

arsenal:NewButton("Ronix Hub", "TOP TIER", function() loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/93f86be991de0ff7d79e6328e4ceea40.lua"))()
    print("Execute")
end)
arsenal:NewButton("BerTox", "", function() loadstring(game:HttpGet("https://pastebin.com/raw/8ysy7ENG",true))()
    print("Execute")
end)
arsenal:NewButton("Unnamed Hub", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/JackyPoopoo/cartel/main/0000000000000000000000000000000000000000000000000"))()
    print("Execute")
end)

      --blox fruits

local Tab = Window:NewTab("Blox Fruits")

local fruits = Tab:NewSection("Keyless")

fruits:NewButton("Alchemy Hub", "", function() loadstring(game:HttpGet("https://scripts.alchemyhub.xyz"))()
    print("Execute")
end)
fruits:NewButton("Zen Hub", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Zenhubtop/zen_hub_pr/main/zennewwwwui.lua", true))()
    print("Execute")
end)
fruits:NewButton("HoHo Hub", "TOP TIER", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI"))()
    print("Execute")
end)

local fruits = Tab:NewSection("UnKeyless")

fruits:NewButton("Mukuro Hub", "TOP TIER", function() loadstring(game:HttpGet("https://auth.quartyz.com/scripts/Loader.lua"))()
    print("Execute")
end)
fruits:NewButton("RedZ", "TOP TIER", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
    print("Execute")
end)
fruits:NewButton("W-Azure", "TOP TIER", function() loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
    print("Execute")
end)
fruits:NewButton("Zenith Hub", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Efe0626/RaitoHub/main/Script"))()
    print("Execute")
end)
fruits:NewButton("Speed Hub", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
    print("Execute")
end)

fruits:NewButton("MaMa Hub", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/MAMAhub1/Mmahub/main/README.md"))()
    print("Execute")
end)

local Tab = Window:NewTab("King Legacy")

local king = Tab:NewSection("Keyless")

king:NewButton("Zen Hub", "TOP TIER", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Zenhubtop/zen_hub_pr/main/zennewwwwui.lua", true))()
    print("Execute")
end)

king:NewButton("Arc Hub", "TOP TIER", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/JuninhoOGado/ScriptsSite/main/Script286"))()
    print("Execute")
end)

local Tab = Window:NewTab("Fisch")

local fish = Tab:NewSection("UnKeyless")

fish:NewButton("Speed Hub", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
    print("Execute")
end)

fish:NewButton("CupPink", "", function() loadstring(game:HttpGet("https://you.whimper.xyz/sources/CupPink/fisch.lua"))()
    print("Execute")
end)

fish:NewButton("Ronix Hub", "TOP TIER", function() loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/f3ac013da72a3b41d6c63454b2749624.lua"))()
    print("Execute")
end)

fish:NewButton("Zenith Hub", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Efe0626/RaitoHub/main/Script"))()
    print("Execute")
end)

fish:NewButton("Project Spectrum 8.0", "TOP TIER", function() loadstring(game:HttpGet("https://you.whimper.xyz/spectrum"))()
    print("Execute")
end)

fish:NewButton("Rinns Hub", "TOP TIER", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/kylosilly/femboyware/refs/heads/main/Fisch.lua"))()
    print("Execute")
end)


local fish = Tab:NewSection("Keyless")

fish:NewButton("Reaper Hub", "TOP TIER", function() loadstring(game:HttpGet("https://reaperscripts.com/loader.lua"))()
    print("Execute")
end)

fish:NewButton("Goomba Hub", "TOP TIER", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/JustLevel/goombahub/main/fisch.lua"))()
    print("Execute")
end)

local Tab = Window:NewTab("Universal")

local universal = Tab:NewSection("Universal")

universal:NewButton("Infinite Yield", "", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
    print("Execute")
end)

universal:NewButton("Remote Spy", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/lipex163/RemoteSpy/refs/heads/main/README.md"))()
    print("Execute")
end)

universal:NewButton("UNC Check", "", function() loadstring(game:HttpGet("https://pastebin.com/raw/QLn8auCa"))()
    print("Execute")
end)

universal:NewButton("Unammed ESP", "", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/lipex163/Unammed-ESP1.0/refs/heads/main/README.md", true))()
    print("Execute")
end)



local Tab = Window:NewTab("Settings")

local Section = Tab:NewSection("KeyBind")

Section:NewKeybind("Keybind", "TO CLOSE AND OPEN UI", Enum.KeyCode.Insert, function()
	Library:ToggleUI()
end)

Section:NewLabel("MADE BY LIPEX")
